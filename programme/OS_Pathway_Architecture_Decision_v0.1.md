# Official Statistics and AI Pathway Architecture Decision

## Decision

The programme will be implemented as a separate SRAI pathway named the SRAI Official Statistics and AI Pathway.

## Identifier

The pathway prefix is `OS`.

The first module identifier is `OS-A01`.

Module assets use identifiers beginning with `OS-A01-A01`.

## Reason

The existing SRAI Books registry requires production-unit identifiers in the form `PU-BNN-CNN`. The Official Statistics and AI programme uses nine competency blocks, role pathways, institutional instruments and controlled workplace implementation. It is therefore structurally a pathway rather than a conventional SRAI Book.

The separate-pathway model follows the architectural precedent established by the SRAI Executive Pathway.

## Repository

`SRAI_Official_Statistics_and_AI_Pathway`

## Website routes

- `/official-statistics/`
- `/official-statistics/modules/`
- `/official-statistics/modules/a1/`
- `/official-statistics/tools/`

## Operations integration

The pathway will use a dedicated module registry. It will not be inserted into the Books-only `production_units.json` schema unless that schema is deliberately generalized in a later controlled change.

## Release rule

No module may be published until its canonical lesson, notebook, assessment materials, facilitator resources, metadata, validation record and public assets have passed their applicable release gates.
