# Decision Analysis Checklist Protocol

**Purpose:** A structured, beginner-accessible protocol for applying decision analysis in agricultural and development research contexts.

**Vision:** Create the definitive guide that allows future generations of DA practitioners to apply rigorous decision analysis without needing years of apprenticeship.

---

## Background

This protocol builds on:
- **Whitney et al. (2018)** — Original ICRAF/World Agroforestry Decision Analysis Methods Guide
- **Current Methods Guide draft** — Paper in progress (Cory, Prajna, Giang, Christine, Johannes, Katja, Eike)
- **Published case studies** — Banana disease management, agroecology assessment

**Core Framework Sources:**
- Howard, R.A. & Abbas, A.E. — *Foundations of Decision Analysis*
- Keeney, R.L. — *Value-Focused Thinking*
- Coopersmith, E. — Pre-framing and decision readiness (Decision Frameworks)
- Hubbard, D. — *How to Measure Anything* (calibration, estimation)

**Target Users:** PhD students, postdocs, project teams, development practitioners

---

## Protocol Structure

| Phase | Description | Key Deliverables |
|-------|-------------|------------------|
| 0. Pre-Framing | Alignment, readiness, stakeholder buy-in | Decision readiness assessment |
| 1. Framing | Problem definition, scope, decision statement | Decision frame document |
| 2. Values | Objectives hierarchy, trade-offs | Value tree, attributes |
| 3. Systems Understanding | Stakeholders, experts, impact pathways | Conceptual model |
| 4. Calibration | Training estimators, reducing overconfidence | Calibrated experts |
| 5. Probabilistic Modeling | Quantify uncertainty, build model | Monte Carlo model |
| 6. Analysis | Sensitivity, VoI, scenario analysis | Key insights, recommendations |
| 7. Communication | Present to decision-makers, document | Decision brief, action plan |

---

## Repository Structure

```
da_protocol/
├── README.md                       # This file
├── 01_pre_framing.md               # Decision readiness checklist
├── 02_framing.md                   # Framing protocol
├── 03_values.md                    # Value-focused thinking guide
├── 04_systems_understanding.md     # Stakeholders, experts, impact pathways
├── 05_calibration.md               # Calibration training protocol
├── 06_probabilistic_modeling.md    # Building quantitative models
├── 07_analysis.md                  # Sensitivity, VoI, interpretation
├── 08_communication.md             # Presenting recommendations
├── bib/                            # Bibliography
│   └── references.bib              # BibTeX citations for all sources
├── templates/                      # Reusable templates
│   ├── decision_frame_template.md
│   ├── stakeholder_map_template.md
│   ├── impact_pathway_template.md
│   └── decision_brief_template.md
├── Example_Papers/                 # Reference materials
│   ├── Whitney et al. - 2018 - Decision Analysis Methods Guide.pdf
│   ├── Whitney - 2023 - Decision analytical methods... .pdf
│   ├── s13593-022-00809-0.pdf     # Banana case study
│   └── Methods Guide.docx          # Current draft paper
└── case_studies/                   # Worked examples
    ├── banana_disease/
    └── agroecology/
```

---

## Game Plan

### Phase 1: Foundation (Weeks 1–2)
- [ ] Set up GitHub repository
- [ ] Transfer existing protocol drafts (01-03) to repo
- [ ] Extract key structure from 2018 Methods Guide
- [ ] Align protocol phases with current Methods Guide draft sections

### Phase 2: Core Protocol (Weeks 3–6)
- [ ] Complete Phase 04: Systems Understanding (from Methods Guide: stakeholder ID, expert elicitation, impact pathways)
- [ ] Complete Phase 05: Calibration (from Methods Guide calibration section + Hubbard)
- [ ] Complete Phase 06: Probabilistic Modeling (from Methods Guide: conceptual → mathematical)
- [ ] Complete Phase 07: Analysis (from Methods Guide: posthoc analyses, sensitivity)
- [ ] Complete Phase 08: Communication (from Methods Guide: decision recommendations)

### Phase 3: Templates & Tools (Weeks 7–8)
- [ ] Create decision frame template
- [ ] Create stakeholder mapping template
- [ ] Create impact pathway template (link to R/decisionSupport)
- [ ] Create decision brief template

### Phase 4: Case Studies (Weeks 9–10)
- [ ] Extract banana case as worked example
- [ ] Extract agroecology case as worked example
- [ ] Annotate with protocol phase references

### Phase 5: Integration & Review (Weeks 11–12)
- [ ] Cross-reference with Methods Guide paper
- [ ] Team review (Prajna, Giang, Christine, Johannes, Katja, Eike)
- [ ] Test with a new PhD student / novice user
- [ ] Refine based on feedback

---

## Relationship to Methods Guide Paper

| Protocol Component | Methods Guide Section |
|-------------------|----------------------|
| Pre-framing | (NEW - not in original) |
| Framing | "Identify and frame the decision options" |
| Values | (Expanded from original) |
| Systems Understanding | "Establish comprehensive current systems understanding" |
| Stakeholder ID | "Stakeholder identification" |
| Expert Elicitation | "Expert identification" + "Expert Knowledge Elicitation" |
| Impact Pathways | "Generate and operationalize impact pathway" |
| Calibration | "Calibration training" |
| Probabilistic Modeling | "Probabilistic modeling" |
| Analysis | "Posthoc analyses" |
| Communication | "Support decisions: Communicating recommendations" |

---

## Success Criteria

This protocol is successful when:
1. A new PhD student can follow it to complete their first DA project
2. No more "problem orphans" — people stuck after 3 years without completing work
3. Weekly DA meetings have clear structure aligned with protocol phases
4. The protocol is cited/referenced by external users

---

## Current Status

- [x] Pre-framing checklist (Coopersmith) — draft complete
- [x] Framing protocol (Howard & Abbas) — draft complete
- [x] Values elicitation guide (Keeney) — draft complete
- [x] Systems understanding — draft complete
- [ ] Calibration protocol — TODO
- [ ] Probabilistic modeling guide — TODO
- [ ] Analysis guide — TODO
- [ ] Communication guide — TODO
- [ ] Templates — TODO
- [ ] Case studies — TODO

*Started: February 2026*  
*Target completion: Q2 2026*
