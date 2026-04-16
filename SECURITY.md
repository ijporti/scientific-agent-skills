# Security Scan Report

**Generated:** 2026-04-11 18:52 UTC  
**Skills scanned:** 135  
**Total findings:** 830  
**Critical:** 69 | **High:** 57 | **Safe skills:** 96/135

> **Personal note:** Forked for learning purposes. I'm primarily interested in the CRITICAL-severity skills related to scientific writing and literature review. Tracking remediation progress in my own branch.
>
> **My focus areas (in order):** `literature-review` → `scientific-writing` → `citation-management` → `peer-review`
>
> **Progress log:**
> - 2026-04-12: Started reviewing `literature-review` findings. Most issues appear to be around unsafe URL fetching and unvalidated external API calls.
> - 2026-04-14: `scientific-writing` — flagged 3 findings as false positives, opened upstream issue for the other 9.
> - 2026-04-17: `citation-management` — beginning review. 13 findings, mostly looks like unvalidated DOI resolution and unsafe redirect following. Will cross-reference with `literature-review` patterns.

## Summary

| Skill | Severity | Findings | Safe | Duration |
|-------|----------|----------|------|----------|
| citation-management | 🔴 CRITICAL | 13 | ❌ | 30.7s |
| clinical-decision-support | 🔴 CRITICAL | 12 | ❌ | 57.4s |
| clinical-reports | 🔴 CRITICAL | 15 | ❌ | 68.4s |
| dask | 🔴 CRITICAL | 3 | ❌ | 24.0s |
| hypothesis-generation | 🔴 CRITICAL | 10 | ❌ | 42.3s |
| infographics | 🔴 CRITICAL | 11 | ❌ | 44.0s |
| latex-posters | 🔴 CRITICAL | 13 | ❌ | 42.9s |
| literature-review | 🔴 CRITICAL | 12 | ❌ | 46.1s |
| markitdown | 🔴 CRITICAL | 12 | ❌ | 40.6s |
| peer-review | 🔴 CRITICAL | 10 | ❌ | 31.7s |
| pptx-posters | 🔴 CRITICAL | 6 | ❌ | 0.8s |
| research-grants | 🔴 CRITICAL | 13 | ❌ | 48.0s |
| research-lookup | 🔴 CRITICAL | 17 | ❌ | 47.9s |
| scholar-evaluation | 🔴 CRITICAL | 11 | ❌ | 44.9s |
| scientific-critical-thinking | 🔴 CRITICAL | 10 | ❌ | 36.6s |
| scientific-schematics | 🔴 CRITICAL | 10 | ❌ | 35.7s |
| scientific-slides | 🔴 CRITICAL | 18 | ❌ | 59.1s |
| scientific-writing | 🔴 CRITICAL | 12 | ❌ | 49.7s |
| seaborn | 🔴 CRITICAL | 4 | ❌ | 29.3s |
| treatment-plans | 🔴 CRITICAL | 13 | ❌ | 54.8s |
| umap-learn | 🔴 CRITICAL | 4 | ❌ | 29.3s |
| venue-templates | 🔴 CRITICAL | 11 | ❌ | 45.1s |
| consciousness-council | 🟠 HIGH | 4 | ❌ | 30.3s |
| dhdna-profiler | 🟠 HIGH | 5 | ❌ | 40.2s |
| esm | 🟠 HIGH | 5 | ❌ | 24.8s |
| geomaster | 🟠 HIGH | 7 | ❌ | 32.4s |
| modal | 🟠 HIGH | 9 | ❌ | 27.4s |
| pathml | 🟠 HIGH | 8 | ❌ | 28.6s |
| polars | 🟠 HIGH | 4 | ❌ | 18.6s |
| primekg | 🟠 HIGH | 6 | ❌ | 38.3s |
| pyhealth | 🟠 HIGH | 4 | ❌ | 33.0s |
| pytorch-lightning | 🟠 HIGH | 5 | ❌ | 26.8s |
| qutip | 🟠 HIGH | 3 | ❌ | 16.7s |
| sympy | 🟠 HIGH | 4 | ❌ | 22.2s |
| torch-geometric | 🟠 HIGH | 7 | ❌ | 28.1s |
| torchdrug | 🟠 HIGH | 3 | ❌ | 15.8s |
| transformers | 🟠 HIGH | 5 | ❌ | 26.2s |
| what-if-oracle | 🟠 HIGH | 4 | ❌ | 33.2s |
| zarr-python | 🟠 HIGH | 4 | ❌ | 28.3s |
| bgpt-paper-search | 🟡 MEDIUM | 4 | ✅ | 25.6s |
| cobrapy | 🟡 MEDIUM | 3 | ✅ | 24.0s |
| database-lookup | 🟡 MEDIUM | 4 | ✅ | 39.9s |
| datamol | 🟡 MEDIUM | 5 | ✅ | 31.8s |
| depmap | 🟡 MEDIUM | 4 | ✅ | 24.9s |
| dnanexus-integration | 🟡 MEDIUM | 3 | ✅ | 25.9s |
| exploratory-data-analysis | 🟡 MEDIUM | 5 | ✅ | 37