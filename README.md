# TFEL

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-chemical_production-lightgrey)

> Anticloud-hardened packaging of the upstream project `TFEL` in category **CHEMICAL PRODUCTION**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** CHEMICAL PRODUCTION · **Upstream:** https://github.com/popcornell/tfelm · **Upstream pin:** `ff3fa7eb3359ac67d532345c9971bcb1401c9f8f` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# TF-ELM
**An experimental API for Extreme Learning machines Neural Networks made with TensorFlow.**

Extreme Learning Machines are a particular machine learning paradigm
based on random weights and biases.

This class of machine-learning techniques because are based upon random projections,
are trainable with almost negligible hardware and time resources.

In some contexts, their performance can be comparable to classical Multi Layer Perceptron Networks with the advantage of mantaining negligible training resources.

This makes these networks ideally suited for fast-prototyping and for certain big-data problems where a result should be obtained in a
reasonable time and/or computing resources for more training-intensive but better models aren’t
available.

#### Support for:

- Single Hidden layer ELM.
- Multi layer ELM.
- Custom weights initialization.
- Custom activation functions.
- TensorFlow Dataset API.
- Full multi-GPU support and model serving through TensorFlow.

#### Examples available through Jupyter Notebooks:
- [ELM class](https://github.com/popcornell/tfelm/blob/pop_new/ELM_class_example.ipynb)
- [ML_ELM class](https://github.com/popcornell/tfelm/blob/pop_new/ML_ELM_class_example.ipynb)

---

#### If you use this work, please cite our conference paper "tfelm: a TensorFlow Toolbox for the Investigation of ELMs and MLPs Performance" in [Proceedings of the 2018 International Conference on Artificial Intelligence](https://csce.ucmss.com/cr/books/2018/LFS/CSREA2018/ICA4128.pdf)

---

#### More on ELMs vs MLPs

While ELMs require a training time which is order of magnitude smaller than a performance-wise comparable MLP,
they usually require more hidden neurons than the MLP network to reach the same performance.

Because of this it can be argued that Single layer ELMs and MLPs are based on a somewhat antithetical philosophy, ELMs bet on
a large number of hidden layer units, MLPs on the other hand bet on a small but properly trained
number of hidden units.
This leads to more training time for MLPs but on the other hand more compact networks which
are less computationally intensive in the feedfoward phase.

ELMs, on the other hand, have trivial training time but produce larger networks which place more
computational burden on platforms when they become part of an actual application.

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Unknown (no standard manifest detected)** (manifests: none detected; scanned in UPSTREAM_CLONE)
- Top-level source layout: `tfelm/`
- Snapshot size: **8 files**, **728 lines of code** (measured; see Benchmarks)
- Primary languages: `.py` (4), `.ipynb` (2), `(none)` (1), `.md` (1)
- Upstream commit pinned for this packaging: `ff3fa7eb3359ac67d532345c9971bcb1401c9f8f`

---

## Installation

No installation section was found in the upstream readme, so the commands below are generated from the manifests detected in this project directory.

```sh
# No standard manifest detected. Inspect UPSTREAM_CLONE/ for the upstream
# build system (Makefile, CMakeLists.txt, configure, ...) and follow it.
```

Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

are trainable with almost negligible hardware and time resources.

In some contexts, their performance can be comparable to classical Multi Layer Perceptron Networks with the advantage of mantaining negligible training resources.

This makes these networks ideally suited for fast-prototyping and for certain big-data problems where a result should be obtained in a
reasonable time and/or computing resources for more training-intensive but better models aren’t
available.

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

Extreme Learning Machines are a particular machine learning paradigm
based on random weights and biases.

This class of machine-learning techniques because are based upon random projections,
are trainable with almost negligible hardware and time resources.

In some contexts, their performance can be comparable to classical Multi Layer Perceptron Networks with the advantage of mantaining negligible training resources.

This makes these networks ideally suited for fast-prototyping and for certain big-data problems where a result should be obtained in a
reasonable time and/or computing resources for more training-intensive but better models aren’t
available.

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Unknown (no standard manifest detected) |
| Manifests detected | none |
| Files in snapshot | 8 |
| Lines of code | 728 |
| Dependency references | 0 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- None detected at the snapshot root; consult the upstream documentation link in the Upstream section.

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `TFEL` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
MIT License

Copyright (c) 2018 Samuele Cornell

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `TFEL` (category: CHEMICAL PRODUCTION)
- **Upstream URL:** https://github.com/popcornell/tfelm
- **Pinned commit (SHA):** `ff3fa7eb3359ac67d532345c9971bcb1401c9f8f`
- **Branch:** master
- **Pin provenance:** GitHub API commits/master. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`f434083f69c63cf027ac74fb7068ca6f7c28732b41c2c3bc95e30156aa93bdac`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

