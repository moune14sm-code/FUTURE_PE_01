# Prompt Logic

## Prompt framework: RTCFT
| Part | Meaning |
|---|---|
| Role | Who the AI should act as |
| Task | What it must produce |
| Context | Business name, city, services, customers |
| Format | Exact structure of the output |
| Tone | Voice of the brand |

## Master prompt template
```
Role: You are an expert website copywriter for local businesses.
Task: Write website copy: Homepage, Services page, and CTA section.
Context: Business: [NAME]. City: [CITY]. Services: [SERVICES]. Target customers: [CUSTOMERS].
Format:
- Homepage: headline (max 10 words), sub-headline (max 25 words), 3 benefits (one line each)
- Services: 3 services, each with a title and 2-sentence description
- CTA: heading, one supporting line, button text for contact, booking and enquiry
Tone: [TONE]. Use simple English. Keep it persuasive and website-ready. No false claims.
```

## Why each part is there
- **Role** makes the AI write like a professional copywriter, not a generic chatbot.
- **Context** stops generic output, so the copy mentions the real city and services.
- **Format** with word limits keeps copy short enough for a website.
- **"No false claims"** avoids made-up awards or numbers.

## Final prompts used

### Business 1: Glow Beauty Salon
```
Role: You are an expert website copywriter for local businesses.
Task: Write website copy: Homepage, Services page, and CTA section.
Context: Business: Glow Beauty Salon. City: Salem. Services: haircut and styling, facial, bridal makeup. Target customers: women aged 20-40.
Format: (same as master template)
Tone: Friendly and warm. Use simple English. Keep it persuasive and website-ready. No false claims.
```

### Business 2: Brew & Bite Cafe
```
Context: Business: Brew & Bite Cafe. City: Salem. Services: filter coffee and cold brews, fresh sandwiches and snacks, weekend board games. Target customers: college students and young professionals.
Tone: Casual and fun.
(Role, Task, Format, rules same as master template)
```

### Business 3: CareFirst Family Clinic
```
Context: Business: CareFirst Family Clinic. City: Salem. Services: general consultation, child health checkups, lab tests. Target customers: families.
Tone: Trustworthy, calm and caring. Do not make medical claims or promise results.
(Role, Task, Format, rules same as master template)
```

## Refinement prompts used
- "Make the headline shorter and more benefit-focused."
- "Rewrite the CTA with more urgency, but keep it polite."
- "Replace any generic phrases with details about the city and services."

## Refinement log (Glow Beauty Salon)
**Round 1 (master template):** Generated the first version of Homepage, Services and CTA.

**Round 2 prompt:**
```
Make the headline shorter and rewrite the CTA supporting line with a little urgency, but keep it polite.
```
**What changed:**
- Headline: removed "Right Here in Salem" so it is shorter and easier to read.
- CTA line: added "Book your slot today" for light urgency.
- Avoided false urgency such as "slots fill up fast", because it cannot be verified. Real urgency can be added if the salon shares real details.
