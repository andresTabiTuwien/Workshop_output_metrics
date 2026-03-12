# Contributing to the OSTRails DMP Evaluation Metrics Catalogue

Thank you for your interest in contributing to this catalogue. Contributions from researchers, data stewards, tool developers, and the broader research data management community are very welcome.

---

## What You Can Contribute

- **New metrics** — propose a new measurable criterion for evaluating maDMPs
- **New tests** — propose an automated test that implements an existing metric
- **Corrections** — fix errors in existing metric or test records
- **Narrative improvements** — improve the clarity or accuracy of descriptions
- **New topic coverage** — identify gaps in the catalogue and propose metrics to fill them

---

## Before You Start

Please check the existing catalogues first:

- [`metrics.md`](metrics.md) — to see whether a similar metric already exists
- [`tests.md`](tests.md) — to see whether a test for the metric already exists

If you are unsure whether your contribution is appropriate, open a GitHub Issue to discuss it before submitting a Pull Request.

---

## Metric Record Format

Each new metric must follow this structure:

```markdown
## Metric: <Title>

**Metric ID:** <domain>.<dimension-code>.<number>
**Persistent URI:** https://example.org/metric/<metric-id>
**Dimension:** <Completeness | Feasibility | Compliance | Coverage | Quality | Openness>

### Title
<Same as section heading>

### Narrative
<1–3 sentences explaining what is being assessed and why it matters, written for a non-technical audience.>

### Intended Outcome
<1–2 sentences explaining what a passing result confirms about the DMP.>

### Applies To
<The type of maDMP input this metric applies to.>

### Success Criterion
<Condition(s) under which the metric passes.>

### Failure Criterion
<Condition(s) under which the metric fails.>

### Associated Test(s)
- [<Test title>](tests.md#<test-anchor>)

### JSON-LD (Metric)
\`\`\`json
{ ... }
\`\`\`
```

### Metric ID convention

Metric IDs follow dot-notation: `<topic>.<dimension-code>.<number>`

| Dimension | Code |
|---|---|
| Completeness | `co` |
| Feasibility | `feas` |
| Compliance | `comp` |
| Coverage | `cov` |
| Quality | `qual` |
| Openness | `op` |

Examples: `data.pid.cov.1`, `role.feas.2`, `cost.co.1`

---

## Test Record Format

Each new test must follow this structure:

```markdown
## Test: Check <what is being checked>

**Test ID:** T-DCSC
**Persistent URI:** https://example.org/test/T-DCSC-<slug>

**Implements:** [<Metric title>](metrics.md#<metric-anchor>)

### Description
<1–2 sentences explaining what the test checks and why, written for a non-technical audience.>

### Input
<maDMP fields or external sources the test reads, comma-separated.>

### Output
pass/fail

### Procedure
1. <Step 1>
2. <Step 2>
...

### JSON-LD (Test)
\`\`\`json
{ ... }
\`\`\`
```

### Test title convention

All test titles must start with **Check** followed by a description of what is verified. Examples:
- `Check dataset.type is specified`
- `Check PID Resolves Successfully`
- `Check contributor PIDs in maDMP against Zenodo contributors`

---

## Catalogue Table

When adding a new metric or test, also add an entry to the **catalogue table** at the top of the relevant file:

- In `metrics.md`: `| <metric-id> | [<Title>](#<anchor>) |`
- In `tests.md`: `| T-DCSC | [<Title>](#<anchor>) |`

Anchors follow standard Markdown heading slug rules: lowercase, spaces replaced by hyphens, special characters removed.

---

## Submitting Your Contribution

1. **Fork** this repository
2. **Create a branch** with a descriptive name, e.g. `add-metric-data-retention`
3. **Add your changes** following the formats above
4. **Open a Pull Request** with a clear title and description explaining:
   - What metric or test you are adding or changing
   - Why it is needed
   - Which DMP standard field(s) or policy requirement it relates to
5. A maintainer will review your contribution and may request changes before merging

---

