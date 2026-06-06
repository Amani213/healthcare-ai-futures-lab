# 🏥 Healthcare AI Futures Lab

> *Learn the future before it arrives.*

A free, open-source clinical AI governance simulation for NHS leaders, clinicians, digital professionals, regulators, and educators. Built as interactive HTML files — no installation, no login, no data collected.

**▶ [Play it now](https://healthcare-ai-futures-lab.vercel.app)** · [Report an issue](https://github.com/Amani213/healthcare-ai-futures-lab/issues) · [Contribute](#contributing)

---

## What is this?

Healthcare AI Futures Lab is a decision simulation that places you inside real NHS AI governance dilemmas. Every choice has second and third-order consequences. There are no perfect answers — only defensible ones.

Each scenario tracks four interconnected metrics — patient safety, clinical trust, innovation, and financial sustainability — and generates a full debrief tied to NHS clinical AI governance frameworks.

---

## Why does this exist?

The NHS is deploying AI into clinical workflows faster than governance frameworks, workforce capability, and patient safety infrastructure can keep pace. Algorithmic inequity — where AI tools trained on historically biased data reproduce and amplify health disparities — is an active and underacknowledged risk.

This tool closes the gap through experiential learning: putting decision-makers inside the complexity *before* they face it in practice.

It is designed for:

- 🩺 **Clinicians** encountering AI-assisted decision support for the first time
- 🛡️ **Clinical Safety Officers** navigating DCB0129/0160 obligations
- 🧠 **CxIOs** (CNIOs, CMIOs, CAHPIOs) managing AI adoption and equity
- 🏛️ **NHS executives and board members** making AI investment decisions
- 🎓 **Educators** in healthcare, nursing, medicine, and health informatics
- ⚖️ **Regulators and policy professionals** stress-testing governance frameworks
- 👥 **Lived experience advocates** understanding NHS AI decision-making

---

## Scenarios

| Level | Role                            | Scenario                                                       | File                             | Status         |
| ----- | ------------------------------- | -------------------------------------------------------------- | -------------------------------- | -------------- |
| 1     | Junior Doctor                   | AI-assisted clinical decisions at the bedside                  | —                                | 🔜 Coming soon  |
| **2** | **Clinical Safety Officer**     | **The Sepsis Signal Problem**                                  | `healthcare-ai-futures-lab.html` | **✅ Playable** |
| **3** | **CxIO — Algorithmic Equity**   | **The Invisible Patient — EIP pathway AI and equity**          | `level3-cxio-psychosis.html`     | **✅ Playable** |
| **3b**| **CxIO — Workforce Adoption**   | **The Adoption Gap — nursing AI, deskilling, NMC accountability** | `healthcare-ai-futures-lab.html` | **✅ Playable** |
| **4** | **Trust Chief Executive**       | **The Vendor Expansion — procurement, equity, parliament**     | `healthcare-ai-futures-lab.html` | **✅ Playable** |
| 5     | ICB Executive                   | Population health, system-wide impact, resource allocation     | —                                | 🔜 Coming soon  |
| 6     | National Regulator              | Standards, oversight, and enforcement                          | —                                | 🔜 Coming soon  |
| 7     | Secretary of State              | National strategy, workforce disruption, AGI preparedness      | —                                | 🔜 Coming soon  |

The career progression model is intentional. Each level reveals a wider system perspective — showing how clinical, organisational, and national AI decisions interact, and how accountability shifts as your role broadens.

### File structure

The repository contains two HTML files:

- **`healthcare-ai-futures-lab.html`** — Multi-scenario file containing Levels 2, 3b, and 4. Open it once, choose a scenario from the title screen.
- **`level3-cxio-psychosis.html`** — Standalone deep-dive on algorithmic equity in NHS mental health (Early Intervention in Psychosis pathway). Held separately because of the depth of the equity material.

---

## Governance frameworks referenced

The simulations are grounded in real NHS and UK regulatory standards. Across the scenarios you will encounter:

- **DCB0129** — Clinical Risk Management for Health IT Systems (manufacturer)
- **DCB0160** — Clinical Risk Management for Health IT Systems (deploying organisation)
- **MHRA AI as a Medical Device (AIaMD)** guidance and post-market surveillance
- **CQC** regulatory expectations for digital safety and algorithmic equity
- **Patient Safety Commissioner** guidance on CEO accountability for AI-related harm
- **LFPSE** — Learn from Patient Safety Events
- **UK GDPR Article 22** — automated decision-making with significant effect on individuals
- **Public Sector Equality Duty** — Equality Act 2010, protected characteristics
- **Workforce Race Equality Standard (WRES)** — health inequalities monitoring
- **NMC Code** — professional accountability for nursing documentation and clinical decisions
- **RCN** — professional engagement and union representation in workforce-impacting technology
- **Topol Review (2019)** — workforce readiness for digital transformation
- **NHS England AI procurement guidance** and the NHS AI Procurement Playbook
- **NHS Long Term Plan** — mental health and health inequalities commitments

---

## How to use

### Play it now

Open either HTML file directly in any modern browser. No server, no dependencies, no data collected. Or play hosted at **[healthcare-ai-futures-lab.vercel.app](https://healthcare-ai-futures-lab.vercel.app)**.

- `healthcare-ai-futures-lab.html` — Levels 2, 3b, and 4 (choose from title screen)
- `level3-cxio-psychosis.html` — Level 3 algorithmic equity deep-dive

### Host on GitHub Pages

1. Fork this repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder
4. Both scenarios will be live at `https://yourusername.github.io/healthcare-ai-futures-lab/`

### Use in a training programme

All simulations run entirely in-browser with no external dependencies. You can:

- Share links before a workshop for pre-reading/play
- Use live in group sessions with structured debrief after each round
- Assign as standalone e-learning
- Host on your organisation's intranet by copying the HTML files
- Pair multiple scenarios to show how the same AI failure looks different at different roles — e.g. Level 2 CSO with Level 4 CEO to surface how accountability shifts across the hierarchy

A **facilitator guide** with suggested debrief questions per round (including notes on contested decisions) is in development. Level 3 in particular contains decisions where the *wrong* answer has a defensible rationale — facilitator framing matters.

### Keyboard shortcuts

- `1` `2` `3` — select decision option A, B, or C
- `Enter` — confirm selection
- `Tab` / `Shift+Tab` — navigate interactive elements

---

## Design principles

1. **Decision-rich environments** — every choice has second- and third-order consequences
2. **No perfect answers** — the simulation reflects real governance dilemmas, not training manuals
3. **Hidden system dynamics** — the player never sees impact deltas before deciding; consequences emerge after the choice
4. **Pedagogical grounding** — debrief tied to named frameworks, not generic reflection prompts
5. **NHS-authentic** — scenarios, roles, regulatory context, and stakeholder tensions drawn from real practice
6. **Equity by design** — algorithmic inequity is treated as a patient safety issue, not an ethics add-on

---

## Roadmap

- [x] Level 2 — Clinical Safety Officer (sepsis AI, alarm fatigue, DCB0129/0160)
- [x] Level 3 — CxIO algorithmic equity (EIP pathway AI, UK GDPR Art. 22)
- [x] Level 3b — CxIO workforce adoption (ambient documentation, NMC, RCN, deskilling)
- [x] Level 4 — Trust CEO (vendor expansion, equity audit, parliamentary evidence)
- [ ] Level 1 — Junior Doctor (AI-assisted bedside decisions)
- [ ] Level 5 — ICB Executive (system-wide allocation and population health)
- [ ] Level 6 — National Regulator (standards, oversight, enforcement)
- [ ] Level 7 — Secretary of State (national strategy, workforce disruption, AGI preparedness)
- [ ] Facilitator debrief mode (trainer-navigable view with contested-decision notes)
- [ ] Mid-round reflection prompts (Socratic questioning layer)
- [ ] Delayed-consequence model (Round 1 decisions surfacing in Round 3 narrative and stakeholder memory)
- [ ] Multiplayer / cohort mode for group learning
- [ ] Scenario authoring tool (create your own NHS AI governance dilemmas)
- [ ] Integration with **ClinAudit AI** governance framework

---

## Contributing

Contributions are welcome — particularly from:

- NHS clinical safety officers and CxIOs with scenario ideas
- Mental health clinicians and lived experience advocates
- Human factors and patient safety professionals
- Clinical informaticists and health equity researchers
- Healthcare educators and curriculum leads
- AI governance, ethics, and procurement specialists

Please open an issue to propose a new scenario, flag a clinical or regulatory inaccuracy, or suggest a feature. Pull requests welcome.

If you have direct experience of algorithmic equity failures in NHS services — as a clinician, service user, or advocate — and would like to contribute to scenario development, please get in touch via the issues page.

---

## Related projects

**[ClinAudit AI](https://clinaudit-ai-mu.vercel.app)** — an open-source clinical AI governance and audit platform for auditing NHS-deployed AI against DCB0129/0160, UK GDPR Article 22, the CERSI-AI Pre-Procurement Readiness Gate, the HAIP Vendor Disclosure framework, ISO/IEC 42001, and BS 30440:2023.

Healthcare AI Futures Lab and ClinAudit AI are designed to be complementary: this Lab helps decision-makers *learn* the dilemmas; ClinAudit AI helps them *govern* the deployments.

---

## Licence

MIT Licence. Free to use, adapt, and redistribute with attribution.

If you use this in a training programme, academic course, or NHS initiative, a note or link back is appreciated but not required.

---

## Author

Developed by **[Sarah Amani](https://www.linkedin.com/in/sarahamani)** — independent clinical AI governance consultant, registered mental health nurse (NMC 01B1028E), Topol Digital Fellow, and former NHS CNIO and Clinical Safety Officer with over 22 years of NHS experience. National programme co-leadership for Early Intervention in Psychosis (Time4Recovery, 2017); author of DCB0129/0160 clinical safety cases across 18 AI and digital health deployments.

Working at the intersection of clinical practice, digital governance, and AI safety — and founder of the [Kwathu Breakfast Club](https://www.linkedin.com/in/sarahamani) in Nkhotakota, Malawi, which feeds over 100 children daily.

[LinkedIn](https://www.linkedin.com/in/sarahamani) · [ClinAudit AI](https://clinaudit-ai-mu.vercel.app)

---

*Healthcare AI Futures Lab is an independent open-source project. It is not affiliated with NHS England, NHSX, the MHRA, or any commercial vendor.*
