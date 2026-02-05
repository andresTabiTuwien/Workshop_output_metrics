# Tests Catalog

| Test Name | Jump to Test |
|----------|-------------|
| Check for reused dataset declaration | [Go](#test-check-for-reused-dataset-declaration) |
| Check for reused dataset PID | [Go](#test-check-for-reused-dataset-pid) |
| License for reused datasets | [Go](#test-license-for-reused-datasets) |
| Distribution present | [Go](#test-distribution-present) |
| Distribution access information | [Go](#test-distribution-access-information) |
| Distribution title | [Go](#test-distribution-title) |
| Access rights for reused datasets | [Go](#test-access-rights-for-reused-datasets) |
| Personal data for reused datasets | [Go](#test-personal-data-for-reused-datasets) |
| Sensitive data for reused datasets | [Go](#test-sensitive-data-for-reused-datasets) |
| Distribution present (URL) | [Go](#test-distribution-present-url) |
| Access URL | [Go](#test-access-url) |
| PID matches destination repository record | [Go](#test-pid-matches-destination-repository-record) |
| PID resolves | [Go](#test-pid-resolves) |
| Reused data access matches destination | [Go](#test-reused-data-access-matches-destination) |
| Reused data license matches destination | [Go](#test-reused-data-license-matches-destination) |


---

## Test: Check for reused dataset declaration

**Implements:** [data.reused.co.1](metrics.md#metric-madmp-declares-reused-datasets)  
**Input:** maDMP JSON  
**Output:** pass/fail  

### Procedure
1. Parse the maDMP JSON document.  
2. Locate dataset entries.  
3. Check whether at least one dataset contains the `is_reused` field.  
4. If present, return pass; otherwise return fail.

---

## Test: Check for reused dataset PID

**Implements:** [data.reused.co.2](metrics.md#metric-reused-data-pid)  
**Input:** maDMP JSON  
**Output:** pass/fail  

### Procedure
1. Parse the maDMP JSON document.  
2. Locate dataset entries.  
3. Select datasets where `is_reused = true`.  
4. Verify that `dataset_id.identifier` exists and is non-empty.  
5. Optionally verify that `dataset_id.type` exists.  
6. If all reused datasets comply, return pass; otherwise return fail.

---

## Test: License for reused datasets

**Implements:** [data.reused.co.3](metrics.md#metric-reused-data-license)  
**Input:** maDMP JSON  
**Output:** pass/fail  

### Procedure
1. Parse the maDMP JSON document.  
2. Locate dataset entries.  
3. Select datasets where `is_reused = true`.  
4. Verify that a `license` object exists.  
5. Verify that `license.ref` exists and is non-empty.  
6. Optionally verify that `license.start_date` exists.  
7. If all reused datasets comply, return pass; otherwise return fail.

---

## Test: Distribution present

**Implements:** [data.reused.co.4](metrics.md#metric-reused-data-source)  
**Input:** maDMP JSON  
**Output:** pass/fail  

### Procedure
1. Parse the maDMP JSON document.  
2. Locate dataset entries.  
3. Select datasets where `is_reused = true`.  
4. Verify that a `distribution` (or equivalent) object or array exists.  
5. If all reused datasets contain distribution metadata, return pass; otherwise return fail.

---

## Test: Distribution access information

**Implements:** [data.reused.co.4](metrics.md#metric-reused-data-source)  
**Input:** maDMP JSON  
**Output:** pass/fail  

### Procedure
1. Parse the maDMP JSON document.  
2. Locate reused datasets (`is_reused = true`).  
3. For each distribution, verify that at least one access field exists (e.g., `access_url`, `download_url`).  
4. If all reused datasets contain access information, return pass; otherwise return fail.

---

## Test: Distribution title

**Implements:** [data.reused.co.4](metrics.md#metric-reused-data-source)  
**Input:** maDMP JSON  
**Output:** pass/fail  

### Procedure
1. Parse the maDMP JSON document.  
2. Locate reused datasets (`is_reused = true`).  
3. For each distribution, verify that a non-empty `title` field exists.  
4. If all reused datasets contain a title, return pass; otherwise return fail.

---

## Test: Access rights for reused datasets

**Implements:** [data.reused.co.5](metrics.md#metric-reused-data-access)  
**Input:** maDMP JSON  
**Output:** pass/fail  

### Procedure
1. Parse the maDMP JSON document.  
2. Locate reused datasets (`is_reused = true`).  
3. Verify that `data_access` exists.  
4. Verify that its value is one of: `open`, `shared`, `closed`.  
5. If all reused datasets comply, return pass; otherwise return fail.

---

## Test: Personal data for reused datasets

**Implements:** [data.reused.co.6](metrics.md#metric-reused-data-personal)  
**Input:** maDMP JSON  
**Output:** pass/fail  

### Procedure
1. Parse the maDMP JSON document.  
2. Locate reused datasets (`is_reused = true`).  
3. Verify that `personal_data` exists.  
4. Verify that its value is explicit and valid.  
5. If all reused datasets comply, return pass; otherwise return fail.

---

## Test: Sensitive data for reused datasets

**Implements:** [data.reused.co.7](metrics.md#metric-reused-data-sensitive)  
**Input:** maDMP JSON  
**Output:** pass/fail  

### Procedure
1. Parse the maDMP JSON document.  
2. Locate reused datasets (`is_reused = true`).  
3. Verify that `sensitive_data` exists.  
4. Verify that its value is explicit and valid.  
5. If all reused datasets comply, return pass; otherwise return fail.

---

## Test: Distribution present (URL)

**Implements:** [data.reused.co.8](metrics.md#metric-reused-data-url)  
**Input:** maDMP JSON  
**Output:** pass/fail  

### Procedure
1. Parse the maDMP JSON document.  
2. Locate reused datasets (`is_reused = true`).  
3. Verify that at least one distribution object exists.  
4. If yes, return pass; otherwise return fail.

---

## Test: Access URL

**Implements:** [data.reused.co.8](metrics.md#metric-reused-data-url)  
**Input:** maDMP JSON  
**Output:** pass/fail  

### Procedure
1. Parse the maDMP JSON document.  
2. Locate reused datasets (`is_reused = true`).  
3. Verify that at least one distribution contains `access_url`.  
4. If yes, return pass; otherwise return fail.

---

## Test: PID matches destination repository record

**Implements:** [data.reused.feas.1](metrics.md#metric-repository-reused-data-pid)  
**Input:** dataset_id in maDMP + repository record  
**Output:** pass/fail  

### Procedure
1. Extract reused dataset identifiers from maDMP (`is_reused = true`).  
2. Query the target repository using the identifier.  
3. Retrieve the repository’s canonical identifier for the record.  
4. Compare with the maDMP dataset identifier.  
5. Pass if all identifiers match a repository record; otherwise fail.

---

## Test: PID resolves

**Implements:** [data.reused.feas.1](metrics.md#metric-repository-reused-data-pid)  
**Input:** dataset_id from maDMP  
**Output:** pass/fail  

### Procedure
1. Extract reused dataset identifiers from maDMP (`is_reused = true`).  
2. Attempt resolution via a PID resolver (HTTP request).  
3. Treat HTTP 2xx/3xx responses as resolvable.  
4. Pass if all PIDs resolve; otherwise fail.

---

## Test: Reused data access matches destination

**Implements:** [data.reused.feas.2](metrics.md#metric-repository-reused-data-access)  
**Input:** data_access in maDMP + access_right in repository  
**Output:** pass/fail  

### Procedure
1. Extract reused datasets from maDMP (`is_reused = true`).  
2. Retrieve destination repository record.  
3. Extract repository access rights value.  
4. Compare maDMP `data_access` with repository `access_right`.  
5. Pass if all values match; otherwise fail.

---

## Test: Reused data license matches destination

**Implements:** [data.reused.feas.3](metrics.md#metric-repository-reused-data-license)  
**Input:** license in maDMP + license in repository  
**Output:** pass/fail  

### Procedure
1. Extract reused datasets from maDMP (`is_reused = true`).  
2. Retrieve destination repository record.  
3. Extract license value from repository record.  
4. Compare with maDMP license value.  
5. Pass if all values match; otherwise fail.
