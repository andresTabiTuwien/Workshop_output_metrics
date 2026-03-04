# Tests Catalog

| ID | Title |
|----------|------|
| madmp-reused-datasets-declared-json | [Check for reused dataset declaration](#test-check-for-reused-dataset-declaration) |
| T-DCSC | [License for reused datasets](#test-license-for-reused-datasets) |
| T-DCSC | [Check for reused dataset PID](#test-check-for-reused-dataset-pid) |
| T-DCSC | [Distribution Present](#test-distribution-present) |
| T-DCSC | [Distribution Access Information](#test-distribution-access-information) |
| T-DCSC | [Distribution Title](#test-distribution-title) |
| T-DCSC | [Access rights for reused datasets](#test-access-rights-for-reused-datasets) |
| T-DCSC | [Personal data for reused datasets](#test-personal-data-for-reused-datasets) |
| T-DCSC | [Sensitive data for reused datasets](#test-sensitive-data-for-reused-datasets) |
| T-DCSC | [Distribution present (URL)](#test-distribution-present-url) |
| T-DCSC | [Access URL](#test-access-url) |
| T-DCSC | [PID matches destination repository record](#test-pid-matches-destination-repository-record) |
| T-DCSC | [PID resolves](#test-pid-resolves) |
| T-DCSC | [Reused data access matches destination](#test-reused-data-access-matches-destination) |
| T-DCSC | [Reused data license matches destination](#test-reused-data-license-matches-destination) |
| T-DCSC | [Check for new data (no is_reused)](#test-check-for-new-data-no-is_reused) |
| T-DCSC | [Check technical_resource for new data collection/creation](#test-check-technical_resource-for-new-data-collectioncreation) |
| T-DCSC | [Check data_access for new datasets](#test-check-data_access-for-new-datasets) |
| T-DCSC | [Check rights of new dataset](#test-check-rights-of-new-dataset) |
| T-DCSC | [Check metadata for new dataset](#test-check-metadata-for-new-dataset) |
| T-DCSC | [Check dataset_id exists](#test-check-dataset_id-exists) |
| T-DCSC | [Check PID resolves for dataset_id](#test-check-pid-resolves-for-dataset_id) |
| T-DCSC | [Check new data access matches destination](#test-check-new-data-access-matches-destination) |
| T-DCSC | [Check new data license matches destination](#test-check-new-data-license-matches-destination) |
| T-DCSC | [Check dataset.type is specified](#test-check-datasettype-is-specified) |
| T-DCSC | [Check distribution.format is specified](#test-check-distributionformat-is-specified) |
| T-DCSC | [Check distribution.byte_size is specified](#test-check-distributionbyte_size-is-specified) |
| T-DCSC | [Check dataset.type matches destination type](#test-check-datasettype-matches-destination-type) |
| T-DCSC | [Check dataset.type aligns with destination subtype](#test-check-datasettype-aligns-with-destination-subtype) |
| T-DCSC | [Check final dataset format matches destination files](#test-check-final-dataset-format-matches-destination-files) |
| T-DCSC | [Check final dataset size matches destination size](#test-check-final-dataset-size-matches-destination-size) |
| T-DCSC | [Validate maDMP JSON against DMP Common Standard schema](#test-validate-madmp-json-against-dmp-common-standard-schema) |
| T-DCSC | [Check dataset_methodology for controlled vocabularies](#test-check-dataset_methodology-for-controlled-vocabularies) |
| T-DCSC | [Check technical_resource.name for electronic lab notebook reference](#test-check-technical_resourcename-for-electronic-lab-notebook-reference) |


---

## Test: Check for reused dataset declaration

**Test ID:** madmp-reused-datasets-declared-json  
**Persistent URI:** https://example.org/test/madmp-reused-datasets-declared-json  

**Implements:** [data.reused.co.1](metrics.md#metric-madmp-declares-reused-datasets)

### Description
Given a maDMP JSON document, inspect dataset objects and verify the presence of a field indicating whether the dataset is reused.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.  
2. Locate dataset entries.  
3. Check whether at least one dataset contains `is_reused`.  
4. If present, return pass; otherwise return fail.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/madmp-reused-datasets-declared-json",
  "@type": "ftr:Test",
  "dcterms:identifier": "madmp-reused-datasets-declared-json",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check for reused dataset declaration"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Given a maDMP JSON document, inspect dataset objects and verify the presence of a field indicating whether the dataset is reused."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "madmp-reused-datasets-declared-json-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/madmp-reused-datasets-declared-json/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/madmp-reused-datasets-declared"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: License for reused datasets

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-license  

**Implements:** [data.reused.co.3](metrics.md#metric-reused-data-license)

### Description
Check if `is_reused` includes license (ref and start_date).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.  
2. Locate all dataset entries.  
3. Select datasets where `is_reused = true`.  
4. Verify that a `license` object exists.  
5. Verify that `license.ref` exists and is non-empty.  
6. Optionally verify that `license.start_date` exists.  
7. If all reused datasets comply, return pass; otherwise return fail.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-license",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "License for reused datasets"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Check if `is_reused` includes license (ref and start_date)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-license/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.reused.co.3"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Check for reused dataset PID

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC  

**Implements:** [data.reused.co.2](metrics.md#metric-reused-data-pid)

### Description
Check if `is_reused` includes `dataset_id` (identifier, type).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.  
2. Locate all dataset entries.  
3. Select datasets where `is_reused = true`.  
4. Verify that `dataset_id.identifier` exists and is non-empty.  
5. Optionally verify that `dataset_id.type` exists.  
6. If all reused datasets comply, return pass; otherwise return fail.  
7. If no reused datasets exist, return not applicable (optional policy).

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check for reused dataset PID"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Check if `is_reused` includes `dataset_id` (identifier, type)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.reused.co.2"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Distribution Present

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-distribution-present  

**Implements:** [data.reused.co.4](metrics.md#metric-reused-data-source)

### Description
Checks the distribution.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.  
2. Locate all dataset entries.  
3. Select datasets where `is_reused = true`.  
4. Verify that a `distribution` (or equivalent) object or array exists.  
5. If all reused datasets contain distribution metadata, return pass; otherwise return fail.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-distribution-present",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Distribution Present"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the distribution."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-distribution-present/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.reused.co.4"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Distribution Access Information

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-distribution-access  

**Implements:** [data.reused.co.4](metrics.md#metric-reused-data-source)

### Description
Checks whether distribution includes access information (e.g., access URL or download URL).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.  
2. Locate reused datasets (`is_reused = true`).  
3. For each distribution, verify that at least one access field exists (e.g., `access_url`, `download_url`, or equivalent).  
4. If all reused datasets contain access information, return pass; otherwise return fail.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-distribution-access",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Distribution Access Information"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks whether distribution includes access information (e.g., access URL or download URL)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-distribution-access/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.reused.co.4"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Distribution Title

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-distribution-title  

**Implements:** [data.reused.co.4](metrics.md#metric-reused-data-source)

### Description
Checks if there is title of distribution.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.  
2. Locate reused datasets (`is_reused = true`).  
3. For each distribution, verify that a non-empty `title` field exists.  
4. If all reused datasets contain a title, return pass; otherwise return fail.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-distribution-title",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Distribution Title"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if there is title of distribution."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-distribution-title/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.reused.co.4"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Access rights for reused datasets

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-access  

**Implements:** [data.reused.co.5](metrics.md#metric-reused-data-access)

### Description
Checks the data_access (open, shared, closed).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.  
2. Locate all dataset entries.  
3. Select datasets where `is_reused = true`.  
4. Verify that `data_access` exists.  
5. Verify that its value is one of: `open`, `shared`, `closed`.  
6. If all reused datasets comply, return pass; otherwise return fail.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-access",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Access rights for reused datasets"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the data_access (open, shared, closed)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-access/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.reused.co.5"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Personal data for reused datasets

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-personal-data  

**Implements:** [data.reused.co.6](metrics.md#metric-reused-data-personal)

### Description
Checks the personal_data.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.  
2. Locate all dataset entries.  
3. Select datasets where `is_reused = true`.  
4. Verify that `personal_data` exists.  
5. Verify that its value is explicit and valid (e.g., `true/false`, or a controlled term your schema allows).  
6. If all reused datasets comply, return pass; otherwise return fail.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-personal-data",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Personal data for reused datasets"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the personal_data."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-personal-data/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.reused.co.6"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Sensitive data for reused datasets

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-sensitive-data  

**Implements:** [data.reused.co.7](metrics.md#metric-reused-data-sensitive)

### Description
Checks the sensitive_data.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.  
2. Locate all dataset entries.  
3. Select datasets where `is_reused = true`.  
4. Verify that `sensitive_data` exists.  
5. Verify that its value is explicit and valid.  
6. If all reused datasets comply, return pass; otherwise return fail.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-sensitive-data",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Sensitive data for reused datasets"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the sensitive_data."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-sensitive-data/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.reused.co.7"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Distribution present (URL)

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-distribution-url-present  

**Implements:** [data.reused.co.8](metrics.md#metric-reused-data-url)

### Description
Checks the distribution.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.  
2. Locate reused datasets (`is_reused = true`).  
3. Verify that at least one distribution object exists.  
4. If yes, return pass; otherwise return fail.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-distribution-url-present",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Distribution present (URL)"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the distribution."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-distribution-url-present/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.reused.co.8"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Access URL

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-access-url  

**Implements:** [data.reused.co.8](metrics.md#metric-reused-data-url)

### Description
Checks the access_url.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.  
2. Locate reused datasets (`is_reused = true`).  
3. Verify that at least one distribution contains `access_url`.  
4. If yes, return pass; otherwise return fail.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-access-url",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Access URL"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the access_url."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-access-url/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.reused.co.8"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: PID matches destination repository record

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-repo-match  

**Implements:** [data.reused.feas.1](metrics.md#metric-repository-reused-data-pid)

### Description
Checks if reused dataset id in DMP matches the destination.

### Input
- dataset_id in maDMP  
- repository identifier field(s) (e.g., DOI URL)

### Output
pass/fail

### Procedure
1. Extract reused dataset identifiers from maDMP (`is_reused = true`).  
2. Query the target repository using the identifier.  
3. Retrieve the repository’s canonical identifier for the record.  
4. Compare with the maDMP dataset identifier.  
5. Pass if all identifiers match a repository record; otherwise fail.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-repo-match",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "PID matches destination repository record"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if reused dataset id in DMP matches the destination."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-repo-match/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.reused.feas.1"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: PID resolves

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-pid-resolves  

**Implements:** [data.reused.feas.1](metrics.md#metric-repository-reused-data-pid)

### Description
Checks if the PID resolves.

### Input
- dataset_id from maDMP  
- PID resolver

### Output
pass/fail

### Procedure
1. Extract reused dataset identifiers from maDMP (`is_reused = true`).  
2. Attempt resolution via the resolver (HTTP request).  
3. Treat successful HTTP responses (2xx/3xx) as resolvable.  
4. Pass if all PIDs resolve; otherwise fail.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-pid-resolves",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "PID resolves"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the PID resolves."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-pid-resolves/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.reused.feas.1"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Reused data access matches destination

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-access-match  

**Implements:** [data.reused.feas.2](metrics.md#metric-repository-reused-data-access)

### Description
Check if reused data access in DMP matches the destination.

### Input
- `data_access` in maDMP  
- `access_right` in destination repository (e.g., Zenodo)

### Output
pass/fail

### Procedure
1. Extract reused datasets from maDMP (`is_reused = true`).  
2. For each reused dataset, retrieve its record from the destination repository.  
3. Extract the repository access rights value.  
4. Compare maDMP `data_access` with repository `access_right`.  
5. Pass if all values match; otherwise fail.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-access-match",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Reused data access matches destination"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Check if reused data access in DMP matches the destination."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-access-match/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.reused.feas.2"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Reused data license matches destination

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-license-match  

**Implements:** [data.reused.feas.3](metrics.md#metric-repository-reused-data-license)

### Description
Checks if the license of the repository is the one mentioned in the DMP.

### Input
- license in maDMP JSON  
- license in destination repository (e.g., Zenodo)

### Output
pass/fail

### Procedure
1. Extract reused datasets from maDMP (`is_reused = true`).  
2. For each reused dataset, retrieve its record from the destination repository.  
3. Extract the license value from the repository record.  
4. Compare the repository license value with the maDMP license value.  
5. Return pass if all values match; otherwise return fail.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-license-match",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Reused data license matches destination"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the license of the repository is the one mentioned in the DMP."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-license-match/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.reused.feas.3"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Check for new data (no is_reused)

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-new-data  

**Implements:** [data.new.1](metrics.md#metric-new-data)

### Description
Checks if there is a dataset without `is_reused`.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries (e.g., the `dataset` array).
3. Identify any dataset entry where the field `is_reused` is **absent**.
4. If at least one dataset without `is_reused` exists, return pass; otherwise return fail.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-new-data",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check for new data (no is_reused)"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if there is a dataset without `is_reused`."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-new-data/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.new.1"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Check technical_resource for new data collection/creation

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-new-data-technical-resource  

**Implements:** [data.new.2](metrics.md#metric-new-data-collection-or-creation)

### Description
Checks the `technical_resource` (description, name, id.identifier and id.type).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries.
3. Identify candidate “new” datasets according to your policy (e.g., datasets where `is_reused` is absent or not true).
4. For each candidate dataset, check whether `technical_resource` exists.
5. Verify that `technical_resource.description` and `technical_resource.name` exist and are non-empty.
6. Verify that `technical_resource.id.identifier` and `technical_resource.id.type` exist and are non-empty.
7. Return **pass** if at least one candidate “new” dataset satisfies all required fields; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-new-data-technical-resource",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check technical_resource for new data collection/creation"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the `technical_resource` (description, name, id.identifier and id.type)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-new-data-technical-resource/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.new.2"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Check data_access for new datasets

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-new-data-access  

**Implements:** [data.new.3](metrics.md#metric-new-data-access)

### Description
Checks the `data_access` (`open`, `shared`, `closed`).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries.
3. Identify “new” datasets according to your policy (e.g., datasets where `is_reused` is absent or not true).
4. For each “new” dataset, check whether `data_access` exists.
5. Verify that `data_access` is one of: `open`, `shared`, `closed`.
6. Return **pass** if at least one “new” dataset has a valid `data_access`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-new-data-access",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check data_access for new datasets"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the `data_access` (`open`, `shared`, `closed`)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-new-data-access/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.new.3"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Check rights of new dataset

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-new-data-rights  

**Implements:** [data.new.3](metrics.md#metric-new-data-access)

### Description
Checks the rights of dataset.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries.
3. Identify “new” datasets according to your policy (e.g., datasets where `is_reused` is absent or not true).
4. For each “new” dataset, verify that a rights field/object exists (use your maDMP schema path, e.g., `rights`, `rights_statement`, or an equivalent rights block).
5. Verify the rights information is non-empty (e.g., contains a statement, URI, or controlled term).
6. Return **pass** if at least one “new” dataset contains rights information; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-new-data-rights",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check rights of new dataset"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the rights of dataset."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-new-data-rights/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.new.3"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Check metadata for new dataset

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-new-data-metadata  

**Implements:** [data.new.4](metrics.md#metric-new-data-metadata)

### Description
Checks the metadata (description, language, metadata_id.identifier and metadata_id.type).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries.
3. Identify “new” datasets according to your policy (e.g., datasets where `is_reused` is absent or not true).
4. For each “new” dataset, verify that a `metadata` object exists.
5. Verify that `metadata.description` exists and is non-empty.
6. Verify that `metadata.language` exists and is non-empty.
7. Verify that `metadata.metadata_id.identifier` exists and is non-empty.
8. Verify that `metadata.metadata_id.type` exists and is non-empty.
9. Return **pass** if at least one “new” dataset satisfies all required metadata fields; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-new-data-metadata",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check metadata for new dataset"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the metadata (description, language, metadata_id.identifier and metadata_id.type)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-new-data-metadata/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.new.4"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Check dataset_id exists

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-dataset-id-exists  

**Implements:** [data.new.feas.1](metrics.md#metric-repository-pid-resolution)

### Description
Checks if there is a `dataset_id`.

### Input
dataset_id of maDMP

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries.
3. For each dataset, check whether `dataset_id` exists.
4. Return **pass** if at least one dataset includes `dataset_id`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-dataset-id-exists",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check dataset_id exists"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if there is a `dataset_id`."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-dataset-id-exists/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.new.feas.1"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Check PID resolves for dataset_id

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-dataset-id-resolves  

**Implements:** [data.new.feas.1](metrics.md#metric-repository-pid-resolution)

### Description
Checks if the PID resolves.

### Input
dataset_id of maDMP in DOI resolver

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Extract all dataset identifiers from `dataset_id`.
3. For each identifier, attempt resolution using the appropriate resolver (e.g., HTTP request to a DOI resolver).
4. Treat successful HTTP responses (2xx/3xx) as resolvable.
5. Return **pass** if all tested PIDs resolve (or if your policy is “at least one resolves”, apply that consistently); otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-dataset-id-resolves",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check PID resolves for dataset_id"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the PID resolves."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-dataset-id-resolves/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.new.feas.1"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Check new data access matches destination

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-new-data-access-match-destination  

**Implements:** [data.new.feas.2](metrics.md#metric-repository-new-data-access)

### Description
Check if new data access in DMP matches the destination.

### Input
data_access in maDMP + access_right in Zenodo

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Identify “new” datasets according to your policy (e.g., datasets where `is_reused` is absent or not true).
3. For each new dataset, extract `data_access`.
4. Query the destination repository (e.g., Zenodo) for the corresponding dataset record (using PID or repository identifier available in the maDMP).
5. Extract the repository’s `access_right` (or equivalent access-rights field).
6. Compare maDMP `data_access` with repository `access_right` using your project’s mapping rules (if value vocabularies differ, apply a normalization mapping).
7. Return **pass** if all compared datasets match; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-new-data-access-match-destination",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check new data access matches destination"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Check if new data access in DMP matches the destination."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-new-data-access-match-destination/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.new.feas.2"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Check new data license matches destination

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-new-data-license-match-destination  

**Implements:** [data.new.feas.3](metrics.md#metric-repository-new-data-license)

### Description
Checks if the license of the repository is the one mentioned in the DMP.

### Input
license in maDMP JSON + license in Zenodo

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Identify “new” datasets according to your policy (e.g., datasets where `is_reused` is absent or not true).
3. For each new dataset, extract the maDMP license value (e.g., `license.ref` or equivalent field your schema uses).
4. Query the destination repository (e.g., Zenodo) for the corresponding dataset record (using PID or repository identifier available in the maDMP).
5. Extract the repository license value (e.g., Zenodo `license` field).
6. Normalize values if needed (e.g., map equivalent SPDX identifiers, URLs, or labels).
7. Compare the maDMP license value to the repository license value.
8. Return **pass** if all compared datasets match; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-new-data-license-match-destination",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check new data license matches destination"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the license of the repository is the one mentioned in the DMP."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-new-data-license-match-destination/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.new.feas.3"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Check dataset.type is specified

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-dataset-type  

**Implements:** [data.info.cov.1](metrics.md#metric-data-type)

### Description
Checks if the dataset type (e.g., qualitative or quantitative) is specified (`dataset.type`).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries (e.g., the `dataset` array).
3. For each dataset entry, check whether `dataset.type` exists and is non-empty.
4. If your project enforces a controlled vocabulary, verify the value is in the allowed set (e.g., `qualitative`, `quantitative`).
5. Return **pass** if all dataset entries in scope have a valid `dataset.type`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-dataset-type",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check dataset.type is specified"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the dataset type (e.g., qualitative or quantitative) is specified (`dataset.type`)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-dataset-type/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.info.cov.1"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Check distribution.format is specified

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-distribution-format  

**Implements:** [data.info.cov.2](metrics.md#metric-data-format)

### Description
Checks the dataset format (`distribution.format`).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their `distribution` objects/arrays.
3. For each distribution in scope, check whether `distribution.format` exists and is non-empty.
4. If your project enforces a controlled vocabulary (e.g., MIME types), optionally validate the value against that vocabulary.
5. Return **pass** if all distributions in scope have a non-empty `distribution.format`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-distribution-format",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check distribution.format is specified"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the dataset format (`distribution.format`)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-distribution-format/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.info.cov.2"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Check distribution.byte_size is specified

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-distribution-byte-size  

**Implements:** [data.info.cov.3](metrics.md#metric-data-size)

### Description
Checks the dataset size (`distribution.byte_size`).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their `distribution` objects/arrays.
3. For each distribution in scope, check whether `distribution.byte_size` exists.
4. Verify that `distribution.byte_size` is numeric (integer or float) and is **≥ 0**.
5. Return **pass** if all distributions in scope have a valid non-negative `distribution.byte_size`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-distribution-byte-size",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check distribution.byte_size is specified"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the dataset size (`distribution.byte_size`)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-distribution-byte-size/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.info.cov.3"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Check dataset.type matches destination type

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-dataset-type-match-destination-type  

**Implements:** [data.info.feas.1](metrics.md#metric-repository-data-type)

### Description
Checks that dataset is both the type of each destination.

### Input
dataset.type in maDMP + type in Zenodo

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. For each dataset in scope, extract `dataset.type`.
3. Determine the destination repository record corresponding to the dataset (e.g., via dataset PID/identifier in the maDMP).
4. Query the destination repository (e.g., Zenodo API/metadata endpoint) and retrieve the record `type`.
5. Normalize values if needed (e.g., mapping maDMP vocabulary to Zenodo vocabulary).
6. Compare maDMP `dataset.type` with destination `type`.
7. Return **pass** if all compared datasets match; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-dataset-type-match-destination-type",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check dataset.type matches destination type"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks that dataset is both the type of each destination."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-dataset-type-match-destination-type/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.info.feas.1"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Check dataset.type aligns with destination subtype

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-dataset-type-align-destination-subtype  

**Implements:** [data.info.feas.1](metrics.md#metric-repository-data-type)

### Description
Checks that sub-properties are pointing to the same type.

### Input
dataset.type in maDMP + subtype in Zenodo

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. For each dataset in scope, extract `dataset.type` (and any local sub-property if your maDMP schema includes it).
3. Retrieve the corresponding destination record from the repository (e.g., Zenodo).
4. Extract destination `subtype` (or equivalent sub-classification field).
5. Apply a mapping/normalization rule that relates maDMP `dataset.type` to acceptable destination subtypes (because subtype may be more granular than type).
6. Verify that the destination subtype is compatible with the maDMP dataset type (or that the maDMP type can be inferred from the subtype).
7. Return **pass** if all compared datasets are compatible; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-dataset-type-align-destination-subtype",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check dataset.type aligns with destination subtype"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks that sub-properties are pointing to the same type."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-dataset-type-align-destination-subtype/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.info.feas.1"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Check final dataset format matches destination files

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-dataset-format-match-destination-files  

**Implements:** [data.info.feas.2](metrics.md#metric-repository-data-format)

### Description
Checks the final dataset format.

### Input
distribution.format in maDMP + files in Zenodo

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset distributions in scope and extract `distribution.format`.
3. Identify the corresponding destination repository record (e.g., Zenodo) for the dataset/distribution using a PID or repository identifier available in the maDMP.
4. Query the destination repository and retrieve the list of deposited files and their format information (e.g., filename extensions and/or MIME types if provided).
5. Normalize formats for comparison (e.g., map extensions to MIME types, normalize case, apply a controlled vocabulary or mapping table).
6. Compare maDMP `distribution.format` to the observed destination file format(s):
   - **Strict mode:** every maDMP format must be present among destination formats.
   - **Compatible mode:** maDMP format is considered valid if it maps to at least one destination file format under your mapping table.
7. Return **pass** if the comparison succeeds for all distributions in scope; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-dataset-format-match-destination-files",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check final dataset format matches destination files"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the final dataset format."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-dataset-format-match-destination-files/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.info.feas.2"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Check final dataset size matches destination size

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-dataset-size-match-destination-size  

**Implements:** [data.info.feas.3](metrics.md#metric-repository-data-size)

### Description
Checks the final dataset size.

### Input
distribution.byte_size in maDMP + size in Zenodo

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset distributions in scope and extract `distribution.byte_size`.
3. Identify the corresponding destination repository record (e.g., Zenodo) using a PID or repository identifier available in the maDMP.
4. Query the destination repository and retrieve the deposited size value:
   - If Zenodo provides per-file sizes, compute a total size (sum of file sizes) for the record, or compare per distribution if your mapping supports it.
5. Normalize size units (ensure all sizes are compared in bytes).
6. Compare maDMP `distribution.byte_size` to destination size:
   - **Exact mode:** values must be equal.
   - **Tolerance mode (optional):** values must be within an acceptable difference threshold (define e.g., ±1%).
7. Return **pass** if all distributions in scope match (per chosen mode); otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-dataset-size-match-destination-size",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check final dataset size matches destination size"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the final dataset size."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-dataset-size-match-destination-size/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/data.info.feas.3"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Validate maDMP JSON against DMP Common Standard schema

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-dmp-cs-schema-validation  

**Implements:** [meta.comp.1](metrics.md#metric-dmp-common-standard-field-compliance)

### Description
Checks if the JSON matches with DMP Common Standard schema.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Obtain the DMP Common Standard JSON Schema version used by your project (local file or URL).
2. Load/parse the input maDMP JSON document.
3. Run JSON Schema validation of the maDMP against the DMP Common Standard schema.
4. If validation reports **zero** errors, return **pass**.
5. If one or more validation errors are reported, return **fail** and record the validation error details (path, expected type, etc.) as diagnostic output.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-dmp-cs-schema-validation",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Validate maDMP JSON against DMP Common Standard schema"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the JSON matches with DMP Common Standard schema."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-dmp-cs-schema-validation/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/meta.comp.1"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Check dataset_methodology for controlled vocabularies

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-dataset-methodology-controlled-vocabularies  

**Implements:** [meta.co.1](metrics.md#metric-controlled-vocabularies-used-in-methodology)

### Description
Checks the dataset_methodology for controlled vocabularies.

### Input
maDMP JSON + controlled vocabularies from external sources

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset methodology information (e.g., `dataset_methodology` or the equivalent field in your schema).
3. Extract methodology terms, identifiers, URIs, or references used in that field.
4. Compare the extracted values against recognized controlled vocabularies or ontology sources defined by your project or external reference lists.
5. Verify whether at least one methodology element points to, or can be matched with, a controlled vocabulary term or external vocabulary source.
6. Return **pass** if controlled vocabulary usage is detected in methodology; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-dataset-methodology-controlled-vocabularies",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check dataset_methodology for controlled vocabularies"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the dataset_methodology for controlled vocabularies."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-dataset-methodology-controlled-vocabularies/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/meta.co.1"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

---

## Test: Check technical_resource.name for electronic lab notebook reference

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-technical-resource-eln-reference  

**Implements:** [meta.co.2](metrics.md#metric-electronic-lab-notebook-referenced-as-a-technical-resource)

### Description
Checks if an electronic lab notebook is mentioned (`technical_resource.name`).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate `technical_resource` entries in scope.
3. Extract each `technical_resource.name` value.
4. Check whether any name explicitly mentions an electronic lab notebook or a known ELN tool/service name used by your project.
5. Return **pass** if at least one technical resource name indicates an ELN; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-technical-resource-eln-reference",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check technical_resource.name for electronic lab notebook reference"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if an electronic lab notebook is mentioned (`technical_resource.name`)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "template keyword"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-technical-resource-eln-reference/run"
  },
  "doap:repository": {
    "@id": "https://example.org/repository"
  },
  "dcterms:type": {
    "@id": "https://example.org/test-type/default"
  },
  "dcterms:license": {
    "@id": "http://creativecommons.org/licenses/by/4.0/"
  },
  "ftr:applicationArea": {
    "@id": "https://example.org/application-area/default"
  },
  "dcat:version": {
    "@value": "0.0.1"
  },
  "adms:versionNotes": {
    "@language": "en",
    "@value": "Initial template version"
  },
  "ftr:status": {
    "@language": "en",
    "@value": "Draft"
  },
  "dcat:contactPoint": {
    "@id": "https://example.org/contact"
  },
  "dcterms:creator": [
    {
      "@id": "https://example.org/organization"
    }
  ],
  "dcat:publisher": {
    "@id": "https://example.org/organization"
  },
  "sio:SIO_000233": {
    "@id": "https://example.org/metric/meta.co.2"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

