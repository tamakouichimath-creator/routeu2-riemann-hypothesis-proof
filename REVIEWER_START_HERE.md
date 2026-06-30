# Reviewer Start Here

Zenodo record: https://zenodo.org/records/21056615

## Summary

This package is a public verification target for a proposed Route U2 proof of the Riemann Hypothesis.

It is intended to be inspected as a fixed research object, not accepted by announcement.

## What is included

The Zenodo package is intended to provide:

- a manuscript describing the proposed Route U2 proof;
- LaTeX source for the manuscript;
- a Lean source snapshot;
- README / workflow notes;
- QA and release metadata;
- SHA256 checksums for the fixed public files.

## How to read this package

Recommended first pass:

1. Read the abstract and introduction of the manuscript.
2. Read `CLAIM_BOUNDARY.md`.
3. Inspect the Lean source snapshot and its stated boundary.
4. Compare the manuscript route with the formal / source-backed boundary.
5. Check the SHA256 ledger and release notes.
6. Report the first precise point where the manuscript route and the formal boundary appear to diverge.

## What kind of feedback is most useful

Helpful comments include:

- a specific mathematical gap;
- a missing dependency;
- an ambiguity in the theorem statement;
- a mismatch between the manuscript and Lean boundary;
- a reproducibility failure;
- a citation/source problem;
- an overclaim in the public description.

Less useful comments include only:

- general skepticism without a located issue;
- acceptance or rejection without identifying a precise checkpoint.

## Current status

This is a public initial release for external inspection.

Community acceptance, journal refereeing, and third-party independent Lean reruns are not claimed by this document.
