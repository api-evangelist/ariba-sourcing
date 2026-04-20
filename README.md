# Ariba Sourcing (ariba-sourcing)
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
