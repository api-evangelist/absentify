# Absentify (absentify)

Absentify is an absence management platform integrated with Microsoft 365 and Microsoft Teams that helps businesses track and manage employee absences, leave requests, approvals, and team schedules. Built by BrainCore Solutions GmbH, it provides a REST API for integrating absence management into custom workflows, HR systems, and business automation tools.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/absentify/refs/heads/main/apis.yml)

## Scope of this API Collection

| Artifact Type | Count |
|---|---|
| APIs | 1 |
| OpenAPI Specs | 1 |
| JSON Schemas | 7 |
| JSON Structure Files | 7 |
| JSON-LD Context Files | 1 |
| Example Files | 6 |
| Spectral Rulesets | 1 |
| Naftiko Capabilities | 2 |
| Vocabularies | 1 |

## APIs

### Absentify API

REST API for managing employee absences, leave requests, members, departments, leave types, public holidays, and workspace settings. Requires an API key (x-api-key header) available on the Plus plan. Rate limit of 150 requests per second per IP address.

**Base URL:** https://api.absentify.com/api/v1

| Property | URL |
|---|---|
| Documentation | https://absentify.com/docs/en/api-reference/introduction |
| OpenAPI Spec | [openapi/absentify-openapi.yml](openapi/absentify-openapi.yml) |
| Member Schema | [json-schema/absentify-member-schema.json](json-schema/absentify-member-schema.json) |
| Department Schema | [json-schema/absentify-department-schema.json](json-schema/absentify-department-schema.json) |
| Leave Type Schema | [json-schema/absentify-leave-type-schema.json](json-schema/absentify-leave-type-schema.json) |
| Request Schema | [json-schema/absentify-request-schema.json](json-schema/absentify-request-schema.json) |
| Absence Schema | [json-schema/absentify-absence-schema.json](json-schema/absentify-absence-schema.json) |
| Workspace Schema | [json-schema/absentify-workspace-schema.json](json-schema/absentify-workspace-schema.json) |
| Public Holiday Calendar Schema | [json-schema/absentify-public-holiday-calendar-schema.json](json-schema/absentify-public-holiday-calendar-schema.json) |
| JSON-LD Context | [json-ld/absentify-context.jsonld](json-ld/absentify-context.jsonld) |

## Common Properties

| Property | URL |
|---|---|
| Portal | https://absentify.com/ |
| Documentation | https://absentify.com/docs/en/ |
| Pricing | https://absentify.com/pricing |
| Privacy Policy | https://absentify.com/privacy-policy |
| Terms of Service | https://absentify.com/terms-and-conditions |
| Blog | https://absentify.com/blog |
| Status Page | https://status.absentify.com |
| Security | https://absentify.com/security |
| MCP Server | https://absentify.com/docs/en/mcp-server |
| Spectral Rules | [rules/absentify-spectral-rules.yml](rules/absentify-spectral-rules.yml) |
| Naftiko Capability | [capabilities/absence-management-absentify.yaml](capabilities/absence-management-absentify.yaml) |
| Vocabulary | [vocabulary/absentify-vocabulary.yaml](vocabulary/absentify-vocabulary.yaml) |

## Features

- **Absence Tracking** — Track and manage employee absences, time off, and leave requests across the organization.
- **Leave Request Management** — Submit, approve, decline, and cancel leave requests with multi-level approval workflows.
- **Microsoft 365 Integration** — Native integration with Microsoft 365 and Microsoft Teams for seamless absence management in existing workflows.
- **Department Management** — Organize employees into departments with custom leave type entitlements and approval chains.
- **Leave Type Configuration** — Define custom leave types with color coding, limits, approval requirements, and accrual policies.
- **Public Holiday Calendars** — Manage public holiday calendars per region and apply them to members and departments.
- **Webhook Support** — Receive real-time webhook notifications for request creation and status changes.
- **Workspace Management** — Configure workspace-wide settings, fiscal year, and default approval workflows.
- **Absence Per Day Reporting** — Query absences broken down by individual day for reporting and payroll integration.

## Use Cases

- **HR System Integration** — Integrate absence data into HRIS platforms like SAP, Workday, or BambooHR for unified people management.
- **Payroll Processing** — Export absence data to payroll systems to automatically calculate pay adjustments for time off.
- **Team Scheduling** — Sync absence data into scheduling tools to prevent understaffing and manage coverage.
- **Compliance Reporting** — Generate absence reports for regulatory compliance, labor law adherence, and audit purposes.
- **Custom Approval Workflows** — Build custom absence request approval workflows integrated with business process automation tools.
- **Absence Analytics** — Analyze absence trends, patterns, and costs to improve workforce planning and reduce absenteeism.
- **Microsoft Teams Automation** — Automate absence-related notifications and approvals directly within Microsoft Teams channels.

## Integrations

- **Microsoft Teams** — Native Microsoft Teams app for submitting and approving absence requests without leaving Teams.
- **Microsoft 365** — Deep integration with Microsoft 365 calendar, Active Directory, and identity management.
- **Zapier** — Connect absentify to thousands of apps via Zapier automation workflows.
- **Make (Integromat)** — Automate absence management workflows using Make's visual automation platform.
- **Custom Webhooks** — Send real-time absence event notifications to any system via configurable webhooks.

## Maintainers

**Kin Lane** (kin@apievangelist.com)
