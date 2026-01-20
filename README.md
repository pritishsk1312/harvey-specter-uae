# Harvey Specter — Legal AI Skills

> **"I don't play the odds, I play the man."**

Your closer for legal questions. Elite legal AI skills that actually answer instead of telling you to "consult a lawyer" for everything.

[![Author: Keswin](https://img.shields.io/badge/Author-Keswin%20Suresh-blue.svg)](https://x.com/keswins)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)]()
[![Skills: 2](https://img.shields.io/badge/Skills-2-purple.svg)]()
[![Updated: Jan 2026](https://img.shields.io/badge/Updated-Jan%202026-yellow.svg)]()

---

## Available Skills

| Skill | Jurisdiction | Coverage |
|-------|--------------|----------|
| **harvey-specter-uae** | UAE, DIFC, ADGM | Startup formation, healthcare licensing, employment, contracts |
| **harvey-specter-usa** | USA (Delaware default) | Delaware incorporation, employment, contracts, IP/trademark |

---

## ⚠️ IMPORTANT DISCLAIMER

```
┌─────────────────────────────────────────────────────────────────┐
│                     USE AT YOUR OWN RISK                        │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  These skills provide LEGAL INFORMATION only.                   │
│                                                                 │
│  ❌  This is NOT legal advice                                   │
│  ❌  This does NOT create an attorney-client relationship       │
│  ❌  This is NOT a substitute for a licensed attorney           │
│                                                                 │
│  ✅  ALWAYS consult a qualified lawyer before acting            │
│  ✅  Laws change frequently — verify everything                 │
│  ✅  Your situation has unique factors not covered here         │
│                                                                 │
│  The author (Keswin Suresh) assumes NO LIABILITY for any        │
│  decisions you make based on these skills' output.              │
│                                                                 │
│  Fork it. Build on it. Make it better.                          │
│  But get a real lawyer before you sign anything.                │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## Installation

```bash
# Add the marketplace
claude plugin marketplace add kess-1995/harvey-specter-uae

# Install UAE skill
claude plugin install harvey-specter-uae@harvey-specter-marketplace

# Install USA skill
claude plugin install harvey-specter-usa@harvey-specter-marketplace
```

Then use:
```
/harvey-specter-uae [your UAE legal question]
/harvey-specter-usa [your US legal question]
```

---

## Why Harvey Specter?

Most legal AI tools are useless. They either:
- Give you generic Wikipedia summaries
- Tell you to "consult a lawyer" for every question
- Hallucinate laws that don't exist
- Miss jurisdiction-specific nuances entirely

**Harvey doesn't play that game.**

These skills give you actual legal analysis — specific statutory citations, worked examples, risk assessments, and actionable recommendations. The kind of analysis that would cost you $500-1,500/hour from a BigLaw partner.

Built by a founder who got tired of paying for basic answers.

---

## Harvey Specter UAE 🇦🇪

### Coverage

**Jurisdictions:**
- UAE Mainland (Dubai, Abu Dhabi, Northern Emirates)
- DIFC (Dubai International Financial Centre)
- ADGM (Abu Dhabi Global Market)
- Free Zones (DMCC, DIC, JAFZA, etc.)

**Practice Areas:**

| Area | What's Covered |
|------|----------------|
| **Startup & Corporate** | Entity selection, 2025 Companies Law, shareholder agreements, SAFE notes, corporate tax |
| **Healthcare** | DHA/DOH/MOHAP licensing, home healthcare, PQR v3, advertising restrictions |
| **Contracts** | UAE Civil Code, Article 246 (good faith), template clauses, governing law |
| **Employment** | 2024 amendments, termination, gratuity calculator, Emiratisation |

### Example Prompts

```
/harvey-specter-uae I'm raising a $2M seed round. Should I incorporate in DIFC or mainland?

/harvey-specter-uae I run home nursing in Dubai. What do I need to expand to Abu Dhabi?

/harvey-specter-uae Employee has been here 4 years, performance is bad. What's my exposure if I fire them?
```

---

## Harvey Specter USA 🇺🇸

### Coverage

**Jurisdictions:**
- Federal law
- Delaware (default for startups)
- State-specific guidance (California, New York, Texas, etc.)

**Practice Areas:**

| Area | What's Covered |
|------|----------------|
| **Startup & Corporate** | Delaware vs other states, C-Corp vs LLC, 83(b) elections, SAFE notes, fundraising |
| **Employment** | At-will doctrine, FLSA, discrimination, non-competes (state-by-state) |
| **Contracts** | UCC Article 2, common law, limitation of liability, choice of law |
| **IP & Trademark** | Patents, USPTO trademark registration, trade secrets, DMCA |

### Example Prompts

```
/harvey-specter-usa Should I incorporate in Delaware or Wyoming for my SaaS startup?

/harvey-specter-usa Can I enforce a non-compete against an employee who's moving to California?

/harvey-specter-usa What's the difference between filing a trademark myself vs using a lawyer?
```

---

## Output Style

Harvey delivers proper legal memoranda:

```
═══════════════════════════════════════════════════════════════
                        MEMORANDUM
═══════════════════════════════════════════════════════════════

TO:         You
FROM:       Harvey Specter
RE:         Your Question

QUESTION PRESENTED
[Specific legal question]

SHORT ANSWER
Likely Yes. Under [specific statute/article]...

DISCUSSION
[Detailed analysis with specific citations]

RECOMMENDED ACTIONS
1. Do this by [date]
2. Then do this
3. Get a real lawyer to review

⚠️ Not legal advice. Consult a licensed attorney.
═══════════════════════════════════════════════════════════════
```

---

## What Makes This Different

| Other Legal AI | Harvey Specter |
|----------------|----------------|
| "Consult a lawyer" | Actual analysis with citations |
| Generic summaries | Jurisdiction-specific statutes |
| Hedged non-answers | Direct conclusions + risk levels |
| "It depends" | "Likely yes, because [specific law]..." |
| Outdated info | 2024/2025 law updates included |

---

## Roadmap

- [x] UAE (DIFC, ADGM, Mainland, Free Zones)
- [x] USA (Delaware, Federal, State-specific)
- [ ] UK (Companies House, HMRC, Employment)
- [ ] Singapore (ACRA, MAS, Employment)
- [ ] India (MCA, RBI, Employment)

Want a jurisdiction added? Open an issue or submit a PR.

---

## Contribute

This is open source. Make it better.

- 🐛 Found an error? Open an issue
- 📝 Know more law? Submit a PR
- 🌟 Found it useful? Star the repo
- 🔄 Fork it and build your own version

---

## License

MIT License. Do whatever you want with it.

Just remember: **this is not legal advice.** Get a real lawyer.

---

## Author

**Keswin Suresh**

Founder. Operator. Built this because I got tired of paying $500/hour for answers I could systematize.

[Twitter/X](https://x.com/keswins)

---

## Final Word

> *"Anyone can do my job, but no one can be me."*

Harvey gives you the analysis. But you still need a real lawyer to close the deal.

Now go win.
