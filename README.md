# Magento 2 (Adobe Commerce) (magento-2)

Magento 2, now branded as Adobe Commerce (with the open source Magento Open Source edition), is a flexible PHP-based ecommerce platform for building storefronts, managing catalogs, processing orders, and orchestrating omnichannel customer experiences. It exposes REST, GraphQL, and SOAP web APIs that allow developers and integrators to programmatically manage products, orders, customers, inventory, and store configuration. Authentication supports OAuth 1.0a, token-based authentication (admin and customer tokens), and Adobe IMS for the cloud service.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/magento-2/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/magento-2/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Ecommerce
- Commerce
- Online Store
- Catalog Management
- Order Management
- GraphQL
- REST
- SOAP

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Adobe Commerce REST API

REST API for managing products, customers, orders, inventory, cart, and checkout in Magento 2 / Adobe Commerce. The base URL pattern is https://{host}/rest/{storeCode}/V1/. Authentication supports OAuth 1.0a for third-party integrations and bearer tokens for admin and customer sessions. A live Swagger UI is available at /swagger when running in developer mode and the OpenAPI schema is available via the schema endpoint.

- **Human URL:** [https://developer.adobe.com/commerce/webapi/rest/](https://developer.adobe.com/commerce/webapi/rest/)
- **Base URL:** `https://{host}/rest/{storeCode}/V1`

#### Tags

- Ecommerce
- REST
- Catalog
- Orders
- Customers

#### Properties

- [Documentation](https://developer.adobe.com/commerce/webapi/rest/)
- [R E S T  Reference](https://developer.adobe.com/commerce/webapi/reference/rest/paas/)
- [O Auth  Authentication](https://developer.adobe.com/commerce/webapi/get-started/authentication/gs-authentication-oauth/)
- [Token  Authentication](https://developer.adobe.com/commerce/webapi/get-started/authentication/gs-authentication-token/)
- [Open A P I  Schema](https://{host}/rest/default/schema?services=all)
- [Postman Collection](collections/magento-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/magento-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe Commerce GraphQL API

GraphQL API for headless storefront use cases in Magento 2 / Adobe Commerce, providing single-request access to catalog, cart, checkout, and customer data. Mutations require customer token authentication via the Authorization header.

- **Human URL:** [https://developer.adobe.com/commerce/webapi/graphql/](https://developer.adobe.com/commerce/webapi/graphql/)
- **Base URL:** `https://{host}/graphql`

#### Tags

- Ecommerce
- GraphQL
- Headless Commerce
- Storefront

#### Properties

- [Documentation](https://developer.adobe.com/commerce/webapi/graphql/)
- [Postman Collection](collections/magento-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/magento-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/adobe-commerce)
- [Website](https://business.adobe.com/products/magento/magento-commerce.html)
- [Documentation](https://developer.adobe.com/commerce/)
- [Git Hub](https://github.com/magento/magento2)
- [Pricing](https://business.adobe.com/products/magento/magento-commerce.html)
- [Sign Up](https://account.magento.com/customer/account/create)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
