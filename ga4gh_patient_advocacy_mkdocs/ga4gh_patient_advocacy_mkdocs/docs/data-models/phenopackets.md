# Phenopackets for registries

## What is a Phenopacket?

A **Phenopacket** is a GA4GH standard for representing phenotype and disease information in a structured, machine-readable way.

For advocacy groups, it can act as an export format rather than the participant-facing form itself.

## Why use it?

Phenopackets can help you package:

- who the record is about,
- what condition is involved,
- which phenotypic features are present or absent,
- when they appeared,
- measurements,
- interpretations and supporting data,
- pedigree or family context when relevant.

## Practical registry use

A common workflow is:

1. collect plain-language survey data,
2. map key fields to standards,
3. generate structured exports for research partners.

## What to include first

A minimal advocacy-group Phenopacket export might include:

- subject record ID,
- disease label and identifier,
- selected phenotypic features with HPO IDs,
- onset category,
- sex/gender fields as defined by your governance policy,
- report provenance,
- genetic finding summary if available,
- timestamp and source.

## What not to do

Do not wait until your registry is perfect before exporting anything. A narrow, high-quality Phenopacket export is better than a broad but inconsistent one.

## Example conceptual mapping

| Registry field | Standardized output |
|---|---|
| “Has hearing loss” = yes | phenotypicFeature: Hearing impairment (HP:0000365) |
| symptoms began at age 2 | onset element |
| diagnosis = confirmed syndrome X | disease element |
| exome report uploaded | file provenance / interpretation support |
