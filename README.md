# Schipper, mag ik overvaren?

Privé studiefeed. Dit is geen publieke podcast: de reeks bestaat alleen zodat Nicholas
zijn eigen leerstof voor het Belgische **beperkt stuurbrevet** onderweg kan beluisteren.

De feed draagt `<itunes:block>Yes</itunes:block>` en de `robots.txt` weert alle crawlers,
dus Apple Podcasts, Spotify en Google nemen de reeks niet op in hun catalogus. Hij is
nooit ergens ingediend.

- Feed: `feed.xml`
- Audio: `audio/epNN.mp3`, uitgeserveerd via GitHub Pages
- Scripts, referentiebladen en de generator staan in de privé Second Brain repo

**Audio hoort hier in de repo en niet in een release.** Release-assets komen binnen met
`Content-Type: application/octet-stream` en `Content-Disposition: attachment`, en dan
weigert Apple Podcasts af te spelen. Pages stuurt `audio/mp3` zonder attachment-header
en ondersteunt range requests, dus spoelen werkt.

De audio is gegenereerd met tekst-naar-spraak. De inhoud is afgeleid van de officiële
examenleerstof en het Algemeen Politiereglement voor de Scheepvaart op de Binnenwateren,
maar dit is studiemateriaal en geen officiële bron.
