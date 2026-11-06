# Verifier-Side Silent Failures — Paper 1

**Verifier-Side Silent Failures: A Taxonomy and a Negative-Control Test Method for Automated Verifiers in Agentic AI Governance**

Author: Xinghua Zhao (ORCID [0009-0001-0512-1237](https://orcid.org/0009-0001-0512-1237)) · Independent researcher

## What this is

A standalone paper building on the [Silent-Failure Catalog](https://github.com/zhaoxinghua09-cell/silent-failure-catalog) (concept DOI [10.5281/zenodo.23051637](https://doi.org/10.5281/zenodo.23051637)):

1. A taxonomy of the **verifier-side** subset of silent failures — verifiers that report success while the checked property was never exercised.
2. A **negative-control test method**: every self-check of a verifier must carry a deliberately broken twin whose expected failure is asserted.
3. A worked example: gate register Q0–Q6 from a regulatory annex (FG-TIDA use-case), cross-walked against four catalog cases and three simulation profiles (`examples/S5-Qregister/` in the catalog repo).

## Files

| File | Purpose |
|---|---|
| `paper1_zenodo_public_v1_20261001.md` | Manuscript source (Markdown) |
| `paper1_verifier_side_silent_failures_20261001.pdf` | Typeset PDF (A4) |
| `.zenodo.json` | Zenodo archival metadata (auto-applied on release) |

## License (split)

- **Manuscript text**: © 2026 赵兴华 / Steven Zhao (ORCID 0009-0001-0512-1237). All rights reserved.
  Citation under attribution is permitted.
- **Referenced code artifacts** (silent-failure catalog, S5-Qregister example): **MIT**.

See `LICENSE-NOTICE.md` for the authoritative rights statement.

## Citation

Cite via the Zenodo DOI minted for this repository's release (see the Zenodo badge / record linked to tag `v1.0.0`). Concept DOI will appear here once the release is archived.
