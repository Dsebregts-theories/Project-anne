# SlimStart Studio · Project-anne

Eerste tweetalige productwebsite voor de Klantstart Toolkit. Statische HTML, CSS en JavaScript zonder buildstap.

## Bestanden

- `dist/index.html`: productpagina en toegankelijke voorbeeldberichten.
- `dist/styles.css`: responsieve vormgeving in donkergroen, crème en goud.
- `dist/app.js`: Nederlandse en Engelse teksten, voorbeeldkeuze en kopieerfunctie.
- `.openai/hosting.json`: Sites-hostingconfiguratie.
- `netlify.toml`: Netlify-configuratie; publiceert uitsluitend `dist/` zonder buildstap.

De site bevat drie voorbeeldberichten per taal. De betaalde toolkit, privé-overdracht en klantgegevens worden niet mee gepubliceerd. Betaling en productlevering zijn nog niet aangesloten. De website meldt dit bij de prijs en in de beschikbaarheidsdialoog.

De oorspronkelijke toolkit staat in https://github.com/Dsebregts-theories/Project-anne.

## Projectlocaties en koppelingen

Gebruik uitsluitend de bestaande Project Anne-locaties voor deze website. Gebruik geen Auto theorie-projecten, accountsleutels, databases, opslag of andere koppelingen. Maak niet automatisch een vervangend project aan als de bestaande Project Anne-locatie niet toegankelijk is.

### Netlify

De bestaande Netlify-site **slimstartstudio** is gekoppeld aan deze repository en de branch `main`. De publicatiemap is `dist`; een buildcommando is niet nodig. De configuratie staat in `netlify.toml`. Een uploadpakket voor handmatige publicatie bevat uitsluitend de inhoud van `dist/`, met `index.html` in de hoofdmap van de ZIP.

- Website: https://slimstartstudio.netlify.app
- Netlify-site-ID: `d62b2b28-1644-4602-8fdb-60cfdc2794b2`.
- De accountkoppeling en een geslaagde GitHub-publicatie zijn gecontroleerd via de Netlify-API.
- De bestaande wachtwoordbeveiliging blijft behouden.
- Lokale Netlify-accountgegevens en projectstatus worden niet in Git opgenomen.

### Supabase

Er is nog geen Supabase-koppeling in de website. Gebruik pas een project nadat de bestaande Project Anne-projectlocatie en de juiste accounttoegang zijn bevestigd. Plaats nooit geheime API-sleutels of service-role-sleutels in `dist/` of in Git. Supabase dient voor backendfuncties; de statische website wordt op de websitehosting gepubliceerd.
