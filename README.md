# OSTRails DMP Evaluation Metrics Catalogue

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![DMP Standard: RDA DMP Common Standard](https://img.shields.io/badge/Standard-RDA%20DMP%20Common%20Standard-blue)](https://www.rd-alliance.org/group/dmp-common-standards-wg/outcomes/rda-dmp-common-standard-machine-actionable-dmps)
[![Project: OSTRails](https://img.shields.io/badge/Project-OSTRails-orange)](https://www.ostrails.eu)

A community-curated catalogue of evaluation metrics and automated tests for assessing the quality, completeness, and feasibility of machine-actionable Data Management Plans (maDMPs) based on the [RDA DMP Common Standard](https://www.rd-alliance.org/group/dmp-common-standards-wg/outcomes/rda-dmp-common-standard-machine-actionable-dmps).

---

## Background

This catalogue is the result of a participatory workshop held in **December 2025** within the [OSTRails](https://www.ostrails.eu) EU-funded project. During the workshop, project pilots collaboratively identified and defined the measurements they need to evaluate DMPs submitted through their platforms. The activity was first conducted on a **Miro board**, then transferred to a structured spreadsheet, and finally curated and formalised into the two catalogue files in this repository.

The metrics and tests are designed to be used as the basis for automated DMP evaluation tools, manual DMP review workflows, and quality benchmarking of research data management plans.

---

## Repository Contents

| File | Description |
|---|---|
| [`metrics.md`](metrics.md) | Catalogue of 95 evaluation metrics, each describing a measurable quality criterion for a maDMP |
| [`tests.md`](tests.md) | Catalogue of 105 automated tests, each implementing one or more metrics with defined inputs, outputs, and procedures |
| [`LICENSE`](LICENSE) | CC BY 4.0 licence |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | Guidelines for contributing new metrics or tests |

---

## Catalogue Structure

### Metrics (`metrics.md`)

Each metric record contains:

- **Metric ID** — a unique dot-notation identifier (e.g. `data.pid.cov.1`)
- **Persistent URI** — a stable identifier for the metric
- **Dimension** — the quality dimension assessed (see below)
- **Title** — a concise name for the metric
- **Narrative** — a plain-language description of what is being assessed and why it matters
- **Intended Outcome** — what a passing result confirms about the DMP
- **Applies To** — the type of DMP or dataset the metric applies to
- **Success / Failure Criteria** — conditions for a pass or fail result
- **Associated Test(s)** — links to the implementing test(s) in `tests.md`
- **JSON-LD** — machine-readable metadata for the metric

### Tests (`tests.md`)

Each test record contains:

- **Test ID** — a unique identifier (e.g. `T-DCSC`)
- **Persistent URI** — a stable identifier for the test
- **Implements** — link to the parent metric in `metrics.md`
- **Description** — what the test checks and why
- **Input** — the maDMP fields or external sources the test reads
- **Output** — `pass` or `fail`
- **Procedure** — step-by-step instructions for executing the test
- **JSON-LD** — machine-readable metadata for the test

---

## Quality Dimensions

Metrics are organised across the following quality dimensions:

| Dimension | Description | Metrics |
|---|---|---|
| **Completeness** | All required fields and information are present | 40 |
| **Feasibility** | Declared information is consistent with the destination repository | 27 |
| **Compliance** | The DMP conforms to a policy, standard, or funder requirement | 12 |
| **Coverage** | The DMP covers the expected scope of datasets and distributions | 8 |
| **Quality** | The DMP includes information that supports data quality assurance | 3 |
| **Openness** | The DMP supports open access and reuse of data | 3 |

---

## Topic Coverage

The catalogue covers the following DMP topic areas:

- Reused datasets (declaration, PIDs, licenses, access)
- New datasets (declaration, collection methods, metadata, access)
- Dataset information (type, format, size)
- Metadata standards and documentation
- Data storage and backup
- Security, sensitive data, and access control
- Data sharing, licensing, and embargo
- Repositories (FAIRness, certification, policies, costs)
- Persistent identifiers (PIDs)
- External resources and references
- Contributor roles and responsibilities
- Ethical issues
- Budget and RDM costs

---

## How to Use This Catalogue

### For researchers and data stewards
Browse [`metrics.md`](metrics.md) to understand what criteria a high-quality maDMP should satisfy. 
Each metric includes a plain-language narrative explaining what is being checked and why it matters.

### For tool developers
Use the structured records in [`metrics.md`](metrics.md) and [`tests.md`](tests.md) to implement automated DMP evaluation pipelines. Each test includes a step-by-step procedure, defined inputs, and a JSON-LD block for machine-readable integration. The metrics are aligned with the [RDA DMP Common Standard](https://www.rd-alliance.org/group/dmp-common-standards-wg/outcomes/rda-dmp-common-standard-machine-actionable-dmps) field names.

### For funders and policy makers
Use the catalogue as a reference framework for defining DMP requirements and quality benchmarks. 
Metrics are mapped to quality dimensions and cover Horizon Europe compliance, FAIR data principles.

---

## Project

This work was produced as part of **[OSTRails](https://www.ostrails.eu)**, an EU-funded project supporting open science infrastructure across European research performing organisations. The metrics catalogue represents the collective requirements gathered from the OSTRails pilots for automated DMP evaluation.

---

## Contributing

Contributions are welcome. Please read [`CONTRIBUTING.md`](CONTRIBUTING.md) before submitting new metrics, tests, or corrections.

---

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to share and adapt this material for any purpose, provided appropriate credit is given.
