# Contractor Foreman (contractorforeman)

Contractor Foreman is all-in-one construction management software for contractors - estimates, invoicing, scheduling, time cards, daily logs, change orders, and job costing - used by contractors in more than 75 countries. There is no self-serve public developer API or public API reference; the company's dedicated API subdomain (api.contractorforeman.net) displays only a "Coming soon" placeholder as of this review. The one confirmed API capability is a private, account-scoped API key (generated under Settings > Integration > Zapier) that powers Contractor Foreman's official Zapier app, exposing Customer and Lead create/archive/delete triggers and actions plus a File Uploaded trigger. That key and its underlying endpoints are not documented or published for direct third-party use outside the Zapier integration; broader third-party connectivity otherwise runs through native integrations (QuickBooks, Gusto, Google Calendar/Outlook, Stripe, Angi Leads, CompanyCam, MS Project, SweetPay) and Zapier/webhook automation rather than an open API.

**Access model:** Gated / undisclosed, with a public API "coming soon." No developer portal, no self-serve API keys for third-party integrations, and no published API reference. See [review.yml](review.yml) for the full findings.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/contractorforeman/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/contractorforeman/refs/heads/main/apis.yml)

## Tags

- Construction
- Construction Management
- Contractor Software
- Estimating
- Invoicing
- Scheduling

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## APIs

### Contractor Foreman Zapier Automation API

A private, account-scoped REST API reached with an API key generated under Settings > Integration > Zapier, used to power Contractor Foreman's official Zapier app rather than published for general developer use. Capabilities confirmed through Zapier's published trigger/action catalog include creating, archiving, and deleting Customer records; creating, archiving, and deleting Lead records; and a File Uploaded trigger for documents attached to a project. No base URL, endpoint paths, or request/response schemas are publicly documented by Contractor Foreman itself, so this API is modeled from Zapier's integration catalog only.

*This API is modeled from Zapier's published trigger/action catalog only (`endpointsModeled: true`); no endpoint paths, base URL, or request/response schema are published by Contractor Foreman.*

- **Human URL:** [https://kb.contractorforeman.com/knowledge-base/zapier-integration/](https://kb.contractorforeman.com/knowledge-base/zapier-integration/)

#### Tags

- Leads
- Customers
- Automation
- Zapier

#### Properties

- [Documentation](https://kb.contractorforeman.com/knowledge-base/zapier-integration/)
- [Documentation](https://zapier.com/apps/contractor-foreman/integrations)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/contractor-foreman)
- [Website](https://contractorforeman.com/)
- [Documentation](https://kb.contractorforeman.com/)
- [Plans](plans/contractorforeman-plans-pricing.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
