# Twenthe Uitvaartverzekering — website

De publieke website van Uitvaartverzekering Twenthe N.V. (Enschede, sinds 1942).

**Live:** https://www.twenthe.nl/

## Inhoud

| Bestand | Doel |
|---|---|
| `index.html` | Homepage met hero, premie‑slider, FAQ |
| `premie.html` | Volledige premie­berekenaar (individueel + gezin) — tarieven 2026 |
| `uitvaartwaardemeter.html` | Uitvaartkosten calculator met 12 onderdelen |
| `wensen.html` | Persoonlijk uitvaartwensen formulier (lokaal opgeslagen, print/PDF/e‑mail/JSON export) |
| `login.html` | Inlogpagina voor Mijn Twenthe |
| `robots.txt` | Crawl‑instructies (incl. expliciete toestemming voor 18 AI‑crawlers) |
| `sitemap.xml` | Sitemap voor zoekmachines |
| `llms.txt` | Beknopte site‑samenvatting voor LLMs (llmstxt.org standaard) |
| `llms-full.txt` | Uitgebreide content voor AI‑indexering |
| `tarieven.json` | Machine‑leesbare premie­tarieven |
| `tarieven.md` | Premie­tarieven in markdown tabel |
| `404.html` | Custom foutpagina |

## Techniek

- **Statische HTML/CSS/JS** — geen build step, geen framework, geen dependencies
- **Self‑contained** — afbeeldingen en logo zijn inline base64/SVG. Geen `assets/` map nodig.
- **Webfonts** via Google Fonts (Cormorant Garamond + Open Sans)
- **Klantgegevens** in `wensen.html` worden opgeslagen in `localStorage` van de bezoeker — niets wordt naar de server verzonden

## Hosting

Werkt op elke statische host:
- GitHub Pages
- Netlify
- Cloudflare Pages
- Eigen webserver

Voor GitHub Pages: zet alle bestanden in de root van de repo, schakel Pages aan via Settings → Pages → Branch: main.

## Bedrijfsgegevens

- Uitvaartverzekering Twenthe N.V.
- Getfertsingel 91, 7513 GB Enschede
- 053 – 4312 732 · info@twenthe.nl
- KvK 06014206 · AFM 12000699 · KiFiD 200.000315

© 2026 Uitvaartverzekering Twenthe N.V.
