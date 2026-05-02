# Salesforce Experience Cloud APIs (salesforce-experience-cloud)
APIs for building and managing Salesforce Experience Cloud sites, communities, and digital experiences including CMS content management, theming, navigation, and Lightning Web Runtime portals.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/salesforce-experience-cloud/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- CMS, Communities, CRM, Customer Portal, Digital Experience, Experience Cloud, Partner Portal

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-02

## APIs

### Experience Cloud Sites API
Manage Experience Cloud sites, navigation menus, and themes.

**Human URL:** https://developer.salesforce.com/docs/atlas.en-us.exp_cloud_apis.meta/exp_cloud_apis/

#### Properties
- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.exp_cloud_apis.meta/exp_cloud_apis/)
- [OpenAPI](openapi/salesforce-experience-cloud-sites-openapi.yml)

---

### Connect REST API (Communities)
Access community feeds, topics, and user engagement features.

**Human URL:** https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/

#### Properties
- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/)
- [OpenAPI](openapi/salesforce-experience-cloud-connect-communities-openapi.yml)

---

### CMS Connect API
Manage content, channels, and media in Experience Cloud CMS.

**Human URL:** https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_cms.htm

#### Properties
- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_cms.htm)
- [OpenAPI](openapi/salesforce-experience-cloud-cms-connect-openapi.yml)

---

### Salesforce REST API
Core REST API for Salesforce data access used in Experience Cloud integrations.

**Human URL:** https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/

#### Properties
- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/)
- [OpenAPI](openapi/salesforce-experience-cloud-rest-api-openapi.yml)

---

### CMS Managed Content API
Retrieve and search published managed content for Experience Cloud sites.

**Human URL:** https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_managed_content_resources.htm

#### Properties
- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_managed_content_resources.htm)
- [OpenAPI](openapi/salesforce-experience-cloud-cms-managed-content-openapi.yml)

---

### CMS Delivery API
Deliver CMS content to external applications and headless frontends.

**Human URL:** https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_cms_delivery_content.htm

#### Properties
- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_cms_delivery_content.htm)
- [OpenAPI](openapi/salesforce-experience-cloud-cms-delivery-openapi.yml)

---

### GraphQL API
Query Salesforce data using GraphQL for Experience Cloud integrations.

**Human URL:** https://developer.salesforce.com/docs/atlas.en-us.graphql.meta/graphql/

#### Properties
- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.graphql.meta/graphql/)
- [OpenAPI](openapi/salesforce-experience-cloud-graphql-openapi.yml)

---

### Experience Cloud Templates API
Retrieve and manage Experience Cloud site templates.

**Human URL:** https://developer.salesforce.com/docs/atlas.en-us.exp_cloud_apis.meta/exp_cloud_apis/

#### Properties
- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.exp_cloud_apis.meta/exp_cloud_apis/)
- [OpenAPI](openapi/salesforce-experience-cloud-templates-openapi.yml)

---

### User Interface API
Access record data and layouts for building custom user interfaces.

**Human URL:** https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/ui_api_get_started.htm

#### Properties
- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/ui_api_get_started.htm)
- [OpenAPI](openapi/salesforce-experience-cloud-user-interface-openapi.yml)

---

## Capabilities

### Shared Definitions

| File | Description |
|------|-------------|
| [capabilities/shared/sites-api.yaml](capabilities/shared/sites-api.yaml) | Shared definition for Experience Cloud Sites API |
| [capabilities/shared/cms-connect-api.yaml](capabilities/shared/cms-connect-api.yaml) | Shared definition for CMS Connect API |
| [capabilities/shared/connect-communities-api.yaml](capabilities/shared/connect-communities-api.yaml) | Shared definition for Connect REST API (Communities) |
| [capabilities/shared/rest-api.yaml](capabilities/shared/rest-api.yaml) | Shared definition for Salesforce REST API |
| [capabilities/shared/cms-delivery-api.yaml](capabilities/shared/cms-delivery-api.yaml) | Shared definition for CMS Delivery API |
| [capabilities/shared/cms-managed-content-api.yaml](capabilities/shared/cms-managed-content-api.yaml) | Shared definition for CMS Managed Content API |
| [capabilities/shared/templates-api.yaml](capabilities/shared/templates-api.yaml) | Shared definition for Experience Cloud Templates API |
| [capabilities/shared/graphql-api.yaml](capabilities/shared/graphql-api.yaml) | Shared definition for Salesforce GraphQL API |
| [capabilities/shared/user-interface-api.yaml](capabilities/shared/user-interface-api.yaml) | Shared definition for Salesforce User Interface API |

### Workflow Capabilities

| File | Description | APIs |
|------|-------------|------|
| [capabilities/site-management.yaml](capabilities/site-management.yaml) | Site and CMS content management | Sites API, CMS Connect API |
| [capabilities/community-engagement.yaml](capabilities/community-engagement.yaml) | Community engagement and content delivery | Connect Communities, CMS Connect API |

## Artifacts

| Artifact | Path |
|----------|------|
| OpenAPI (Sites) | [openapi/salesforce-experience-cloud-sites-openapi.yml](openapi/salesforce-experience-cloud-sites-openapi.yml) |
| OpenAPI (Connect Communities) | [openapi/salesforce-experience-cloud-connect-communities-openapi.yml](openapi/salesforce-experience-cloud-connect-communities-openapi.yml) |
| OpenAPI (CMS Connect) | [openapi/salesforce-experience-cloud-cms-connect-openapi.yml](openapi/salesforce-experience-cloud-cms-connect-openapi.yml) |
| OpenAPI (REST API) | [openapi/salesforce-experience-cloud-rest-api-openapi.yml](openapi/salesforce-experience-cloud-rest-api-openapi.yml) |
| OpenAPI (CMS Delivery) | [openapi/salesforce-experience-cloud-cms-delivery-openapi.yml](openapi/salesforce-experience-cloud-cms-delivery-openapi.yml) |
| OpenAPI (CMS Managed Content) | [openapi/salesforce-experience-cloud-cms-managed-content-openapi.yml](openapi/salesforce-experience-cloud-cms-managed-content-openapi.yml) |
| OpenAPI (GraphQL) | [openapi/salesforce-experience-cloud-graphql-openapi.yml](openapi/salesforce-experience-cloud-graphql-openapi.yml) |
| OpenAPI (Templates) | [openapi/salesforce-experience-cloud-templates-openapi.yml](openapi/salesforce-experience-cloud-templates-openapi.yml) |
| OpenAPI (User Interface) | [openapi/salesforce-experience-cloud-user-interface-openapi.yml](openapi/salesforce-experience-cloud-user-interface-openapi.yml) |
| JSON Schema (Site) | [json-schema/salesforce-experience-cloud-site-schema.json](json-schema/salesforce-experience-cloud-site-schema.json) |
| JSON Schema (Managed Content) | [json-schema/salesforce-experience-cloud-managed-content-schema.json](json-schema/salesforce-experience-cloud-managed-content-schema.json) |
| JSON Schema (Feed Element) | [json-schema/salesforce-experience-cloud-feed-element-schema.json](json-schema/salesforce-experience-cloud-feed-element-schema.json) |
| JSON Schema (Community User) | [json-schema/salesforce-experience-cloud-community-user-schema.json](json-schema/salesforce-experience-cloud-community-user-schema.json) |
| JSON Schema (CMS Channel) | [json-schema/salesforce-experience-cloud-cms-channel-schema.json](json-schema/salesforce-experience-cloud-cms-channel-schema.json) |
| JSON Schema (SObject Record) | [json-schema/salesforce-experience-cloud-sobject-record-schema.json](json-schema/salesforce-experience-cloud-sobject-record-schema.json) |
| JSON-LD Context | [json-ld/salesforce-experience-cloud-context.jsonld](json-ld/salesforce-experience-cloud-context.jsonld) |
| JSON Structure | [json-structure/salesforce-experience-cloud-structure.json](json-structure/salesforce-experience-cloud-structure.json) |
| Spectral Rules | [rules/salesforce-experience-cloud-rules.yml](rules/salesforce-experience-cloud-rules.yml) |
| Vocabulary | [vocabulary/salesforce-experience-cloud-vocabulary.yml](vocabulary/salesforce-experience-cloud-vocabulary.yml) |

## Examples

- [Create Experience Cloud Site](examples/salesforce-experience-cloud-create-site-example.json)
- [Create CMS Content](examples/salesforce-experience-cloud-cms-content-example.json)

## Common Properties

- [Developer Portal](https://developer.salesforce.com/)
- [Documentation](https://developer.salesforce.com/docs)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm)
- [Trailhead](https://trailhead.salesforce.com/)
- [Postman Collection](https://www.postman.com/salesforce-developers/workspace/salesforce-developers)
- [Status](https://status.salesforce.com/)
- [Support](https://help.salesforce.com/)
- [Terms of Service](https://www.salesforce.com/company/legal/sfdc-website-terms-of-service/)
- [Privacy Policy](https://www.salesforce.com/company/privacy/full_privacy/)
- [GitHub Organization](https://github.com/salesforce)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
