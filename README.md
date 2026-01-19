# Pre-Sales Assets Repository

Welcome to the **Pre-Sales Repo** — this is the centralized hub for all pre-sales artifacts, demos, PoC kits, and solution blueprints that support Tredence business development activities and solution acceleration.

This repository is organized to make it easy to find and reuse pre-sales content across opportunities and engagements.

---

## Repository Structure

The repo is organized into the following key folders:

/demos
/poc-kits
/solution-blueprints



### `demos`

This folder contains interactive or script-driven demo assets useful for showcasing capabilities in pre-sales conversations.

Examples (replace these with real names once filled in):

- Customer 360 demo
- Forecasting dashboard demo
- Governance/lineage demo

Use this folder to:
- Quickly launch live demos
- Validate solution concepts
- Support proof of value in customer calls

---

### `poc-kits`

This folder includes **Proof-of-Concept kits** that can be used to accelerate PoCs with prospects.

Contents may include:
- Starter templates
- Databricks/Snowflake notebooks
- Cloud deployment scripts (Terraform/ARM/Bicep)
- API samples

**Each PoC kit should have a README** explaining:
- Purpose
- Prerequisites
- How to run

---

### `solution-blueprints`

This folder holds **solution architecture blueprints** and narrative decks for typical enterprise use cases.

Contents may include:
- Architecture diagrams
- Component flows
- Deployment patterns
- Best practice notes

Examples:
- AI-ready data platform
- Real-time analytics reference architecture
- Governance & security pattern

---

## How to Use This Repo

### Finding the right asset

1. **Start in the relevant folder**:
   - Looking for a demo? Look under `demos/`
   - Need a PoC kit? Go to `poc-kits/`
   - Architectural guidance? Check `solution-blueprints/`

2. **Open the sub-folder README** if present  
   Each sub-folder (ex: demo name) should have its own `README.md` explaining:
   - What it does
   - How to deploy/run
   - Dependencies

3. **Use templates and follow standards**
   Templates (if any) help maintain consistency across deliverables.

---

## Naming & Contribution Guidelines

To keep this repo organized and reusable:

### Naming conventions
- Use clear, descriptive names:
  - `demos/customer-360-dashboard`
  - `poc-kits/databricks-data-pipeline-kit`
  - `solution-blueprints/ai-lakehouse-pattern`

### Contribution workflow
- Fork → Feature branch → PR → Review → Merge
- Add/Update the `CATALOG.md` (if present) with a new entry for your asset
- Include metadata:
  - Owner
  - Platform (Snowflake, Databricks, AWS, Azure, GCP)
  - Last updated

---

## Catalog of Assets (Example)

| Asset | Folder | Owner | Platform | Description |
|-------|--------|-------|----------|-------------|
| Customer 360 Demo | demos/customer-360 | Abhijit Das | Databricks/Snowflake | Demo showing 360 view of customer data |
| AI Accelerator PoC | poc-kits/ai-accel | Team | Multi-cloud | Starter kit for AI PoC |
| Governance Blueprint | solution-blueprints/governance | Team | Snowflake | Reference architecture for governance |

*(Update this table as you add content)*

---

## Contact & Support

If you have questions or want to contribute content:
- Create an Issue in this repo
- Tag contributors or owners in the pull request
- Use branch names like: `feat/<your-asset-name>` or `docs/update-catalog`

---

## Next Steps

1. Add meaningful content to each folder  
2. Ensure each asset has its own `README.md`  
3. Update this README and a `CATALOG.md` to include a searchable index

---

*This repository supports pre-sales enablement and is intended to accelerate delivery of value in pursuit engagements across Tredence.*  

