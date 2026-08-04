# Contractor Foreman (contractorforeman)

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
