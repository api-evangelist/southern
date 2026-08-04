# Southern Company

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

Southern Company is a leading American gas and electric utility holding company headquartered in Atlanta, Georgia. Through its subsidiaries — Alabama Power, Georgia Power, Mississippi Power, Southern Natural Gas, and Southern Company Gas — it serves 9 million gas and electric utility customers across 6 states. Southern Company is a Fortune 500 company with operations spanning electricity generation, transmission, distribution, and natural gas distribution.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/southern/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Fortune 500
- Electric Utility
- Natural Gas
- Energy

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-02

## APIs

### Southern Company Customer Account API

The Southern Company Customer Account API provides access to utility account data for Alabama Power, Georgia Power, and Mississippi Power customers. It supports reading energy usage data, account balances, billing history, and daily consumption data with costs and kilowatt-hour measurements.

- [Documentation](https://www.southerncompany.com/)
- [GitHub](https://github.com/apearson/southern-company-api)
- [JSON Schema - Utility Account](https://raw.githubusercontent.com/api-evangelist/southern/refs/heads/main/json-schema/southern-utility-account-schema.json)
- [JSON Schema - Energy Usage](https://raw.githubusercontent.com/api-evangelist/southern/refs/heads/main/json-schema/southern-energy-usage-schema.json)


## Common Properties

- [Website](https://www.southerncompany.com)
- [Investor Relations](https://investor.southerncompany.com/)
- [GitHub Organization](https://github.com/Southern-Company-HA)
- [LinkedIn](https://www.linkedin.com/company/southern-company)
- [X (Twitter)](https://twitter.com/SouthernCompany)

## Artifacts

### JSON Schemas

| Schema | Description |
|---|---|
| [southern-utility-account-schema.json](json-schema/southern-utility-account-schema.json) | Customer utility account with service address, metering, and billing data |
| [southern-energy-usage-schema.json](json-schema/southern-energy-usage-schema.json) | Daily or interval energy consumption records in kWh or therms |

### JSON Structure

| Structure | Description |
|---|---|
| [southern-utility-account-structure.json](json-structure/southern-utility-account-structure.json) | Hierarchical structure of account, meter, usage, and billing entities |

### JSON-LD Context

| Context | Description |
|---|---|
| [southern-context.jsonld](json-ld/southern-context.jsonld) | Linked data context mapping Southern Company vocabulary to schema.org |

### Examples

| Example | Description |
|---|---|
| [southern-utility-account-example.json](examples/southern-utility-account-example.json) | Sample Georgia Power customer account |
| [southern-energy-usage-example.json](examples/southern-energy-usage-example.json) | Sample daily electric usage record |

### Vocabulary

| Vocabulary | Description |
|---|---|
| [southern-vocabulary.yml](vocabulary/southern-vocabulary.yml) | Domain vocabulary for Southern Company utility operations |

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
