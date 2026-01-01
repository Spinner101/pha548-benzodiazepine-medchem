# PHA 548 Assessment Bank — ExamSoft Integration Guide

This folder houses the **official secure assessment versions** for Lecture 01: Benzodiazepine Sedative-Hypnotics.  
It is designed for **easy extraction and import** into **ExamSoft / Examplify**, Canvas, or other assessment systems.

---

## 📂 Folder Contents

| File Name | Purpose |
|----------|---------|
| L01_BZD_iRAT_TRAT_bank.md | Human-readable version (faculty editing) |
| L01_BZD_item_bank.json | Machine-readable version for automated conversion |
| README.md | This instruction file |

> **Faculty Edit Rule**  
> Update questions **only in the Markdown file** (`L01_BZD_iRAT_TRAT_bank.md`).  
> Automated tools will regenerate the `.json` for import formatting.

---

## 🎯 ExamSoft Export Overview

ExamSoft supports **CSV import**, **Rich Text**, or **QTI XML**.  
We use CSV for fastest alignment:

### Required ExamSoft CSV Fields

| ExamSoft Column | Our Source Tag in JSON/MD |
|----------------|--------------------------|
| Question Type  | `"multiple_choice_single"` *(default)* |
| Question Title | `"id"` (e.g., L01_Q5) |
| Question Stem | `"stem"` |
| Correct Answer | `"correct_option_index"` |
| Answer Choices | `"options[]"` |
| Category / Outcome Mappings | `"blooms_level"`, `"acpe_outcomes[]"`, `"topic_tags[]"`, `"naplex_domain"` |

Optional import fields supported from our bank:

- **Comments / Solutions** → Rationale (in Markdown)
- **Distractor analysis metadata** retained (for future psychometrics tracking)

---

## 🧪 Difficulty & Discrimination

Each item includes **pre-assigned psychometric targets**:

| Metric | Tag in JSON | Expected Value |
|--------|-------------|----------------|
| Difficulty | `"difficulty_target_p"` | 0.55–0.80 |
| Discrimination | `"discrimination_target_d"` | ≥ 0.30 |

These tags align with **ACPE Standard 1** and **NAPLEX competency distribution** for item quality monitoring.

> After administration, faculty should upload ExamSoft export metrics  
> → update this repository with **observed** p-values & discrimination for longitudinal analytics.

---

## 🔄 Conversion Process (Local Script)

Run the conversion tool (Python script coming in `tools/convert_to_examsoft.py`) to generate importable files:

```bash
# Example command
python tools/convert_to_examsoft.py \
  --input lectures/01_BZD_MedChem/assessments/L01_BZD_item_bank.json \
  --output exams/PHA548_L01_ExamSoft.csv
