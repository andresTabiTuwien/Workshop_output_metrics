# Tests Catalog

| No. | Test ID | Title |
|-----|---------|------|
| 1 | T-DCSC | [Check for reused dataset declaration](#test-1-check-for-reused-dataset-declaration) |
| 2 | T-DCSC | [Check License for Reused Datasets](#test-2-check-license-for-reused-datasets) |
| 3 | T-DCSC | [Check for reused dataset PID](#test-3-check-for-reused-dataset-pid) |
| 4 | T-DCSC | [Check Distribution Entry is Present](#test-4-check-distribution-entry-is-present) |
| 5 | T-DCSC | [Check Distribution Access Information is Present](#test-5-check-distribution-access-information-is-present) |
| 6 | T-DCSC | [Check Distribution Title is Present](#test-6-check-distribution-title-is-present) |
| 7 | T-DCSC | [Check Access Rights for Reused Datasets](#test-7-check-access-rights-for-reused-datasets) |
| 8 | T-DCSC | [Check Personal Data Flag for Reused Datasets](#test-8-check-personal-data-flag-for-reused-datasets) |
| 9 | T-DCSC | [Check Sensitive Data Flag for Reused Datasets](#test-9-check-sensitive-data-flag-for-reused-datasets) |
| 10 | T-DCSC | [Check Distribution URL is Present](#test-10-check-distribution-url-is-present) |
| 11 | T-DCSC | [Check Access URL is Present and Non-empty](#test-11-check-access-url-is-present-and-non-empty) |
| 12 | T-DCSC | [Check PID Matches Destination Repository Record](#test-12-check-pid-matches-destination-repository-record) |
| 13 | T-DCSC | [Check PID Resolves Successfully](#test-13-check-pid-resolves-successfully) |
| 14 | T-DCSC | [Check Reused Data Access Matches Destination](#test-14-check-reused-data-access-matches-destination) |
| 15 | T-DCSC | [Check Reused Data License Matches Destination](#test-15-check-reused-data-license-matches-destination) |
| 16 | T-DCSC | [Check for new data (no is_reused)](#test-16-check-for-new-data-no-is_reused) |
| 17 | T-DCSC | [Check technical_resource for new data collection/creation](#test-17-check-technical_resource-for-new-data-collectioncreation) |
| 18 | T-DCSC | [Check data_access for new datasets](#test-18-check-data_access-for-new-datasets) |
| 19 | T-DCSC | [Check rights of new dataset](#test-19-check-rights-of-new-dataset) |
| 20 | T-DCSC | [Check metadata for new dataset](#test-20-check-metadata-for-new-dataset) |
| 21 | T-DCSC | [Check dataset_id exists](#test-21-check-dataset_id-exists) |
| 22 | T-DCSC | [Check PID resolves for dataset_id](#test-22-check-pid-resolves-for-dataset_id) |
| 23 | T-DCSC | [Check new data access matches destination](#test-23-check-new-data-access-matches-destination) |
| 24 | T-DCSC | [Check new data license matches destination](#test-24-check-new-data-license-matches-destination) |
| 25 | T-DCSC | [Check dataset.type is specified](#test-25-check-datasettype-is-specified) |
| 26 | T-DCSC | [Check distribution.format is specified](#test-26-check-distributionformat-is-specified) |
| 27 | T-DCSC | [Check distribution.byte_size is specified](#test-27-check-distributionbyte_size-is-specified) |
| 28 | T-DCSC | [Check dataset.type matches destination type](#test-28-check-datasettype-matches-destination-type) |
| 29 | T-DCSC | [Check dataset.type aligns with destination subtype](#test-29-check-datasettype-aligns-with-destination-subtype) |
| 30 | T-DCSC | [Check final dataset format matches destination files](#test-30-check-final-dataset-format-matches-destination-files) |
| 31 | T-DCSC | [Check final dataset size matches destination size](#test-31-check-final-dataset-size-matches-destination-size) |
| 32 | T-DCSC | [Check maDMP JSON Validates Against DMP Common Standard Schema](#test-32-check-madmp-json-validates-against-dmp-common-standard-schema) |
| 33 | T-DCSC | [Check dataset_methodology for controlled vocabularies](#test-33-check-dataset_methodology-for-controlled-vocabularies) |
| 34 | T-DCSC | [Check technical_resource.name for electronic lab notebook reference](#test-34-check-technical_resourcename-for-electronic-lab-notebook-reference) |
| 35 | T-DCSC | [Check related_identifier resource_type for ReadMe file](#test-35-check-related_identifier-resource_type-for-readme-file) |
| 36 | T-DCSC | [Check metadata_standard_id is registered in metadata registries](#test-36-check-metadata_standard_id-is-registered-in-metadata-registries) |
| 37 | T-DCSC | [Check distribution format is open](#test-37-check-distribution-format-is-open) |
| 38 | T-DCSC | [Check ELN dataset linked via related_ids](#test-38-check-eln-dataset-linked-via-related_ids) |
| 39 | T-DCSC | [Check technical_resource for dataset documentation](#test-39-check-technical_resource-for-dataset-documentation) |
| 40 | T-DCSC | [Check data_quality_assurance for quality control methods](#test-40-check-data_quality_assurance-for-quality-control-methods) |
| 41 | T-DCSC | [Check host.title and host.url for storage location](#test-41-check-hosttitle-and-hosturl-for-storage-location) |
| 42 | T-DCSC | [Check host for trusted repository storage](#test-42-check-host-for-trusted-repository-storage) |
| 43 | T-DCSC | [Check sensitive_data classification is assigned](#test-43-check-sensitive_data-classification-is-assigned) |
| 44 | T-DCSC | [Check host security and backup reflect sensitivity level](#test-44-check-host-security-and-backup-reflect-sensitivity-level) |
| 45 | T-DCSC | [Check contributor.role for backup responsibility](#test-45-check-contributorrole-for-backup-responsibility) |
| 46 | T-DCSC | [Check backup_frequency is declared](#test-46-check-backup_frequency-is-declared) |
| 47 | T-DCSC | [Check host.id matches Zenodo deposit location](#test-47-check-hostid-matches-zenodo-deposit-location) |
| 48 | T-DCSC | [Check security_and_privacy.title for security measures](#test-48-check-security_and_privacytitle-for-security-measures) |
| 49 | T-DCSC | [Check security_and_privacy.description for access rights management](#test-49-check-security_and_privacydescription-for-access-rights-management) |
| 50 | T-DCSC | [Check security_and_privacy.description for authorised access controls](#test-50-check-security_and_privacydescription-for-authorised-access-controls) |
| 51 | T-DCSC | [Check security_and_privacy.description for access control and user permissions](#test-51-check-security_and_privacydescription-for-access-control-and-user-permissions) |
| 52 | T-DCSC | [Check security_and_privacy.description for access procedures](#test-52-check-security_and_privacydescription-for-access-procedures) |
| 53 | T-DCSC | [Check security_and_privacy.description and ethical_issues_report for GDPR and ethics compliance](#test-53-check-security_and_privacydescription-and-ethical_issues_report-for-gdpr-and-ethics-compliance) |
| 54 | T-DCSC | [Check security_and_privacy.title for implemented security measures at destination](#test-54-check-security_and_privacytitle-for-implemented-security-measures-at-destination) |
| 55 | T-DCSC | [Check security_and_privacy.description for data protection method when sensitive_data is true](#test-55-check-security_and_privacydescription-for-data-protection-method-when-sensitive_data-is-true) |
| 56 | T-DCSC | [Check security_and_privacy for anonymised synthetic data provision](#test-56-check-security_and_privacy-for-anonymised-synthetic-data-provision) |
| 57 | T-DCSC | [Check rights for statement of no data restrictions](#test-57-check-rights-for-statement-of-no-data-restrictions) |
| 58 | T-DCSC | [Check license_ref for dataset licence](#test-58-check-license_ref-for-dataset-licence) |
| 59 | T-DCSC | [Check license_ref against SPDX for software datasets](#test-59-check-license_ref-against-spdx-for-software-datasets) |
| 60 | T-DCSC | [Check data_access and rights for access agreements or MoUs](#test-60-check-data_access-and-rights-for-access-agreements-or-mous) |
| 61 | T-DCSC | [Check contributor.role for data owner](#test-61-check-contributorrole-for-data-owner) |
| 62 | T-DCSC | [Check contributor for author role when dataset type is software](#test-62-check-contributor-for-author-role-when-dataset-type-is-software) |
| 63 | T-DCSC | [Check ethical_issues_exist for valid value](#test-63-check-ethical_issues_exist-for-valid-value) |
| 64 | T-DCSC | [Check ethical_issues_description is present when ethical_issues_exist is no](#test-64-check-ethical_issues_description-is-present-when-ethical_issues_exist-is-no) |
| 65 | T-DCSC | [Check data_access for open status](#test-65-check-data_access-for-open-status) |
| 66 | T-DCSC | [Check distribution is present for dataset](#test-66-check-distribution-is-present-for-dataset) |
| 67 | T-DCSC | [Check license_ref is present within distribution](#test-67-check-license_ref-is-present-within-distribution) |
| 68 | T-DCSC | [Check rights for data restrictions reference](#test-68-check-rights-for-data-restrictions-reference) |
| 69 | T-DCSC | [Check distribution license_ref for Horizon Europe CC-BY compliance](#test-69-check-distribution-license_ref-for-horizon-europe-cc-by-compliance) |
| 70 | T-DCSC | [Check data_access matches destination host access policy](#test-70-check-data_access-matches-destination-host-access-policy) |
| 71 | T-DCSC | [Check distribution license_ref matches destination host licence policy](#test-71-check-distribution-license_ref-matches-destination-host-licence-policy) |
| 72 | T-DCSC | [Check distribution license.start_date matches destination embargo policy](#test-72-check-distribution-licensestart_date-matches-destination-embargo-policy) |
| 73 | T-DCSC | [Check rights matches destination host restriction policy](#test-73-check-rights-matches-destination-host-restriction-policy) |
| 74 | T-DCSC | [Check repository host for absence of embargo date](#test-74-check-repository-host-for-absence-of-embargo-date) |
| 75 | T-DCSC | [Check distribution.license.start_date for absence in maDMP](#test-75-check-distributionlicensestart_date-for-absence-in-madmp) |
| 76 | T-DCSC | [Check host.title and host.url against thematic repository registries](#test-76-check-hosttitle-and-hosturl-against-thematic-repository-registries) |
| 77 | T-DCSC | [Check host against OpenAIRE and FAIRsharing FAIR benchmarks](#test-77-check-host-against-openaire-and-fairsharing-fair-benchmarks) |
| 78 | T-DCSC | [Check host against trusted repository registry benchmark](#test-78-check-host-against-trusted-repository-registry-benchmark) |
| 79 | T-DCSC | [Check host.backup_frequency and host.backup_type for back-up strategy](#test-79-check-hostbackup_frequency-and-hostbackup_type-for-back-up-strategy) |
| 80 | T-DCSC | [Check certified_with exists in host](#test-80-check-certified_with-exists-in-host) |
| 81 | T-DCSC | [Check cost title or description for preservation reference](#test-81-check-cost-title-or-description-for-preservation-reference) |
| 82 | T-DCSC | [Check host_id against FAIRsharing for repository policy](#test-82-check-host_id-against-fairsharing-for-repository-policy) |
| 83 | T-DCSC | [Check dataset_id resolves to declared destination via DOI URL](#test-83-check-dataset_id-resolves-to-declared-destination-via-doi-url) |
| 84 | T-DCSC | [Check preservation_statement and host for long-term storage intention](#test-84-check-preservation_statement-and-host-for-long-term-storage-intention) |
| 85 | T-DCSC | [Check dataset.keyword against Zenodo keywords](#test-85-check-datasetkeyword-against-zenodo-keywords) |
| 86 | T-DCSC | [Check dataset.language against Zenodo language support](#test-86-check-datasetlanguage-against-zenodo-language-support) |
| 87 | T-DCSC | [Check host_id against Zenodo and FAIRsharing for policy compliance](#test-87-check-host_id-against-zenodo-and-fairsharing-for-policy-compliance) |
| 88 | T-DCSC | [Check related_identifier.identifier for external resources](#test-88-check-related_identifieridentifier-for-external-resources) |
| 89 | T-DCSC | [Check related_identifier for metadata standard fields](#test-89-check-related_identifier-for-metadata-standard-fields) |
| 90 | T-DCSC | [Check URLs in maDMP are valid and resolvable](#test-90-check-urls-in-madmp-are-valid-and-resolvable) |
| 91 | T-DCSC | [Check dataset fields against OpenAIRE SKG-IF API](#test-91-check-dataset-fields-against-openaire-skg-if-api) |
| 92 | T-DCSC | [Check contributor roles against CRediT taxonomy](#test-92-check-contributor-roles-against-credit-taxonomy) |
| 93 | T-DCSC | [Check host.pid_system for PID declaration](#test-93-check-hostpid_system-for-pid-declaration) |
| 94 | T-DCSC | [Check certified_with against trusted registry](#test-94-check-certified_with-against-trusted-registry) |
| 95 | T-DCSC | [Check host_id.identifier and host_id.type for valid repository link](#test-95-check-host_ididentifier-and-host_idtype-for-valid-repository-link) |
| 96 | T-DCSC | [Check host.pid_system matches destination PID system in Zenodo](#test-96-check-hostpid_system-matches-destination-pid-system-in-zenodo) |
| 97 | T-DCSC | [Check dmp.contributor name, role, and contact](#test-97-check-dmpcontributor-name-role-and-contact) |
| 98 | T-DCSC | [Check dmp.contributor.role for Data Steward](#test-98-check-dmpcontributorrole-for-data-steward) |
| 99 | T-DCSC | [Check contributor_id and affiliation.affiliation_id for PIDs](#test-99-check-contributor_id-and-affiliationaffiliation_id-for-pids) |
| 100 | T-DCSC | [Check dmp.contributor fields against destination contributors](#test-100-check-dmpcontributor-fields-against-destination-contributors) |
| 101 | T-DCSC | [Check Data Steward role in maDMP against contributors.type Other in destination](#test-101-check-data-steward-role-in-madmp-against-contributorstype-other-in-destination) |
| 102 | T-DCSC | [Check contributor PIDs in maDMP against Zenodo contributors](#test-102-check-contributor-pids-in-madmp-against-zenodo-contributors) |
| 103 | T-DCSC | [Check cost in maDMP against repository cost](#test-103-check-cost-in-madmp-against-repository-cost) |
| 104 | T-DCSC | [Check cost fields for budget specification](#test-104-check-cost-fields-for-budget-specification) |
| 105 | T-DCSC | [Check cost in maDMP for no additional resources statement](#test-105-check-cost-in-madmp-for-no-additional-resources-statement) |



---

## Test 1: Check for reused dataset declaration

**Test ID:** madmp-reused-datasets-declared-json  
**Persistent URI:** https://example.org/test/madmp-reused-datasets-declared-json

**Implements:** [data.reused.co.1](metrics.md#metric-1-madmp-declares-reused-datasets)

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
      "@value": "reused dataset"
    },
    {
      "@language": "en",
      "@value": "data reuse"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    },
    {
      "@language": "en",
      "@value": "completeness"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
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

## Test 2: Check License for Reused Datasets

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-license

**Implements:** [data.reused.co.3](metrics.md#metric-3-reused-data-license)

### Description
Checks whether the `is_reused` dataset entry includes a license reference (`license_ref`) with both a license identifier and a start date, confirming that the legal terms for reusing the dataset are declared.

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
    "@value": "Check License for Reused Datasets"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Check if `is_reused` includes license (ref and start_date)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "reused dataset"
    },
    {
      "@language": "en",
      "@value": "data license"
    },
    {
      "@language": "en",
      "@value": "license reference"
    },
    {
      "@language": "en",
      "@value": "maDMP"
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

## Test 3: Check for reused dataset PID

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-reused-dataset-pid

**Implements:** [data.reused.co.2](metrics.md#metric-2-reused-data-pid)

### Description
Checks whether the `is_reused` dataset entry includes a persistent identifier (`dataset_id`) with both an identifier value and a type, confirming that the reused dataset can be unambiguously referenced.

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
  "@id": "https://example.org/test/T-DCSC-reused-dataset-pid",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check for reused dataset PID"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks whether the reused dataset entry includes a persistent identifier with both an identifier value and type, confirming the dataset can be unambiguously referenced."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "reused dataset"
    },
    {
      "@language": "en",
      "@value": "persistent identifier"
    },
    {
      "@language": "en",
      "@value": "PID"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-reused-dataset-pid/run"
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

## Test 4: Check Distribution Entry is Present

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-distribution-present

**Implements:** [data.reused.co.4](metrics.md#metric-4-reused-data-source)

### Description
Checks whether at least one distribution entry exists for the dataset, confirming that information about how and where the data is accessible has been provided in the maDMP.

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
    "@value": "Check Distribution Entry is Present"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks whether at least one distribution entry exists for the dataset, confirming that information about how and where the data is accessible has been provided."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "reused dataset"
    },
    {
      "@language": "en",
      "@value": "data distribution"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    },
    {
      "@language": "en",
      "@value": "completeness"
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

## Test 5: Check Distribution Access Information is Present

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-distribution-access

**Implements:** [data.reused.co.4](metrics.md#metric-4-reused-data-source)

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
    "@value": "Check Distribution Access Information is Present"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks whether distribution includes access information (e.g., access URL or download URL)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "reused dataset"
    },
    {
      "@language": "en",
      "@value": "data access"
    },
    {
      "@language": "en",
      "@value": "distribution"
    },
    {
      "@language": "en",
      "@value": "maDMP"
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

## Test 6: Check Distribution Title is Present

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-distribution-title

**Implements:** [data.reused.co.4](metrics.md#metric-4-reused-data-source)

### Description
Checks whether the distribution entry includes a non-empty title, confirming that the distribution is named and can be identified by users browsing the dataset record.

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
    "@value": "Check Distribution Title is Present"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks whether the distribution entry includes a non-empty title, confirming that the distribution is named and identifiable."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "reused dataset"
    },
    {
      "@language": "en",
      "@value": "distribution title"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    },
    {
      "@language": "en",
      "@value": "completeness"
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

## Test 7: Check Access Rights for Reused Datasets

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-access

**Implements:** [data.reused.co.5](metrics.md#metric-5-reused-data-access)

### Description
Checks whether the data access field (`data_access`) for the reused dataset is declared with a recognised value — open, shared, or closed — confirming that access conditions are explicitly stated.

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
    "@value": "Check Access Rights for Reused Datasets"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks whether the data access field for the reused dataset is declared with a recognised value — open, shared, or closed."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "reused dataset"
    },
    {
      "@language": "en",
      "@value": "access rights"
    },
    {
      "@language": "en",
      "@value": "data access"
    },
    {
      "@language": "en",
      "@value": "maDMP"
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

## Test 8: Check Personal Data Flag for Reused Datasets

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-personal-data

**Implements:** [data.reused.co.6](metrics.md#metric-6-reused-data-personal)

### Description
Checks whether the `personal_data` field is present and populated for the reused dataset entry, confirming that the DMP addresses whether the data contains personal information subject to data protection regulations.

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
    "@value": "Check Personal Data Flag for Reused Datasets"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks whether the personal_data field is present and populated, confirming the DMP addresses whether the data contains personal information."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "personal data"
    },
    {
      "@language": "en",
      "@value": "data protection"
    },
    {
      "@language": "en",
      "@value": "reused dataset"
    },
    {
      "@language": "en",
      "@value": "maDMP"
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

## Test 9: Check Sensitive Data Flag for Reused Datasets

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-sensitive-data

**Implements:** [data.reused.co.7](metrics.md#metric-7-reused-data-sensitive)

### Description
Checks whether the `sensitive_data` field is present and populated for the reused dataset entry, confirming that the DMP addresses whether the data requires special handling or protection measures.

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
    "@value": "Check Sensitive Data Flag for Reused Datasets"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks whether the sensitive_data field is present and populated, confirming the DMP addresses whether the data requires special handling."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "sensitive data"
    },
    {
      "@language": "en",
      "@value": "data security"
    },
    {
      "@language": "en",
      "@value": "reused dataset"
    },
    {
      "@language": "en",
      "@value": "maDMP"
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

## Test 10: Check Distribution URL is Present

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-distribution-url-present

**Implements:** [data.reused.co.8](metrics.md#metric-8-reused-data-url)

### Description
Checks whether a distribution entry with an access URL is present for the reused dataset, confirming that users can locate and retrieve the data from a declared address.

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
    "@value": "Check Distribution URL is Present"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks whether a distribution entry with an access URL is present for the reused dataset, confirming users can locate and retrieve the data."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "reused dataset"
    },
    {
      "@language": "en",
      "@value": "access URL"
    },
    {
      "@language": "en",
      "@value": "data location"
    },
    {
      "@language": "en",
      "@value": "maDMP"
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

## Test 11: Check Access URL is Present and Non-empty

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-access-url

**Implements:** [data.reused.co.8](metrics.md#metric-8-reused-data-url)

### Description
Checks whether the `access_url` field within the distribution entry is present and non-empty, confirming that a direct link to the data is provided in the maDMP.

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
    "@value": "Check Access URL is Present and Non-empty"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks whether the access_url field within the distribution entry is present and non-empty, confirming a direct link to the data is provided."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "access URL"
    },
    {
      "@language": "en",
      "@value": "data location"
    },
    {
      "@language": "en",
      "@value": "distribution"
    },
    {
      "@language": "en",
      "@value": "maDMP"
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

## Test 12: Check PID Matches Destination Repository Record

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-repo-match

**Implements:** [data.reused.feas.1](metrics.md#metric-9-repository-reused-data-pid)

### Description
Checks whether the persistent identifier declared for the reused dataset in the maDMP matches the corresponding record found in the destination repository, confirming consistency between the plan and the repository.

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
    "@value": "Check PID Matches Destination Repository Record"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if reused dataset id in DMP matches the destination."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "persistent identifier"
    },
    {
      "@language": "en",
      "@value": "PID"
    },
    {
      "@language": "en",
      "@value": "repository"
    },
    {
      "@language": "en",
      "@value": "feasibility"
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

## Test 13: Check PID Resolves Successfully

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-pid-resolves

**Implements:** [data.reused.feas.1](metrics.md#metric-9-repository-reused-data-pid)

### Description
Checks whether the persistent identifier declared in the maDMP resolves to an accessible online resource, confirming that the PID is active, valid, and leads to the correct dataset.

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
    "@value": "Check PID Resolves Successfully"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks whether the persistent identifier declared in the maDMP resolves to an accessible online resource, confirming the PID is active and valid."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "persistent identifier"
    },
    {
      "@language": "en",
      "@value": "PID resolution"
    },
    {
      "@language": "en",
      "@value": "DOI"
    },
    {
      "@language": "en",
      "@value": "maDMP"
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

## Test 14: Check Reused Data Access Matches Destination

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-access-match

**Implements:** [data.reused.feas.2](metrics.md#metric-10-repository-reused-data-access)

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
    "@value": "Check Reused Data Access Matches Destination"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Check if reused data access in DMP matches the destination."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "reused dataset"
    },
    {
      "@language": "en",
      "@value": "data access"
    },
    {
      "@language": "en",
      "@value": "repository"
    },
    {
      "@language": "en",
      "@value": "feasibility"
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

## Test 15: Check Reused Data License Matches Destination

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-license-match

**Implements:** [data.reused.feas.3](metrics.md#metric-11-repository-reused-data-license)

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
    "@value": "Check Reused Data License Matches Destination"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the license of the repository is the one mentioned in the DMP."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "reused dataset"
    },
    {
      "@language": "en",
      "@value": "data license"
    },
    {
      "@language": "en",
      "@value": "repository"
    },
    {
      "@language": "en",
      "@value": "feasibility"
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

## Test 16: Check for new data (no is_reused)

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-new-data

**Implements:** [data.new.1](metrics.md#metric-12-new-dataset-declared-in-the-dmp)

### Description
Checks whether the maDMP includes at least one dataset entry that does not carry an `is_reused` flag, confirming that newly produced or collected data is declared as part of the research project.

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
    "@value": "Checks whether the maDMP includes at least one dataset entry without an is_reused flag, confirming newly produced data is declared."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "new dataset"
    },
    {
      "@language": "en",
      "@value": "data production"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    },
    {
      "@language": "en",
      "@value": "completeness"
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

## Test 17: Check technical_resource for new data collection/creation

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-new-data-technical-resource

**Implements:** [data.new.2](metrics.md#metric-13-new-data-collection-or-creation)

### Description
Checks whether the `technical_resource` entries for new datasets include description, name, and identifier fields, confirming that the tools and methods used for data collection or creation are documented.

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
    "@value": "Checks whether the technical_resource entries for new datasets include description, name, and identifier fields documenting the data collection tools and methods."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "new dataset"
    },
    {
      "@language": "en",
      "@value": "technical resource"
    },
    {
      "@language": "en",
      "@value": "data collection"
    },
    {
      "@language": "en",
      "@value": "maDMP"
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

## Test 18: Check data_access for new datasets

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-new-data-access

**Implements:** [data.new.3](metrics.md#metric-14-new-data-access)

### Description
Checks whether the `data_access` field for new datasets is declared with a recognised value — open, shared, or closed — confirming that access conditions for newly produced data are explicitly stated.

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
    "@value": "Checks whether the data_access field for new datasets is declared with a recognised value — open, shared, or closed."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "new dataset"
    },
    {
      "@language": "en",
      "@value": "data access"
    },
    {
      "@language": "en",
      "@value": "access rights"
    },
    {
      "@language": "en",
      "@value": "maDMP"
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

## Test 19: Check rights of new dataset

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-new-data-rights

**Implements:** [data.new.3](metrics.md#metric-14-new-data-access)

### Description
Checks whether the `rights` field is present and non-empty for new datasets, confirming that the legal terms or conditions governing access to the newly produced data are documented.

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
    "@value": "Checks whether the rights field is present and non-empty for new datasets, confirming legal terms governing access are documented."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "new dataset"
    },
    {
      "@language": "en",
      "@value": "data rights"
    },
    {
      "@language": "en",
      "@value": "license"
    },
    {
      "@language": "en",
      "@value": "maDMP"
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

## Test 20: Check metadata for new dataset

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-new-data-metadata

**Implements:** [data.new.4](metrics.md#metric-15-new-data-metadata)

### Description
Checks whether new dataset entries include metadata fields such as description, language, and metadata standard identifier, confirming that sufficient information is provided for users to understand and reuse the data.

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
    "@value": "Checks whether new dataset entries include metadata fields such as description, language, and metadata standard identifier."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "new dataset"
    },
    {
      "@language": "en",
      "@value": "metadata"
    },
    {
      "@language": "en",
      "@value": "reproducibility"
    },
    {
      "@language": "en",
      "@value": "maDMP"
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

## Test 21: Check dataset_id exists

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-dataset-id-exists

**Implements:** [data.new.feas.1](metrics.md#metric-16-repository-pid-resolution)

### Description
Checks whether a `dataset_id` field with a non-empty identifier is present for the new dataset, confirming that the data has been assigned a reference that can be used to locate and cite it.

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
    "@value": "Checks whether a dataset_id field with a non-empty identifier is present, confirming the new dataset has been assigned a referenceable identifier."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "new dataset"
    },
    {
      "@language": "en",
      "@value": "dataset identifier"
    },
    {
      "@language": "en",
      "@value": "PID"
    },
    {
      "@language": "en",
      "@value": "maDMP"
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

## Test 22: Check PID resolves for dataset_id

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-dataset-id-resolves

**Implements:** [data.new.feas.1](metrics.md#metric-16-repository-pid-resolution)

### Description
Checks whether the persistent identifier declared in the `dataset_id` field resolves successfully to an accessible online resource, confirming that the identifier is active and leads to the correct dataset record.

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
    "@value": "Checks whether the persistent identifier in the dataset_id field resolves successfully to an accessible online resource."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "persistent identifier"
    },
    {
      "@language": "en",
      "@value": "PID resolution"
    },
    {
      "@language": "en",
      "@value": "dataset identifier"
    },
    {
      "@language": "en",
      "@value": "maDMP"
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

## Test 23: Check new data access matches destination

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-new-data-access-match-destination

**Implements:** [data.new.feas.2](metrics.md#metric-17-repository-new-data-access)

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
      "@value": "new dataset"
    },
    {
      "@language": "en",
      "@value": "data access"
    },
    {
      "@language": "en",
      "@value": "repository"
    },
    {
      "@language": "en",
      "@value": "feasibility"
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

## Test 24: Check new data license matches destination

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-new-data-license-match-destination

**Implements:** [data.new.feas.3](metrics.md#metric-18-repository-new-data-license)

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
      "@value": "new dataset"
    },
    {
      "@language": "en",
      "@value": "data license"
    },
    {
      "@language": "en",
      "@value": "repository"
    },
    {
      "@language": "en",
      "@value": "feasibility"
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

## Test 25: Check dataset.type is specified

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-dataset-type

**Implements:** [data.info.cov.1](metrics.md#metric-19-dataset-type-specified)

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
      "@value": "dataset type"
    },
    {
      "@language": "en",
      "@value": "dataset classification"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    },
    {
      "@language": "en",
      "@value": "coverage"
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

## Test 26: Check distribution.format is specified

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-distribution-format

**Implements:** [data.info.cov.2](metrics.md#metric-20-dataset-file-format-specified)

### Description
Checks whether the `format` field within the dataset distribution entry is present and non-empty, confirming that the file format of the data has been declared so users know what tools are needed to open it.

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
    "@value": "Checks whether the format field within the dataset distribution entry is present and non-empty, confirming the file format has been declared."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "file format"
    },
    {
      "@language": "en",
      "@value": "distribution"
    },
    {
      "@language": "en",
      "@value": "interoperability"
    },
    {
      "@language": "en",
      "@value": "maDMP"
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

## Test 27: Check distribution.byte_size is specified

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-distribution-byte-size

**Implements:** [data.info.cov.3](metrics.md#metric-21-dataset-size-specified)

### Description
Checks whether the `byte_size` field within the dataset distribution entry is present and has a positive value, confirming that the size of the dataset has been declared to support storage planning.

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
    "@value": "Checks whether the byte_size field within the distribution entry is present and has a positive value, confirming the dataset size has been declared."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "dataset size"
    },
    {
      "@language": "en",
      "@value": "storage planning"
    },
    {
      "@language": "en",
      "@value": "distribution"
    },
    {
      "@language": "en",
      "@value": "maDMP"
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

## Test 28: Check dataset.type matches destination type

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-dataset-type-match-destination-type

**Implements:** [data.info.feas.1](metrics.md#metric-22-repository-data-type)

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
      "@value": "dataset type"
    },
    {
      "@language": "en",
      "@value": "repository"
    },
    {
      "@language": "en",
      "@value": "type consistency"
    },
    {
      "@language": "en",
      "@value": "feasibility"
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

## Test 29: Check dataset.type aligns with destination subtype

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-dataset-type-align-destination-subtype

**Implements:** [data.info.feas.1](metrics.md#metric-22-repository-data-type)

### Description
Checks whether the dataset type declared in the maDMP aligns with the sub-type or resource type classification used by the destination repository, confirming consistency in how the data is categorised.

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
    "@value": "Checks whether the dataset type declared in the maDMP aligns with the sub-type or resource type classification used by the destination repository."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "dataset type"
    },
    {
      "@language": "en",
      "@value": "repository"
    },
    {
      "@language": "en",
      "@value": "subtype"
    },
    {
      "@language": "en",
      "@value": "feasibility"
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

## Test 30: Check final dataset format matches destination files

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-dataset-format-match-destination-files

**Implements:** [data.info.feas.2](metrics.md#metric-23-repository-data-format)

### Description
Checks whether the file format declared in the maDMP for the dataset distribution matches the actual file format of the data deposited in the destination repository, confirming that the plan reflects reality.

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
    "@value": "Checks whether final dataset format matches destination files as required by the maDMP specification."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "file format"
    },
    {
      "@language": "en",
      "@value": "repository"
    },
    {
      "@language": "en",
      "@value": "format consistency"
    },
    {
      "@language": "en",
      "@value": "feasibility"
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

## Test 31: Check final dataset size matches destination size

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-dataset-size-match-destination-size

**Implements:** [data.info.feas.3](metrics.md#metric-24-repository-data-size)

### Description
Checks whether the dataset size declared in the maDMP matches the actual size of the data deposited in the destination repository, confirming that the stated and actual storage requirements are consistent.

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
    "@value": "Checks whether final dataset size matches destination size as required by the maDMP specification."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "dataset size"
    },
    {
      "@language": "en",
      "@value": "repository"
    },
    {
      "@language": "en",
      "@value": "size consistency"
    },
    {
      "@language": "en",
      "@value": "feasibility"
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

## Test 32: Check maDMP JSON Validates Against DMP Common Standard Schema

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-dmp-cs-schema-validation

**Implements:** [meta.comp.1](metrics.md#metric-25-dmp-common-standard-field-compliance)

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
    "@value": "Check maDMP JSON Validates Against DMP Common Standard Schema"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the JSON matches with DMP Common Standard schema."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "DMP Common Standard"
    },
    {
      "@language": "en",
      "@value": "schema validation"
    },
    {
      "@language": "en",
      "@value": "JSON"
    },
    {
      "@language": "en",
      "@value": "compliance"
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

## Test 33: Check dataset_methodology for controlled vocabularies

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-dataset-methodology-controlled-vocabularies

**Implements:** [meta.co.1](metrics.md#metric-26-controlled-vocabularies-used-in-methodology)

### Description
Checks whether the methodology description in the maDMP references terms from a recognised controlled vocabulary, confirming that the research methods are described in a standardised and interoperable way.

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
    "@value": "Checks whether dataset_methodology for controlled vocabularies as required by the maDMP specification."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "controlled vocabulary"
    },
    {
      "@language": "en",
      "@value": "methodology"
    },
    {
      "@language": "en",
      "@value": "interoperability"
    },
    {
      "@language": "en",
      "@value": "maDMP"
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

## Test 34: Check technical_resource.name for electronic lab notebook reference

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-technical-resource-eln-reference

**Implements:** [meta.co.2](metrics.md#metric-27-electronic-lab-notebook-referenced-as-a-technical-resource)

### Description
Checks whether the `technical_resource.name` field in the maDMP includes a reference to an electronic lab notebook, confirming that the use of this documentation tool has been declared in the plan.

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
      "@value": "electronic lab notebook"
    },
    {
      "@language": "en",
      "@value": "ELN"
    },
    {
      "@language": "en",
      "@value": "technical resource"
    },
    {
      "@language": "en",
      "@value": "maDMP"
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

## Test 35: Check related_identifier resource_type for ReadMe file

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-related-identifier-readme-file

**Implements:** [meta.qual.2](metrics.md#metric-28-readme-file-reference)

### Description
Checks if a ReadMe file is included in the related_identifier resource_type.

### Input
json madmp

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate `related_identifier` entries in scope.
3. Extract the `resource_type` (or equivalent field) for each related identifier.
4. Check whether any `resource_type` value indicates a ReadMe file (for example `ReadMe`, `README`, or a project-defined equivalent).
5. Return **pass** if at least one related identifier references a ReadMe file; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-related-identifier-readme-file",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check related_identifier resource_type for ReadMe file"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if a ReadMe file is included in the related_identifier resource_type."
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
    "@id": "https://example.org/test/T-DCSC-related-identifier-readme-file/run"
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
    "@id": "https://example.org/metric/meta.qual.2"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

## Test 36: Check metadata_standard_id is registered in metadata registries

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-metadata-standard-registered

**Implements:** [meta.stand.comp.1](metrics.md#metric-29-metadata-standards-used)

### Description
Checks metadata_standard_id to be registered in RDA Directory and FAIRsharing.

### Input
metadata in maDMP + metadata registries (https://rdamsc.bath.ac.uk/)

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate metadata standard identifiers in scope (e.g., `metadata_standard_id` or equivalent schema field).
3. Extract the metadata standard identifiers or names.
4. Check whether each extracted metadata standard can be matched against recognized metadata registries such as the RDA Metadata Standards Catalog and FAIRsharing.
5. If your project uses identifier normalization, normalize names, URIs, or registry identifiers before comparison.
6. Return **pass** if all metadata standards in scope are found in the registries; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-metadata-standard-registered",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check metadata_standard_id is registered in metadata registries"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks metadata_standard_id to be registered in RDA Directory and FAIRsharing."
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
    "@id": "https://example.org/test/T-DCSC-metadata-standard-registered/run"
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
    "@id": "https://example.org/metric/meta.stand.comp.1"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```

## Test 37: Check distribution format is open

**Test ID:** T-DCSC  
**Persistent URI:** https://example.org/test/T-DCSC-distribution-format-open

**Implements:** [meta.form.op.1](metrics.md#metric-30-use-of-open-file-formats-for-datasets)

### Description
Checks distribution_format to be open.

### Input
madmp

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset distributions in scope and extract the declared format field (e.g., `distribution_format` or the equivalent schema field such as `distribution.format`).
3. Normalize the extracted format values if needed (e.g., extension, MIME type, or controlled term).
4. Compare each format against the list, registry, or rule set your project uses to classify formats as open.
5. Return **pass** if all formats in scope are classified as open; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-distribution-format-open",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check distribution format is open"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks distribution_format to be open."
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
    "@id": "https://example.org/test/T-DCSC-distribution-format-open/run"
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
    "@id": "https://example.org/metric/meta.form.op.1"
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

## Test 38: Check ELN dataset linked via related_ids

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-eln-dataset-linked-related-ids

**Implements:** [meta.doc.qual.1](metrics.md#metric-31-electronic-lab-notebook-linked)

### Description
Checks that the electronic lab notebook dataset or `technical_resource.name` includes `related_ids` with the dataset.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `technical_resource` objects.
3. For each `technical_resource`, check whether `technical_resource.name` identifies an electronic lab notebook.
4. If an ELN technical resource is found, verify that `related_ids` (or equivalent related identifier field) is present and contains at least one entry linking back to the dataset.
5. Additionally, check the dataset's `related_identifier` entries for any reference that identifies an ELN record.
6. Return **pass** if at least one dataset has a confirmed ELN linkage via `related_ids` or `related_identifier`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-eln-dataset-linked-related-ids",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check ELN dataset linked via related_ids"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks that the electronic lab notebook dataset or technical_resource.name includes related_ids with the dataset."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "electronic lab notebook"
    },
    {
      "@language": "en",
      "@value": "related identifier"
    },
    {
      "@language": "en",
      "@value": "dataset linkage"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-eln-dataset-linked-related-ids/run"
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
    "@id": "https://example.org/metric/meta.doc.qual.1"
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

## Test 39: Check technical_resource for dataset documentation

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-technical-resource-dataset-documentation

**Implements:** [meta.feas.1](metrics.md#metric-32-existence-of-dataset-documentation)

### Description
Checks if there is the presence of any documentation supporting the dataset.

### Input
`technical_resource.name`; `technical_resource.technical_resource_id` in maDMP

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `technical_resource` objects or arrays.
3. For each `technical_resource` entry, check whether `technical_resource.name` exists and is non-empty.
4. Additionally check whether `technical_resource.technical_resource_id` exists and is non-empty.
5. Return **pass** if at least one dataset contains a `technical_resource` entry with a non-empty `name` or `technical_resource_id`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-technical-resource-dataset-documentation",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check technical_resource for dataset documentation"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if there is the presence of any documentation supporting the dataset."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "dataset documentation"
    },
    {
      "@language": "en",
      "@value": "technical resource"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    },
    {
      "@language": "en",
      "@value": "feasibility"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-technical-resource-dataset-documentation/run"
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
    "@id": "https://example.org/metric/meta.feas.1"
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

## Test 40: Check data_quality_assurance for quality control methods

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-data-quality-assurance

**Implements:** [qc.qual.1](metrics.md#metric-33-quality-control-methods-stated)

### Description
Checks if quality control methods are mentioned, either as narrative or controlled terms (`data_quality_assurance`).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries in scope.
3. For each dataset, check whether the `data_quality_assurance` field exists.
4. Verify that the field is non-empty — either containing a free-text narrative description or one or more controlled terms.
5. Return **pass** if at least one dataset contains a non-empty `data_quality_assurance` value; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-data-quality-assurance",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check data_quality_assurance for quality control methods"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if quality control methods are mentioned, either as narrative or controlled terms (data_quality_assurance)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "quality control"
    },
    {
      "@language": "en",
      "@value": "data quality assurance"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    },
    {
      "@language": "en",
      "@value": "quality"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-data-quality-assurance/run"
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
    "@id": "https://example.org/metric/qc.qual.1"
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

## Test 41: Check host.title and host.url for storage location

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-host-storage-location

**Implements:** [store.cov.1](metrics.md#metric-34-data-storage-location-mentioned-in-the-dmp)

### Description
Checks if there is a reference of storage (`host.title`; `host.url`).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, check whether a `host` object is present.
4. Verify that `host.title` exists and is non-empty, or that `host.url` exists and is non-empty.
5. Return **pass** if at least one distribution contains a `host` entry with a non-empty `title` or `url`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-host-storage-location",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check host.title and host.url for storage location"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if there is a reference of storage (host.title; host.url)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "data storage"
    },
    {
      "@language": "en",
      "@value": "storage location"
    },
    {
      "@language": "en",
      "@value": "host"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-host-storage-location/run"
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
    "@id": "https://example.org/metric/store.cov.1"
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

## Test 42: Check host for trusted repository storage

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-host-trusted-repository

**Implements:** [store.cov.2](metrics.md#metric-35-use-of-secure-storage-for-the-dataset-in-a-trusted-repository)

### Description
Checks if the data are stored in trusted repositories (`host`).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, check whether a `host` object is present.
4. Inspect `host` properties (e.g., `host.title`, `host.url`, `host.certified_with`, `host.pid_system`) to determine whether the declared host can be identified as a trusted or institutional repository.
5. Apply your project's rule set for classifying a host as trusted (e.g., presence of a certification, match against a known repository list, or absence of indicators of personal storage).
6. Return **pass** if at least one distribution declares a host that qualifies as a trusted repository; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-host-trusted-repository",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check host for trusted repository storage"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the data are stored in trusted repositories (host)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "trusted repository"
    },
    {
      "@language": "en",
      "@value": "secure storage"
    },
    {
      "@language": "en",
      "@value": "host"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-host-trusted-repository/run"
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
    "@id": "https://example.org/metric/store.cov.2"
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

## Test 43: Check sensitive_data classification is assigned

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-sensitive-data-classification

**Implements:** [store.comp.1](metrics.md#metric-36-alignment-of-storage-and-backup-with-information-sensitivity)

### Description
Checks if the dataset has an assigned classification level (`sensitive_data`).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries in scope.
3. For each dataset, check whether the `sensitive_data` field is present.
4. Verify that the value is explicit and valid (e.g., a boolean or controlled term allowed by your schema).
5. Return **pass** if at least one dataset contains an explicitly set `sensitive_data` value; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-sensitive-data-classification",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check sensitive_data classification is assigned"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the dataset has an assigned classification level (sensitive_data)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "sensitive data"
    },
    {
      "@language": "en",
      "@value": "data classification"
    },
    {
      "@language": "en",
      "@value": "compliance"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-sensitive-data-classification/run"
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
    "@id": "https://example.org/metric/store.comp.1"
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

## Test 44: Check host security and backup reflect sensitivity level

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-host-security-backup-sensitivity

**Implements:** [store.comp.1](metrics.md#metric-36-alignment-of-storage-and-backup-with-information-sensitivity)

### Description
Checks if the host/storage method reflects appropriate protection level (`security_and_privacy`; `backup_type`).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, check whether a `host` object is present.
4. Verify that `host.security_and_privacy` exists and is non-empty.
5. Verify that `host.backup_type` exists and is non-empty.
6. Cross-reference the declared `sensitive_data` value for the dataset with the `security_and_privacy` and `backup_type` values, applying your project's mapping rules for appropriate protection levels.
7. Return **pass** if at least one distribution declares storage and backup properties consistent with the dataset's sensitivity classification; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-host-security-backup-sensitivity",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check host security and backup reflect sensitivity level"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the host/storage method reflects appropriate protection level (security_and_privacy; backup_type)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "storage security"
    },
    {
      "@language": "en",
      "@value": "backup"
    },
    {
      "@language": "en",
      "@value": "sensitive data"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-host-security-backup-sensitivity/run"
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
    "@id": "https://example.org/metric/store.comp.1"
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

## Test 45: Check contributor.role for backup responsibility

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-contributor-role-backup

**Implements:** [store.cov.3](metrics.md#metric-37-back-up-responsibility)

### Description
Checks if someone is responsible for back up activities (`contributor.role`).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate `contributor` entries in scope (at DMP level or dataset level, depending on your schema).
3. For each contributor, extract the `role` field value.
4. Check whether any `role` value indicates backup responsibility according to your project's controlled vocabulary or role list (e.g., a backup manager, data steward, or equivalent term).
5. Return **pass** if at least one contributor has a role associated with backup responsibility; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-contributor-role-backup",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check contributor.role for backup responsibility"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if someone is responsible for back up activities (contributor.role)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "backup responsibility"
    },
    {
      "@language": "en",
      "@value": "contributor role"
    },
    {
      "@language": "en",
      "@value": "data stewardship"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-contributor-role-backup/run"
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
    "@id": "https://example.org/metric/store.cov.3"
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

## Test 46: Check backup_frequency is declared

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-backup-frequency

**Implements:** [store.co.1](metrics.md#metric-38-back-up-frequency)

### Description
Checks whether the `backup_frequency` field in the maDMP is present and non-empty, confirming that the plan specifies how often data backups will be performed to protect against loss.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, check whether a `host` object is present.
4. Verify that `host.backup_frequency` exists and is non-empty.
5. Return **pass** if at least one distribution declares a non-empty `backup_frequency`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-backup-frequency",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check backup_frequency is declared"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the back up performance is frequent (backup_frequency)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "backup frequency"
    },
    {
      "@language": "en",
      "@value": "backup schedule"
    },
    {
      "@language": "en",
      "@value": "data storage"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-backup-frequency/run"
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
    "@id": "https://example.org/metric/store.co.1"
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

## Test 47: Check host.id matches Zenodo deposit location

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-host-id-matches-zenodo

**Implements:** [stor.feas.1](metrics.md#metric-40-stored-dataset-location-confirmed)

### Description
Checks if the storage of the data matches the destination.

### Input
`host.id` in maDMP + id in Zenodo

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, extract the `host.id` value.
4. Query the target repository (e.g., Zenodo API) using the dataset identifier to retrieve the actual deposit record.
5. Compare the `host.id` from the maDMP with the repository identifier returned by the external query.
6. Return **pass** if the `host.id` resolves and matches the confirmed deposit location in the target repository; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-host-id-matches-zenodo",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check host.id matches Zenodo deposit location"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the storage of the data matches the destination."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "storage location"
    },
    {
      "@language": "en",
      "@value": "deposit confirmation"
    },
    {
      "@language": "en",
      "@value": "Zenodo"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-host-id-matches-zenodo/run"
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
    "@id": "https://example.org/metric/stor.feas.1"
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

## Test 48: Check security_and_privacy.title for security measures

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-security-and-privacy-title

**Implements:** [secur.co.1](metrics.md#metric-41-security-measures-implementation)

### Description
Checks whether the `security_and_privacy.title` field is present and non-empty in the maDMP, confirming that at least one security measure has been named and associated with the dataset.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, check whether a `host` object containing a `security_and_privacy` array or object is present.
4. For each `security_and_privacy` entry, verify that `title` exists and is non-empty.
5. Return **pass** if at least one distribution contains a `security_and_privacy` entry with a non-empty `title`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-security-and-privacy-title",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check security_and_privacy.title for security measures"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks whether security_and_privacy.title for security measures as required by the maDMP specification."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "security measures"
    },
    {
      "@language": "en",
      "@value": "data security"
    },
    {
      "@language": "en",
      "@value": "security and privacy"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-security-and-privacy-title/run"
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
    "@id": "https://example.org/metric/secur.co.1"
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

## Test 49: Check security_and_privacy.description for access rights management

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-security-and-privacy-description

**Implements:** [secur.co.2](metrics.md#metric-42-sensitive-data-protection-description)

### Description
Checks if the sensitive data includes a description for access rights management (`security_and_privacy.description`).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and identify those where `sensitive_data` is set to true or an equivalent positive value.
3. For each sensitive dataset, locate the associated `distribution` objects and their `host` entries.
4. Check whether a `security_and_privacy` object or array is present within the host.
5. For each `security_and_privacy` entry, verify that `description` exists, is non-empty, and contains a reference to access rights management (e.g., institutional storage, access controls, or authorization mechanisms).
6. Return **pass** if at least one sensitive dataset has a qualifying `security_and_privacy.description`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-security-and-privacy-description",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check security_and_privacy.description for access rights management"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the sensitive data includes a description for access rights management (security_and_privacy.description)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "sensitive data"
    },
    {
      "@language": "en",
      "@value": "access rights management"
    },
    {
      "@language": "en",
      "@value": "data protection"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-security-and-privacy-description/run"
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
    "@id": "https://example.org/metric/secur.co.2"
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

## Test 50: Check security_and_privacy.description for authorised access controls

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-security-and-privacy-authorised-access

**Implements:** [secur.co.3](metrics.md#metric-43-authorised-access-control)

### Description
Checks if access control measures exist for authorised users (`security_and_privacy.description`).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, check whether a `host` object containing a `security_and_privacy` array or object is present.
4. For each `security_and_privacy` entry, verify that `description` exists and is non-empty.
5. Check whether the `description` value contains a reference to access control measures for authorised users (e.g., role-based access, authentication, user authorisation procedures, or equivalent terms defined by your project's vocabulary).
6. Return **pass** if at least one qualifying `security_and_privacy.description` is found; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-security-and-privacy-authorised-access",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check security_and_privacy.description for authorised access controls"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if access control measures exist for authorised users (security_and_privacy.description)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "access control"
    },
    {
      "@language": "en",
      "@value": "authorised users"
    },
    {
      "@language": "en",
      "@value": "data security"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-security-and-privacy-authorised-access/run"
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
    "@id": "https://example.org/metric/secur.co.3"
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

## Test 51: Check security_and_privacy.description for access control and user permissions

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-security-and-privacy-user-management

**Implements:** [secur.co.4](metrics.md#metric-44-access-control-and-user-management)

### Description
Checks how access to the data is controlled and if user roles or permissions are defined (`security_and_privacy.description`).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and identify those where sensitive data is present.
3. For each such dataset, locate the associated `distribution` objects and their `host` entries.
4. Check whether a `security_and_privacy` object or array is present within each host.
5. For each `security_and_privacy` entry, verify that `description` exists and is non-empty.
6. Check whether the `description` references both access control mechanisms and user roles or permissions (e.g., role-based access control, permission levels, user group definitions, or equivalent terms defined by your project's vocabulary).
7. Return **pass** if at least one qualifying `security_and_privacy.description` is found; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-security-and-privacy-user-management",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check security_and_privacy.description for access control and user permissions"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks how access to the data is controlled and if user roles or permissions are defined (security_and_privacy.description)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "access control"
    },
    {
      "@language": "en",
      "@value": "user management"
    },
    {
      "@language": "en",
      "@value": "user permissions"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-security-and-privacy-user-management/run"
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
    "@id": "https://example.org/metric/secur.co.4"
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

## Test 52: Check security_and_privacy.description for access procedures

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-security-and-privacy-access-procedures

**Implements:** [secur.co.5](metrics.md#metric-45-required-access-procedures)

### Description
Checks if access procedures for restricted/sensitive data are described in the DMP (`security_and_privacy.description`).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, check whether a `host` object containing a `security_and_privacy` array or object is present.
4. For each `security_and_privacy` entry, verify that `description` exists and is non-empty.
5. Check whether the `description` contains a reference to access procedures for restricted or sensitive data (e.g., a data access request process, approval workflow, designated contact point for access, or equivalent procedural terms defined by your project's vocabulary).
6. Return **pass** if at least one qualifying `security_and_privacy.description` is found; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-security-and-privacy-access-procedures",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check security_and_privacy.description for access procedures"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if access procedures for restricted/sensitive data are described in the DMP (security_and_privacy.description)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "access procedures"
    },
    {
      "@language": "en",
      "@value": "restricted data"
    },
    {
      "@language": "en",
      "@value": "data access request"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-security-and-privacy-access-procedures/run"
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
    "@id": "https://example.org/metric/secur.co.5"
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

## Test 53: Check security_and_privacy.description and ethical_issues_report for GDPR and ethics compliance

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-gdpr-ethics-compliance

**Implements:** [secur.comp.1](metrics.md#metric-46-gdpr-and-ethics-compliance)

### Description
Checks if GDPR and ethical review is mentioned in the DMP `security_and_privacy.description` of the maDMP, validated against the GDPR checklist at https://gdpr.eu/checklist/, and whether `ethical_issues_report` is present.

### Input
`security_and_privacy.description` in maDMP JSON; `ethical_issues_report` in maDMP JSON; GDPR checklist at https://gdpr.eu/checklist/

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, check whether a `host` object containing a `security_and_privacy` array or object is present.
4. For each `security_and_privacy` entry, verify that `description` exists and is non-empty, and check whether it contains a reference to GDPR or applicable data protection legislation (cross-validated against the GDPR checklist at https://gdpr.eu/checklist/).
5. Independently, check whether the maDMP includes an `ethical_issues_report` field that is present and non-empty.
6. Return **pass** if at least one of the following conditions is met: a qualifying `security_and_privacy.description` referencing GDPR is found, or a non-empty `ethical_issues_report` is present; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-gdpr-ethics-compliance",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check security_and_privacy.description and ethical_issues_report for GDPR and ethics compliance"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if GDPR and ethical review is mentioned in the DMP security_and_privacy.description of the maDMP, validated against the GDPR checklist, and whether ethical_issues_report is present."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "GDPR"
    },
    {
      "@language": "en",
      "@value": "ethics compliance"
    },
    {
      "@language": "en",
      "@value": "ethical review"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-gdpr-ethics-compliance/run"
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
    "@id": "https://example.org/metric/secur.comp.1"
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

## Test 54: Check security_and_privacy.title for implemented security measures at destination

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-security-and-privacy-title-destination

**Implements:** [secur.feas.1](metrics.md#metric-47-final-security-measures-implementation)

### Description
Checks if security measures are implemented in the destination (`security_and_privacy.title` in maDMP).

### Input
`security_and_privacy.title` in maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, check whether a `host` object containing a `security_and_privacy` array or object is present.
4. For each `security_and_privacy` entry, verify that `title` exists and is non-empty.
5. Return **pass** if at least one distribution contains a `security_and_privacy` entry with a non-empty `title`, confirming that a security measure is implemented at the destination; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-security-and-privacy-title-destination",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check security_and_privacy.title for implemented security measures at destination"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if security measures are implemented in the destination (security_and_privacy.title in maDMP)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "security measures"
    },
    {
      "@language": "en",
      "@value": "destination repository"
    },
    {
      "@language": "en",
      "@value": "feasibility"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-security-and-privacy-title-destination/run"
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
    "@id": "https://example.org/metric/secur.feas.1"
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

## Test 55: Check security_and_privacy.description for data protection method when sensitive_data is true

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-sensitive-data-protection-method

**Implements:** [sens.secure.co.1](metrics.md#metric-48-sensitive-data-using-method)

### Description
Checks if a data protection method is mentioned when sensitive data exist.

### Input
maDMP JSON — if `sensitive_data` = yes, then check `security_and_privacy.description`

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and identify those where `sensitive_data` is set to true or an equivalent positive value.
3. If no dataset is flagged as sensitive, return **pass** (metric is not applicable).
4. For each sensitive dataset, locate the associated `distribution` objects and their `host` entries.
5. Check whether a `security_and_privacy` object or array is present within each host.
6. For each `security_and_privacy` entry, verify that `description` exists, is non-empty, and describes a method used to protect the sensitive data.
7. Return **pass** if at least one sensitive dataset has a qualifying `security_and_privacy.description`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-sensitive-data-protection-method",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check security_and_privacy.description for data protection method when sensitive_data is true"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if a data protection method is mentioned when sensitive data exist."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "sensitive data"
    },
    {
      "@language": "en",
      "@value": "data protection method"
    },
    {
      "@language": "en",
      "@value": "security and privacy"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-sensitive-data-protection-method/run"
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
    "@id": "https://example.org/metric/sens.secure.co.1"
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

## Test 56: Check security_and_privacy for anonymised synthetic data provision

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-anonymised-synthetic-data

**Implements:** [sens.secure.co.2](metrics.md#metric-49-provision-of-anonymised-synthetic-data)

### Description
Checks if anonymised synthetic data will be provided (`security_and_privacy` in maDMP).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, check whether a `host` object containing a `security_and_privacy` array or object is present.
4. For each `security_and_privacy` entry, inspect both `title` and `description` fields for references to anonymisation, pseudonymisation, synthetic data generation, or equivalent terms indicating the intent to provide an anonymised or synthetic version of the data.
5. Return **pass** if at least one qualifying `security_and_privacy` entry is found; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-anonymised-synthetic-data",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check security_and_privacy for anonymised synthetic data provision"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if anonymised synthetic data will be provided (security_and_privacy in maDMP)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "anonymisation"
    },
    {
      "@language": "en",
      "@value": "synthetic data"
    },
    {
      "@language": "en",
      "@value": "sensitive data"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-anonymised-synthetic-data/run"
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
    "@id": "https://example.org/metric/sens.secure.co.2"
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

## Test 57: Check rights for statement of no data restrictions

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-rights-no-restrictions

**Implements:** [data.restrict.co.3](metrics.md#metric-50-statement-of-no-data-restrictions)

### Description
Checks if there are any restrictions applied to the data (`rights` in maDMP).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, check whether a `rights` field (or equivalent access rights field) is present.
4. Inspect the `rights` value to determine whether it explicitly indicates that no restrictions apply (e.g., an open licence URI, a public domain declaration, or a value such as "open" or "unrestricted" as defined by your project's controlled vocabulary).
5. Return **pass** if at least one distribution contains a `rights` value that confirms the absence of restrictions; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-rights-no-restrictions",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check rights for statement of no data restrictions"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if there are any restrictions applied to the data (rights in maDMP)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "data restrictions"
    },
    {
      "@language": "en",
      "@value": "access rights"
    },
    {
      "@language": "en",
      "@value": "open access"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-rights-no-restrictions/run"
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
    "@id": "https://example.org/metric/data.restrict.co.3"
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

## Test 58: Check license_ref for dataset licence

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-license-ref

**Implements:** [data.lice.co.1](metrics.md#metric-51-dataset-license-declared)

### Description
Checks whether the `license_ref` field within the dataset distribution entry is present and non-empty, confirming that a license has been declared and users know the terms under which the data may be used.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, check whether a `license_ref` field is present.
4. Verify that the `license_ref` value is non-empty and resolves to a recognisable licence identifier or URI.
5. Return **pass** if at least one distribution contains a non-empty `license_ref`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-license-ref",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check license_ref for dataset licence"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the dataset has a licence (license_ref)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "dataset licence"
    },
    {
      "@language": "en",
      "@value": "license reference"
    },
    {
      "@language": "en",
      "@value": "open licence"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-license-ref/run"
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
    "@id": "https://example.org/metric/data.lice.co.1"
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

## Test 59: Check license_ref against SPDX for software datasets

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-license-ref-spdx-software

**Implements:** [soft.lice.comp.1](metrics.md#metric-52-software-dataset-license-declared)

### Description
Checks if the dataset type is software, then verifies that `license_ref` matches a recognised software licence from the SPDX licence list at https://spdx.org/licenses/.

### Input
maDMP JSON; SPDX licence list at https://spdx.org/licenses/

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and identify those where `type` is set to software or an equivalent value.
3. If no dataset is typed as software, return **pass** (metric is not applicable).
4. For each software dataset, locate the associated `distribution` objects and check whether a `license_ref` field is present and non-empty.
5. Retrieve the current SPDX licence list from https://spdx.org/licenses/ and check whether the declared `license_ref` value matches a recognised SPDX licence identifier or URI.
6. Return **pass** if at least one software dataset declares a `license_ref` that matches a recognised SPDX software licence; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-license-ref-spdx-software",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check license_ref against SPDX for software datasets"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the dataset type is software, then verifies that license_ref matches a recognised software licence from the SPDX licence list."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "software licence"
    },
    {
      "@language": "en",
      "@value": "SPDX"
    },
    {
      "@language": "en",
      "@value": "licence compliance"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-license-ref-spdx-software/run"
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
    "@id": "https://example.org/metric/soft.lice.comp.1"
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

## Test 60: Check data_access and rights for access agreements or MoUs

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-data-access-agreements

**Implements:** [data.agree.comp.2](metrics.md#metric-53-data-access-agreements)

### Description
Checks the `data_access` and `rights` fields in the maDMP for references to collaborative agreements or MoUs.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries in scope.
3. For each dataset, check whether a `data_access` field is present and inspect its value for references to a formal data access agreement or MoU.
4. Additionally, locate associated `distribution` objects and check whether `rights` entries reference a formal agreement or MoU (e.g., a named agreement, a URI pointing to an agreement document, or explicit mention of collaborative access terms).
5. Return **pass** if at least one dataset contains a qualifying reference to a data access agreement or MoU in either `data_access` or `rights`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-data-access-agreements",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check data_access and rights for access agreements or MoUs"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the data_access and rights fields in the maDMP for references to collaborative agreements or MoUs."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "data access agreement"
    },
    {
      "@language": "en",
      "@value": "MoU"
    },
    {
      "@language": "en",
      "@value": "access rights"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-data-access-agreements/run"
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
    "@id": "https://example.org/metric/data.agree.comp.2"
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

## Test 61: Check contributor.role for data owner

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-contributor-role-owner

**Implements:** [own.co.2](metrics.md#metric-54-data-ownership-role-declared)

### Description
Checks that the `contributor.role` field is not blank and contains the value `owner`.

### Input
`contributor.role` = owner in maDMP

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate `contributor` entries in scope (at DMP level or dataset level, depending on your schema).
3. For each contributor, extract the `role` field value.
4. Check whether any `role` value is equal to `owner` or an equivalent ownership term as defined by your project's controlled vocabulary.
5. For any contributor with `role` = `owner`, verify that the associated identifying fields (e.g., `name`, `contributor_id`) are present and non-empty.
6. Return **pass** if at least one contributor has a non-blank `role` of `owner` with identifying information present; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-contributor-role-owner",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check contributor.role for data owner"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks that the contributor.role field is not blank and contains the value owner."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "data ownership"
    },
    {
      "@language": "en",
      "@value": "contributor role"
    },
    {
      "@language": "en",
      "@value": "data stewardship"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-contributor-role-owner/run"
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
    "@id": "https://example.org/metric/own.co.2"
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

## Test 62: Check contributor for author role when dataset type is software

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-contributor-author-software

**Implements:** [soft.auth.co.3](metrics.md#metric-55-software-dataset-author-declared)

### Description
Checks if the dataset type is software, then verifies that at least one contributor is present as author.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and identify those where `type` is set to software or an equivalent value.
3. If no dataset is typed as software, return **pass** (metric is not applicable).
4. For each software dataset, locate associated `contributor` entries (at dataset level or DMP level, depending on your schema).
5. Check whether at least one contributor has a `role` value indicating authorship (e.g., `author`, `creator`, or equivalent term defined by your project's controlled vocabulary).
6. Return **pass** if at least one software dataset has a contributor with an authorship role; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-contributor-author-software",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check contributor for author role when dataset type is software"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the dataset type is software, then verifies that at least one contributor is present as author."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "software authorship"
    },
    {
      "@language": "en",
      "@value": "contributor role"
    },
    {
      "@language": "en",
      "@value": "software dataset"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-contributor-author-software/run"
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
    "@id": "https://example.org/metric/soft.auth.co.3"
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

## Test 63: Check ethical_issues_exist for valid value

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-ethical-issues-exist

**Implements:** [ethics.co.1](metrics.md#metric-56-ethical-issues-status-declared)

### Description
Checks the `ethical_issues_exist` field for a valid value (`yes`, `no`, `unknown`).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate the `ethical_issues_exist` field at the DMP level.
3. Check whether the field is present and non-empty.
4. Verify that the value is one of the accepted controlled values: `yes`, `no`, or `unknown`.
5. Return **pass** if `ethical_issues_exist` is present and contains a valid value; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-ethical-issues-exist",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check ethical_issues_exist for valid value"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the ethical_issues_exist field for a valid value (yes, no, unknown)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "ethical issues"
    },
    {
      "@language": "en",
      "@value": "ethics declaration"
    },
    {
      "@language": "en",
      "@value": "research ethics"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-ethical-issues-exist/run"
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
    "@id": "https://example.org/metric/ethics.co.1"
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

## Test 64: Check ethical_issues_description is present when ethical_issues_exist is no

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-ethical-issues-description-no

**Implements:** [ethics.co.3](metrics.md#metric-58-justification-for-absence-of-ethical-issues)

### Description
Checks if a justification is provided when `ethical_issues_exist` = `no`, by verifying the presence of `ethical_issues_description`.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate the `ethical_issues_exist` field at the DMP level.
3. If `ethical_issues_exist` is not set to `no`, return **pass** (metric is not applicable).
4. If `ethical_issues_exist` is set to `no`, check whether the `ethical_issues_description` field is present and non-empty.
5. Return **pass** if `ethical_issues_description` is present and non-empty; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-ethical-issues-description-no",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check ethical_issues_description is present when ethical_issues_exist is no"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if a justification is provided when ethical_issues_exist = no, by verifying the presence of ethical_issues_description."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "ethical issues"
    },
    {
      "@language": "en",
      "@value": "ethics justification"
    },
    {
      "@language": "en",
      "@value": "ethics description"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-ethical-issues-description-no/run"
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
    "@id": "https://example.org/metric/ethics.co.3"
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

## Test 65: Check data_access for open status

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-data-access-open

**Implements:** [data.shar.op.1](metrics.md#metric-59-data-access-status-open-for-the-dataset)

### Description
Checks that `data_access` is set to `open` (accepted values: `open`, `shared`, `closed`).

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries in scope.
3. For each dataset, check whether a `data_access` field is present.
4. Verify that the `data_access` value is set to `open`.
5. Return **pass** if at least one dataset has `data_access` set to `open`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-data-access-open",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check data_access for open status"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks that data_access is set to open (accepted values: open, shared, closed)."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "open access"
    },
    {
      "@language": "en",
      "@value": "data access status"
    },
    {
      "@language": "en",
      "@value": "openness"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-data-access-open/run"
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
    "@id": "https://example.org/metric/data.shar.op.1"
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

## Test 66: Check distribution is present for dataset

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-distribution-present

**Implements:** [data.shar.co.1](metrics.md#metric-60-data-license-is-present)

### Description
Checks that a `distribution` entry is present for the dataset.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries in scope.
3. For each dataset, check whether a `distribution` array or object is present and non-empty.
4. Return **pass** if at least one dataset contains a non-empty `distribution` entry; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-distribution-present",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check distribution is present for dataset"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks that a distribution entry is present for the dataset."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "data licence"
    },
    {
      "@language": "en",
      "@value": "distribution"
    },
    {
      "@language": "en",
      "@value": "license reference"
    },
    {
      "@language": "en",
      "@value": "maDMP"
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
    "@id": "https://example.org/metric/data.shar.co.1"
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

## Test 67: Check license_ref is present within distribution

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-distribution-license-ref

**Implements:** [data.shar.co.1](metrics.md#metric-60-data-license-is-present)

### Description
Checks that a `license_ref` is present within the distribution entry.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, check whether a `license_ref` field is present and non-empty.
4. Return **pass** if at least one distribution contains a non-empty `license_ref`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-distribution-license-ref",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check license_ref is present within distribution"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks that a license_ref is present within the distribution entry."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "data licence"
    },
    {
      "@language": "en",
      "@value": "distribution"
    },
    {
      "@language": "en",
      "@value": "license reference"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-distribution-license-ref/run"
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
    "@id": "https://example.org/metric/data.shar.co.1"
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

## Test 68: Check rights for data restrictions reference

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-rights-restrictions-reference

**Implements:** [data.shar.co.2](metrics.md#metric-61-data-restrictions-reference)

### Description
Checks if any data restrictions are referenced via the `rights` field in the maDMP.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, check whether a `rights` field is present and non-empty.
4. Return **pass** if at least one distribution contains a non-empty `rights` value referencing data restrictions or access rights; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-rights-restrictions-reference",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check rights for data restrictions reference"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if any data restrictions are referenced via the rights field in the maDMP."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "data restrictions"
    },
    {
      "@language": "en",
      "@value": "access rights"
    },
    {
      "@language": "en",
      "@value": "distribution"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-rights-restrictions-reference/run"
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
    "@id": "https://example.org/metric/data.shar.co.2"
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

## Test 69: Check distribution license_ref for Horizon Europe CC-BY compliance

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-distribution-license-cc-by

**Implements:** [data.shar.comp.1](metrics.md#metric-62-funders-data-license)

### Description
Checks if the maDMP `dataset.distribution.license_ref` matches Horizon Europe RDM requirements, i.e. CC-BY.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, check whether a `license_ref` field is present and non-empty.
4. Verify that the `license_ref` value corresponds to a CC-BY licence URI or identifier (e.g., https://creativecommons.org/licenses/by/4.0/, or an equivalent CC-BY variant) as required by Horizon Europe RDM guidelines.
5. Return **pass** if at least one distribution contains a `license_ref` matching a CC-BY licence; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-distribution-license-cc-by",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check distribution license_ref for Horizon Europe CC-BY compliance"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the maDMP dataset.distribution.license_ref matches Horizon Europe RDM requirements, i.e. CC-BY."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "funder licence"
    },
    {
      "@language": "en",
      "@value": "Horizon Europe"
    },
    {
      "@language": "en",
      "@value": "CC-BY"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-distribution-license-cc-by/run"
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
    "@id": "https://example.org/metric/data.shar.comp.1"
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

## Test 70: Check data_access matches destination host access policy

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-data-access-host-consistency

**Implements:** [data.shar.feas.1](metrics.md#metric-63-repository-access-rights-consistency-aligned)

### Description
Checks if the dataset `data_access` value matches the access rights supported by the destination host in the maDMP.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and extract the `data_access` value for each.
3. For each dataset, locate the associated `distribution` objects and their `host` entries.
4. Extract any access-related fields from the `host` entry (e.g., `url`, `pid_system`, or access policy metadata) that indicate the access conditions supported by the destination repository.
5. Compare the dataset-level `data_access` value against the access policy of the destination host, checking for consistency (e.g., a dataset declared as `open` should be hosted at a repository that supports open access).
6. Return **pass** if at least one dataset has a `data_access` value that is consistent with its destination host access policy; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-data-access-host-consistency",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check data_access matches destination host access policy"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the dataset data_access value matches the access rights supported by the destination host in the maDMP."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "access rights"
    },
    {
      "@language": "en",
      "@value": "repository consistency"
    },
    {
      "@language": "en",
      "@value": "feasibility"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-data-access-host-consistency/run"
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
    "@id": "https://example.org/metric/data.shar.feas.1"
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

## Test 71: Check distribution license_ref matches destination host licence policy

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-distribution-license-host-alignment

**Implements:** [data.shar.feas.2](metrics.md#metric-64-repository-data-license-aligned-with-the-dmp)

### Description
Checks if the data licence matches the destination by verifying `distribution.license.license_ref` against the destination host's licence policy in the maDMP.

### Input
`distribution.license.license_ref` in maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, extract the `license_ref` value from the `license` object.
4. Identify the destination host for the same distribution and extract any licence-related metadata from the `host` entry (e.g., supported licence types, host URL, or policy references).
5. Compare the `license_ref` value against the licence policy of the destination host, checking for consistency.
6. Return **pass** if at least one distribution has a `license_ref` that is consistent with its destination host licence policy; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-distribution-license-host-alignment",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check distribution license_ref matches destination host licence policy"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the data licence matches the destination by verifying distribution.license.license_ref against the destination host licence policy in the maDMP."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "data licence"
    },
    {
      "@language": "en",
      "@value": "repository alignment"
    },
    {
      "@language": "en",
      "@value": "feasibility"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-distribution-license-host-alignment/run"
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
    "@id": "https://example.org/metric/data.shar.feas.2"
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

## Test 72: Check distribution license.start_date matches destination embargo policy

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-distribution-license-start-date-embargo

**Implements:** [data.shar.feas.3](metrics.md#metric-65-embargo-implementation-alignment)

### Description
Checks if the embargo date matches the destination by verifying `distribution.license.start_date` against the destination host's embargo policy in the maDMP.

### Input
`distribution.license.start_date` in maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, extract the `start_date` value from the `license` object.
4. Identify the destination host for the same distribution and extract any embargo-related metadata from the `host` entry (e.g., supported embargo periods, availability windows, or policy references).
5. Compare the `start_date` value against the embargo policy of the destination host, checking that the declared embargo period is supported by the repository.
6. Return **pass** if at least one distribution has a `license.start_date` that is consistent with its destination host embargo policy; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-distribution-license-start-date-embargo",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check distribution license.start_date matches destination embargo policy"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the embargo date matches the destination by verifying distribution.license.start_date against the destination host embargo policy in the maDMP."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "embargo"
    },
    {
      "@language": "en",
      "@value": "availability date"
    },
    {
      "@language": "en",
      "@value": "repository alignment"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-distribution-license-start-date-embargo/run"
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
    "@id": "https://example.org/metric/data.shar.feas.3"
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

## Test 73: Check rights matches destination host restriction policy

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-rights-destination-restriction-alignment

**Implements:** [data.shar.feas.4](metrics.md#metric-66-repository-data-restrictions)

### Description
Checks if the data restrictions match the destination by verifying the `rights` field against the destination host's restriction policy in the maDMP.

### Input
`rights` in maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, extract the `rights` field value.
4. Identify the destination host for the same distribution and extract any restriction-related metadata from the `host` entry (e.g., supported access conditions, restriction policies, or host URL for policy lookup).
5. Compare the `rights` value against the restriction policy of the destination host, checking that the declared restrictions are consistent with what the repository supports.
6. Return **pass** if at least one distribution has a `rights` value that is consistent with its destination host restriction policy; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-rights-destination-restriction-alignment",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check rights matches destination host restriction policy"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the data restrictions match the destination by verifying the rights field against the destination host restriction policy in the maDMP."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "data restrictions"
    },
    {
      "@language": "en",
      "@value": "access rights"
    },
    {
      "@language": "en",
      "@value": "repository alignment"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-rights-destination-restriction-alignment/run"
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
    "@id": "https://example.org/metric/data.shar.feas.4"
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

## Test 74: Check repository host for absence of embargo date

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-host-embargo-date-absent

**Implements:** [data.shar.comp.2](metrics.md#metric-67-embargo-period-license-declared)

### Description
Checks that no embargo date field exists in the destination repository host entry, in compliance with Horizon Europe embargo policy.

### Input
Repository host entry in maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, locate the `host` entry.
4. Check whether any embargo date field is present within the `host` entry.
5. Return **pass** if no embargo date field is found in any destination host entry; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-host-embargo-date-absent",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check repository host for absence of embargo date"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks that no embargo date field exists in the destination repository host entry, in compliance with Horizon Europe embargo policy."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "embargo"
    },
    {
      "@language": "en",
      "@value": "Horizon Europe"
    },
    {
      "@language": "en",
      "@value": "licence compliance"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-host-embargo-date-absent/run"
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
    "@id": "https://example.org/metric/data.shar.comp.2"
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

## Test 75: Check distribution.license.start_date for absence in maDMP

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-distribution-license-start-date-absent

**Implements:** [data.shar.comp.2](metrics.md#metric-67-embargo-period-license-declared)

### Description
Checks that `distribution.license.start_date` is not set in the maDMP, in compliance with Horizon Europe embargo policy.

### Input
`distribution.license.start_date` in maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, check whether a `license` object is present containing a `start_date` field.
4. Return **pass** if no `distribution.license.start_date` field is present or set across all distributions; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-distribution-license-start-date-absent",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check distribution.license.start_date for absence in maDMP"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks that distribution.license.start_date is not set in the maDMP, in compliance with Horizon Europe embargo policy."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "embargo"
    },
    {
      "@language": "en",
      "@value": "Horizon Europe"
    },
    {
      "@language": "en",
      "@value": "licence compliance"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-distribution-license-start-date-absent/run"
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
    "@id": "https://example.org/metric/data.shar.comp.2"
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

## Test 76: Check host.title and host.url against thematic repository registries

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-host-thematic-registry-match

**Implements:** [repo.co.3](metrics.md#metric-68-thematic-data-repositories-referenced)

### Description
Checks if the repository `host.title` or `host.url` matches a thematic repository in the OpenAIRE Graph repositories API or another SKG API repository registry.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, extract the `host.title` and `host.url` values.
4. Query the OpenAIRE Graph repositories API (or an equivalent SKG API repository registry) using `host.title` or `host.url` as search parameters.
5. Check whether the returned results indicate that the referenced repository is classified as a thematic repository within the registry.
6. Return **pass** if at least one distribution's `host.title` or `host.url` matches a thematic repository entry in the registry; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-host-thematic-registry-match",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check host.title and host.url against thematic repository registries"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the repository host.title or host.url matches a thematic repository in the OpenAIRE Graph repositories API or another SKG API repository registry."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "thematic repository"
    },
    {
      "@language": "en",
      "@value": "OpenAIRE"
    },
    {
      "@language": "en",
      "@value": "repository registry"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-host-thematic-registry-match/run"
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
    "@id": "https://example.org/metric/repo.co.3"
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

## Test 77: Check host against OpenAIRE and FAIRsharing FAIR benchmarks

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-host-fair-benchmark

**Implements:** [repo.comp.2](metrics.md#metric-69-repository-fairness-conformation)

### Description
Checks if the repository declared in `host` is aligned with FAIR data principles by cross-referencing against benchmarks in OpenAIRE and FAIRsharing.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, extract the `host.title` and `host.url` values.
4. Query the OpenAIRE repository API using `host.title` or `host.url` to check whether the repository is listed and carries a FAIR-related assessment or endorsement.
5. Query the FAIRsharing registry using `host.title` or `host.url` to check whether the repository is listed and associated with FAIR data principles compliance.
6. Return **pass** if at least one distribution's host is found in either OpenAIRE or FAIRsharing with a FAIR benchmark or endorsement; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-host-fair-benchmark",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check host against OpenAIRE and FAIRsharing FAIR benchmarks"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the repository declared in host is aligned with FAIR data principles by cross-referencing against benchmarks in OpenAIRE and FAIRsharing."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "FAIR data principles"
    },
    {
      "@language": "en",
      "@value": "FAIRsharing"
    },
    {
      "@language": "en",
      "@value": "OpenAIRE"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-host-fair-benchmark/run"
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
    "@id": "https://example.org/metric/repo.comp.2"
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

## Test 78: Check host against trusted repository registry benchmark

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-host-trusted-registry

**Implements:** [repo.comp.3](metrics.md#metric-70-trusted-repository-is-used)

### Description
Checks if the repository declared in `host` is included in a trusted repository registry benchmark.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, extract the `host.title` and `host.url` values.
4. Query a recognised trusted repository registry (e.g., CoreTrustSeal certified repositories list, CLARIN centres, DINI certified repositories, or an equivalent benchmark) using `host.title` or `host.url` as search parameters.
5. Check whether the repository is listed and holds a valid trusted repository certification or endorsement.
6. Return **pass** if at least one distribution's host is found in a recognised trusted repository registry; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-host-trusted-registry",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check host against trusted repository registry benchmark"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the repository declared in host is included in a trusted repository registry benchmark."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "trusted repository"
    },
    {
      "@language": "en",
      "@value": "CoreTrustSeal"
    },
    {
      "@language": "en",
      "@value": "repository certification"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-host-trusted-registry/run"
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
    "@id": "https://example.org/metric/repo.comp.3"
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

## Test 79: Check host.backup_frequency and host.backup_type for back-up strategy

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-host-backup-strategy

**Implements:** [repo.co.4](metrics.md#metric-71-verification-of-back-up-strategy)

### Description
Checks that a back-up strategy exists by verifying that `host.backup_frequency` and `host.backup_type` are present and non-empty in the maDMP.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, locate the `host` entry.
4. Check whether the `backup_frequency` field is present and non-empty within the `host` entry.
5. Check whether the `backup_type` field is present and non-empty within the same `host` entry.
6. Return **pass** if at least one host entry contains both a non-empty `backup_frequency` and a non-empty `backup_type`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-host-backup-strategy",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check host.backup_frequency and host.backup_type for back-up strategy"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks that a back-up strategy exists by verifying that host.backup_frequency and host.backup_type are present and non-empty in the maDMP."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "back-up strategy"
    },
    {
      "@language": "en",
      "@value": "backup frequency"
    },
    {
      "@language": "en",
      "@value": "repository"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-host-backup-strategy/run"
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
    "@id": "https://example.org/metric/repo.co.4"
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

## Test 80: Check certified_with exists in host

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-host-certified-with

**Implements:** [repo.co.5](metrics.md#metric-72-certification-of-repository)

### Description
Checks that a `certified_with` field exists and is non-empty within the `host` entry of the maDMP.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, locate the `host` entry.
4. Check whether a `certified_with` field is present and non-empty within the `host` entry.
5. Return **pass** if at least one host entry contains a non-empty `certified_with` value; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-host-certified-with",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check certified_with exists in host"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks that a certified_with field exists and is non-empty within the host entry of the maDMP."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "repository certification"
    },
    {
      "@language": "en",
      "@value": "certified_with"
    },
    {
      "@language": "en",
      "@value": "repository"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-host-certified-with/run"
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
    "@id": "https://example.org/metric/repo.co.5"
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

## Test 81: Check cost title or description for preservation reference

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-cost-preservation-reference

**Implements:** [repo.co.7](metrics.md#metric-73-used-resources-for-preservation)

### Description
Checks if a `cost` entry with `currency_code`, `description`, `title`, and `value` includes a reference to preservation in its `title` or `description`.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate `cost` entries at DMP level.
3. For each cost entry, check whether `currency_code` and `value` are present and non-empty.
4. Check whether the `title` or `description` field of the cost entry contains a term related to preservation (e.g., "preservation", "archiving", "long-term storage", or equivalent).
5. Return **pass** if at least one cost entry has non-empty `currency_code` and `value`, and a `title` or `description` referencing preservation; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-cost-preservation-reference",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check cost title or description for preservation reference"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if a cost entry with currency_code, description, title, and value includes a reference to preservation in its title or description."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "long-term preservation"
    },
    {
      "@language": "en",
      "@value": "cost"
    },
    {
      "@language": "en",
      "@value": "resources"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-cost-preservation-reference/run"
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
    "@id": "https://example.org/metric/repo.co.7"
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

## Test 82: Check host_id against FAIRsharing for repository policy

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-host-id-fairsharing-policy

**Implements:** [repo.co.6](metrics.md#metric-74-repository-policy-is-present)

### Description
Checks if the repository identified by `host_id.identifier` and `host_id.type` in the maDMP has associated policies in FAIRsharing.

### Input
maDMP JSON; FAIRsharing registry

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, extract the `host_id.identifier` and `host_id.type` values from the `host` entry.
4. Query the FAIRsharing registry using the extracted `host_id.identifier` and `host_id.type` to locate the corresponding repository record.
5. Check whether the FAIRsharing record for the repository contains one or more associated policy entries (e.g., via the `id_policy` field or equivalent policy linkage in the FAIRsharing API response).
6. Return **pass** if at least one distribution's host resolves to a FAIRsharing repository record with at least one associated policy; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-host-id-fairsharing-policy",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check host_id against FAIRsharing for repository policy"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the repository identified by host_id.identifier and host_id.type in the maDMP has associated policies in FAIRsharing."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "repository policy"
    },
    {
      "@language": "en",
      "@value": "FAIRsharing"
    },
    {
      "@language": "en",
      "@value": "host identifier"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-host-id-fairsharing-policy/run"
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
    "@id": "https://example.org/metric/repo.co.6"
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

## Test 83: Check dataset_id resolves to declared destination via DOI URL

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-dataset-id-doi-destination

**Implements:** [repo.feas.1](metrics.md#metric-75-repository-identifier-accuracy)

### Description
Checks if the reused dataset identifier in the maDMP matches the destination by resolving `dataset_id` against its DOI URL.

### Input
`dataset_id` in maDMP JSON; DOI URL resolution

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and extract the `dataset_id` field (identifier and type) for each.
3. For each dataset, check whether the `dataset_id` value is present, non-empty, and of type DOI or resolvable identifier.
4. Resolve the `dataset_id` via its DOI URL (e.g., via https://doi.org/) and retrieve the landing page or metadata record.
5. Compare the resolved repository or hosting institution against the destination declared in the associated `distribution.host` entry.
6. Return **pass** if at least one dataset's `dataset_id` resolves to the declared destination repository; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-dataset-id-doi-destination",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check dataset_id resolves to declared destination via DOI URL"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the reused dataset identifier in the maDMP matches the destination by resolving dataset_id against its DOI URL."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "dataset identifier"
    },
    {
      "@language": "en",
      "@value": "DOI"
    },
    {
      "@language": "en",
      "@value": "repository destination"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-dataset-id-doi-destination/run"
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
    "@id": "https://example.org/metric/repo.feas.1"
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

## Test 84: Check preservation_statement and host for long-term storage intention

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-preservation-statement-host

**Implements:** [repo.feas.2](metrics.md#metric-76-long-term-preservation-dataset)

### Description
Checks the dataset `preservation_statement` and `host` fields to verify that the dataset is intended to be archived in a long-term storage repository.

### Input
`preservation_statement` in maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, check whether a `preservation_statement` field is present and non-empty within the `host` entry.
4. Check whether the same distribution contains a `host` entry with at least a `title` or `url` identifying a destination repository.
5. Return **pass** if at least one distribution contains both a non-empty `preservation_statement` and a declared destination `host`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-preservation-statement-host",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check preservation_statement and host for long-term storage intention"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the dataset preservation_statement and host fields to verify that the dataset is intended to be archived in a long-term storage repository."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "long-term preservation"
    },
    {
      "@language": "en",
      "@value": "preservation statement"
    },
    {
      "@language": "en",
      "@value": "feasibility"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-preservation-statement-host/run"
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
    "@id": "https://example.org/metric/repo.feas.2"
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

## Test 85: Check dataset.keyword against Zenodo keywords

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-dataset-keyword-zenodo

**Implements:** [repo.feas.4](metrics.md#metric-77-repository-compatibility-with-dataset-characteristics)

### Description
Checks if the repository has the appropriate characteristics by verifying that `dataset.keyword` values in the maDMP match keywords supported or indexed in Zenodo.

### Input
`dataset.keyword` in maDMP JSON; Zenodo keyword index

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and extract the `keyword` field values for each.
3. If no `keyword` values are present, return **fail**.
4. Query the Zenodo API using the extracted keyword values to check whether they are recognised or indexed within Zenodo's subject or keyword metadata.
5. Return **pass** if at least one dataset's `keyword` values match keywords supported or indexed in Zenodo; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-dataset-keyword-zenodo",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check dataset.keyword against Zenodo keywords"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the repository has the appropriate characteristics by verifying that dataset.keyword values in the maDMP match keywords supported or indexed in Zenodo."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "repository appropriateness"
    },
    {
      "@language": "en",
      "@value": "Zenodo"
    },
    {
      "@language": "en",
      "@value": "dataset keyword"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-dataset-keyword-zenodo/run"
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
    "@id": "https://example.org/metric/repo.feas.4"
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

## Test 86: Check dataset.language against Zenodo language support

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-dataset-language-zenodo

**Implements:** [repo.feas.4](metrics.md#metric-77-repository-compatibility-with-dataset-characteristics)

### Description
Checks if the repository has the appropriate characteristics by verifying that `dataset.language` in the maDMP matches a language supported by Zenodo.

### Input
`dataset.language` in maDMP JSON; Zenodo language support

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and extract the `language` field value for each.
3. If no `language` value is present, return **fail**.
4. Query the Zenodo API or consult Zenodo's supported language list to check whether the declared `language` value is recognised and supported by Zenodo.
5. Return **pass** if at least one dataset's `language` value matches a language supported by Zenodo; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-dataset-language-zenodo",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check dataset.language against Zenodo language support"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the repository has the appropriate characteristics by verifying that dataset.language in the maDMP matches a language supported by Zenodo."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "repository appropriateness"
    },
    {
      "@language": "en",
      "@value": "Zenodo"
    },
    {
      "@language": "en",
      "@value": "dataset language"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-dataset-language-zenodo/run"
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
    "@id": "https://example.org/metric/repo.feas.4"
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

## Test 87: Check host_id against Zenodo and FAIRsharing for policy compliance

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-host-id-zenodo-fairsharing-policy

**Implements:** [repo.comp.3](metrics.md#metric-70-trusted-repository-is-used)

### Description
Checks if the repository is aligned with policies and registry entries by cross-referencing `host_id.identifier` and `host_id.type` against repository records in Zenodo and FAIRsharing.

### Input
`host_id.identifier` and `host_id.type` in maDMP JSON; Zenodo repository records; FAIRsharing registry

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, extract the `host_id.identifier` and `host_id.type` values from the `host` entry.
4. Query the Zenodo API using the extracted identifier to check whether the repository is listed and has associated policy or compliance metadata.
5. Query the FAIRsharing registry using the extracted identifier to check whether the repository record contains associated policy entries or compliance information.
6. Return **pass** if at least one distribution's host resolves to a matching record in either Zenodo or FAIRsharing with associated policy compliance information; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-host-id-zenodo-fairsharing-policy",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check host_id against Zenodo and FAIRsharing for policy compliance"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the repository is aligned with policies and registry entries by cross-referencing host_id.identifier and host_id.type against repository records in Zenodo and FAIRsharing."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "repository policy compliance"
    },
    {
      "@language": "en",
      "@value": "FAIRsharing"
    },
    {
      "@language": "en",
      "@value": "Zenodo"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-host-id-zenodo-fairsharing-policy/run"
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
    "@id": "https://example.org/metric/repo.comp.3"
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

## Test 88: Check related_identifier.identifier for external resources

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-related-identifier-external-resources

**Implements:** [data.exteresource.co.1](metrics.md#metric-78-data-external-resources-included-in-the-dmp)

### Description
Checks if there are external resources declared in the DMP by verifying the presence of `related_identifier.identifier` entries.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and check for the presence of a `related_identifier` array or object.
3. For each `related_identifier` entry, check whether the `identifier` field is present and non-empty.
4. Return **pass** if at least one dataset contains a `related_identifier` entry with a non-empty `identifier` field; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-related-identifier-external-resources",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check related_identifier.identifier for external resources"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if there are external resources declared in the DMP by verifying the presence of related_identifier.identifier entries."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "external resources"
    },
    {
      "@language": "en",
      "@value": "related identifier"
    },
    {
      "@language": "en",
      "@value": "completeness"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-related-identifier-external-resources/run"
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
    "@id": "https://example.org/metric/data.exteresource.co.1"
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

## Test 89: Check related_identifier for metadata standard fields

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-related-identifier-metadata-standard

**Implements:** [data.exteresource.co.2](metrics.md#metric-79-metadata-standard-specified-in-the-dmp)

### Description
Checks if a metadata format or standard is listed in the DMP by verifying that `related_identifier.metadata_scheme`, `related_identifier.scheme_type`, and `related_identifier.scheme_uri` are present and non-empty.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and check for the presence of a `related_identifier` array or object.
3. For each `related_identifier` entry, check whether `metadata_scheme`, `scheme_type`, and `scheme_uri` fields are all present and non-empty.
4. Return **pass** if at least one dataset contains a `related_identifier` entry with non-empty values for all three fields; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-related-identifier-metadata-standard",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check related_identifier for metadata standard fields"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if a metadata format or standard is listed in the DMP by verifying that related_identifier.metadata_scheme, related_identifier.scheme_type, and related_identifier.scheme_uri are present and non-empty."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "metadata standard"
    },
    {
      "@language": "en",
      "@value": "metadata scheme"
    },
    {
      "@language": "en",
      "@value": "completeness"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-related-identifier-metadata-standard/run"
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
    "@id": "https://example.org/metric/data.exteresource.co.2"
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

## Test 90: Check URLs in maDMP are valid and resolvable

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-url-resolvable

**Implements:** [data.exteresource.feas.1](metrics.md#metric-80-resolvable-external-resources)

### Description
Checks if all included URLs in the maDMP are syntactically valid and resolve to accessible resources.

### Input
URLs in maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Extract all URL values present across the document (e.g., from `related_identifier.identifier`, `host.url`, `distribution.access_url`, and any other URL-bearing fields).
3. For each extracted URL, validate its syntax against standard URL format rules.
4. Attempt to resolve each syntactically valid URL via an HTTP request and check whether it returns a successful response (e.g., HTTP 200 or 3xx redirect to a valid resource).
5. Return **pass** if at least one URL is both syntactically valid and successfully resolvable; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-url-resolvable",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check URLs in maDMP are valid and resolvable"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if all included URLs in the maDMP are syntactically valid and resolve to accessible resources."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "resolvable URLs"
    },
    {
      "@language": "en",
      "@value": "external resources"
    },
    {
      "@language": "en",
      "@value": "feasibility"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-url-resolvable/run"
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
    "@id": "https://example.org/metric/data.exteresource.feas.1"
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

## Test 91: Check dataset fields against OpenAIRE SKG-IF API

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-dataset-openaire-skg-if

**Implements:** [data.exteresource.feas.2](metrics.md#metric-81-openaire-mentioned-dataset-validation)

### Description
Checks if datasets declared in the maDMP are found in the OpenAIRE SKG-IF API by querying with `dataset_id.identifier`, `dataset_id.type`, `dataset.title`, and `dataset.type`.

### Input
`dataset_id.identifier`, `dataset_id.type`, `dataset.title`, `dataset.type` in maDMP JSON; OpenAIRE SKG-IF API

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and extract `dataset_id.identifier`, `dataset_id.type`, `dataset.title`, and `dataset.type` for each.
3. For each dataset, query the OpenAIRE SKG-IF API using the extracted identifier (preferring `dataset_id.identifier` and `dataset_id.type`) to search for a matching record.
4. If no match is found by identifier, retry the query using `dataset.title` and `dataset.type` as search parameters.
5. Check whether the API response contains a record that corresponds to the declared dataset.
6. Return **pass** if at least one dataset produces a matching record in the OpenAIRE SKG-IF API; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-dataset-openaire-skg-if",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check dataset fields against OpenAIRE SKG-IF API"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if datasets declared in the maDMP are found in the OpenAIRE SKG-IF API by querying with dataset_id.identifier, dataset_id.type, dataset.title, and dataset.type."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "OpenAIRE"
    },
    {
      "@language": "en",
      "@value": "SKG-IF"
    },
    {
      "@language": "en",
      "@value": "dataset validation"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-dataset-openaire-skg-if/run"
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
    "@id": "https://example.org/metric/data.exteresource.feas.2"
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

## Test 92: Check contributor roles against CRediT taxonomy

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-contributor-credit-taxonomy

**Implements:** [data.exteresource.feas.3](metrics.md#metric-82-contributor-roles-follow-credit-taxonomy)

### Description
Checks if the dataset uses the CRediT taxonomy by verifying that `contributor` role values in the maDMP match recognised CRediT taxonomy terms.

### Input
`contributor` in maDMP JSON; CRediT taxonomy

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate `contributor` entries at DMP or dataset level and extract the `role` value for each.
3. If no `contributor` entries or `role` values are present, return **fail**.
4. Compare each extracted `role` value against the list of recognised CRediT taxonomy role terms (e.g., Conceptualization, Data Curation, Formal Analysis, Funding Acquisition, Investigation, Methodology, Project Administration, Resources, Software, Supervision, Validation, Visualization, Writing – Original Draft, Writing – Review & Editing).
5. Return **pass** if at least one contributor's `role` value matches a recognised CRediT taxonomy term; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-contributor-credit-taxonomy",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check contributor roles against CRediT taxonomy"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the dataset uses the CRediT taxonomy by verifying that contributor role values in the maDMP match recognised CRediT taxonomy terms."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "CRediT taxonomy"
    },
    {
      "@language": "en",
      "@value": "contributor roles"
    },
    {
      "@language": "en",
      "@value": "feasibility"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-contributor-credit-taxonomy/run"
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
    "@id": "https://example.org/metric/data.exteresource.feas.3"
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

## Test 93: Check host.pid_system for PID declaration

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-host-pid-system

**Implements:** [data.pid.cov.1](metrics.md#metric-83-dataset-persistent-identifier-declared)

### Description
Checks if the dataset has a PID by verifying that `host.pid_system` is present and non-empty in the maDMP.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, locate the `host` entry.
4. Check whether a `pid_system` field is present and non-empty within the `host` entry.
5. Return **pass** if at least one host entry contains a non-empty `pid_system` value; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-host-pid-system",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check host.pid_system for PID declaration"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the dataset has a PID by verifying that host.pid_system is present and non-empty in the maDMP."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "persistent identifier"
    },
    {
      "@language": "en",
      "@value": "PID"
    },
    {
      "@language": "en",
      "@value": "coverage"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-host-pid-system/run"
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
    "@id": "https://example.org/metric/data.pid.cov.1"
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

## Test 94: Check certified_with against trusted registry

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-certified-with-trusted-registry

**Implements:** [data.pid.cov.2](metrics.md#metric-84-trusted-repository-referenced)

### Description
Checks if the repository is listed in a trusted registry by verifying the `certified_with` field in the maDMP.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, locate the `host` entry and extract the `certified_with` field value.
4. Check whether the `certified_with` value is present, non-empty, and corresponds to a recognised trusted registry (e.g., CoreTrustSeal, CLARIN, DINI, or equivalent).
5. Return **pass** if at least one host entry contains a `certified_with` value matching a trusted registry; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-certified-with-trusted-registry",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check certified_with against trusted registry"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the repository is listed in a trusted registry by verifying the certified_with field in the maDMP."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "trusted repository"
    },
    {
      "@language": "en",
      "@value": "certification"
    },
    {
      "@language": "en",
      "@value": "coverage"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-certified-with-trusted-registry/run"
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
    "@id": "https://example.org/metric/data.pid.cov.2"
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

## Test 95: Check host_id.identifier and host_id.type for valid repository link

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-host-id-valid-link

**Implements:** [data.pid.cov.2](metrics.md#metric-84-trusted-repository-referenced)

### Description
Checks if a valid link to the repository is provided by verifying that `host_id.identifier` and `host_id.type` are present, non-empty, and resolvable in the maDMP.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, extract `host_id.identifier` and `host_id.type` from the `host` entry.
4. Check whether both `host_id.identifier` and `host_id.type` are present and non-empty.
5. Attempt to resolve the `host_id.identifier` value as a URL or persistent identifier to confirm it leads to a valid, accessible repository resource.
6. Return **pass** if at least one distribution's `host_id.identifier` and `host_id.type` are present and the identifier resolves successfully; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-host-id-valid-link",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check host_id.identifier and host_id.type for valid repository link"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if a valid link to the repository is provided by verifying that host_id.identifier and host_id.type are present, non-empty, and resolvable in the maDMP."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "repository link"
    },
    {
      "@language": "en",
      "@value": "host identifier"
    },
    {
      "@language": "en",
      "@value": "coverage"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-host-id-valid-link/run"
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
    "@id": "https://example.org/metric/data.pid.cov.2"
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

## Test 96: Check host.pid_system matches destination PID system in Zenodo

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-host-pid-system-zenodo

**Implements:** [data.pid.feas.1](metrics.md#metric-85-repository-persistent-identifier-system-verified)

### Description
Checks if the PID system declared in `host.pid_system` matches the PID system provided by the destination repository, cross-referenced against Zenodo DOI metadata.

### Input
`host.pid_system` in maDMP JSON; Zenodo DOI metadata

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate dataset entries and their associated `distribution` objects or arrays.
3. For each distribution, extract the `host.pid_system` value and the destination repository identifier from the `host` entry.
4. Query the Zenodo API using the destination repository identifier to retrieve the repository's supported PID system (e.g., DOI assignment via Zenodo).
5. Compare the `host.pid_system` value against the PID system confirmed as supported by the destination repository in Zenodo.
6. Return **pass** if at least one distribution's `host.pid_system` matches the PID system provided by its declared destination in Zenodo; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-host-pid-system-zenodo",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check host.pid_system matches destination PID system in Zenodo"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if the PID system declared in host.pid_system matches the PID system provided by the destination repository, cross-referenced against Zenodo DOI metadata."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "persistent identifier"
    },
    {
      "@language": "en",
      "@value": "Zenodo"
    },
    {
      "@language": "en",
      "@value": "feasibility"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-host-pid-system-zenodo/run"
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
    "@id": "https://example.org/metric/data.pid.feas.1"
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

## Test 97: Check dmp.contributor name, role, and contact

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-contributor-name-role-contact

**Implements:** [role.co.1](metrics.md#metric-87-research-data-management-roles-declared)

### Description
Checks that `dmp.contributor.name`, `dmp.contributor.role`, and `dmp.contributor.contact` are present and non-empty in the maDMP.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate `contributor` entries at DMP level.
3. For each contributor entry, check whether `name`, `role`, and `contact` fields are all present and non-empty.
4. Return **pass** if at least one contributor entry contains non-empty values for all three of `name`, `role`, and `contact`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-contributor-name-role-contact",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check dmp.contributor name, role, and contact"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks that dmp.contributor.name, dmp.contributor.role, and dmp.contributor.contact are present and non-empty in the maDMP."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "contributor roles"
    },
    {
      "@language": "en",
      "@value": "RDM roles"
    },
    {
      "@language": "en",
      "@value": "completeness"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-contributor-name-role-contact/run"
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
    "@id": "https://example.org/metric/role.co.1"
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

## Test 98: Check dmp.contributor.role for Data Steward

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-contributor-role-data-steward

**Implements:** [dmp.valid.co.2](metrics.md#metric-88-dmp-validation-by-data-steward)

### Description
Checks that at least one `dmp.contributor.role` value equals `Data Steward` in the maDMP.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate `contributor` entries at DMP level.
3. For each contributor entry, extract the `role` field value.
4. Check whether any `role` value matches `Data Steward` (case-insensitive).
5. Return **pass** if at least one contributor entry has a `role` value of `Data Steward`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-contributor-role-data-steward",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check dmp.contributor.role for Data Steward"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks that at least one dmp.contributor.role value equals Data Steward in the maDMP."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "Data Steward"
    },
    {
      "@language": "en",
      "@value": "DMP validation"
    },
    {
      "@language": "en",
      "@value": "completeness"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-contributor-role-data-steward/run"
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
    "@id": "https://example.org/metric/dmp.valid.co.2"
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

## Test 99: Check contributor_id and affiliation.affiliation_id for PIDs

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-contributor-id-affiliation-id

**Implements:** [role.pid.co.1](metrics.md#metric-89-contributors-and-organisations-pids)

### Description
Checks that `contributor.contributor_id` and `contributor.affiliation.affiliation_id` are present and non-empty in the maDMP.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate `contributor` entries at DMP level.
3. For each contributor entry, check whether `contributor_id` is present and non-empty.
4. For the same contributor entry, check whether `affiliation.affiliation_id` is present and non-empty within at least one affiliated organisation entry.
5. Return **pass** if at least one contributor entry contains both a non-empty `contributor_id` and a non-empty `affiliation.affiliation_id`; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-contributor-id-affiliation-id",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check contributor_id and affiliation.affiliation_id for PIDs"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks that contributor.contributor_id and contributor.affiliation.affiliation_id are present and non-empty in the maDMP."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "contributor PID"
    },
    {
      "@language": "en",
      "@value": "affiliation PID"
    },
    {
      "@language": "en",
      "@value": "completeness"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-contributor-id-affiliation-id/run"
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
    "@id": "https://example.org/metric/role.pid.co.1"
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

## Test 100: Check dmp.contributor fields against destination contributors

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-contributor-fields-destination

**Implements:** [role.feas.1](metrics.md#metric-90-referenced-rdm-roles)

### Description
Checks that the roles of the contributors declared in the maDMP are mentioned in the destination by cross-referencing `dmp.contributor.name`, `dmp.contributor.role`, and `dmp.contributor.contact` against `contributors.name` and `contributors.type` in the destination.

### Input
`dmp.contributor.name`, `dmp.contributor.role`, `dmp.contributor.contact` in maDMP JSON; `contributors.name`, `contributors.type` in destination metadata

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate `contributor` entries at DMP level and extract `name`, `role`, and `contact` for each.
3. If no contributor entries or required fields are present, return **fail**.
4. Retrieve contributor metadata from the destination, extracting `contributors.name` and `contributors.type` entries.
5. For each contributor declared in the maDMP, attempt to match `dmp.contributor.name` against `contributors.name` and `dmp.contributor.role` against `contributors.type` in the destination.
6. Return **pass** if at least one maDMP contributor can be matched by name and role type in the destination contributor metadata; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-contributor-fields-destination",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check dmp.contributor fields against destination contributors"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks that the roles of the contributors declared in the maDMP are mentioned in the destination by cross-referencing dmp.contributor.name, dmp.contributor.role, and dmp.contributor.contact against contributors.name and contributors.type in the destination."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "contributor roles"
    },
    {
      "@language": "en",
      "@value": "RDM roles"
    },
    {
      "@language": "en",
      "@value": "feasibility"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-contributor-fields-destination/run"
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
    "@id": "https://example.org/metric/role.feas.1"
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

## Test 101: Check Data Steward role in maDMP against contributors.type Other in destination

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-data-steward-role-destination-other

**Implements:** [role.feas.2](metrics.md#metric-91-final-data-steward-validation)

### Description
Checks that the contribution of a Data Steward is referenced in the destination by verifying that `dmp.contributor.role` equals `Data Steward` in the maDMP and a corresponding `contributors.type` of `Other` is present in the destination.

### Input
`dmp.contributor.role` in maDMP JSON; `contributors.type` in destination metadata

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate `contributor` entries at DMP level and extract the `role` field value for each.
3. Check whether at least one contributor entry has a `role` value of `Data Steward` (case-insensitive).
4. If no `Data Steward` role is found, return **fail**.
5. Retrieve contributor metadata from the destination and extract `contributors.type` values.
6. Check whether at least one `contributors.type` entry in the destination has a value of `Other`.
7. Return **pass** if both a `Data Steward` role is declared in the maDMP and a `contributors.type` of `Other` is present in the destination; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-data-steward-role-destination-other",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check Data Steward role in maDMP against contributors.type Other in destination"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks that the contribution of a Data Steward is referenced in the destination by verifying that dmp.contributor.role equals Data Steward in the maDMP and a corresponding contributors.type of Other is present in the destination."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "Data Steward"
    },
    {
      "@language": "en",
      "@value": "DMP validation"
    },
    {
      "@language": "en",
      "@value": "feasibility"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-data-steward-role-destination-other/run"
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
    "@id": "https://example.org/metric/role.feas.2"
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

## Test 102: Check contributor PIDs in maDMP against Zenodo contributors

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-contributor-pids-zenodo

**Implements:** [role.feas.3](metrics.md#metric-92-referenced-contributors-and-organisations-pids)

### Description
Checks if each contributor entry includes a valid PID in the destination by cross-referencing `contributor.affiliation.affiliation_id` and `contributor.contributor_id` in the maDMP against `contributors.affiliation` and `contributors.orcid` in Zenodo.

### Input
`contributor.affiliation.affiliation_id` and `contributor.contributor_id` in maDMP JSON; `contributors.affiliation` and `contributors.orcid` in Zenodo

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate `contributor` entries at DMP level and extract `contributor_id` and `affiliation.affiliation_id` for each.
3. If no contributor entries or required PID fields are present, return **fail**.
4. Query the Zenodo API for the relevant dataset record and retrieve `contributors.orcid` and `contributors.affiliation` values.
5. For each contributor declared in the maDMP, attempt to match `contributor.contributor_id` against `contributors.orcid` and `contributor.affiliation.affiliation_id` against `contributors.affiliation` in the Zenodo record.
6. Return **pass** if at least one contributor's PIDs are matched in the Zenodo destination record; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-contributor-pids-zenodo",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check contributor PIDs in maDMP against Zenodo contributors"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks if each contributor entry includes a valid PID in the destination by cross-referencing contributor.affiliation.affiliation_id and contributor.contributor_id in the maDMP against contributors.affiliation and contributors.orcid in Zenodo."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "contributor PID"
    },
    {
      "@language": "en",
      "@value": "affiliation PID"
    },
    {
      "@language": "en",
      "@value": "Zenodo"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-contributor-pids-zenodo/run"
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
    "@id": "https://example.org/metric/role.feas.3"
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

## Test 103: Check cost in maDMP against repository cost

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-cost-repository

**Implements:** [cost.comp.1](metrics.md#metric-93-repository-cost-verified-against-actual-pricing)

### Description
Checks the cost of the repository by verifying that the `cost` declared in the maDMP is consistent with the actual cost of the destination repository.

### Input
`cost` in maDMP JSON; repository cost information

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate `cost` entries at DMP level and extract `currency_code`, `value`, `title`, and `description` for each.
3. If no `cost` entries are present, return **fail**.
4. Identify the destination repository from the associated `distribution.host` entries.
5. Retrieve the actual cost information for the destination repository from the repository's pricing documentation or API.
6. Compare the declared `cost.value` and `cost.currency_code` in the maDMP against the actual repository cost.
7. Return **pass** if at least one declared cost entry is consistent with the actual cost of the destination repository; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-cost-repository",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check cost in maDMP against repository cost"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the cost of the repository by verifying that the cost declared in the maDMP is consistent with the actual cost of the destination repository."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "repository cost"
    },
    {
      "@language": "en",
      "@value": "cost"
    },
    {
      "@language": "en",
      "@value": "compliance"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-cost-repository/run"
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
    "@id": "https://example.org/metric/cost.comp.1"
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

## Test 104: Check cost fields for budget specification

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-cost-budget-specification

**Implements:** [cost.co.1](metrics.md#metric-94-dmp-budget-specifications)

### Description
Checks that the `cost` field in the maDMP is present and contains the required budget information for PMs and monetary resources.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate `cost` entries at DMP level.
3. For each cost entry, check whether `currency_code`, `value`, `title`, and `description` are all present and non-empty.
4. Return **pass** if at least one `cost` entry contains non-empty values for all required fields; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-cost-budget-specification",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check cost fields for budget specification"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks that the cost field in the maDMP is present and contains the required budget information for PMs and monetary resources."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "budget"
    },
    {
      "@language": "en",
      "@value": "cost"
    },
    {
      "@language": "en",
      "@value": "completeness"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-cost-budget-specification/run"
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
    "@id": "https://example.org/metric/cost.co.1"
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

## Test 105: Check cost in maDMP for no additional resources statement

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-cost-no-additional-resources

**Implements:** [cost.co.2](metrics.md#metric-95-no-extra-rdm-costs)

### Description
Checks the `cost` field in the maDMP to verify that it explicitly states that no additional resources are needed for data management activities.

### Input
maDMP JSON

### Output
pass/fail

### Procedure
1. Parse the maDMP JSON document.
2. Locate `cost` entries at DMP level.
3. If no `cost` entries are present, return **fail**.
4. For each cost entry, inspect the `title` and `description` fields for explicit statements indicating that no additional resources are required (e.g., phrases such as "no additional resources", "no extra costs", "within existing budget", or equivalent).
5. Return **pass** if at least one `cost` entry contains a `title` or `description` that explicitly states no additional resources are needed; otherwise return **fail**.

### JSON-LD (Test)
```json
{
  "@context": "https://w3id.org/ftr/context",
  "@id": "https://example.org/test/T-DCSC-cost-no-additional-resources",
  "@type": "ftr:Test",
  "dcterms:identifier": "T-DCSC",
  "dcterms:title": {
    "@language": "en",
    "@value": "Check cost in maDMP for no additional resources statement"
  },
  "dcterms:description": {
    "@language": "en",
    "@value": "Checks the cost field in the maDMP to verify that it explicitly states that no additional resources are needed for data management activities."
  },
  "dcat:keyword": [
    {
      "@language": "en",
      "@value": "no additional resources"
    },
    {
      "@language": "en",
      "@value": "RDM costs"
    },
    {
      "@language": "en",
      "@value": "completeness"
    },
    {
      "@language": "en",
      "@value": "maDMP"
    }
  ],
  "vivo:abbreviation": {
    "@value": "T-DCSC-T"
  },
  "dcat:endpointDescription": {
    "@id": "https://example.org/api"
  },
  "dcat:endpointURL": {
    "@id": "https://example.org/test/T-DCSC-cost-no-additional-resources/run"
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
    "@id": "https://example.org/metric/cost.co.2"
  },
  "ftr:supportedBy": {
    "@id": "https://example.org/project"
  },
  "dpv:isApplicableFor": {
    "@id": "https://schema.org/Dataset"
  }
}
```
