---
marp: true
theme: default
paginate: true
title: Medicinal Chemistry of Benzodiazepine Sedative-Hypnotics
author: PHA 548 – Pharmacology & Medicinal Chemistry
---

# 🧬 Medicinal Chemistry of Benzodiazepine Sedative-Hypnotics

**Course:** PHA 548 Pharmacology & Medicinal Chemistry  
**Reference:** *Foye’s Principles of Medicinal Chemistry, 8th Ed.*

---

## 🎯 Learning Objectives

By the end of this 75–90 minute lecture, you should be able to:

1. Explain how benzodiazepines interact with the GABAA receptor at the α–γ interface.  
2. Analyze key SAR features that govern affinity, potency, and subtype preference.  
3. Predict pharmacokinetic behavior from structural modifications.  
4. Evaluate design improvements that led to newer agents such as remimazolam.

---

## 🧠 GABAA Receptor & Benzodiazepine MOA

- GABAA is a **pentameric ligand-gated Cl⁻ channel**  
  - Typical stoichiometry: **2α + 2β + 1γ**
- Benzodiazepines bind at the **α–γ subunit interface**  
- They **do not** activate the receptor alone  
  - They **enhance GABA’s effect** by increasing the **frequency** of Cl⁻ channel openings  
- Result: **Neuronal hyperpolarization** and reduced excitability

---

## α Subunit Selectivity

| α Subunit | Primary Functional Effect |
|----------|---------------------------|
| α1       | Sedation, anterograde amnesia, anticonvulsant |
| α2 / α3  | Anxiolysis, muscle relaxation |
| α5       | Cognitive effects / memory impairment |

> Medicinal chemistry takeaway: small structural changes can bias activity toward α1 vs α2/3/5–containing receptors.

---

## Required Benzodiazepine Pharmacophore

**Core scaffold: 5-phenyl-1,4-benzodiazepine-2-one**

Key features:

- **Ring A (benzene)** with **C7 electronegative substituent**  
- **Ring B (diazepine)** with **N1–C2 carbonyl**  
- **Ring C (C5 phenyl)** providing an aromatic π-system

---

![Benzodiazepine backbone and sedative-hypnotic benzodiazepines (Foye Fig. 12.6)](figures/figure_12.6.jpg)

*5-Phenyl-1,4-benzodiazepin-2-one backbone and sedative-hypnotic benzodiazepines (Flurazepam, Quazepam, Triazolam, Estazolam, Temazepam).*

---

## Pharmacophore – Functional Elements

| Feature                          | Why It’s Required                                  |
|----------------------------------|----------------------------------------------------|
| **C7 electronegative group**     | Increases GABAA affinity via electronic effects    |
| **C5 phenyl ring (Ring C)**      | Aromatic π–π stacking in binding pocket           |
| **N1–C2 carbonyl**               | H-bond anchoring at BZD binding site              |

Color convention (for SAR overlays in notes):  
- 🟪 Ring A  🟦 Ring B  🟥 Ring C

---

## SAR Overview – Key Sites

| Site                 | MedChem Rule                        | Effect                              |
|----------------------|-------------------------------------|-------------------------------------|
| **C7 (Ring A)**      | Electronegative (Cl, Br, NO₂)       | Essential for high potency          |
| **C5 phenyl (Ring C)** | Must remain planar and aromatic  | Required for agonist activity       |
| **o-halogenation**   | 2′-F / 2′-Cl on Ring C             | ↑ Lipophilicity, ↑ CNS penetration |
| **p-substitution**   | Bulky groups at para position       | Steric clash → ↓ binding / inactive |
| **C3–OH group**      | Introduces conjugation site         | Shorter duration (Phase II)         |
| **Triazolo/imidazo fusion** | Metabolic shielding        | ↑ Potency, ↓ active metabolites     |
| **Ester moiety** (remimazolam-like) | Esterase substrate | Ultra-short, hydrolysis-driven t½   |

---

## SAR → Pharmacokinetics Theme

- **Lipophilicity** drives:
  - CNS penetration  
  - Tissue distribution  
  - Duration of action

- **Metabolic “soft spots”**:
  - Exposed N-alkyl chains → CYP N-dealkylation → active metabolites  
  - Aromatic rings → hydroxylation → Phase II conjugation

- **Design philosophy** for newer agents:
  > Replace **oxidative liabilities** with **hydrolytic or conjugation liabilities**.

---

## Case SAR Examples – Classical BZDs

- **Flurazepam**
  - N-alkyl chain at N1  
  - Lipophilic o-halogenated phenyl ring  
  - → Multiple long-acting active metabolites

- **Quazepam**
  - Very lipophilic and sulfur-containing moiety  
  - → Long t½ and metabolite accumulation

- **Triazolam / Estazolam**
  - **Fused triazole ring** reduces oxidative metabolism  
  - More predictable, shorter duration

- **Temazepam**
  - **C3–OH** promotes direct glucuronidation  
  - Minimizes Phase I metabolism, short duration

---

## Metabolism of Flurazepam & Quazepam

![Metabolism of flurazepam and quazepam (Foye Fig. 12.7)](figures/figure_12.7.jpg)

*Note the N-dealkylation and formation of long-acting active metabolites.*

---

## PK & Metabolism Comparison

| Drug        | Key SAR Feature       | Primary Metabolic Route    | PK Outcome                         |
|-------------|-----------------------|----------------------------|------------------------------------|
| Flurazepam  | N-alkyl at N1         | CYP3A4 N-dealkylation      | Very long-acting active metabolites |
| Quazepam    | Highly lipophilic     | CYP3A4 / CYP2C9 oxidation  | Prolonged duration, accumulation   |
| Estazolam   | Triazolo fusion       | CYP3A4 hydroxylation       | Intermediate t½, limited actives   |
| Triazolam   | Compact triazolo BZD  | Oxidation → conjugation    | Short-acting, minimal accumulation |
| Temazepam   | C3–OH                 | Direct glucuronidation     | Rapid clearance, short duration    |
| Remimazolam | Ester-containing side chain | Esterase hydrolysis | Ultra-short duration, predictable  |

---

## Remimazolam – Design Rationale

- Maintains **benzodiazepine pharmacophore** for GABAA binding  
- Incorporates a **cleavable ester** in the side chain  
  - Substrate for **tissue carboxylesterases**  
  - Rapid inactivation to non-BZD metabolite  
- Minimizes dependence on CYP enzymes

> Medicinal chemistry goal: **tight temporal control** of sedation.

---

## Active Learning – Structural Prediction

For each structural change, predict:

1. Effect on receptor binding (↑, ↓, or inactive)  
2. Effect on PK (shorter, longer, or unchanged t½)  

Examples:

- Remove the **C7-Cl** and replace with H  
- Add a **bulky para-substituent** on the C5 phenyl ring  
- Introduce a **C3–OH** group  
- Fuse a **triazole ring** onto Ring B  
- Add an **ester side chain** similar to remimazolam

Discuss in pairs, then we review as a group.

---

## Key Takeaways

- Benzodiazepines require:
  - **C7 electronegative substitution**
  - **C5 phenyl ring**
  - **N1–C2 carbonyl**

- SAR modifications can:
  - Tune **affinity and selectivity**  
  - Dramatically change **t½ and metabolic fate**

- Newer drugs (e.g., **remimazolam**) are engineered using:
  - Ester **hydrolysis** instead of oxidative pathways  
  - Design for **predictable, ultra-short** sedation

---

## Molecular Note – Flumazenil

- **Competitive antagonist** at the same benzodiazepine α–γ binding site  
- Recognizes the **same pharmacophore** but lacks intrinsic efficacy

---

# Questions?

Thank you!  
Next session: Non-benzodiazepine GABAA modulators and sedative-hypnotic SAR.

