# EcomIQ Global — Interactive Demo

Live demo of the E-Commerce Intelligence Platform.
Try it: **[ecomiq-demo.github.io](https://artemsanisimow-ux.github.io/ecom-global-demo)**

## What you can do in the demo

**Review Analyzer** — paste any product reviews, get:
- Sentiment score + label
- Purchase signals with confidence scores and recommended actions (P0/P1/P2)
- Top complaints ranked by frequency
- Unmet needs — what customers want but no product delivers

**Demand Segmentor** — enter a category and keywords, get:
- Market segments with opportunity scores (1–10)
- Unmet need per segment
- White space opportunities — gaps where demand exists but competition is weak
- TF-IDF keyword clustering

**Vector Search** — search stored reviews by semantic similarity (TF-IDF cosine)

**Pipeline Demo** — see both agents run in sequence, signals passed between them

## Demo limits

5 free analyses. Each analysis uses one of your 5 credits.
After that, contact us for full access.

## Full version

The demo uses pre-computed mock data. The full version:

| Feature | Demo | Full |
|---------|------|------|
| AI engine | Mock responses | Claude claude-opus-4-5 |
| Platform data | Stubs | Live Amazon, eBay, Walmart, Etsy, Shopify APIs |
| Analyses | 5 free | Unlimited |
| Database | In-browser | SQLite with full history |
| Vector search | Pre-stored reviews | Your actual review database |
| Language | EN only | EN + RU |
| Source code | Not included | Full source + deployment guide |

## Contact

Interested in the full version or custom integration?

📧 a.s.anisimow1@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/artemsanisimow)

## Tech stack (full version)

- FastAPI (async Python) + AsyncAnthropic
- TF-IDF vectorization — no external ML libraries
- SQLite with 6 normalized tables
- Protocol-based platform adapters
- 89 tests
