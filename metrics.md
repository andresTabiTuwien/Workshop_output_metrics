# Metrics Catalog

| ID | Title |
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
| meta.co.1 | [Controlled Vocabularies Used in Methodology](#metric-controlled-vocabularies-used-in-methodology) |
| meta.co.2 | [Electronic Lab Notebook Referenced as a technical resource](#metric-electronic-lab-notebook-referenced-as-a-technical-resource) |


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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/madmp-reused-datasets-declared",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/madmp-reused-datasets-declared",
  "title": {
    "@language": "en",
    "@value": "maDMP declares reused datasets"
  },
  "description": {
    "@language": "en",
    "@value": "The machine-actionable Data Management Plan (maDMP) declares whether any dataset described in the plan is reused."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/madmp-reused-datasets-declared-json"
  },
  "abbreviation": {
    "@value": "data.reused.co.1-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/madmp-reused-datasets-declared"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Not specified"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.reused.co.2",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.reused.co.2",
  "title": {
    "@language": "en",
    "@value": "Reused Data PID"
  },
  "description": {
    "@language": "en",
    "@value": "Verifies that reused datasets come with PIDs."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC"
  },
  "abbreviation": {
    "@value": "data.reused.co.2-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.reused.co.2"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Completeness"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.reused.co.3",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.reused.co.3",
  "title": {
    "@language": "en",
    "@value": "Reused Data License"
  },
  "description": {
    "@language": "en",
    "@value": "Verifies that reused datasets come with license."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-license"
  },
  "abbreviation": {
    "@value": "data.reused.co.3-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.reused.co.3"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Completeness"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
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
- [Distribution Present](tests.md#test-distribution-present)
- [Distribution Access Information](tests.md#test-distribution-access-information)
- [Distribution Title](tests.md#test-distribution-title)

### JSON-LD (Metric)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.reused.co.4",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.reused.co.4",
  "title": {
    "@language": "en",
    "@value": "Reused Data Source"
  },
  "description": {
    "@language": "en",
    "@value": "Verifies that reused datasets are shared."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-distribution-present"
  },
  "abbreviation": {
    "@value": "data.reused.co.4-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.reused.co.4"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Completeness"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.reused.co.5",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.reused.co.5",
  "title": {
    "@language": "en",
    "@value": "Reused Data Access"
  },
  "description": {
    "@language": "en",
    "@value": "Verifies the access rights of the reused datasets."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-access"
  },
  "abbreviation": {
    "@value": "data.reused.co.5-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.reused.co.5"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Completeness"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.reused.co.6",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.reused.co.6",
  "title": {
    "@language": "en",
    "@value": "Reused Data Personal"
  },
  "description": {
    "@language": "en",
    "@value": "Verifies the existence of personal data."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-personal-data"
  },
  "abbreviation": {
    "@value": "data.reused.co.6-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.reused.co.6"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Completeness"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.reused.co.7",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.reused.co.7",
  "title": {
    "@language": "en",
    "@value": "Reused Data Sensitive"
  },
  "description": {
    "@language": "en",
    "@value": "Verifies the existence of sensitive data."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-sensitive-data"
  },
  "abbreviation": {
    "@value": "data.reused.co.7-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.reused.co.7"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Completeness"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.reused.co.8",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.reused.co.8",
  "title": {
    "@language": "en",
    "@value": "Reused Data URL"
  },
  "description": {
    "@language": "en",
    "@value": "Verifies that the reused data have URL."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-distribution-url-present"
  },
  "abbreviation": {
    "@value": "data.reused.co.8-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.reused.co.8"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Completeness"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.reused.feas.1",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.reused.feas.1",
  "title": {
    "@language": "en",
    "@value": "Repository Reused Data PID"
  },
  "description": {
    "@language": "en",
    "@value": "Validates that the reused dataset exists in the repository."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-repo-match"
  },
  "abbreviation": {
    "@value": "data.reused.feas.1-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.reused.feas.1"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Feasibility"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.reused.feas.2",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.reused.feas.2",
  "title": {
    "@language": "en",
    "@value": "Repository Reused Data Access"
  },
  "description": {
    "@language": "en",
    "@value": "Validates that the access rights of the reused dataset match those of the destination."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-access-match"
  },
  "abbreviation": {
    "@value": "data.reused.feas.2-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.reused.feas.2"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Feasibility"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.reused.feas.3",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.reused.feas.3",
  "title": {
    "@language": "en",
    "@value": "Repository Reused Data License"
  },
  "description": {
    "@language": "en",
    "@value": "Validates that license of the reused dataset match those of the destination."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-license-match"
  },
  "abbreviation": {
    "@value": "data.reused.feas.3-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.reused.feas.3"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Feasibility"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
}
```

---

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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.new.1",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.new.1",
  "title": {
    "@language": "en",
    "@value": "New Data"
  },
  "description": {
    "@language": "en",
    "@value": "Verifies that information about the new data exist."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-new-data"
  },
  "abbreviation": {
    "@value": "data.new.1-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.new.1"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Completeness"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
}
```

---

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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.new.2",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.new.2",
  "title": {
    "@language": "en",
    "@value": "New Data Collection or Creation"
  },
  "description": {
    "@language": "en",
    "@value": "Verifies how the new data were collected or created."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-new-data-technical-resource"
  },
  "abbreviation": {
    "@value": "data.new.2-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.new.2"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "RDM Coverage"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
}
```

---

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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.new.3",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.new.3",
  "title": {
    "@language": "en",
    "@value": "New Data Access"
  },
  "description": {
    "@language": "en",
    "@value": "Verifies that access rights of the new dataset is specified."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-new-data-access"
  },
  "abbreviation": {
    "@value": "data.new.3-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.new.3"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Openness / Reuse"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
}
```

---

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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.new.4",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.new.4",
  "title": {
    "@language": "en",
    "@value": "New Data Metadata"
  },
  "description": {
    "@language": "en",
    "@value": "Verifies the reproducibility of the new data."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-new-data-metadata"
  },
  "abbreviation": {
    "@value": "data.new.4-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.new.4"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Completeness"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
}
```

---

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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.new.feas.1",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.new.feas.1",
  "title": {
    "@language": "en",
    "@value": "Repository PID Resolution"
  },
  "description": {
    "@language": "en",
    "@value": "Validates that the PID provided is resolvable according to its system resolver."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-dataset-id-exists"
  },
  "abbreviation": {
    "@value": "data.new.feas.1-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.new.feas.1"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Feasibility"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
}
```

---

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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.new.feas.2",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.new.feas.2",
  "title": {
    "@language": "en",
    "@value": "Repository New Data Access"
  },
  "description": {
    "@language": "en",
    "@value": "Validates that the access rights of the new dataset match those of the destination."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-new-data-access-match-destination"
  },
  "abbreviation": {
    "@value": "data.new.feas.2-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.new.feas.2"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Feasibility"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
}
```

---

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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.new.feas.3",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.new.feas.3",
  "title": {
    "@language": "en",
    "@value": "Repository New Data License"
  },
  "description": {
    "@language": "en",
    "@value": "Validates that license of the new dataset match those of the destination."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-new-data-license-match-destination"
  },
  "abbreviation": {
    "@value": "data.new.feas.3-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.new.feas.3"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Feasibility"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
}
```

---

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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.info.cov.1",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.info.cov.1",
  "title": {
    "@language": "en",
    "@value": "Data Type"
  },
  "description": {
    "@language": "en",
    "@value": "Verifies that the type of the dataset is qualitative or quantitative."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-dataset-type"
  },
  "abbreviation": {
    "@value": "data.info.cov.1-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.info.cov.1"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Coverage"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
}
```

---

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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.info.cov.2",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.info.cov.2",
  "title": {
    "@language": "en",
    "@value": "Data Format"
  },
  "description": {
    "@language": "en",
    "@value": "Verifies the format of the dataset."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-distribution-format"
  },
  "abbreviation": {
    "@value": "data.info.cov.2-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.info.cov.2"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Coverage"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
}
```

---

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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.info.cov.3",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.info.cov.3",
  "title": {
    "@language": "en",
    "@value": "Data Size"
  },
  "description": {
    "@language": "en",
    "@value": "Verifies the size of the dataset."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-distribution-byte-size"
  },
  "abbreviation": {
    "@value": "data.info.cov.3-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.info.cov.3"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Coverage"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
}
```

---

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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.info.feas.1",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.info.feas.1",
  "title": {
    "@language": "en",
    "@value": "Repository Data Type"
  },
  "description": {
    "@language": "en",
    "@value": "Validates that the type of the dataset match those of the destination."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-dataset-type-match-destination-type"
  },
  "abbreviation": {
    "@value": "data.info.feas.1-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.info.feas.1"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Feasibility"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
}
```

---

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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.info.feas.2",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.info.feas.2",
  "title": {
    "@language": "en",
    "@value": "Repository Data Format"
  },
  "description": {
    "@language": "en",
    "@value": "Validates that the format of the dataset match those of the destination."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-dataset-format-match-destination-files"
  },
  "abbreviation": {
    "@value": "data.info.feas.2-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.info.feas.2"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Feasibility"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
}
```

---

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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/data.info.feas.3",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/data.info.feas.3",
  "title": {
    "@language": "en",
    "@value": "Repository Data Size"
  },
  "description": {
    "@language": "en",
    "@value": "Validates that the size of the dataset match those of the destination."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-dataset-size-match-destination-size"
  },
  "abbreviation": {
    "@value": "data.info.feas.3-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/data.info.feas.3"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Feasibility"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
}
```

---

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
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/meta.comp.1",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/meta.comp.1",
  "title": {
    "@language": "en",
    "@value": "DMP Common Standard Field Compliance"
  },
  "description": {
    "@language": "en",
    "@value": "Verifies that the fields of the DMP JSON are aligned with the data types of the DMP Common Standard."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-dmp-cs-schema-validation"
  },
  "abbreviation": {
    "@value": "meta.comp.1-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/meta.comp.1"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Compliance"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
}
```

---

## Metric: Controlled Vocabularies Used in Methodology

**Metric ID:** meta.co.1  
**Persistent URI:** https://example.org/metric/meta.co.1  
**Dimension:** Completeness  

### Title
Controlled Vocabularies Used in Methodology

### Narrative
Verifies that controlled vocabularies are used in methodology.

### Intended Outcome
Determine whether the methodology information in the maDMP refers to controlled vocabularies, supporting semantic consistency and interoperability.

### Applies To
Machine-actionable Data Management Plan (maDMP) in JSON format.

### Success Criterion
For dataset methodology information in scope, `dataset_methodology` includes references to one or more controlled vocabularies, ontology terms, or externally defined vocabulary sources.

### Failure Criterion
No controlled vocabulary usage can be identified in `dataset_methodology`, or methodology information is missing where expected.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Check dataset_methodology for controlled vocabularies](tests.md#test-check-dataset_methodology-for-controlled-vocabularies)

### JSON-LD (Metric)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/meta.co.1",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/meta.co.1",
  "title": {
    "@language": "en",
    "@value": "Controlled Vocabularies Used in Methodology"
  },
  "description": {
    "@language": "en",
    "@value": "Verifies that controlled vocabularies are used in methodology."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-dataset-methodology-controlled-vocabularies"
  },
  "abbreviation": {
    "@value": "meta.co.1-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/meta.co.1"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Completeness"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
}
```

---

## Metric: Electronic Lab Notebook Referenced as a technical resource

**Metric ID:** meta.co.2  
**Persistent URI:** https://example.org/metric/meta.co.2  
**Dimension:** Completeness  

### Title
Electronic Lab Notebook Referenced as a technical resource

### Narrative
Verifies that the reference of an electronic lab notebook is included.

### Intended Outcome
Determine whether the maDMP includes a reference to an electronic lab notebook (ELN) as part of the declared technical resources.

### Applies To
Machine-actionable Data Management Plan (maDMP) in JSON format.

### Success Criterion
At least one `technical_resource.name` value indicates an electronic lab notebook, or a technical resource is clearly identified as an ELN.

### Failure Criterion
No technical resource references an electronic lab notebook, or technical resource information is missing where expected.

### Expected Result Type
Boolean (pass/fail)

### Associated Test(s)
- [Check technical_resource.name for electronic lab notebook reference](tests.md#test-check-technical_resourcename-for-electronic-lab-notebook-reference)

### JSON-LD (Metric)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/metric/meta.co.2",
  "@type": "dqv:Metric",
  "identifier": "https://example.org/metric/meta.co.2",
  "title": {
    "@language": "en",
    "@value": "Electronic Lab Notebook Referenced as a technical resource"
  },
  "description": {
    "@language": "en",
    "@value": "Verifies that the reference of an electronic lab notebook is included."
  },
  "license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcterms:publisher": {
    "@id": "https://example.org/organization"
  },
  "hasImplementation": {
    "@id": "https://example.org/test/T-DCSC-technical-resource-eln-reference"
  },
  "abbreviation": {
    "@value": "meta.co.2-M"
  },
  "contactPoint": {
    "@id": "https://example.org/contact"
  },
  "keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "landingPage": {
    "@id": "https://example.org/metric/meta.co.2"
  },
  "version": {
    "@value": "0.0.1"
  },
  "inDimension": {
    "@value": "Completeness"
  },
  "isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  },
  "hasBenchmark": {
    "@id": "https://example.org/benchmark/default"
  },
  "status": {
    "@language": "en",
    "@value": "Draft"
  },
  "supportedBy": {
    "@id": "https://example.org/project"
  }
}
```

