# Example mapping workflow

## Step 1: Build plain-language items

Example:

> Have you had cleft lip and/or cleft palate?

## Step 2: Add explanatory text

Example explanation:

> A split or opening in the lip and/or roof of the mouth that is present at birth.

## Step 3: Create structured answer options

- Yes
- No
- Unsure

## Step 4: Add timing fields

- Age symptoms first appeared
- Age at diagnosis

## Step 5: Map internally

- HPO: Oral cleft (HP:0000202)

## Step 6: Record provenance

- self-report / caregiver report / clinician-confirmed / report-derived

## Step 7: Export when needed

The exported record can represent the phenotype consistently even if the original questionnaire wording changes later.

## Example JSON-like pattern

```json
{
  "question_id": "head_neck_cleft",
  "label": "Have you had cleft lip and/or cleft palate?",
  "answers": {
    "present": true,
    "age_of_onset": "before birth",
    "age_at_diagnosis": "before birth",
    "source": "caregiver_report"
  },
  "mapping": {
    "hpo_id": "HP:0000202",
    "hpo_label": "Oral cleft"
  }
}
```
