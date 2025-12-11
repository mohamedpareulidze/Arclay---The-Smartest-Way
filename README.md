# ARCLAY — The Smartest Way

**Strategic Neuromarketing & Behavioral Economics Report**

Master M2 BDEEM – Behavioral and Digital Economics for Effective Management  
Université Marie et Louis Pasteur – Academic Year 2025–2026  

Authors: **Mohamed PAREULIDZE, Mohamed HAMZA, Eliz SAGER**

---

## 🎯 Project Overview

ARCLAY is a fictional **fintech / smart banking assistant** that helps users cope with
rising inflation, volatile prices and financial stress by combining:

- **Tiered payment cards & cashback**
- **Receipt scanning (OCR) and price comparison**
- **AI-powered personalised nudges**
- **Gamification & habit formation mechanics**

The objective is to design ARCLAY using **behavioural economics** and **neuromarketing**
so that the app:

- Reduces **cognitive and emotional load**
- Increases **perceived value and control**
- Reinforces **habit formation** and **long-term loyalty**   

---

## 🧠 Central Research Question

> **How can ARCLAY leverage neuromarketing and behavioural economics to reduce the cognitive
> and emotional burden of financial decisions while strengthening perceived value, habit
> formation and long-term loyalty?** :contentReference[oaicite:3]{index=3}  

---

## 👥 User Understanding

The project is structured around two core personas:   

1. **The Optimizing Consumer (25–45, active worker)**  
   - Feels overwhelmed by fluctuating prices and hidden overspending  
   - Seeks clarity, price intelligence and visible savings  
   - Neuroscience: strong *insula* activation (pain of paying), dlPFC fatigue, vmPFC value integration  

2. **The Budget-Conscious Student (18–25)**  
   - Lives on a tight budget where every euro counts  
   - Looks for fast wins, promotions and cashback  
   - Neuroscience: highly sensitive to dopaminergic micro-rewards (streaks, progress bars, cashback)  

The **emotional journey** goes from *anxiety* (no visibility) to *curiosity*, *first dopamine hit*,
*habit*, and finally *loyalty & empowerment*.   

---

## 🎨 Brand & Interface Strategy

Key branding and UI decisions:   

- **Slogan:** _“ARCLAY — The Smartest Way.”_  
  - Short, fluent, easy to process → improves memory encoding and perceived simplicity.
- **Colour tiers:**
  - **Starter – Mint Green:** calm, accessible, lowers anxiety & pain of paying  
  - **Smart – Sapphire Blue:** trust, rationality, competence (default “smart” choice)  
  - **Elite – Gold & Black:** reward anticipation & premium status  
- **Interface design:**
  - Minimalistic layout, clear hierarchy of actions (“Scan receipt”, “View savings”, “Best price”)  
  - Micro-interactions (animations, vibrations, badges) as **micro-rewards**  
  - Weekly recaps use the **peak-end rule** to leave a strong positive memory of the experience.  

---

## 💶 Behavioral Economics Architecture

Pricing and cashback structure:   

| Tier    | Monthly Price | Cashback | Colour        |
|--------|---------------|---------|---------------|
| Starter| €2.99         | 1%      | Mint Green    |
| Smart  | €7.99         | 4%      | Sapphire Blue |
| Elite  | €14.99        | 7%      | Gold & Black  |

Core mechanisms:

- **Anchoring:** Starter tier (€2.99) as reference point
- **Decoy Effect:** Elite tier makes Smart look like the rational “best value” option
- **Charm Pricing:** “.99” endings reduce perceived cost
- **Loss Aversion:** framing such as “You may lose €20–30 per month if you ignore these suggestions”
- **Mental Accounting:** turning abstract savings into concrete amounts per product and per week
- **Social Proof:** e.g. “42,000 users saved with ARCLAY this week”  

AI-powered nudges are generated from OCR receipt data, e.g.:

> “Your Lactel milk is €0.45 cheaper at Carrefour today.”

These nudges lower decision costs (less manual comparison) and trigger **dopamine-based reward
anticipation**, increasing engagement. :contentReference[oaicite:8]{index=8}  

---

## 🔁 Loyalty, Habits & Gamification

ARCLAY is designed around a **reinforcement loop**:

**Trigger → Action → Reward → Dopamine → Repetition**   

Examples:

- Notifications when preferred products are cheaper
- Instant feedback after receipt scanning (cashback animation, savings badge)
- **Loyalty levels** (Blue, Silver, Gold) using the **endowed progress effect**
- **Weekly goals** and **streaks** leveraging the **goal-gradient effect**
- Weekly reports applying the **peak-end rule** (“You saved €18.40 this week.”)

Over time, ARCLAY evolves from a simple app into a **“financial companion”** that learns
habits and provides context-aware guidance.

---

## 🧪 Neuromarketing Validation

The project proposes a mixed **EEG + A/B testing** validation framework:   

- EEG frequency bands:
  - **Alpha:** cognitive ease & comfort
  - **Beta:** attention & analytical focus
  - **Theta:** cognitive effort and friction points
  - **Gamma:** memory encoding during emotionally salient events
- Key regions:
  - **Insula:** pain of paying (should decrease with savings feedback)
  - **vmPFC:** value integration (pricing, cashback, nudges)
  - **dlPFC:** cognitive control & budgeting discipline (should be relieved by good UX)

A/B testing compares:

1. **Full behavioural version** (all nudges, framing, gamification)
2. **Reduced-nudge version**
3. **Neutral control interface**

The **KPI framework** includes neuromarketing, behavioural, financial and marketing KPIs
(EEG ratios, receipt scanning frequency, savings per user, WAU, referrals, etc.). :contentReference[oaicite:11]{index=11}  

---

## 📁 Repository Structure

Recommended structure for this repository:

```text
.
├── README.md                      # This file
├── report/
│   └── ARCLAY_Neuromarketing_Report.pdf
├── slides/
│   └── ARCLAY_The_Smartest_Way_Slides.pdf
└── src/                           # (optional) prototypes, UI code, experiments
