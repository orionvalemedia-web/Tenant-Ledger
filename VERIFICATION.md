# Verification

Measured results for Devadex Tenant Ledger.

Every figure came from running the software while the data room was prepared. None of it is copied
out of a document, and each figure is reproducible by a buyer from the delivered files.

---

## Results

| Measure | Value |
|---|---|
| Files delivered | 29 |
| Significant authored lines | 3,569 |
| Of those, test code | 982 |
| Documentation lines | 165 |
| Automated tests passing | 112 |
| Runtime dependencies | none |

## Worth knowing

Verified by an eight-check release gate, all passing: tests, no stubs, zero dependencies, required files present, no emoji, type check, build, and licences with 0 copyleft and 0 grants.

## How this was produced

The software was run from the delivered files. Where a product ships with an installer, the
installer was built. Where a product declares a type check or a build step, both were run. Test
counts are the totals reported by the products' own test commands.

## What is not claimed

A verification record that lists only passes is not a verification record. The package's
open-items document lists every known gap, and it is part of the data room rather than something
a buyer has to discover. Where a test command did not run, where a path went unexercised, or
where behaviour at scale is unproven, the data room says so plainly.

That document is available under a signed non-disclosure agreement, together with the full
verification record and the provenance file. See [ACQUISITION.md](ACQUISITION.md).
