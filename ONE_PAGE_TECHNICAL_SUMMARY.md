# One-Page Technical Summary

Zenodo record: https://zenodo.org/records/21056615

## Object

A public manuscript and Lean-source package for a proposed Route U2 proof of the Riemann Hypothesis.

## Main target

The Riemann Hypothesis asserts that every nontrivial zero of the Riemann zeta function has real part `1/2`.

The Route U2 package is presented as a proposed proof route toward this target.

## What distinguishes this release

This release is packaged as a reviewable object rather than only as a standalone PDF.

It includes manuscript material, source material, release notes, QA metadata, and checksums intended to make the public version fixed and inspectable.

## First thing to verify

The first technical check is not whether the announcement sounds convincing.

The first technical check is whether the manuscript route, source-backed assumptions, and Lean snapshot boundary agree.

## Suggested review path

1. Identify the main theorem statement in the manuscript.
2. Trace the dependency route backward.
3. Mark each step as one of:
   - formalized in Lean;
   - source-backed/imported;
   - manuscript-level argument;
   - unclear or missing.
4. Check whether any manuscript-level bridge is doing essential work without a formal or source-backed counterpart.
5. Confirm that the packaged files match the SHA256 ledger.

## Minimal expected review output

A useful review can be short:

```text
I checked [section/file].
The first unclear point is [precise location].
It matters because [reason].
The needed clarification is [specific missing statement/dependency].
```

## Public framing

Recommended wording:

> This is a public verification target for a proposed Route U2 proof of RH. Technical review of the formal boundary and reproducibility package is welcome.
