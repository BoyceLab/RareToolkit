# Minimal data model

Below is a practical starting schema for a patient advocacy registry.

## Participant

- internal participant ID
- person completing form
- relationship to participant
- contact and recontact status
- language preference

## Diagnosis

- diagnosis label
- diagnosis status: confirmed / suspected / none / unknown
- diagnosis date or year
- disease code if available
- diagnosing specialty or institution

## Genetic testing

- testing performed: yes / no / unsure
- test type
- laboratory name
- report uploaded: yes / no
- variant summary if available
- reinterpretation update flag

## Phenotype observations

- domain
- patient-facing answer
- mapped HPO term
- present / absent / unknown
- onset
- diagnosis timing
- current status
- source of information

## Treatments and outcomes

- treatment name
- start/stop timing
- indication
- perceived benefit
- side effects
- outcome priority domain

## Family history

- relative
- affected status
- diagnosis
- genetic testing status
- relevant age fields

## Provenance and governance

- consent version
- date of collection
- collector type
- data source
- version of mapping dictionary
