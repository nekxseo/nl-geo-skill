---
name: nl-geo
description: >
  GEO en AI-vindbaarheid voor Nederlandse websites: zorgen dat AI-zoekmachines
  (Google AI Overviews en AI Mode, ChatGPT Search, Perplexity, Copilot, Gemini,
  Claude) een Nederlandse site begrijpen, vertrouwen en citeren. Gebruik bij
  vragen over AI-vindbaarheid, AI Overviews, genoemd worden in ChatGPT, GEO,
  AEO, llms.txt of AI-crawlers, en bij een GEO-check van een URL.
argument-hint: "[url]"
license: Apache-2.0
metadata:
  author: Nekx SEO (Stijn Rolink)
  version: "1.0.0"
  category: geo
  language: nl
  market: NL
  homepage: https://nekxseo.com/seo-met-claude/
---

# NL GEO: AI-vindbaarheid voor Nederlandse websites

## Uitgangspunt

**GEO is nog steeds SEO.** Google zegt dat in zijn eigen gids "Optimizing your website for generative AI features on Google Search" (mei 2026): wie optimaliseert voor de AI-functies in Google Search, optimaliseert voor de zoekervaring, en dat is SEO. Unieke, bruikbare content die goed bereikbaar is, weegt het zwaarst. Een apart GEO-trucje bestaat niet. ([samenvatting van de gids](https://www.semrush.com/blog/google-publishes-generative-ai-search-guide/))

Verkoop GEO daarom niet als aparte magie, maar als vier dingen samen:
SEO-basis + citeerbare opbouw + een duidelijke entiteit + autoriteit buiten de eigen site.

**Zekerheidslabels zijn verplicht** bij elke GEO-bewering in je antwoord:
- **Bevestigd**: staat in documentatie van Google, OpenAI, Anthropic of Microsoft.
- **Sterk bewijs**: groot onderzoek met openbare methode.
- **Industrie-observatie**: wat praktijkmensen breed zien, zonder hard onderzoek.
- **Hypothese**: aannemelijk, niet aangetoond.

## Werkwijze bij een GEO-check van een URL

1. Haal de pagina op en kijk of de kerntekst in de HTML staat (zonder JavaScript).
2. Controleer `robots.txt` op AI-bots (zie stap 4) en of de site die bots niet per ongeluk blokkeert via een firewall of CDN.
3. Beoordeel de citeerbare opbouw (zie stap 1) en de entiteit (zie stap 2).
4. Kijk naar autoriteit buiten de site (zie stap 3): wordt het bedrijf genoemd op plekken die AI-zoekmachines gebruiken?
5. Lever de bevindingen op volgens "Rapportage" onderaan, met zekerheidslabel en prioriteit per punt.

Schrijf het antwoord in het Nederlands, in klare taal, en noem bronnen bij elk cijfer.

## 1. Citeerbare opbouw (per belangrijke pagina)

- **Antwoord eerst.** Geef elke kernvraag direct onder de kop een zelfstandig antwoord van 25 tot 50 woorden dat ook losgeknipt nog klopt. *(Industrie-observatie)*
- **Het beste staat bovenaan.** In een analyse van 1,2 miljoen ChatGPT-antwoorden kwam 44,2% van de citaties uit de eerste 30% van de tekst. ([Kevin Indig via Search Engine Land](https://searchengineland.com/chatgpt-citations-content-study-469483)) *(Sterk bewijs)*
- Koppen als vragen, zoals Nederlanders ze stellen. Korte alinea's van 2 tot 4 zinnen. Tabellen voor vergelijkingen, lijsten voor stappen.
- Definities in het patroon "X is ...", in het Nederlands.
- FAQ-secties waarbij het FAQ-schema exact gelijk is aan de zichtbare tekst. Nooit antwoorden die alleen in het schema staan.
- Concrete feiten met bron. Eigen data (cijfers, cases, ervaring) is het sterkst, want die heeft niemand anders.

## 2. Een duidelijke entiteit

AI-systemen moeten zonder twijfel kunnen vaststellen wie het bedrijf is, waar het zit, wat het doet en waarom het te vertrouwen is.

- `Organization`- of `LocalBusiness`-schema volledig: naam zoals bij de KVK, adres, logo, oprichtingsjaar en `sameAs` naar Google Bedrijfsprofiel, LinkedIn en andere profielen.
- Een over-ons-pagina die het bedrijf in gewone taal beschrijft: wie, sinds wanneer, voor wie, met welk bewijs.
- Auteursvermelding bij inhoudelijke artikelen, met functie en ervaring (`Person`-schema).
- Dezelfde bedrijfsomschrijving op de site, in het Bedrijfsprofiel, op LinkedIn en in gidsen. Tegenstrijdige omschrijvingen maken het lastiger om het bedrijf te noemen. *(Industrie-observatie)*
- Publicatiedatum en datum van laatste update zichtbaar, en kernpagina's echt actueel houden. *(Industrie-observatie)*

## 3. Autoriteit buiten de eigen site

- **Vermeldingen wegen zwaar.** In een onderzoek naar 75.000 merken hingen vermeldingen van een merk op het web veel sterker samen met zichtbaarheid in Google AI Overviews (correlatie 0,664) dan backlinks (0,218). ([Ahrefs](https://ahrefs.com/blog/ai-overview-brand-correlation/)) *(Sterk bewijs)*
- Wees zichtbaar op platforms die AI-systemen vaak als bron gebruiken: YouTube, Reddit, LinkedIn en waar haalbaar Wikipedia of Wikidata. *(Industrie-observatie)*
- Nederlandse varianten: vakmedia en branchesites, regionale media, en Nederlandse communities die bij de branche passen.
- **Meet per platform.** In een onderzoek naar 15.000 vragen stond gemiddeld maar 12% van de links die ChatGPT, Gemini en Copilot citeren ook in Google's top 10 voor dezelfde vraag. Bij Google AI Overviews kwam 76% van de citaties wel uit de top 10. ([Ahrefs](https://ahrefs.com/blog/ai-search-overlap/)) *(Sterk bewijs)*

## 4. Technische toegankelijkheid voor AI-crawlers

- **Kerntekst in de HTML.** Veel AI-crawlers voeren weinig of geen JavaScript uit. Tekst die pas na JavaScript verschijnt, lezen ze vaak niet. Dit is de meest voorkomende harde blokkade. *(Industrie-observatie)*
- **robots.txt:** maak onderscheid tussen bots die zoeken voor een antwoord (zoals OAI-SearchBot, Claude-SearchBot, PerplexityBot) en bots voor training (zoals GPTBot, ClaudeBot, en het token Google-Extended). Advies: zoekbots toestaan. Training is een keuze van de eigenaar; leg die uit, leg hem niet op.
- **llms.txt is geen vindbaarheidsmaatregel.** Google noemt het in de gids van mei 2026 expliciet als iets wat je niet nodig hebt. ([Search Engine Journal](https://www.searchenginejournal.com/googles-llms-txt-guidance-depends-on-which-product-you-ask/575431/)) Een onderzoek naar ongeveer 300.000 domeinen vond geen verband tussen een llms.txt-bestand en hoe vaak een domein wordt geciteerd. ([SE Ranking](https://seranking.com/blog/llms-txt/)) Vraagt iemand erom: uitleggen, niet verkopen. *(Bevestigd voor Google, sterk bewijs voor citaties)*
- Controleer of firewalls en CDN's (bijvoorbeeld de bot-instellingen van Cloudflare) legitieme AI-bots niet blokkeren als de eigenaar wél geciteerd wil worden.

## 5. Meten in het Nederlands

- Stel de vragen waarop je gevonden wilt worden **in het Nederlands** aan ChatGPT (met zoeken), Perplexity, Copilot en Google AI Mode. Noteer of en hoe het bedrijf wordt genoemd of geciteerd. Herhaal elke maand met dezelfde vragen.
- Maak onderscheid tussen **citeerbaarheid** (kan een AI-zoekmachine de pagina gebruiken als je de URL geeft? Binnen minuten te testen) en **spontaan genoemd worden** (duurt weken, afhankelijk van hoe snel de zoekmachine de pagina oppikt). Beloof nooit snelle resultaten.
- In Google Search Console is verkeer uit AI Overviews niet apart zichtbaar. Volg daarom vertoningen en CTR op vraagachtige zoekopdrachten.

## Rapportage

Lever de bevindingen op als tabel, gesorteerd op prioriteit:

| Bevinding | Zekerheid | Impact | Moeite | Actie |
|---|---|---|---|---|

Vertaal het daarna in één alinea naar de ondernemer, bijvoorbeeld: "Steeds meer klanten stellen hun vraag eerst aan een AI-assistent. Nu noemt die assistent jou wel of niet. Dit is wat we doen om ervoor te zorgen dat jij in het antwoord staat."

---

*Bronverantwoording: deze skill bouwt voort op de methode van [claude-seo](https://github.com/AgriciDaniel/claude-seo) (seo-geo, MIT-licentie, Daniel Agrici) en [aaron-marketing-skills](https://github.com/aaron-he-zhu/aaron-marketing-skills) (geo-content-optimizer, Apache-2.0, Aaron He Zhu), vertaald en aangepast voor de Nederlandse markt. Zie NOTICE.*
