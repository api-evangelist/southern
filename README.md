# Southern Company

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

### Southern Company Investor Relations

Southern Company's investor relations portal provides financial data, earnings summaries, filings, reports, and shareholder information for investors and analysts.

- [Investor Relations Portal](https://investor.southerncompany.com/home/default.aspx)
- [Download Library](https://investor.southerncompany.com/news-and-resources/download-library/default.aspx)

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
