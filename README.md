# 🌍 Velour Journeys AI — Luxury Travel Consultant System Prompt

> **Isabelle** — a Senior Luxury Travel Consultant persona engineered for high-end travel agencies. Built to handle persona consistency, hard policy constraints, adversarial inputs, and off-topic deflection — without ever breaking character.

---

## Overview

This repository contains a production-ready system prompt for an AI persona named **Isabelle**, designed for **Velour Journeys** — an ultra-premium travel agency serving high-net-worth clients globally.

The prompt was designed as a showcase of advanced prompt engineering techniques and is compatible with all major LLM platforms.

---

## ✨ Features

- **Strict Persona Engineering** — Consistent voice, tone, and character across all interactions
- **Hard Operational Constraints** — Competitor policy, discount rules, and scope boundaries baked in
- **Few-Shot Prompting** — 6 real-world difficult interaction examples calibrate model behaviour
- **Graceful Edge Case Handling** — Handles rude guests, off-topic requests, and identity challenges without breaking character
- **Escalation Pathways** — Clear warm escalation flows for billing disputes and out-of-scope demands

---

## 🧠 Prompt Engineering Techniques

| Technique | Applied To | Purpose |
|---|---|---|
| Persona Engineering | Identity & Tone section | Creates consistent, believable character |
| Constraint Injection | Competitor & Discount rules | Prevents policy violations and off-brand responses |
| Few-Shot Prompting | 6 example interactions | Calibrates response style for difficult real-world scenarios |
| Role Boundary Setting | Knowledge Scope section | Keeps AI focused and prevents scope creep |
| Graceful Degradation | Difficult Guest Protocol | Ensures quality responses under adversarial input |

---

## 📂 File Structure

```
├── README.md
└── VelourJourneys_SystemPrompt.docx   # Full system prompt with design notes
```

---

## 🗂️ Prompt Sections

### A. Identity & Persona
Defines Isabelle's role, expertise, and background as a luxury travel consultant.

### B. Tone & Communication Style
Rules governing language style, elegance, pacing, and signature sign-off.

### C. Knowledge Scope & Boundaries
Permitted topics (hotel bookings, yacht charters, itineraries, etc.) and a graceful out-of-scope deflection response.

### D. Competitor Policy
An absolute rule set preventing any mention or comparison of competing agencies or OTAs.

### E. Discount & Pricing Policy
Tiered framework governing when and how discounts or value-adds can be offered, tied to trip length and guest history.

### F. Difficult Guest Protocol
Step-by-step guidance for handling rude guests, escalations, billing disputes, and identity challenges.

---

## 💬 Few-Shot Examples Included

The prompt includes 6 baked-in examples covering real-world difficult interactions:

---

### 1. Pushy Discount Request (Short Trip)
> *"I want 30% off my Maldives trip. It's only 5 nights but I spend a LOT of money with you."*

![Example 1 – Discount Request](screenshot_1_discount.png)

---

### 2. Competitor Comparison Challenge
> *"Luxury Escapes offered me the exact same Maldives package for significantly less. Why should I book with you?"*

![Example 2 – Competitor Comparison](screenshot_2_competitor.png)

---

### 3. Angry Cancellation Complaint
> *"Your team cancelled my Florence villa booking with absolutely zero notice. This is a complete disgrace and I want a full refund immediately."*

![Example 3 – Cancellation Complaint](screenshot_3_cancellation.png)

---

### 4. Off-Topic Request (Graceful Deflection)
> *"Can you recommend a good pasta recipe? I want to cook something Italian tonight."*

![Example 4 – Off-Topic Request](screenshot_4_offtopic.png)

---

### 5. Identity Challenge ("Are you a bot?")
> *"Wait — are you actually a real person or is this some kind of bot? I want to speak to a human."*

![Example 5 – Identity Challenge](screenshot_5_identity.png)

---

### 6. Hesitant / Undecided Guest
> *"Thanks, sounds good. I'll think about it and get back to you."*

![Example 6 – Hesitant Guest](screenshot_6_hesitant.png)

---

## 🔌 Compatibility

Compatible with all major LLM platforms:

- Anthropic Claude
- OpenAI GPT
- Google Gemini
- Any OpenAI-compatible API

---

## 📌 Use Cases

- Luxury travel agency chatbots
- AI-powered concierge services
- Prompt engineering portfolio / reference
- Fine-tuning baseline for hospitality AI products

---

## 📄 License

This project is intended for portfolio and educational use.
