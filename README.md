# SBI Saarthi
### One AI companion for every Indian's banking journey — *Speak · Learn · Protect*

**SBI Hackathon @ Global Fintech Fest 2026** · Theme: Agentic AI & Emerging Tech · Problem Statement: Customer Acquisition

### ▶️ [**Open the live prototype (one click)**](https://adipal10.github.io/sbi-saarthi/) &nbsp;|&nbsp; [▶️ Watch the pitch reel](https://adipal10.github.io/sbi-saarthi/SBI_Saarthi_Pitch.html)

SBI Saarthi is a single agentic-AI companion that carries a customer across the whole banking lifecycle. It finds creditworthy but "invisible" customers (like Ramesh, a kirana-store owner) from consented data, opens their account in one WhatsApp or voice chat in their own language, funds their business through SBI's loan engine, helps them start small investments, and keeps them safe from fraud — all with a human one tap away.

---

## 🔴 Live demo (try it in your browser)

> Once GitHub Pages is enabled (see below), these links go live:

- **Interactive prototype** — talk to Saarthi, drive the flow yourself:
  `https://adipal10.github.io/sbi-saarthi/index.html`
- **Pitch reel** — the auto-playing story of Ramesh:
  `https://adipal10.github.io/sbi-saarthi/SBI_Saarthi_Pitch.html`

You can also just **download this repo and open `index.html`** in any browser — it runs fully offline, no install.

---

## What's inside

| File | What it is |
|------|-----------|
| `index.html` | The interactive prototype — WhatsApp chat (left) + banker dashboard (right). Tap reply chips or type in Hindi/English. Includes the Sikho practice sandbox and the Kavach fraud-block. |
| `SBI_Saarthi_Pitch.html` | The full pitch video reel (auto-plays the problem → Ramesh → live demo → architecture → close). |
| `VOICEOVER_SCRIPT.md` | Narration script for the pitch video. |

---

## The system

**Six agents, one shared memory:**
Pehchaan (find + qualify) · Ek Baat-cheet (onboard) · Punji (MSME credit) · Aadat (activate) · Nivesh (grow wealth) · Zindagi Radar (life-events)

**Three layers under every agent:**
- **Boliye** — vernacular voice across 22 languages (Bhashini)
- **Sikho** — a play-money practice sandbox that removes the fear of losing real money
- **Kavach** — a plain-language fraud shield ("you are SENDING, not receiving")

**Built on live Indian rails:** Account Aggregator (consent), Bhashini (voice), Aadhaar + DigiLocker (identity), and SBI's own digital-loan engine. WhatsApp + IVR is the front door; the same brain also embeds inside YONO 2.0.

---

## Run locally
No build step. Either:
- Double-click `index.html`, **or**
- Serve the folder: `python -m http.server 5610` then open `http://localhost:5610/index.html`

---

*Prototype for the SBI Hackathon 2026. Figures cited are calibrated ranges from public SBI and banking-AI sources.*
