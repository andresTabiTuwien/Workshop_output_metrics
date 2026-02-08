# Metrics Catalog

| Metric ID | Title | 
|----------|------|
| data.reused.co.1 | [maDMP declares reused datasets](#metric-madmp-declares-reused-datasets) |
| data.reused.co.2 | [Reused Data PID](#metric-reused-data-pid) |
| data.reused.co.3 | [Reused Data License](#metric-reused-data-license) |
| data.reused.co.4 | [Reused Data Source](#metric-reused-data-source) |
| data.reused.co.5 | [Reused Data Access](#metric-reused-data-access) |
| data.reused.co.6 | [Reused Data Personal](#metric-reused-data-personal) |
| data.reused.co.7 | [Reused Data Sensitive](#metric-reused-data-sensitive) |
| data.reused.co.8 | [Reused Data URL](#metric-reused-data-url) |
| data.reused.feas.1 | [Repository Reused Data PID](#metric-repository-reused-data-pid) |
| data.reused.feas.2 | [Repository Reused Data Access](#metric-repository-reused-data-access) |
| data.reused.feas.3 | [Repository Reused Data License](#metric-repository-reused-data-license) |
| data.new.1 | [New Data](#metric-new-data) |
| data.new.2 | [New Data Collection or Creation](#metric-new-data-collection-or-creation) |
| data.new.3 | [New Data Access](#metric-new-data-access) |
| data.new.4 | [New Data Metadata](#metric-new-data-metadata) |
| data.new.feas.1 | [Repository PID Resolution](#metric-repository-pid-resolution) |
| data.new.feas.2 | [Repository New Data Access](#metric-repository-new-data-access) |
| data.new.feas.3 | [Repository New Data License](#metric-repository-new-data-license) |
| data.info.cov.1 | [Data Type](#metric-data-type) |
| data.info.cov.2 | [Data Format](#metric-data-format) |
| data.info.cov.3 | [Data Size](#metric-data-size) |
| data.info.feas.1 | [Repository Data Type](#metric-repository-data-type) |
| data.info.feas.2 | [Repository Data Format](#metric-repository-data-format) |
| data.info.feas.3 | [Repository Data Size](#metric-repository-data-size) |



| meta.comp.1 | [DMP Common Standard Field Compliance](#metric-dmp-common-standard-field-compliance) |




---

## Metric: maDMP declares reused datasets

**Metric ID:** data.reused.co.1  
**Persistent URI:** https://example.org/metric/madmp-reused-datasets-declared  

### Title
maDMP declares reused datasets

### Narrative
The machine-actionable Data Management Plan (maDMP) declares whether any dataset described in the plan is reused.

### Intended Outcome
Determine whether reuse of datasets is explicitly declared in the maDMP.

### Applies To
Machine-actionable Data Management Plan (maDMP) in JSON format.

### Success Criterion
At least one dataset entry in the maDMP contains a boolean field indicating reuse.

### Failure Criterion
No dataset entry contains reuse information.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Check for reused dataset declaration](tests.md#test-check-for-reused-dataset-declaration)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/madmp-reused-datasets-declared",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.reused.co.1",
  "dcterms:title": "maDMP declares reused datasets",
  "dcterms:description": "The machine-actionable Data Management Plan (maDMP) declares whether any dataset described in the plan is reused.",
  "ftr:intendedOutcome": "Determine whether reuse of datasets is explicitly declared in the maDMP.",
  "ftr:successCriterion": "At least one dataset entry in the maDMP contains a boolean field indicating reuse.",
  "ftr:failureCriterion": "No dataset entry contains reuse information.",
  "ftr:appliesTo": "Machine-actionable Data Management Plan (maDMP) in JSON format.",
  "ftr:expectedResultType": "boolean"
}
```

---

## Metric: Reused Data PID

**Metric ID:** data.reused.co.2  
**Persistent URI:** https://example.org/metric/data.reused.co.2  
**Dimension:** Completeness  

### Title
Reused Data PID

### Narrative
Verifies that reused datasets come with PIDs.

### Intended Outcome
Determine whether reused datasets declared in the machine-actionable Data Management Plan (maDMP) include persistent identifiers.

### Applies To
Machine-actionable Data Management Plan (maDMP) in JSON format.

### Success Criterion
For each dataset declared as reused (`is_reused = true`), an identifier is present (e.g., `dataset_id.identifier`) and, where applicable, an identifier `type` is provided.

### Failure Criterion
At least one reused dataset is missing an identifier or identifier metadata.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Check for reused dataset PID](tests.md#test-check-for-reused-dataset-pid)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.reused.co.2",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.reused.co.2",
  "dcterms:title": "Reused Data PID",
  "dcterms:description": "Verifies that reused datasets come with PIDs.",
  "ftr:dimension": "Completeness",
  "ftr:intendedOutcome": "Determine whether reused datasets declared in the maDMP include persistent identifiers.",
  "ftr:successCriterion": "For each dataset declared as reused (is_reused=true), an identifier is present (e.g., dataset_id.identifier) and, where applicable, an identifier type is provided.",
  "ftr:failureCriterion": "At least one reused dataset is missing an identifier or identifier metadata.",
  "ftr:appliesTo": "Machine-actionable Data Management Plan (maDMP) in JSON format.",
  "ftr:expectedResultType": "boolean"
}
```

---

## Metric: Reused Data License

**Metric ID:** data.reused.co.3  
**Persistent URI:** https://example.org/metric/data.reused.co.3  
**Dimension:** Completeness  

### Title
Reused Data License

### Narrative
Verifies that reused datasets come with license.

### Intended Outcome
Determine whether reused datasets declared in the machine-actionable Data Management Plan (maDMP) include license information.

### Applies To
Machine-actionable Data Management Plan (maDMP) in JSON format.

### Success Criterion
For each dataset declared as reused (`is_reused = true`), license metadata is present, including at least a license reference and, where applicable, a start date.

### Failure Criterion
At least one reused dataset is missing license information or required license fields.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [License for reused datasets](tests.md#test-license-for-reused-datasets)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.reused.co.3",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.reused.co.3",
  "dcterms:title": "Reused Data License",
  "dcterms:description": "Verifies that reused datasets come with license.",
  "ftr:dimension": "Completeness",
  "ftr:intendedOutcome": "Determine whether reused datasets declared in the maDMP include license information.",
  "ftr:successCriterion": "For each reused dataset (is_reused=true), license metadata is present, including at least a license reference and, where applicable, a start date.",
  "ftr:failureCriterion": "At least one reused dataset is missing license information or required license fields.",
  "ftr:appliesTo": "Machine-actionable Data Management Plan (maDMP) in JSON format.",
  "ftr:expectedResultType": "boolean"
}
```

---

## Metric: Reused Data Source

**Metric ID:** data.reused.co.4  
**Persistent URI:** https://example.org/metric/data.reused.co.4  
**Dimension:** Completeness  

### Title
Reused Data Source

### Narrative
Verifies that reused datasets are shared.

### Intended Outcome
Determine whether reused datasets declared in the machine-actionable Data Management Plan (maDMP) include accessible source or distribution information.

### Applies To
Machine-actionable Data Management Plan (maDMP) in JSON format.

### Success Criterion
For each dataset declared as reused (`is_reused = true`), distribution or source metadata is present and contains minimally identifying information such as a title and/or an access location.

### Failure Criterion
At least one reused dataset lacks distribution or source metadata, or required minimal fields.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Distribution present](tests.md#test-distribution-present)  
- [Distribution access information](tests.md#test-distribution-access-information)  
- [Distribution title](tests.md#test-distribution-title)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.reused.co.4",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.reused.co.4",
  "dcterms:title": "Reused Data Source",
  "dcterms:description": "Verifies that reused datasets are shared.",
  "ftr:dimension": "Completeness",
  "ftr:intendedOutcome": "Determine whether reused datasets declared in the maDMP include accessible source or distribution information.",
  "ftr:successCriterion": "For each reused dataset (is_reused=true), distribution or source metadata is present and contains minimally identifying information such as a title and/or an access location.",
  "ftr:failureCriterion": "At least one reused dataset lacks distribution or source metadata, or required minimal fields.",
  "ftr:appliesTo": "Machine-actionable Data Management Plan (maDMP) in JSON format.",
  "ftr:expectedResultType": "boolean"
}
```

---

## Metric: Reused Data Access

**Metric ID:** data.reused.co.5  
**Persistent URI:** https://example.org/metric/data.reused.co.5  
**Dimension:** Completeness  

### Title
Reused Data Access

### Narrative
Verifies the access rights of the reused datasets.

### Intended Outcome
Determine whether reused datasets declared in the machine-actionable Data Management Plan (maDMP) include an explicit access rights statement.

### Applies To
Machine-actionable Data Management Plan (maDMP) in JSON format.

### Success Criterion
For each dataset declared as reused (`is_reused = true`), a `data_access` value is present and has an allowed value (open, shared, or closed).

### Failure Criterion
At least one reused dataset is missing a `data_access` value or contains an invalid value.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Access rights for reused datasets](tests.md#test-access-rights-for-reused-datasets)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.reused.co.5",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.reused.co.5",
  "dcterms:title": "Reused Data Access",
  "dcterms:description": "Verifies the access rights of the reused datasets.",
  "ftr:dimension": "Completeness",
  "ftr:intendedOutcome": "Determine whether reused datasets declared in the maDMP include an explicit access rights statement.",
  "ftr:successCriterion": "For each reused dataset (is_reused=true), a data_access value is present and has an allowed value (open, shared, or closed).",
  "ftr:failureCriterion": "At least one reused dataset is missing a data_access value or contains an invalid value.",
  "ftr:appliesTo": "Machine-actionable Data Management Plan (maDMP) in JSON format.",
  "ftr:expectedResultType": "boolean"
}
```

---

## Metric: Reused Data Personal

**Metric ID:** data.reused.co.6  
**Persistent URI:** https://example.org/metric/data.reused.co.6  
**Dimension:** Completeness  

### Title
Reused Data Personal

### Narrative
Verifies the existence of personal data.

### Intended Outcome
Determine whether reused datasets declared in the machine-actionable Data Management Plan (maDMP) include an explicit statement about the presence of personal data.

### Applies To
Machine-actionable Data Management Plan (maDMP) in JSON format.

### Success Criterion
For each dataset declared as reused (`is_reused = true`), a `personal_data` field exists and is explicitly set (e.g., boolean or controlled value).

### Failure Criterion
At least one reused dataset is missing `personal_data` information or contains an invalid or undefined value.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Personal data for reused datasets](tests.md#test-personal-data-for-reused-datasets)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.reused.co.6",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.reused.co.6",
  "dcterms:title": "Reused Data Personal",
  "dcterms:description": "Verifies the existence of personal data.",
  "ftr:dimension": "Completeness",
  "ftr:intendedOutcome": "Determine whether reused datasets declared in the maDMP include an explicit statement about the presence of personal data.",
  "ftr:successCriterion": "For each reused dataset (is_reused=true), a personal_data field exists and is explicitly set (e.g., boolean or controlled value).",
  "ftr:failureCriterion": "At least one reused dataset is missing personal_data information or contains an invalid or undefined value.",
  "ftr:appliesTo": "Machine-actionable Data Management Plan (maDMP) in JSON format.",
  "ftr:expectedResultType": "boolean"
}
```

---

## Metric: Reused Data Sensitive

**Metric ID:** data.reused.co.7  
**Persistent URI:** https://example.org/metric/data.reused.co.7  
**Dimension:** Completeness  

### Title
Reused Data Sensitive

### Narrative
Verifies the existence of sensitive data.

### Intended Outcome
Determine whether reused datasets declared in the machine-actionable Data Management Plan (maDMP) include an explicit statement about the presence of sensitive data.

### Applies To
Machine-actionable Data Management Plan (maDMP) in JSON format.

### Success Criterion
For each dataset declared as reused (`is_reused = true`), a `sensitive_data` field exists and is explicitly set (e.g., boolean or controlled value).

### Failure Criterion
At least one reused dataset is missing `sensitive_data` information or contains an invalid or undefined value.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Sensitive data for reused datasets](tests.md#test-sensitive-data-for-reused-datasets)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.reused.co.7",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.reused.co.7",
  "dcterms:title": "Reused Data Sensitive",
  "dcterms:description": "Verifies the existence of sensitive data.",
  "ftr:dimension": "Completeness",
  "ftr:intendedOutcome": "Determine whether reused datasets declared in the maDMP include an explicit statement about the presence of sensitive data.",
  "ftr:successCriterion": "For each reused dataset (is_reused=true), a sensitive_data field exists and is explicitly set (e.g., boolean or controlled value).",
  "ftr:failureCriterion": "At least one reused dataset is missing sensitive_data information or contains an invalid or undefined value.",
  "ftr:appliesTo": "Machine-actionable Data Management Plan (maDMP) in JSON format.",
  "ftr:expectedResultType": "boolean"
}
```

---

## Metric: Reused Data URL

**Metric ID:** data.reused.co.8  
**Persistent URI:** https://example.org/metric/data.reused.co.8  
**Dimension:** Completeness  

### Title
Reused Data URL

### Narrative
Verifies that the reused data have URL.

### Intended Outcome
Determine whether reused datasets declared in the machine-actionable Data Management Plan (maDMP) include a URL pointing to their distribution or access location.

### Applies To
Machine-actionable Data Management Plan (maDMP) in JSON format.

### Success Criterion
For each dataset declared as reused (`is_reused = true`), at least one distribution includes a non-empty `access_url` (or equivalent URL field).

### Failure Criterion
At least one reused dataset lacks a distribution URL.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Distribution present (URL)](tests.md#test-distribution-present-url)  
- [Access URL](tests.md#test-access-url)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.reused.co.8",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.reused.co.8",
  "dcterms:title": "Reused Data URL",
  "dcterms:description": "Verifies that the reused data have URL.",
  "ftr:dimension": "Completeness",
  "ftr:intendedOutcome": "Determine whether reused datasets declared in the maDMP include a URL pointing to their distribution or access location.",
  "ftr:successCriterion": "For each reused dataset (is_reused=true), at least one distribution includes a non-empty access_url (or equivalent URL field).",
  "ftr:failureCriterion": "At least one reused dataset lacks a distribution URL.",
  "ftr:appliesTo": "Machine-actionable Data Management Plan (maDMP) in JSON format.",
  "ftr:expectedResultType": "boolean"
}
```

---

## Metric: Repository Reused Data PID

**Metric ID:** data.reused.feas.1  
**Persistent URI:** https://example.org/metric/data.reused.feas.1  
**Dimension:** Feasibility  

### Title
Repository Reused Data PID

### Narrative
Validates that the reused dataset exists in the repository.

### Intended Outcome
Determine whether the PID for each reused dataset declared in the machine-actionable Data Management Plan (maDMP) corresponds to an existing record in a target repository and resolves via a PID resolver.

### Applies To
- maDMP JSON (dataset reuse declarations)  
- Target repository endpoint  
- PID resolver service  

### Success Criterion
For each dataset declared as reused (`is_reused = true`):
1. The dataset identifier in the maDMP matches an identifier discoverable in the target repository record (e.g., DOI URL), **and**  
2. The dataset PID resolves successfully.

### Failure Criterion
At least one reused dataset PID:
- cannot be matched to a target repository record, **or**  
- does not resolve via a PID resolver.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [PID matches destination repository record](tests.md#test-pid-matches-destination-repository-record)  
- [PID resolves](tests.md#test-pid-resolves)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.reused.feas.1",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.reused.feas.1",
  "dcterms:title": "Repository Reused Data PID",
  "dcterms:description": "Validates that the reused dataset exists in the repository.",
  "ftr:dimension": "Feasibility",
  "ftr:intendedOutcome": "Determine whether the PID for each reused dataset declared in the maDMP corresponds to an existing record in a target repository and resolves via a PID resolver.",
  "ftr:successCriterion": "For each reused dataset (is_reused=true): (1) the maDMP dataset identifier matches an identifier discoverable in the target repository record, and (2) the PID resolves successfully.",
  "ftr:failureCriterion": "At least one reused dataset PID cannot be matched to a target repository record or does not resolve via a PID resolver.",
  "ftr:appliesTo": "maDMP JSON + target repository endpoint + PID resolver service",
  "ftr:expectedResultType": "boolean"
}
```

---

## Metric: Repository Reused Data Access

**Metric ID:** data.reused.feas.2  
**Persistent URI:** https://example.org/metric/data.reused.feas.2  
**Dimension:** Feasibility  

### Title
Repository Reused Data Access

### Narrative
Validates that the access rights of the reused dataset match those of the destination.

### Intended Outcome
Determine whether the access rights declared for reused datasets in the maDMP match the access rights recorded in the destination repository.

### Applies To
- maDMP JSON (dataset reuse declarations)  
- Target repository endpoint  

### Success Criterion
For each dataset declared as reused (`is_reused = true`), the `data_access` value in the maDMP matches the corresponding access rights value in the destination repository record (e.g., `access_right`).

### Failure Criterion
At least one reused dataset has a `data_access` value in the maDMP that does not match the access rights recorded in the destination repository.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Reused data access matches destination](tests.md#test-reused-data-access-matches-destination)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.reused.feas.2",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.reused.feas.2",
  "dcterms:title": "Repository Reused Data Access",
  "dcterms:description": "Validates that the access rights of the reused dataset match those of the destination.",
  "ftr:dimension": "Feasibility",
  "ftr:intendedOutcome": "Determine whether the access rights declared for reused datasets in the maDMP match the access rights recorded in the destination repository.",
  "ftr:successCriterion": "For each reused dataset (is_reused=true), the maDMP data_access value matches the access rights value recorded in the destination repository.",
  "ftr:failureCriterion": "At least one reused dataset has a data_access value in the maDMP that does not match the destination repository access rights.",
  "ftr:appliesTo": "maDMP JSON + target repository endpoint",
  "ftr:expectedResultType": "boolean"
}
```

---

## Metric: Repository Reused Data License

**Metric ID:** data.reused.feas.3  
**Persistent URI:** https://example.org/metric/data.reused.feas.3  
**Dimension:** Feasibility  

### Title
Repository Reused Data License

### Narrative
Validates that license of the reused dataset match those of the destination.

### Intended Outcome
Determine whether the license declared for reused datasets in the maDMP matches the license recorded in the destination repository.

### Applies To
- maDMP JSON (dataset reuse declarations)  
- Target repository endpoint  

### Success Criterion
For each dataset declared as reused (`is_reused = true`), the license value in the maDMP matches the license value in the destination repository record.

### Failure Criterion
At least one reused dataset has a license value in the maDMP that does not match the license recorded in the destination repository.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Reused data license matches destination](tests.md#test-reused-data-license-matches-destination)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.reused.feas.3",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.reused.feas.3",
  "dcterms:title": "Repository Reused Data License",
  "dcterms:description": "Validates that license of the reused dataset match those of the destination.",
  "ftr:dimension": "Feasibility",
  "ftr:intendedOutcome": "Determine whether the license declared for reused datasets in the maDMP matches the license recorded in the destination repository.",
  "ftr:successCriterion": "For each reused dataset (is_reused=true), the maDMP license value matches the license value in the destination repository record.",
  "ftr:failureCriterion": "At least one reused dataset has a license value in the maDMP that does not match the license recorded in the destination repository.",
  "ftr:appliesTo": "maDMP JSON + target repository endpoint",
  "ftr:expectedResultType": "boolean"
}
```

## Metric: New Data

**Metric ID:** data.new.1  
**Persistent URI:** https://example.org/metric/data.new.1  
**Dimension:** Completeness  

### Title
New Data

### Narrative
Verifies that information about the new data exist.

### Intended Outcome
Determine whether the maDMP contains at least one dataset that is not explicitly declared as reused (i.e., a “new” dataset is present).

### Applies To
Machine-actionable Data Management Plan (maDMP) in JSON format.

### Success Criterion
At least one dataset entry exists where `is_reused` is **absent** (per the stated check), indicating the dataset is not marked as reused.

### Failure Criterion
All dataset entries include `is_reused` (i.e., no dataset is found without `is_reused`), or no dataset entries exist.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Check for new data (no is_reused)](tests.md#test-check-for-new-data-no-is_reused)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.new.1",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.new.1",
  "dcterms:title": "New Data",
  "dcterms:description": "Verifies that information about the new data exist.",
  "ftr:dimension": "Completeness",
  "ftr:intendedOutcome": "Determine whether the maDMP contains at least one dataset that is not explicitly declared as reused (i.e., a “new” dataset is present).",
  "ftr:successCriterion": "At least one dataset entry exists where is_reused is absent, indicating the dataset is not marked as reused.",
  "ftr:failureCriterion": "All dataset entries include is_reused (no dataset found without is_reused), or no dataset entries exist.",
  "ftr:appliesTo": "Machine-actionable Data Management Plan (maDMP) in JSON format.",
  "ftr:expectedResultType": "boolean"
}
```

## Metric: New Data Collection or Creation

**Metric ID:** data.new.2  
**Persistent URI:** https://example.org/metric/data.new.2  
**Sub-Dimension:** RDM Coverage  

### Title
New Data Collection or Creation

### Narrative
Verifies how the new data were collected or created.

### Intended Outcome
Determine whether the maDMP includes technical resource information describing how new data were collected or created.

### Applies To
Machine-actionable Data Management Plan (maDMP) in JSON format.

### Success Criterion
For at least one “new” dataset (i.e., dataset not marked as reused per your convention), the `technical_resource` object is present and includes:
- `description`
- `name`
- `id.identifier`
- `id.type`

### Failure Criterion
No dataset provides `technical_resource`, or one or more required fields are missing (`description`, `name`, `id.identifier`, `id.type`).

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Check technical_resource for new data collection/creation](tests.md#test-check-technical_resource-for-new-data-collectioncreation)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.new.2",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.new.2",
  "dcterms:title": "New Data Collection or Creation",
  "dcterms:description": "Verifies how the new data were collected or created.",
  "ftr:subDimension": "RDM Coverage",
  "ftr:intendedOutcome": "Determine whether the maDMP includes technical resource information describing how new data were collected or created.",
  "ftr:successCriterion": "For at least one new dataset, technical_resource is present and includes description, name, id.identifier, and id.type.",
  "ftr:failureCriterion": "No dataset provides technical_resource or one or more required fields are missing (description, name, id.identifier, id.type).",
  "ftr:appliesTo": "Machine-actionable Data Management Plan (maDMP) in JSON format.",
  "ftr:expectedResultType": "boolean"
}
```

## Metric: New Data Access

**Metric ID:** data.new.3  
**Persistent URI:** https://example.org/metric/data.new.3  
**Dimension:** Openness / Reuse  

### Title
New Data Access

### Narrative
Verifies that access rights of the new dataset is specified.

### Intended Outcome
Determine whether “new” datasets in the maDMP specify access rights and rights information needed to understand how the data can be accessed and reused.

### Applies To
Machine-actionable Data Management Plan (maDMP) in JSON format.

### Success Criterion
For at least one “new” dataset (dataset not marked as reused per your policy):
- `data_access` exists and has a valid value (`open`, `shared`, `closed`), **and**
- dataset rights information is present (according to the maDMP schema used by your project).

### Failure Criterion
No “new” dataset contains `data_access` and/or rights information, or `data_access` is missing/invalid.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Check data_access for new datasets](tests.md#test-check-data_access-for-new-datasets)  
- [Check rights of new dataset](tests.md#test-check-rights-of-new-dataset)

### JSON-LD (Metric)
```json 
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.new.3",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.new.3",
  "dcterms:title": "New Data Access",
  "dcterms:description": "Verifies that access rights of the new dataset is specified.",
  "ftr:dimension": "Openness / Reuse",
  "ftr:intendedOutcome": "Determine whether new datasets in the maDMP specify access rights and rights information needed to understand how the data can be accessed and reused.",
  "ftr:successCriterion": "For at least one new dataset, data_access exists with a valid value (open, shared, closed) and rights information is present.",
  "ftr:failureCriterion": "No new dataset contains valid data_access and/or rights information; or data_access is missing/invalid.",
  "ftr:appliesTo": "Machine-actionable Data Management Plan (maDMP) in JSON format.",
  "ftr:expectedResultType": "boolean"
}
```
## Metric: New Data Metadata

**Metric ID:** data.new.4  
**Persistent URI:** https://example.org/metric/data.new.4  
**Dimension:** Completeness  

### Title
New Data Metadata

### Narrative
Verifies the reproducibility of the new data.

### Intended Outcome
Determine whether the maDMP includes sufficient metadata information for new datasets, supporting reproducibility and understanding of the data.

### Applies To
Machine-actionable Data Management Plan (maDMP) in JSON format.

### Success Criterion
For at least one “new” dataset (dataset not marked as reused per your policy), the `metadata` object is present and includes:
- `description`
- `language`
- `metadata_id.identifier`
- `metadata_id.type`

### Failure Criterion
No “new” dataset provides `metadata`, or one or more required fields are missing (`description`, `language`, `metadata_id.identifier`, `metadata_id.type`).

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Check metadata for new dataset](tests.md#test-check-metadata-for-new-dataset)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.new.4",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.new.4",
  "dcterms:title": "New Data Metadata",
  "dcterms:description": "Verifies the reproducibility of the new data.",
  "ftr:dimension": "Completeness",
  "ftr:intendedOutcome": "Determine whether the maDMP includes sufficient metadata information for new datasets, supporting reproducibility and understanding of the data.",
  "ftr:successCriterion": "For at least one new dataset, metadata is present and includes description, language, metadata_id.identifier, and metadata_id.type.",
  "ftr:failureCriterion": "No new dataset provides metadata or one or more required fields are missing (description, language, metadata_id.identifier, metadata_id.type).",
  "ftr:appliesTo": "Machine-actionable Data Management Plan (maDMP) in JSON format.",
  "ftr:expectedResultType": "boolean"
}
```

## Metric: Repository PID Resolution

**Metric ID:** data.new.feas.1  
**Persistent URI:** https://example.org/metric/data.new.feas.1  
**Dimension:** Feasibility  

### Title
Repository PID Resolution

### Narrative
Validates that the PID provided is resolvable according to its system resolver.

### Intended Outcome
Determine whether dataset identifiers provided in the maDMP exist and can be resolved using an appropriate PID resolver (e.g., DOI resolver).

### Applies To
- maDMP JSON (dataset identifiers)  
- PID resolver service (e.g., DOI resolver)

### Success Criterion
1. At least one dataset includes a `dataset_id`, **and**
2. The `dataset_id` resolves successfully using the appropriate resolver.

### Failure Criterion
No `dataset_id` is provided, and/or the provided PID(s) do not resolve.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Check dataset_id exists](tests.md#test-check-dataset_id-exists)  
- [Check PID resolves for dataset_id](tests.md#test-check-pid-resolves-for-dataset_id)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.new.feas.1",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.new.feas.1",
  "dcterms:title": "Repository PID Resolution",
  "dcterms:description": "Validates that the PID provided is resolvable according to its system resolver.",
  "ftr:dimension": "Feasibility",
  "ftr:intendedOutcome": "Determine whether dataset identifiers provided in the maDMP exist and can be resolved using an appropriate PID resolver (e.g., DOI resolver).",
  "ftr:successCriterion": "At least one dataset includes dataset_id and the dataset_id resolves successfully using the appropriate resolver.",
  "ftr:failureCriterion": "No dataset_id is provided and/or the provided PID(s) do not resolve.",
  "ftr:appliesTo": "maDMP JSON + PID resolver service",
  "ftr:expectedResultType": "boolean"
}
```

## Metric: Repository New Data Access

**Metric ID:** data.new.feas.2  
**Persistent URI:** https://example.org/metric/data.new.feas.2  
**Dimension:** Feasibility  

### Title
Repository New Data Access

### Narrative
Validates that the access rights of the new dataset match those of the destination.

### Intended Outcome
Determine whether access rights declared for new datasets in the maDMP match the access rights recorded in the destination repository (e.g., Zenodo).

### Applies To
- maDMP JSON (new dataset access information)  
- Destination repository metadata (e.g., Zenodo access_right)

### Success Criterion
For each “new” dataset (per your policy for determining new vs reused), the maDMP `data_access` value matches the destination repository `access_right` value.

### Failure Criterion
At least one new dataset has `data_access` in the maDMP that does not match the destination repository access rights, or required fields cannot be found.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Check new data access matches destination](tests.md#test-check-new-data-access-matches-destination)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.new.feas.2",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.new.feas.2",
  "dcterms:title": "Repository New Data Access",
  "dcterms:description": "Validates that the access rights of the new dataset match those of the destination.",
  "ftr:dimension": "Feasibility",
  "ftr:intendedOutcome": "Determine whether access rights declared for new datasets in the maDMP match the access rights recorded in the destination repository (e.g., Zenodo).",
  "ftr:successCriterion": "For each new dataset, the maDMP data_access value matches the destination repository access_right value.",
  "ftr:failureCriterion": "At least one new dataset has data_access that does not match destination access_right, or required fields cannot be found.",
  "ftr:appliesTo": "maDMP JSON + destination repository metadata",
  "ftr:expectedResultType": "boolean"
}
```

## Metric: Repository New Data License

**Metric ID:** data.new.feas.3  
**Persistent URI:** https://example.org/metric/data.new.feas.3  
**Dimension:** Feasibility  

### Title
Repository New Data License

### Narrative
Validates that license of the new dataset match those of the destination.

### Intended Outcome
Determine whether the license declared for new datasets in the maDMP matches the license recorded in the destination repository (e.g., Zenodo).

### Applies To
- maDMP JSON (new dataset license information)  
- Destination repository metadata (e.g., Zenodo license)

### Success Criterion
For each “new” dataset (per your policy for determining new vs reused), the maDMP license value matches the destination repository license value.

### Failure Criterion
At least one new dataset has a license value in the maDMP that does not match the destination repository license, or required fields cannot be found.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Check new data license matches destination](tests.md#test-check-new-data-license-matches-destination)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.new.feas.3",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.new.feas.3",
  "dcterms:title": "Repository New Data License",
  "dcterms:description": "Validates that license of the new dataset match those of the destination.",
  "ftr:dimension": "Feasibility",
  "ftr:intendedOutcome": "Determine whether the license declared for new datasets in the maDMP matches the license recorded in the destination repository (e.g., Zenodo).",
  "ftr:successCriterion": "For each new dataset, the maDMP license value matches the destination repository license value.",
  "ftr:failureCriterion": "At least one new dataset has a license value that does not match destination license, or required fields cannot be found.",
  "ftr:appliesTo": "maDMP JSON + destination repository metadata",
  "ftr:expectedResultType": "boolean"
}
```

# 1b Data - Info

## Metric: Data Type

**Metric ID:** data.info.cov.1  
**Persistent URI:** https://example.org/metric/data.info.cov.1  
**Dimension:** Coverage  

### Title
Data Type

### Narrative
Verifies that the type of the dataset is qualitative or quantitative.

### Intended Outcome
Determine whether each dataset in the maDMP specifies its dataset type (e.g., qualitative or quantitative), supporting clearer understanding and management of the data.

### Applies To
Machine-actionable Data Management Plan (maDMP) in JSON format.

### Success Criterion
For each dataset (or at minimum for the dataset(s) in scope), the field `dataset.type` exists and is non-empty, and its value matches the expected controlled vocabulary (e.g., `qualitative` or `quantitative`, or your project’s equivalent terms).

### Failure Criterion
`dataset.type` is missing/empty for one or more dataset entries, or uses values outside the accepted vocabulary (if validation against a vocabulary is required).

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Check dataset.type is specified](tests.md#test-check-datasettype-is-specified)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.info.cov.1",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.info.cov.1",
  "dcterms:title": "Data Type",
  "dcterms:description": "Verifies that the type of the dataset is qualitative or quantitative.",
  "ftr:dimension": "Coverage",
  "ftr:intendedOutcome": "Determine whether each dataset in the maDMP specifies its dataset type (e.g., qualitative or quantitative).",
  "ftr:successCriterion": "dataset.type exists and is non-empty for dataset entries and matches the expected vocabulary (e.g., qualitative/quantitative).",
  "ftr:failureCriterion": "dataset.type is missing/empty for one or more datasets, or uses values outside the accepted vocabulary (if required).",
  "ftr:appliesTo": "Machine-actionable Data Management Plan (maDMP) in JSON format.",
  "ftr:expectedResultType": "boolean"
}
```

## Metric: Data Format

**Metric ID:** data.info.cov.2  
**Persistent URI:** https://example.org/metric/data.info.cov.2  
**Dimension:** Coverage  

### Title
Data Format

### Narrative
Verifies the format of the dataset.

### Intended Outcome
Determine whether dataset distribution information includes an explicit format, supporting understanding of how the data can be accessed and processed.

### Applies To
Machine-actionable Data Management Plan (maDMP) in JSON format.

### Success Criterion
For each dataset distribution (or at minimum for the distribution(s) in scope), `distribution.format` exists and is non-empty.

### Failure Criterion
`distribution.format` is missing/empty for one or more distributions, or no distribution information exists where expected.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Check distribution.format is specified](tests.md#test-check-distributionformat-is-specified)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.info.cov.2",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.info.cov.2",
  "dcterms:title": "Data Format",
  "dcterms:description": "Verifies the format of the dataset.",
  "ftr:dimension": "Coverage",
  "ftr:intendedOutcome": "Determine whether dataset distribution information includes an explicit format.",
  "ftr:successCriterion": "distribution.format exists and is non-empty for distributions in scope.",
  "ftr:failureCriterion": "distribution.format is missing/empty for one or more distributions, or no distribution information exists where expected.",
  "ftr:appliesTo": "Machine-actionable Data Management Plan (maDMP) in JSON format.",
  "ftr:expectedResultType": "boolean"
}
```

## Metric: Data Size

**Metric ID:** data.info.cov.3  
**Persistent URI:** https://example.org/metric/data.info.cov.3  
**Dimension:** Coverage  

### Title
Data Size

### Narrative
Verifies the size of the dataset.

### Intended Outcome
Determine whether dataset distribution information includes an explicit size, supporting planning for storage, transfer, and processing.

### Applies To
Machine-actionable Data Management Plan (maDMP) in JSON format.

### Success Criterion
For each dataset distribution (or at minimum for the distribution(s) in scope), `distribution.byte_size` exists and is a valid non-negative number.

### Failure Criterion
`distribution.byte_size` is missing, empty, non-numeric, or negative for one or more distributions, or no distribution information exists where expected.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Check distribution.byte_size is specified](tests.md#test-check-distributionbyte_size-is-specified)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.info.cov.3",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.info.cov.3",
  "dcterms:title": "Data Size",
  "dcterms:description": "Verifies the size of the dataset.",
  "ftr:dimension": "Coverage",
  "ftr:intendedOutcome": "Determine whether dataset distribution information includes an explicit size.",
  "ftr:successCriterion": "distribution.byte_size exists and is a valid non-negative number for distributions in scope.",
  "ftr:failureCriterion": "distribution.byte_size is missing/invalid for one or more distributions, or no distribution information exists where expected.",
  "ftr:appliesTo": "Machine-actionable Data Management Plan (maDMP) in JSON format.",
  "ftr:expectedResultType": "boolean"
}
```


## Metric: Repository Data Type

**Metric ID:** data.info.feas.1  
**Persistent URI:** https://example.org/metric/data.info.feas.1  
**Dimension:** Feasibility  

### Title
Repository Data Type

### Narrative
Validates that the type of the dataset match those of the destination.

### Intended Outcome
Determine whether the dataset type declared in the maDMP matches the dataset type information recorded in the destination repository (e.g., Zenodo), including subtype alignment.

### Applies To
- maDMP JSON (`dataset.type`)  
- Destination repository metadata (e.g., Zenodo `type` and `subtype`)

### Success Criterion
For each dataset in scope:
1. `dataset.type` in the maDMP matches the destination repository `type` for the corresponding record, and  
2. Any declared sub-properties or subtype mappings align (maDMP `dataset.type` is consistent with destination `subtype`).

### Failure Criterion
At least one dataset has a type or subtype mismatch between maDMP and the destination repository, or required fields cannot be retrieved.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Check dataset.type matches destination type](tests.md#test-check-datasettype-matches-destination-type)  
- [Check dataset.type aligns with destination subtype](tests.md#test-check-datasettype-aligns-with-destination-subtype)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.info.feas.1",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.info.feas.1",
  "dcterms:title": "Repository Data Type",
  "dcterms:description": "Validates that the type of the dataset match those of the destination.",
  "ftr:dimension": "Feasibility",
  "ftr:intendedOutcome": "Determine whether the dataset type declared in the maDMP matches the dataset type information recorded in the destination repository (e.g., Zenodo), including subtype alignment.",
  "ftr:successCriterion": "dataset.type matches destination type and is consistent with destination subtype for datasets in scope.",
  "ftr:failureCriterion": "At least one dataset has a type/subtype mismatch or required fields cannot be retrieved.",
  "ftr:appliesTo": "maDMP JSON + destination repository metadata",
  "ftr:expectedResultType": "boolean"
}
```

## Metric: Repository Data Format

**Metric ID:** data.info.feas.2  
**Persistent URI:** https://example.org/metric/data.info.feas.2  
**Dimension:** Feasibility  

### Title
Repository Data Format

### Narrative
Validates that the format of the dataset match those of the destination.

### Intended Outcome
Determine whether the dataset format declared in the maDMP matches the actual file formats stored in the destination repository (e.g., Zenodo).

### Applies To
- maDMP JSON (`distribution.format`)  
- Destination repository record (e.g., Zenodo files metadata)

### Success Criterion
For each dataset distribution in scope, the maDMP `distribution.format` matches the file format(s) observed in the destination repository record (or is compatible with them under a defined mapping rule).

### Failure Criterion
At least one distribution format declared in the maDMP does not match (or cannot be mapped to) the formats of the deposited files in the destination repository, or required repository metadata cannot be retrieved.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Check final dataset format matches destination files](tests.md#test-check-final-dataset-format-matches-destination-files)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.info.feas.2",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.info.feas.2",
  "dcterms:title": "Repository Data Format",
  "dcterms:description": "Validates that the format of the dataset match those of the destination.",
  "ftr:dimension": "Feasibility",
  "ftr:intendedOutcome": "Determine whether the dataset format declared in the maDMP matches the actual file formats stored in the destination repository (e.g., Zenodo).",
  "ftr:successCriterion": "distribution.format matches (or is compatible with) destination repository file formats for distributions in scope.",
  "ftr:failureCriterion": "At least one declared distribution.format does not match destination file formats or required repository metadata cannot be retrieved.",
  "ftr:appliesTo": "maDMP JSON + destination repository metadata",
  "ftr:expectedResultType": "boolean"
}
```

## Metric: Repository Data Size

**Metric ID:** data.info.feas.3  
**Persistent URI:** https://example.org/metric/data.info.feas.3  
**Dimension:** Feasibility  

### Title
Repository Data Size

### Narrative
Validates that the size of the dataset match those of the destination.

### Intended Outcome
Determine whether the dataset size declared in the maDMP matches the actual deposited size recorded in the destination repository (e.g., Zenodo).

### Applies To
- maDMP JSON (`distribution.byte_size`)  
- Destination repository metadata (e.g., Zenodo file size / total size)

### Success Criterion
For each dataset distribution in scope, the maDMP `distribution.byte_size` matches the destination repository recorded size (or is within an acceptable tolerance if you define one).

### Failure Criterion
At least one distribution has a size mismatch between maDMP and destination repository, or required repository metadata cannot be retrieved.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Check final dataset size matches destination size](tests.md#test-check-final-dataset-size-matches-destination-size)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/data.info.feas.3",
  "@type": "dqv:Metric",
  "dcterms:identifier": "data.info.feas.3",
  "dcterms:title": "Repository Data Size",
  "dcterms:description": "Validates that the size of the dataset match those of the destination.",
  "ftr:dimension": "Feasibility",
  "ftr:intendedOutcome": "Determine whether the dataset size declared in the maDMP matches the actual deposited size recorded in the destination repository (e.g., Zenodo).",
  "ftr:successCriterion": "distribution.byte_size matches destination repository recorded size for distributions in scope (or within tolerance if defined).",
  "ftr:failureCriterion": "At least one distribution has a size mismatch or required repository metadata cannot be retrieved.",
  "ftr:appliesTo": "maDMP JSON + destination repository metadata",
  "ftr:expectedResultType": "boolean"
}
```









# 2a Metadata doc

## Metric: DMP Common Standard Field Compliance

**Metric ID:** meta.comp.1  
**Persistent URI:** https://example.org/metric/meta.comp.1  
**Dimension:** Compliance  

### Title
DMP Common Standard Field Compliance

### Narrative
Verifies that the fields of the DMP JSON are aligned with the data types of the DMP Common Standard.

### Intended Outcome
Determine whether a maDMP JSON instance conforms to the DMP Common Standard schema, including correct field presence, structure, and data types.

### Applies To
Machine-actionable Data Management Plan (maDMP) in JSON format.

### Success Criterion
The maDMP JSON validates successfully against the DMP Common Standard JSON Schema (no validation errors).

### Failure Criterion
The maDMP JSON fails schema validation (one or more validation errors), including type mismatches, missing required fields, or invalid structures.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Validate maDMP JSON against DMP Common Standard schema](tests.md#test-validate-madmp-json-against-dmp-common-standard-schema)

### JSON-LD (Metric)
```json
{
  "@context": {
    "dqv": "http://www.w3.org/ns/dqv#",
    "dcterms": "http://purl.org/dc/terms/",
    "ftr": "https://w3id.org/ftr#"
  },
  "@id": "https://example.org/metric/meta.comp.1",
  "@type": "dqv:Metric",
  "dcterms:identifier": "meta.comp.1",
  "dcterms:title": "DMP Common Standard Field Compliance",
  "dcterms:description": "Verifies that the fields of the DMP JSON are aligned with the data types of the DMP Common Standard.",
  "ftr:dimension": "Compliance",
  "ftr:intendedOutcome": "Determine whether a maDMP JSON instance conforms to the DMP Common Standard schema, including correct field presence, structure, and data types.",
  "ftr:successCriterion": "The maDMP JSON validates successfully against the DMP Common Standard JSON Schema (no validation errors).",
  "ftr:failureCriterion": "The maDMP JSON fails schema validation (one or more validation errors), including type mismatches, missing required fields, or invalid structures.",
  "ftr:appliesTo": "Machine-actionable Data Management Plan (maDMP) in JSON format.",
  "ftr:expectedResultType": "boolean"
}
```