# NL GEO-skill voor Claude

Een gratis skill voor Claude die Nederlandse websites beoordeelt op **GEO**: de kans dat AI-zoekmachines zoals ChatGPT, Perplexity, Gemini, Copilot en Google AI Overviews een site begrijpen, vertrouwen en citeren.

Gemaakt door [Nekx SEO](https://nekxseo.com/seo-met-claude/), het white-label SEO- en GEO-platform voor webbureaus.

## Wat de skill doet

- Checkt een URL op de vier dingen die tellen: citeerbare opbouw, een duidelijke entiteit, autoriteit buiten de site en technische toegang voor AI-crawlers.
- Geeft bij elke bewering een zekerheidslabel (bevestigd, sterk bewijs, industrie-observatie of hypothese) en een bron bij elk cijfer.
- Kent de Nederlandse invulling: KVK-naam in het schema, Google Bedrijfsprofiel, Nederlandse vakmedia en communities, en meten met Nederlandse vragen.
- Zegt ook wat niet werkt, zoals llms.txt als vindbaarheidsmaatregel.
- Levert een tabel met bevindingen op prioriteit, plus één alinea in gewone taal voor de ondernemer.

## Installeren

**Claude Code**

```bash
git clone https://github.com/nekxseo/nl-geo-skill.git
mkdir -p ~/.claude/skills
cp -r nl-geo-skill/nl-geo ~/.claude/skills/
```

Start daarna Claude Code opnieuw en vraag bijvoorbeeld: *"Doe een GEO-check van https://jouwsite.nl"*.

**Claude-app (claude.ai, desktop)**

Pak de map `nl-geo` in als ZIP en voeg die toe bij de skills in de instellingen van Claude.

## Voorbeeldvragen

- "Doe een GEO-check van https://voorbeeld.nl/diensten/"
- "Waarom noemt ChatGPT mijn bedrijf niet?"
- "Moet ik een llms.txt-bestand maken?"
- "Welke AI-bots moet ik toelaten in robots.txt?"

## Licentie

Apache-2.0, zie [LICENSE](LICENSE). Deze skill bouwt voort op [claude-seo](https://github.com/AgriciDaniel/claude-seo) (MIT) en [aaron-marketing-skills](https://github.com/aaron-he-zhu/aaron-marketing-skills) (Apache-2.0); zie [NOTICE](NOTICE).

---

## English

A free Claude skill that audits Dutch websites for **GEO** (Generative Engine Optimisation): how likely AI search engines are to understand, trust and cite a site. Written in Dutch for the Dutch market, with confidence labels and a source for every number. Made by [Nekx SEO](https://nekxseo.com/en/). Licensed under Apache-2.0.
