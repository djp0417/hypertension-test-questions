# Hypertension Test Questions

A comprehensive dataset of hypertension test questions based on the **2024 Chinese Guidelines for the Prevention and Treatment of Hypertension** (*中国高血压防治指南（2024年修订版）*).

## Dataset Overview

| File | Type | Questions | Description |
|------|------|-----------|-------------|
| `hypertension_essay.csv` | Essay / Short Answer | 51 | Detailed short-answer and essay questions covering etiology, diagnosis, treatment strategies, and special populations |
| `hypertension_judgment.csv` | True/False | 212 | Binary true/false questions covering the full scope of the 2024 guidelines |
| `hypertension_objective_questions.csv` | Objective (True/False) | 101 | Concise true/false questions on key guideline knowledge points |
| `hypertension_objective_questions_2.csv` | Objective (True/False) | 101 | Additional true/false questions with quoted formatting |
| `hypertension_subjective_questions.csv` | Subjective (Short Answer) | 25 | Open-ended questions with detailed multi-point answers |
| `hypertension_subjective_questions_2.csv` | Subjective (Short Answer) | 26 | Open-ended questions with concise answers and guideline section references |

**Total: 516 questions across 6 files**

## Data Format

All files use CSV format with UTF-8 encoding. Each file contains two columns:

- **`question`** — The test question text
- **`answer`** — The correct answer (either `正确`/`错误` for true/false, or multi-line descriptive text for subjective/essay questions)

## Topics Covered

- Epidemiology and risk factors of hypertension in China
- Blood pressure measurement and diagnostic criteria
- Cardiovascular risk stratification
- Lifestyle interventions (DASH diet, CHH diet, sodium reduction, exercise, etc.)
- Pharmacological treatment (CCB, ACEI, ARB, diuretics, β-blockers, ARNI)
- Combination therapy and single-pill combinations (SPC)
- Special populations: elderly, children, pregnancy, diabetes, CKD, CAD, heart failure
- Secondary hypertension (primary aldosteronism, pheochromocytoma, renal artery stenosis, OSAS, etc.)
- Hypertensive emergencies and urgencies
- Community management and internet-based healthcare
- Traditional Chinese Medicine in hypertension management
- Renal denervation (RDN) therapy

## Usage

This dataset can be used for:

- Medical education and exam preparation
- AI/LLM training and evaluation for medical knowledge
- Clinical knowledge assessment
- Research on hypertension awareness and guidelines dissemination

## License

This dataset is made available for academic and research purposes. Please cite the source guidelines:

> 中国高血压防治指南修订委员会. 中国高血压防治指南（2024年修订版）. 中华高血压杂志, 2024.
