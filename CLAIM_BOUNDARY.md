# Claim Boundary

Zenodo record: https://zenodo.org/records/21056615

## Public claim

This package publicly releases a proposed Route U2 proof of the Riemann Hypothesis.

## Verification target

The intended verification target is the combination of:

- manuscript argument;
- LaTeX source;
- Lean source snapshot;
- QA / release metadata;
- SHA256 file ledger;
- package-level documentation.

## Claimed by the package

The package claims to provide a fixed public object suitable for technical inspection.

It is meant to expose:

- the main proof route;
- the formalization boundary;
- source-backed assumptions or imported material;
- reproducibility and packaging metadata;
- the intended correspondence between manuscript prose and formal artifacts.

## Not claimed by this boundary document

This boundary document does not claim:

- community acceptance;
- journal acceptance;
- Clay / prize-level recognition;
- independent third-party verification;
- that all readers should accept the proof without checking the boundary.

## Primary review questions

Reviewers are invited to check:

1. Does the manuscript state a precise theorem target?
2. Does the proof route actually imply the Riemann Hypothesis as stated?
3. Are all nontrivial imported mathematical assumptions visible?
4. Does the Lean snapshot correspond to the mathematical route asserted in the manuscript?
5. Are there any gaps between the prose proof and the formal/source-backed boundary?
6. Are the release files reproducible from the supplied source package?
7. Are there any hidden changes, missing files, or checksum inconsistencies?

## Suggested issue format

When reporting an issue, please include:

```text
File:
Page / line / theorem:
Observed issue:
Why this affects the proof:
Suggested correction or missing dependency:
```
