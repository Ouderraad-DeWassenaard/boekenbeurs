# Boekenbeurs De Wassenaard

De website van de jaarlijkse boekenbeurs van VBS De Wassenaard in Varsenare, gemaakt door de ouderraad.

Online: https://boekenbeurs.dewassenaard.be

## Wat staat waar

| Bestand | Inhoud |
|---|---|
| `index.html` | De volledige pagina: tekst, opmaak en een klein script, in één bestand. |
| `img/` | Afbeeldingen (tekeningen, logo's, foto van de auteur), als WebP. |
| `CNAME` | Het domein voor GitHub Pages. Niet verwijderen. |
| `.nojekyll` | Zorgt dat GitHub Pages de bestanden toont zoals ze zijn. |

De achtergrond met auteursnamen en de tekeningen komen uit de affiche van de beurs.

## Aanpassen

- **In de browser**: open `index.html` op github.com, klik op het potlood, pas aan en klik op *Commit changes*. Na een paar minuten staat de nieuwe versie online.
- **Lokaal**: clone de repo, pas aan, commit en push naar `main`.
- **Afbeeldingen**: liefst WebP en niet breder dan ongeveer 1000 px.

Deze repo is publiek. Zet er geen persoonsgegevens, namen van leerlingen of foto's zonder toestemming in.

## Elk jaar

1. Pas data, uren, auteur, foto en bestelinfo aan in `index.html` (zoek op het jaartal).
2. Kijk de `TODO`-opmerkingen in `index.html` na.
3. Zolang de pagina een voorbeeld is, staan `<meta name="robots" content="noindex, nofollow">` in de `<head>` en de balk "Voorbeeldpagina" bovenaan. Haal beide weg zodra de inhoud klopt.

## Hosting en domein

- **Hosting**: GitHub Pages, gratis, vanuit de branch `main` (*Settings > Pages*).
- **DNS**: bij de beheerder van dewassenaard.be (tophosting.be) staat een CNAME-record `boekenbeurs` naar `ouderraad-dewassenaard.github.io`. Het HTTPS-certificaat regelt GitHub zelf.
- **Doorgeven**: voeg de nieuwe persoon toe als *owner* van de organisatie [Ouderraad-DeWassenaard](https://github.com/Ouderraad-DeWassenaard).
