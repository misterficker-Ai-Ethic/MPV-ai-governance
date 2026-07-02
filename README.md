# AI Governance Assessment

This repository contains a small governance data model for documenting AI use cases.

## Purpose

The goal of this project is to define a simple, structured way to describe an AI use case, the data it uses, the level of human review, and the expected risk level.

## Repository structure

- `docs/` contains explanatory documentation such as the field definitions and glossary.
- `examples/` contains example JSON records that show valid assessment data.
- `schemas/` contains the JSON Schema used to validate assessment records.

## Main files

- `docs/field-definitions.md` — field list with types, required status, valid values, and descriptions.
- `examples/example-assessment-01.json` — sample assessment record.
- `schemas/assessment.schema.json` — JSON Schema for validation.

## How to use

1. Read `docs/field-definitions.md` to understand the fields.
2. Use `examples/example-assessment-01.json` as a reference for writing new records.
3. Validate new records against `schemas/assessment.schema.json`.

## Notes

- JSON object field order is mainly for readability; validation depends on the schema, not the display order.
- The schema is intended to evolve as the governance model grows.

## Next steps

Possible future extensions include additional governance fields, more example records, and validation rules for specific use-case types.
