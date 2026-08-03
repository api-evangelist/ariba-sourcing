# Ariba Sourcing (ariba-sourcing)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

SAP Ariba Sourcing provides cloud-based strategic sourcing capabilities for procurement organizations. It enables supplier collaboration, RFx management, electronic auctions, and contract management through APIs that integrate sourcing processes with enterprise systems.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/ariba-sourcing/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Approvals, Auctions, B2B, Contracts, Procurement, RFx, SAP, Sourcing, Supplier Management, Supply Chain

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Ariba Sourcing - External Approval API
The External Approval API for Sourcing and Supplier Management enables client applications to approve or deny SAP Ariba strategic sourcing approval tasks. It supports external approval tasks in sourcing projects, contract workspaces, engagement risk assessment, and all types of supplier management projects.

**Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)

#### Tags:

 - Approvals, Contracts, RFx, Sourcing, Supplier Management

#### Properties

- [Documentation](https://help.sap.com/doc/69824194c55e4393870c5d3587aaf821/cloud/en-US/abdf297f281243ed9f8f3ead706a74d3.pdf)
- [OpenAPI](openapi/ariba-sourcing-external-approval-api.yaml)
- [JSONSchema](json-schema/external-approval-api-approval-task-schema.json)
- [JSONSchema](json-schema/external-approval-api-approvable-document-schema.json)
- [JSONSchema](json-schema/external-approval-api-approval-changes-response-schema.json)
- [JSONStructure](json-structure/external-approval-api-approval-task-structure.json)
- [JSONStructure](json-structure/external-approval-api-approvable-document-structure.json)
- [JSON-LD](json-ld/ariba-sourcing-external-approval-api-context.jsonld)

## Common Properties

- [Portal](https://developer.ariba.com)
- [Documentation](https://help.sap.com/docs/ariba-apis)
- [GettingStarted](https://help.sap.com/docs/ariba-apis/help-for-sap-ariba-developer-portal/sap-ariba-developer-portal-quick-start-guide-for-developers)
- [Support](https://help.sap.com/ariba)
- [TermsOfService](https://www.sap.com/corporate/en/legal/terms-of-use.html)
- [PrivacyPolicy](https://www.sap.com/about/legal/privacy.html)
- [GitHubOrganization](https://github.com/SAP-samples)
- [CodeExamples - SAP Ariba Extensibility Samples](https://github.com/SAP-samples/ariba-extensibility-samples)

## Features

| Name | Description |
|------|-------------|
| External Approval Workflow | Enables external systems to retrieve, review, and approve or deny SAP Ariba sourcing approval tasks programmatically. |
| Multi-Document Type Support | Supports approval tasks for sourcing projects, RFX documents, contract workspaces, contract content, and supplier management projects. |
| Rate-Limited API Access | Well-defined rate limits of 20 req/sec, 400 req/min, 12000 req/hour, and 40000 req/day for production stability. |
| Pagination Support | Results pagination with offset and limit parameters plus X-Total-Count headers for efficient data retrieval. |
| Group-Based Approval | Supports approval flows with groups, enabling retrieval of group membership to identify eligible approvers. |
| Attachment Downloads | Enables downloading attachments associated with approvable documents for review prior to approval decisions. |

## Use Cases

| Name | Description |
|------|-------------|
| Automated Sourcing Approvals | Automate the approval workflow for sourcing events and contracts by polling for pending tasks and submitting programmatic approval actions. |
| ERP-Integrated Approvals | Route SAP Ariba sourcing approval tasks to external ERP or workflow systems for approval by authorized personnel. |
| Supplier Onboarding Approval | Manage external approval of supplier registration and onboarding projects through the supplier management approval workflow. |
| Contract Approval Automation | Integrate contract workspace approvals with enterprise contract management systems for streamlined legal and commercial review. |

## Integrations

| Name | Description |
|------|-------------|
| SAP ERP | Route sourcing approval tasks to SAP ERP workflows and approval hierarchies. |
| SAP Integration Suite | Orchestrate approval workflows across SAP Ariba and connected systems using SAP Integration Suite. |
| SAP Ariba Contracts | Approve contract workspaces and contract content documents through the external approval API. |
| SAP Ariba Supplier Management | Approve supplier lifecycle and performance management projects and supplier registration requests. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Ariba Sourcing - External Approval API](openapi/ariba-sourcing-external-approval-api.yaml)

### JSON Schema

- [external-approval-api-approval-task-schema](json-schema/external-approval-api-approval-task-schema.json)
- [external-approval-api-approvable-document-schema](json-schema/external-approval-api-approvable-document-schema.json)
- [external-approval-api-approval-changes-response-schema](json-schema/external-approval-api-approval-changes-response-schema.json)
- [external-approval-api-approval-change-schema](json-schema/external-approval-api-approval-change-schema.json)
- [external-approval-api-pending-approvables-response-schema](json-schema/external-approval-api-pending-approvables-response-schema.json)
- [external-approval-api-pending-approval-task-schema](json-schema/external-approval-api-pending-approval-task-schema.json)
- [external-approval-api-approval-action-request-schema](json-schema/external-approval-api-approval-action-request-schema.json)
- [external-approval-api-approval-action-response-schema](json-schema/external-approval-api-approval-action-response-schema.json)
- [external-approval-api-group-members-response-schema](json-schema/external-approval-api-group-members-response-schema.json)
- [external-approval-api-group-member-schema](json-schema/external-approval-api-group-member-schema.json)
- [external-approval-api-approval-request-schema](json-schema/external-approval-api-approval-request-schema.json)
- [external-approval-api-approver-schema](json-schema/external-approval-api-approver-schema.json)

### JSON Structure

- [external-approval-api-approval-task-structure](json-structure/external-approval-api-approval-task-structure.json)
- [external-approval-api-approvable-document-structure](json-structure/external-approval-api-approvable-document-structure.json)
- [external-approval-api-approval-changes-response-structure](json-structure/external-approval-api-approval-changes-response-structure.json)
- [external-approval-api-approval-change-structure](json-structure/external-approval-api-approval-change-structure.json)
- [external-approval-api-pending-approvables-response-structure](json-structure/external-approval-api-pending-approvables-response-structure.json)
- [external-approval-api-pending-approval-task-structure](json-structure/external-approval-api-pending-approval-task-structure.json)
- [external-approval-api-approval-action-request-structure](json-structure/external-approval-api-approval-action-request-structure.json)
- [external-approval-api-approval-action-response-structure](json-structure/external-approval-api-approval-action-response-structure.json)
- [external-approval-api-group-members-response-structure](json-structure/external-approval-api-group-members-response-structure.json)
- [external-approval-api-group-member-structure](json-structure/external-approval-api-group-member-structure.json)

### JSON-LD

- [ariba-sourcing-external-approval-api-context](json-ld/ariba-sourcing-external-approval-api-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [External Approval API](capabilities/shared/external-approval-api.yaml) — 6 operations for approval task retrieval, document review, and action submission

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Sourcing Approvals](capabilities/sourcing-approvals.yaml) | External Approval API | 7 | Sourcing Manager, Procurement Approver |

## Vocabulary

- [Ariba Sourcing Vocabulary](vocabulary/ariba-sourcing-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 3 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Ariba Sourcing Spectral Rules](rules/ariba-sourcing-spectral-rules.yml) — 28 rules across 9 categories enforcing Ariba Sourcing API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
