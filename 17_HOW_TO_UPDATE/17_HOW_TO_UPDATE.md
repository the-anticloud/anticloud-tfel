# How to Update — TFEL

**Project:** `TFEL`
**Category:** CHEMICAL_PRODUCTION
**Domain:** chemical production and simulation
**Date:** 2026-10-07

---

## Update Procedure

### Checking for Updates
```bash
TFEL --version
TFEL check-update
```

### Applying Updates
```bash
pip install --upgrade TFEL
```

### Rolling Back
```bash
pip install TFEL==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

All 16 checks PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
