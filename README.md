# Check Am

A Ghana-first scam checker. Paste a suspicious SMS, WhatsApp message or investment offer and get:

- a **risk level** and a **scam score** (0–100)
- the **scam type**: MoMo reversal, fake promo, Ponzi/investment, fake job, phishing
- the **red flags** found, in plain language
- **what to do next**

## Why

Mobile money fraud is widespread in Ghana, yet no Ghana-specific, real-time checker exists for ordinary users. Scammers reuse the same scripts on many people, so a tool that names the pattern helps users spot the next one.

## Design rules

1. **It warns, it never guarantees.** No verdict says a message is 100% safe.
2. **It explains, it does not just judge.** Every verdict shows the words that raised the alarm.

## How this demo works

A single HTML page with no dependencies. A rule-based library of local scam patterns scores each message, with weights per pattern and a bonus when several patterns appear together.

Open `index.html` in any browser to try it.

## Roadmap

- AI analysis on top of the pattern library
- Community "report a scam" database
- Fraud-screening API for fintechs, MFIs and telcos (the revenue model)

## Author

Samuel Kwame Yeboah, Accra, Ghana
