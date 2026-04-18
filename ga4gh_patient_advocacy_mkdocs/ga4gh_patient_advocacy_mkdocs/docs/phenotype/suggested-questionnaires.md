# Suggested questionnaires for patient registries

This section proposes a modular registry design informed by patient registry practice and by the structure seen in GenomeConnect sample materials.

## Recommended questionnaire set

### 1. Core intake questionnaire
Use at enrollment.

Suggested sections:

- participant and contact details
- diagnosis or reason for enrollment
- genetic testing history
- upload of genetic test report
- broad health history by body system
- pregnancy, birth, and development
- family history
- current medications and major interventions
- consent preferences

### 2. Annual update questionnaire
Use once per year or after major changes.

Suggested sections:

- new diagnoses
- changes in symptoms
- hospitalizations and surgeries
- new genetic testing or reinterpretation
- new medications or devices
- changes in function, school, work, or care needs

### 3. Diagnosis-specific module
Use when the group serves a defined condition or subtype.

Suggested sections:

- hallmark manifestations
- condition-specific treatments
- disease milestones
- patient-reported priorities and outcomes

### 4. Family history module
Use when inheritance and recurrence are important.

Suggested sections:

- affected relatives
- relationship to participant
- known diagnoses
- genetic testing status in relatives
- ages at onset or death when relevant

### 5. Biospecimen and research readiness module
Only if appropriate for your program.

Suggested sections:

- interest in future studies
- willingness to be recontacted
- sample types available
- travel willingness
- language preferences

## Registry question patterns borrowed from GenomeConnect-style design

GenomeConnect’s sample health survey shows a useful pattern for advocacy groups to emulate:

- broad body-system questions,
- plain-language examples,
- branching follow-up,
- HPO mappings in the background,
- age of onset and age at diagnosis fields for specific items.

That design pattern is often more scalable than starting with a long fixed list of detailed rare-disease terms.

## Suggested core items

### Enrollment and background

- What is the participant's relationship to the person completing this form?
- Has the participant had genetic testing?
- What kind of genetic testing was performed?
- Is a copy of the genetic test report available for upload?
- What diagnosis has been given, if any?
- Is the diagnosis confirmed, suspected, or unknown?

### Phenotype screening

For each body system:

- Have there been significant issues in this area?
- Please select all that apply.
- When did symptoms first appear?
- When was the issue diagnosed?
- Is it ongoing?
- Which clinician or specialty has managed it?

### Development and function

- Were there concerns during pregnancy, delivery, or the neonatal period?
- Were there developmental delays or regression?
- What supports or therapies have been used?
- What is the participant's current functional status?

### Care journey and outcomes

- What treatments have been tried?
- Which treatments helped, did not help, or caused side effects?
- What outcomes matter most to the participant or family?

## Suggested HPO-enabled follow-up table

| Domain | Example patient-facing prompt | Internal mapping examples |
|---|---|---|
| Growth | Have you had issues with growth, weight gain, or height? | Growth abnormality terms in HPO |
| Head/face/neck | Have you had significant differences affecting the head, face, or neck? | Broad HPO head/face/neck terms |
| Hearing | Have you had hearing loss or other hearing problems? | Hearing impairment and subtype terms |
| Cardiac | Have you had heart defects, rhythm problems, or high blood pressure? | Congenital heart defect, arrhythmia, hypertension terms |
| Respiratory | Have you had breathing problems or repeated lung infections? | Respiratory insufficiency, abnormal respiratory system terms |

## Suggested data dictionary columns

For every question or answer option, maintain a spreadsheet with:

- field name
- question text
- answer type
- allowed values
- branching rule
- HPO term or other code
- source of mapping
- version date
- notes for curators

## Minimal must-have questionnaires for small groups

If resources are limited, start with these three:

1. Core intake
2. Annual update
3. Diagnosis-specific add-on
