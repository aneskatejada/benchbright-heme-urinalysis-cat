# Instructor quality review — action recommended before commercial launch

## Imported source

`BenchBright_200_Combined_Heme_Coag_UA_BodyFluids_Questions_Rationales.docx` is the sole source for question wording, all four choices, correct answers and explanation text. The CSV preserves the original question IDs 1–200 and the corresponding explanations. The source itself states that the material is **not independently expert-validated or psychometrically calibrated**.

## Structural verification (complete)

- **200/200** numbered questions were imported successfully.
- **50** Hematology, **50** Hemostasis / Coagulation, **50** Urinalysis, **50** Body Fluids.
- Every question has exactly **four nonempty answer choices**, **one correct answer key**, and **four nonempty answer rationales**.
- Answer-letter and answer-text matching was verified automatically against the source document.
- A generated bank of 200 questions is used by the CAT. The algorithm checks that it can select 25 distinct items from each subject.

## Major content concern: 112 / 200 flagged items

**112 items (28 from each subject)** contain distractor rationales with the phrase *"This does not answer the specific finding or process described in the question"* — an unmistakable marker that incorrect choices are recycled from unrelated questions. This creates extremely easy giveaway options, undermines the validity of the adaptive difficulty estimates, and could confuse students.

**Examples from the uploaded file (preserved unchanged):**

- **Q23 (Hematology)** asks for hematocrit from MCV and RBC count; options include **"Orthochromatic erythroblast"** and **"Assess proportions of marrow hematopoietic precursors"**.
- **Q24 (Hematology)** asks for MCH, while distractors include **"Vitamin B12 deficiency"** and **"New methylene blue"**.
- **Q73 (Hemostasis / Coagulation)** asks which enzyme converts prothrombin to thrombin; a distractor says **"INR is not standardized for DOAC intensity"**.

The same pattern begins at item 23, 73, 123 and 173 in the four content areas. *The supplied correct answers appear structurally consistent with their labeled answer texts; this is not a scientific expert verification.*

**Editorial priority:** Rewrite misleading distractors into plausible alternatives from the same clinical concept, then check all rationales for scientific accuracy. Have a subject-matter expert review before sales. The initial practice version does **not** automatically exclude flagged questions, because doing so would leave only 88 unflagged items and make it impossible to deliver the requested 100-question assessment with no repeats.

## What the CAT testing does and does not validate

**Verified automatically:** bank structure, source answer-text agreement, 100 questions per exam, 25 per topic, uniqueness of question IDs within the exam, answer-choice shuffling, and computed ability updates under correct/incorrect/mixed-answer scenarios.

**Not verified:** scientific accuracy of all 200 answers, appropriateness of distractors, clinical recency of diagnostic practice, psychometric item parameters, final ability validity, or equivalence to the ASCP scoring scale. The difficulty labels are only a preliminary rank based on wording complexity and clinical cues and are **not** empirical item-difficulty estimates.

## Publish readiness

**Technical prototype: ready for instructor testing.**

**Paid high-stakes exam preparation product: content revision and subject-matter validation recommended before publication.**
