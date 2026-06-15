# Trustwell (trustwell)

Trustwell is a food industry software company formed from the merger of ESHA Research and FoodLogiQ in 2023, providing the food and beverage industry with an integrated platform covering product formulation, nutrition labeling, regulatory compliance, supply chain management, traceability, quality assurance, and recall management. The Trustwell Connect Platform offers two primary APIs: the Genesis Foods GraphQL API for nutrition analysis, food formulation, and label generation (with support for US, Canadian, EU, Mexican, and Australian regulatory standards), and the FoodLogiQ API for supply chain visibility, compliance management, supplier relationships, and FSMA 204-compliant traceability. Both APIs require X-API-KEY authentication. The platform serves food manufacturers, retailers, restaurants, and distributors across the global food supply chain.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/trustwell/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/trustwell/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
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

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Trustwell Genesis Foods GraphQL API

The Trustwell Genesis Foods GraphQL API provides programmatic access to food formulation, nutrition analysis, and label generation capabilities. The GraphQL endpoint at api.trustwell.com/genesis supports 16 query types (foods, labels, nutrients, allergens, products, suppliers, regulations, documents, and more), 6 mutation categories (foods with 50+ sub-operations, label, documents, products, suppliers, tags), and 2 subscription types (documentEvents, tenantEvents) for real-time monitoring. The API supports 600+ schema types covering US, Canadian, EU, Mexican, and Australian/New Zealand regulatory standards for nutrition labeling. Authentication uses the X-API-KEY header. The API connects nutrition analysis data to ERP, PLM, POS, and website systems.

- **Human URL:** [https://docs.trustwell.com/genesis/api/](https://docs.trustwell.com/genesis/api/)
- **Base URL:** `https://api.trustwell.com/genesis`

#### Tags

- Food Formulation
- Nutrition Labeling
- Regulatory Compliance
- Food Industry

#### Properties

- [Documentation](https://docs.trustwell.com/genesis/api/)
- [Documentation](https://www.trustwell.com/products/genesis/food-formulation-and-labeling/)
- [Postman Collection](collections/trustwell-foodlogiq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trustwell-foodlogiq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trustwell FoodLogiQ API

The Trustwell FoodLogiQ API is an open REST API that enables enterprise food brands to integrate supply chain data with their existing systems. The API supports supplier relationship management, compliance documentation, quality incident management, product specification management, FSMA 204-compliant traceability (farm-to-fork tracking), and recall management workflows. The Q3 2025 release introduced role-based API tokens with scoped permissions for fine-grained access control. The API is documented within the FoodLogiQ Connect platform Resource Center and supports integration with ERP, WMS, and third-party food safety systems.

- **Human URL:** [https://www.trustwell.com/products/foodlogiq/](https://www.trustwell.com/products/foodlogiq/)
- **Base URL:** `https://api.trustwell.com/foodlogiq`

#### Tags

- Food Safety
- Supply Chain
- Traceability
- Compliance
- Quality Management
- Recall Management
- Food Industry

#### Properties

- [Documentation](https://www.trustwell.com/products/foodlogiq/)
- [Documentation](https://www.trustwell.com/products/foodlogiq/product-management/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/trustwell/refs/heads/main/openapi/trustwell-foodlogiq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trustwell-foodlogiq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trustwell-foodlogiq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trustwell Genesis Supplements API

The Trustwell Genesis Supplements API provides formulation and regulatory compliance capabilities for dietary supplement manufacturers. Built on the same Genesis Foods GraphQL endpoint, it supports Supplement Facts label generation, ingredient declaration, allergen statements, and compliance with FDA dietary supplement regulations. The API enables integration of supplement formulation data into ERP and PLM systems.

- **Human URL:** [https://www.trustwell.com/products/genesis/](https://www.trustwell.com/products/genesis/)
- **Base URL:** `https://api.trustwell.com/genesis`

#### Tags

- Supplement Formulation
- Nutrition Labeling
- Regulatory Compliance
- Food Industry

#### Properties

- [Documentation](https://www.trustwell.com/products/genesis/)
- [Documentation](https://docs.trustwell.com/genesis/api/)
- [Postman Collection](collections/trustwell-foodlogiq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trustwell-foodlogiq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.trustwell.com/)
- [Documentation](https://docs.trustwell.com/)
- [Documentation](https://docs.trustwell.com/genesis/api/)
- [Portal](https://www.trustwell.com/platform/)
- [Products](https://www.trustwell.com/products/)
- [Blog](https://blog.trustwell.com/)
- [News](https://www.trustwell.com/news-and-press/)
- [Privacy Policy](https://www.trustwell.com/privacy-policy/)
- [Terms of Service](https://www.trustwell.com/terms-of-service/)
- [LinkedIn](https://www.linkedin.com/company/trustwell-llc)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/trustwell/refs/heads/main/rules/trustwell-rules.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
