# NiveshRakshak (निवेश रक्षक)
> A Public-Good Investor Resilience Platform built for the SANGYAN Investor Resilience Hackathon (SEBI × NSDL × IIT BHU Varanasi).

---

## 📌 Problem Statement & Target User
- Target User: First-time retail investors from Tier-2/Tier-3 cities across Bharat, senior citizens, and homemakers.
- Core Challenge: While retail Demat accounts have crossed 16+ crore, market access has outrun financial literacy. 9 out of 10 individual traders in equity F&O incur net losses.



## 🚀 Key Features & Track Integration
- Track A & E (Scam & Content Interceptor): Forward WhatsApp/Telegram screenshots to detect fake SEBI registration numbers, guaranteed return scams, and pump-and-dump claims with an explainable risk score.
- Track B (Grievance & Nominee Engine): Simplified assistant for filing broker complaints on SCORES and tracking nominee details across Demat, Mutual Fund, and Bank folios.
- Track C (Voice-First Bharat Explainer): Regional language audio guides powered by Bhashini APIs, explaining market jargon (NAV, Volatility, Options) using everyday analogies.
- Track D (Behavioural Circuit Breaker): Enforces a 15–30 minute cooling-off pause and displays a pre-trade decision journal during panic selling or loss-chasing.



## 🛡️ Mandatory Guardrails Compliance
- Zero Speculative Advice: No stock tips, buy/sell/hold signals, or price predictions.
- Zero Monetization Funnels: No broker affiliate links, margin nudges, or paid subscription upsells.
- Privacy by Design: Zero scraping of personal SMS, OTPs, or private financial records.



## 🛠️ Tech Stack
- Frontend: React Native / Flutter (optimized for low-end Android devices and low bandwidth)
- Voice Processing: Bhashini Speech-to-Speech APIs (Government of India)
- AI/ML Engine: Quantized Sentence-BERT / Llama-3 for on-device scam pattern analysis
- Integrations: SEBI/NSDL Public Registries, DigiLocker, Account Aggregator
