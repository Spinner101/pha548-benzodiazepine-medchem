---
marp: true
theme: uncover
paginate: true
backgroundColor: #ffffff
style: |
  section {
    font-family: 'Helvetica', sans-serif;
    text-align: left;
    font-size: 22px;   /* smaller global font */
    padding: 40px;     /* add some breathing room */
  }
  h1 { font-size: 40px; }
  h2 { font-size: 32px; }
  h3 { font-size: 26px; }
  footer { font-size: 14px; color: #7f8c8d; }
  .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }


title: Medicinal Chemistry of Benzodiazepine Sedative-Hypnotics
footer: "PHA 548 | Hampton University | PY1 PharmD"
---

# 🧬 Medicinal Chemistry: Benzodiazepine Sedative-Hypnotics

**Course:** PHA 548 Pharmacology & Medicinal Chemistry  
**Instructor:** Sidney Bolden, Jr., Ph.D.

---

## 🎯 Learning Objectives

By the end of this lecture, you should be able to:

1. **MOA:** Describe benzodiazepine interaction at the $GABA_A$ α–γ interface.  
2. **SAR:** Identify structural features that drive potency, affinity, and selectivity.  
3. **PK/Metabolism:** Predict metabolic pathways and duration of action based on key substituents.  
4. **Innovation:** Evaluate “soft drug” design using remimazolam as a modern example.

---

## $GABA_A$ Receptor: The Biological Target

<div class="columns">
<div>

**Key Concepts**

- **Type:** Pentameric ligand-gated $Cl^-$ channel  
  - Typical stoichiometry: 2α, 2β, 1γ  
- **BZDs bind:** at the **α–γ subunit interface**  
- **Mechanism:** Increase the **frequency** of GABA-induced channel opening  
- **Safety:** Require GABA presence → lower risk vs. barbiturates at therapeutic doses  

</div>
<div>

![GABAA binding site](figures/BZ_Allosteric_Binding.jpg)

</div>
</div>

---

## 🛠️ The BZD Pharmacophore

**Core scaffold: 5-phenyl-1,4-benzodiazepine-2-one**

<div class="columns">
<div>

**Essential Anchors**

1. **Ring A:** Aromatic ring; C7 electronegative substituent (e.g., $Cl$, $Br$, $NO_2$)  
2. **Ring B:** C2 carbonyl and diazepine ring (H-bonding and geometry)  
3. **Ring C:** Phenyl ring providing aromatic $\pi$–$\pi$ stacking in the binding pocket  

> Loss or major distortion of these elements usually leads to large loss of BZD activity.

</div>
<div>

![Backbone](figures/BZ_backbone.jpg)

</div>
</div>

---

## SAR — High-Yield “Cheat Sheet”

| Site | Preferred / Required Feature | MedChem Effect |
| :--- | :--- | :--- |
| **C7 (Ring A)** | Electronegative ($Cl$, $Br$, $NO_2$) | ↑ Affinity and potency |
| **N1 / Ring B** | Small substituents (or H) | Modulates PK; large groups can reduce activity |
| **C3 (Ring B)** | **–OH group** (3-OH BZDs) | ↑ Phase II clearance; shorter duration |
| **C2′ (Ring C)** | o-Halogenation ($F$, $Cl$) | ↑ Lipophilicity, ↑ CNS penetration, often ↑ potency |
| **C4′ (Ring C)** | Bulky substituents | Steric clash; often **abolishes or greatly reduces activity** |

> PY1 Focus: C7, C3, and Ring C substitutions are the most testable and clinically relevant.

---

## 🧪 Metabolism: The Oxidative Liability  
### Example: Flurazepam (Long-Acting)

- **Pathway:** CYP3A4-mediated N-dealkylation and oxidation  
- **Consequence:** Formation of **long-acting active metabolites**  
- **Clinical:**  
  - Extended sedation  
  - Daytime drowsiness  
  - Increased fall/cognitive risk in elderly

![Flurazepam metabolism](figures/flurazepam_metabolism.jpg)

---

## ⚡ Metabolism: The 3-OH Advantage

**3-OH Benzodiazepines**  
(e.g., **Temazepam**, Oxazepam, Lorazepam)

- **Structural feature:** C3 **–OH** group  
- **Pathway:** Direct **Phase II glucuronidation** (UGTs)  
- **Result:**  
  - Minimal Phase I oxidative metabolism  
  - No long-acting active metabolites  
  - **Temazepam** — sedative-hypnotic with safer use in hepatic impairment  

![Temazepam metabolism](figures/Temazepam_metabolism.jpg)

> Note: Lorazepam and oxazepam are not usually used as hypnotics, but share the same 3-OH / Phase II metabolism concept.

---

## 🚀 Modern Innovation: Remimazolam (Byfavo)

**“Soft Drug” Evolution of the Benzodiazepine Scaffold**

- **Core:** Triazolobenzodiazepine-like pharmacophore (preserves GABAA binding)  
- **Design Feature:** Carboxylic **ester side chain** built in as a “soft spot”  
- **Metabolism:**  
  - Rapid hydrolysis by **tissue esterases**  
  - Minimal dependence on CYPs (CYP-mediated routes are minor)  
- **Benefit:**  
  - Predictable, **ultra-short** sedation  
  - Useful for procedural sedation (e.g., endoscopy)  
  - Reduced risk of accumulation even with repeated dosing  

![Remimazolam](figures/Remimazolam-metabolism.jpg)

---

## 📊 Comparative PK Summary

| Drug | Dominant Metabolic Route | PK Outcome (Simplified) |
| :--- | :--- | :--- |
| **Flurazepam** | CYP3A4 (N-dealkylation, oxidation) | Long-acting active metabolites; residual sedation |
| **Estazolam** | Oxidation of triazolo-BZD | Intermediate duration; fewer long-acting metabolites |
| **Temazepam** | Direct Phase II conjugation (3-OH) | Relatively rapid clearance; shorter duration |
| **Remimazolam** | Ester hydrolysis by esterases | Ultra-short duration; soft-drug behavior |

---

## 🧠 PY1 Critical Thinking Exercise

**Predict the outcome of these structural changes (qualitatively):**

1. **Remove C7–Cl:**
   - Expect **markedly reduced potency/affinity** at $GABA_A$ BZD site.

2. **Add bulky para-substitution on Ring C (4′ position):**
   - Likely **abolishes or severely reduces activity** due to steric clash.

3. **Add a fused triazolo ring (triazolobenzodiazepine):**
   - Often **increases potency**  
   - Provides **metabolic shielding**, reducing some oxidative pathways.

> Be prepared to explain your reasoning using SAR logic (electronic, steric, lipophilicity, and metabolism effects).

---

# Questions?

**Next Lecture:** Non-benzodiazepine hypnotics (“Z-drugs”) and comparison of pharmacophore vs. BZDs.
