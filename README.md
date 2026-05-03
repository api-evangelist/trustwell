# Trustwell

Trustwell is a food industry software company formed from the merger of ESHA Research and FoodLogiQ in 2023, providing the food and beverage industry with an integrated platform covering product formulation, nutrition labeling, regulatory compliance, supply chain management, traceability, quality assurance, and recall management.

The Trustwell Connect Platform offers two primary APIs: the Genesis Foods GraphQL API for nutrition analysis, food formulation, and label generation (with support for US, Canadian, EU, Mexican, and Australian regulatory standards), and the FoodLogiQ REST API for supply chain visibility, compliance management, supplier relationships, and FSMA 204-compliant traceability. Both APIs use X-API-KEY header authentication.

**URL:** [https://raw.githubusercontent.com/api-evangelist/trustwell/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/trustwell/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Food Industry
- Food Safety
- Nutrition
- Supply Chain
- Food Labeling
- Traceability
- Compliance
- Food Technology

## APIs

| API | Description | Auth | Docs |
|-----|-------------|------|------|
| Trustwell Genesis Foods GraphQL API | Food formulation, nutrition analysis, allergen declarations, label generation (US, CA, EU, MX, AU), and regulatory compliance via GraphQL. 16 query types, 6 mutation categories. | X-API-KEY | [Docs](https://docs.trustwell.com/genesis/api/) |
| Trustwell FoodLogiQ API | Supply chain management, supplier compliance, quality incident tracking, FSMA 204 traceability, and recall management via REST API. | X-API-KEY | [Docs](https://www.trustwell.com/products/foodlogiq/) |
| Trustwell Genesis Supplements API | Dietary supplement formulation and Supplement Facts label generation built on the Genesis Foods GraphQL endpoint. | X-API-KEY | [Docs](https://docs.trustwell.com/genesis/api/) |

## Artifacts

| Artifact | Location | Description |
|----------|----------|-------------|
| OpenAPI (FoodLogiQ) | [openapi/trustwell-foodlogiq-openapi.yml](openapi/trustwell-foodlogiq-openapi.yml) | OpenAPI 3.0.3 specification for the FoodLogiQ REST API |
| Spectral Rules | [rules/trustwell-rules.yml](rules/trustwell-rules.yml) | API linting rules for Trustwell API standards |
| Naftiko: Genesis Foods | [capabilities/shared/genesis-foods.yaml](capabilities/shared/genesis-foods.yaml) | Shared capability definition for Genesis Foods GraphQL API |
| Naftiko: FoodLogiQ | [capabilities/shared/foodlogiq.yaml](capabilities/shared/foodlogiq.yaml) | Shared capability definition for FoodLogiQ REST API |
| Naftiko: Food Safety Management | [capabilities/food-safety-management.yaml](capabilities/food-safety-management.yaml) | Unified food safety management workflow capability |
| JSON Schema: Food Item | [json-schema/trustwell-food-item-schema.json](json-schema/trustwell-food-item-schema.json) | JSON Schema for food item with nutrients, allergens, and labels |
| JSON Schema: Supplier | [json-schema/trustwell-supplier-schema.json](json-schema/trustwell-supplier-schema.json) | JSON Schema for supply chain supplier records |
| JSON Schema: Quality Incident | [json-schema/trustwell-quality-incident-schema.json](json-schema/trustwell-quality-incident-schema.json) | JSON Schema for food quality incident reports |
| JSON Schema: Recall | [json-schema/trustwell-recall-schema.json](json-schema/trustwell-recall-schema.json) | JSON Schema for food recall and withdrawal events |
| JSON Structure: Food Item | [json-structure/trustwell-food-item-structure.json](json-structure/trustwell-food-item-structure.json) | Structure reference for food item fields |
| JSON Structure: Supplier | [json-structure/trustwell-supplier-structure.json](json-structure/trustwell-supplier-structure.json) | Structure reference for supplier fields |
| JSON-LD Context | [json-ld/trustwell-context.jsonld](json-ld/trustwell-context.jsonld) | Linked data context mapping to schema.org, GS1, and food ontologies |
| Examples | [examples/](examples/) | Request/response examples for Genesis Foods and FoodLogiQ APIs |
| Vocabulary | [vocabulary/trustwell-vocabulary.yml](vocabulary/trustwell-vocabulary.yml) | Domain vocabulary for food safety and supply chain terms |

## Authentication

Both the Genesis Foods GraphQL API and the FoodLogiQ REST API use API key authentication via the `X-API-KEY` request header:

```
X-API-KEY: YOUR_TRUSTWELL_API_KEY
```

API keys are obtained through the Trustwell Connect Platform and may be scoped to specific roles and permissions (role-based API tokens introduced in Q3 2025 for FoodLogiQ).

## Key Concepts

- **FSMA 204**: US Food Safety Modernization Act Section 204 traceability rule requiring lot-level records for foods on the Food Traceability List (FTL), effective January 2026.
- **Genesis Foods**: Trustwell's food formulation platform using GraphQL, supporting 600+ schema types and 5 regulatory label formats.
- **FoodLogiQ**: Trustwell's supply chain platform with supplier management, compliance tracking, quality incidents, traceability lots, and recall management.
- **Nutrition Labels**: Supported regulatory formats include US (FDA), CA (Health Canada), EU (EFSA), MX (COFEPRIS NOM-051), and AU/NZ (FSANZ).

## Resources

- [Trustwell Website](https://www.trustwell.com/)
- [Developer Documentation](https://docs.trustwell.com/)
- [Genesis API Documentation](https://docs.trustwell.com/genesis/api/)
- [Trustwell Connect Platform](https://www.trustwell.com/platform/)
- [Trustwell Blog](https://blog.trustwell.com/)
- [Privacy Policy](https://www.trustwell.com/privacy-policy/)
- [Terms of Service](https://www.trustwell.com/terms-of-service/)

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-03

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
