# CDC (cdc)

The US Centers for Disease Control and Prevention (CDC) provides a suite of public APIs for accessing disease surveillance data, vaccination rates, health statistics, environmental public health tracking, and public health datasets. Key offerings include the CDC WONDER API for querying mortality and disease databases, the Open Data API powered by Socrata for thousands of datasets across categories such as flu vaccinations, STDs, injury, and NCHS statistics, the Environmental Public Health Tracking Network API for environmental health data, and the PHIN VADS vocabulary service for public health terminology.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cdc/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cdc/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Public Health
- Disease Surveillance
- Vaccination
- Health Statistics
- Government
- Open Data
- Environmental Health
- Mortality
- CDC WONDER

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### CDC Open Data API

Repository of all available CDC datasets accessible via the Socrata Open Data API (SODA). Covers categories including administrative data, biomonitoring, child vaccinations, flu vaccinations, health statistics, injury and violence, NCHS data, NNDSS reportable disease surveillance, pregnancy and vaccination, STDs, smoking and tobacco use, traumatic brain injury, and web metrics. Supports JSON, XML, and CSV response formats.

- **Human URL:** [https://data.cdc.gov](https://data.cdc.gov)
- **Base URL:** `https://data.cdc.gov/resource`

#### Tags

- Open Data
- Health Statistics
- Disease Surveillance
- Vaccination

#### Properties

- [Documentation](https://dev.socrata.com/docs/endpoints.html)
- [OpenAPI](https://data.cdc.gov/api/docs) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### CDC WONDER API

The CDC WONDER (Wide-ranging Online Data for Epidemiologic Research) API enables automated data queries in XML format over HTTP. Supports access to online databases covering mortality, natality, cancer statistics, AIDS/HIV, tuberculosis, sexually transmitted diseases, and environmental health data. Requests are HTTP POST to the WONDER controller endpoint with XML parameters; responses are returned as XML.

- **Human URL:** [https://wonder.cdc.gov](https://wonder.cdc.gov)
- **Base URL:** `https://wonder.cdc.gov/controller/datarequest`

#### Tags

- Disease Surveillance
- Mortality
- Epidemiology
- Public Health

#### Properties

- [Documentation](https://wonder.cdc.gov/wonder/help/WONDER-API.html)

### CDC Environmental Public Health Tracking Network API

Allows querying of data from the CDC National Environmental Public Health Tracking Network. Returns JSON-formatted responses covering environmental health indicators such as air quality, water quality, climate data, and their associations with health outcomes across the United States.

- **Human URL:** [https://ephtracking.cdc.gov](https://ephtracking.cdc.gov)
- **Base URL:** `https://ephtracking.cdc.gov/apigateway/api/v1`

#### Tags

- Environmental Health
- Air Quality
- Water Quality
- Climate
- Public Health

#### Properties

- [Documentation](https://ephtracking.cdc.gov/apihelp)

### CDC Content Syndication API

Enables CDC to offer web content to other sites and applications. Provides structured access to CDC health content including articles, health topics, media, and tools in JSON and XML formats for syndication to third-party websites and public health information systems.

- **Human URL:** [https://tools.cdc.gov/api/docs/info.aspx](https://tools.cdc.gov/api/docs/info.aspx)
- **Base URL:** `https://tools.cdc.gov/api/v2`

#### Tags

- Content
- Health Information
- Syndication

#### Properties

- [Documentation](https://tools.cdc.gov/api/docs/info.aspx#response)

### PHIN VADS API

The Public Health Information Network Vocabulary Access and Distribution System (PHIN VADS) is a web-based enterprise vocabulary system for accessing, searching, and distributing vocabularies used in public health and clinical care practice. Provides REST access to standardized code sets and value sets used in public health reporting.

- **Human URL:** [https://phinvads.cdc.gov](https://phinvads.cdc.gov)
- **Base URL:** `https://phinvads.cdc.gov/vocabService/v2`

#### Tags

- Vocabulary
- Terminology
- Standards
- Public Health

#### Properties

- [Documentation](https://phinvads.cdc.gov/vads/developersGuide.action)

### DIBBs eCR Refiner API

CDC DIBBS (Data Integration Building Blocks) electronic Case Reporting (eCR) Refiner API for managing disease reporting configurations with customizable code sets. Supports creating and managing reportable condition configurations, custom code management, eICR document refinement and simulation, jurisdiction audit logs, and release tracking.

- **Human URL:** [https://github.com/CDCgov/dibbs-ecr-refiner](https://github.com/CDCgov/dibbs-ecr-refiner)
- **Base URL:** `https://github.com/CDCgov/dibbs-ecr-refiner`

#### Tags

- Electronic Case Reporting
- eCR
- Disease Reporting
- Public Health
- DIBBS

#### Properties

- [Documentation](https://github.com/CDCgov/dibbs-ecr-refiner)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/cdc/refs/heads/main/openapi/dibbs-ecr-refiner-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### DIBBs Query Connector API

CDC DIBBS (Data Integration Building Blocks) Query Connector API for executing healthcare data queries against FHIR servers using patient identifiers. Accepts FHIR patient resources or HL7v2 messages and returns matching FHIR resources from target FHIR servers.

- **Human URL:** [https://github.com/CDCgov/dibbs-query-connector](https://github.com/CDCgov/dibbs-query-connector)
- **Base URL:** `https://github.com/CDCgov/dibbs-query-connector`

#### Tags

- FHIR
- HL7
- Healthcare Data
- Patient Data
- Public Health
- DIBBS

#### Properties

- [Documentation](https://github.com/CDCgov/dibbs-query-connector)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/cdc/refs/heads/main/openapi/dibbs-query-connector-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [Portal](https://open.cdc.gov/apis.html)
- [Git Hub](https://github.com/CDCgov)
- [Authentication](https://dev.socrata.com/docs/app-tokens.html)
- [Terms of Service](https://www.cdc.gov/other/policies.html)
- [Privacy Policy](https://www.cdc.gov/other/privacy.html)
- [Licensing](https://www.cdc.gov/other/policies.html#linking)
- [Json L D](https://raw.githubusercontent.com/api-evangelist/cdc/refs/heads/main/json-ld/apis-jsonld.json) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
