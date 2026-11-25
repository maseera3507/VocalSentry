# VocalSentry: Deterministic Paralinguistic Safety Middleware

**Perfios × IIT Bombay Techfest Hackathon 2026 | Theme 1: Debt Collections (Problem 1)**

> VocalSentry is an in-line, deterministic safety middleware between the telephony SIP/RTP trunk and the collection voicebot. It detects acute vocal distress from acoustic physics (not transcripts) and cuts automated collection speech mid-syllable in under 50ms.

---

### 📄 Official Round 1 Submission Document
* **[Click Here to View / Download the 3-Page Technical Proposal (PDF)](./Finalized%20submission.pdf)**

### Key Technical Highlights
- **Telephony Degrader:** 8 kHz downsampling, 300–3,400 Hz Butterworth bandpass, bit-exact ITU-T G.711 μ-law companding.
- **Dual Intelligence Engines:** Praat-Parselmouth acoustic DSP + PTP Commitment Uncertainty scoring.
- **Three-Stage Audio Circuit Breaker:** Stop Bot TTS mid-syllable (<50ms) → Allow Approved Safety Prompt → Human Handoff.
- **Regulatory Alignment:** RBI Outsourcing Directions (2023), Fair Practices Code, and India's DPDP Act 2023.
