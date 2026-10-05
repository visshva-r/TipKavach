# TipKavach

On-device checker for WhatsApp and Telegram investment tips. Built for **SANGYAN Track A** (Digital Fraud & Scam Resilience): pattern-based risk scoring, Hindi/English UI, Listen (Web Speech), no stock tips, no data upload.

**Live demo:** [https://visshva-r.github.io/TipKavach/](https://visshva-r.github.io/TipKavach/)

**Source:** [github.com/visshva-r/TipKavach](https://github.com/visshva-r/TipKavach)

## Run locally

Open `index.html` in a browser, or:

```powershell
npx --yes serve .
```

## How it works

1. Paste a tip or tap a sample scam message.
2. On-device rules score red flags (UPI to personal IDs, OTP asks, AnyDesk, fake IPO fees, etc.).
3. See **Neutral / Medium / High** risk with uncertainty note and safe next steps (1930, cybercrime.gov.in, SCORES, SEBI verify).

## Tech

Single HTML/CSS/JS file. No backend, no npm build, no analytics.

## License

Public-good investor protection prototype. Submitted to Sangyan Hackathon 2026.
