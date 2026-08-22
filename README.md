# Salesforce Experience Cloud (salesforce-experience-cloud)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

APIs for building and managing Salesforce Experience Cloud sites, communities, and digital experiences including content management, theming, navigation, and Lightning Web Runtime powered portals.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/salesforce-experience-cloud/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/salesforce-experience-cloud/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- CMS
- Communities
- CRM
- Customer Portal
- Digital Experience
- Experience Cloud
- Partner Portal

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Experience Cloud Sites API

Manage Experience Cloud sites, themes, and configurations. Provides programmatic access to create, update, and retrieve site settings, branding, and navigation for digital experience portals.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.exp_cloud_apis.meta/exp_cloud_apis/](https://developer.salesforce.com/docs/atlas.en-us.exp_cloud_apis.meta/exp_cloud_apis/)
- **Base URL:** `https://yourInstance.salesforce.com/services/data/v59.0`

#### Tags

- CMS
- Communities
- Configuration
- Digital Experiences
- Sites

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.exp_cloud_apis.meta/exp_cloud_apis/)
- [OpenAPI](openapi/salesforce-experience-cloud-sites-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salesforce-experience-cloud-sites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-sites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.communities_dev.meta/communities_dev/communities_dev_intro_before.htm)

### Connect REST API (Communities)

Access community data, feeds, topics, and user engagement features. The Connect REST API provides endpoints for social collaboration, content sharing, and community management within Experience Cloud sites.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/)
- **Base URL:** `https://yourInstance.salesforce.com/services/data/v59.0/connect`

#### Tags

- Chatter
- Communities
- Feeds
- Social
- Topics

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/)
- [OpenAPI](openapi/salesforce-experience-cloud-connect-communities-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salesforce-experience-cloud-connect-communities.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-connect-communities.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman  Collection](https://www.postman.com/salesforce-developers/workspace/salesforce-developers)
- [Reference](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/features_communities.htm)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/quickstart_dev_org.htm)

### CMS Connect API

Manage content, channels, and media in Experience Cloud CMS. Supports creating, updating, and delivering managed content across channels for headless content delivery and site publishing.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_cms.htm](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_cms.htm)
- **Base URL:** `https://yourInstance.salesforce.com/services/data/v59.0/connect/cms`

#### Tags

- Channels
- CMS
- Content
- Media
- Publishing

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_cms.htm)
- [OpenAPI](openapi/salesforce-experience-cloud-cms-connect-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salesforce-experience-cloud-cms-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-cms-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Reference](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_cms_content.htm)
- [Getting Started](https://developer.salesforce.com/docs/platform/cms/guide/cms-developer-guide.html)

### Salesforce REST API

Core REST API for accessing Salesforce objects and data. Provides CRUD operations on standard and custom objects, query execution, and metadata access used as the foundation for Experience Cloud data integrations.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/)
- **Base URL:** `https://yourInstance.salesforce.com/services/data/v59.0`

#### Tags

- CRUD
- Data
- Objects
- Platform
- REST

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/)
- [OpenAPI](openapi/salesforce-experience-cloud-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salesforce-experience-cloud-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman  Collection](https://www.postman.com/salesforce-developers/workspace/salesforce-developers)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm)

### Experience Cloud Templates API

Retrieve and manage Experience Cloud site templates including Build Your Own and Microsite LWR templates. Supports programmatic theme and branding configuration for digital experience portals.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.exp_cloud_apis.meta/exp_cloud_apis/](https://developer.salesforce.com/docs/atlas.en-us.exp_cloud_apis.meta/exp_cloud_apis/)
- **Base URL:** `https://yourInstance.salesforce.com/services/data/v59.0`

#### Tags

- Branding
- Design
- LWR
- Templates
- Themes

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.exp_cloud_apis.meta/exp_cloud_apis/)
- [OpenAPI](openapi/salesforce-experience-cloud-templates-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salesforce-experience-cloud-templates.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-templates.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.exp_cloud_lwr.meta/exp_cloud_lwr/template_overview.htm)

### GraphQL API

Query Salesforce data using GraphQL for Experience Cloud. Offers a flexible query language for retrieving exactly the data needed, reducing over-fetching and improving performance for digital experiences.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.graphql.meta/graphql/](https://developer.salesforce.com/docs/atlas.en-us.graphql.meta/graphql/)
- **Base URL:** `https://yourInstance.salesforce.com/services/data/v59.0/graphql`

#### Tags

- Data
- GraphQL
- Performance
- Query

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.graphql.meta/graphql/)
- [OpenAPI](openapi/salesforce-experience-cloud-graphql-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salesforce-experience-cloud-graphql.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-graphql.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Schema](https://developer.salesforce.com/docs/atlas.en-us.graphql.meta/graphql/graphql_schema.htm)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.graphql.meta/graphql/)

### CMS Managed Content API

Retrieve and search published managed content versions for Experience Cloud sites. Provides endpoints for querying managed content delivery channels and searching content across workspaces.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_managed_content_resources.htm](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_managed_content_resources.htm)
- **Base URL:** `https://yourInstance.salesforce.com/services/data/v59.0/connect/cms/delivery`

#### Tags

- Channels
- Content Management
- Delivery
- Headless CMS
- Managed Content

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_managed_content_resources.htm)
- [OpenAPI](openapi/salesforce-experience-cloud-cms-managed-content-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salesforce-experience-cloud-cms-managed-content.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-cms-managed-content.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Reference](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_managed_content_enhanced_resources.htm)
- [Getting Started](https://developer.salesforce.com/docs/platform/cms/guide/cms-dev-retrieve-cms-content-with-a-connected-app.html)

### CMS Delivery API

Delivers CMS content to external applications and headless frontends. Enables content retrieval by channel, content type, and content key for building decoupled digital experiences.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_cms_delivery_content.htm](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_cms_delivery_content.htm)
- **Base URL:** `https://yourInstance.salesforce.com/services/data/v59.0/connect/cms/delivery`

#### Tags

- Channels
- CMS
- Content Delivery
- Headless

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_cms_delivery_content.htm)
- [OpenAPI](openapi/salesforce-experience-cloud-cms-delivery-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salesforce-experience-cloud-cms-delivery.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-cms-delivery.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Reference](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_cms_contents.htm)

### User Interface API

Access record data, layouts, list views, and navigation items for building custom user interfaces. Powers Lightning web components in Experience Cloud sites with metadata-driven UI rendering.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/ui_api_get_started.htm](https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/ui_api_get_started.htm)
- **Base URL:** `https://yourInstance.salesforce.com/services/data/v59.0/ui-api`

#### Tags

- Layouts
- Lightning
- Navigation
- Records
- User Interface

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/ui_api_get_started.htm)
- [OpenAPI](openapi/salesforce-experience-cloud-user-interface-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salesforce-experience-cloud-user-interface.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-user-interface.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Reference](https://developer.salesforce.com/docs/atlas.en-us.exp_cloud_lwr.meta/exp_cloud_lwr/get_started_comp_api.htm)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/ui_api_get_started.htm)

### Metadata API (Experience Cloud)

Deploy and retrieve Experience Cloud site configurations, navigation menus, and digital experience bundles. Enables programmatic management of ExperienceBundle and Network metadata types for CI/CD workflows.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/meta_experiencebundle.htm](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/meta_experiencebundle.htm)
- **Base URL:** `https://yourInstance.salesforce.com/services/Soap/m/59.0`

#### Tags

- CI/CD
- Configuration
- Deployment
- DevOps
- Metadata

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/meta_intro.htm)
- [Reference](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/meta_experiencebundle.htm)
- [Reference](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/meta_digitalexperiencebundle.htm)
- [Reference](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/meta_network.htm)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/meta_types_list.htm)
- [Postman Collection](collections/salesforce-experience-cloud-cms-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-cms-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-experience-cloud-cms-delivery.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-cms-delivery.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-experience-cloud-cms-managed-content.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-cms-managed-content.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-experience-cloud-connect-communities.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-connect-communities.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-experience-cloud-graphql.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-graphql.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-experience-cloud-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-experience-cloud-sites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-sites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-experience-cloud-templates.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-templates.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-experience-cloud-user-interface.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-user-interface.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LWR Sites API

Build and customize Lightning Web Runtime sites for Experience Cloud. Provides documentation for creating LWR-based digital experiences with custom components, page layouts, and theme configurations.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.exp_cloud_lwr.meta/exp_cloud_lwr/intro.htm](https://developer.salesforce.com/docs/atlas.en-us.exp_cloud_lwr.meta/exp_cloud_lwr/intro.htm)
- **Base URL:** `https://yourInstance.salesforce.com/services/data/v59.0`

#### Tags

- Components
- Lightning Web Runtime
- LWR
- Performance
- Sites

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.exp_cloud_lwr.meta/exp_cloud_lwr/intro.htm)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.exp_cloud_lwr.meta/exp_cloud_lwr/get_started.htm)
- [Reference](https://developer.salesforce.com/docs/atlas.en-us.exp_cloud_lwr.meta/exp_cloud_lwr/get_started_navigation.htm)
- [Postman Collection](collections/salesforce-experience-cloud-cms-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-cms-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-experience-cloud-cms-delivery.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-cms-delivery.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-experience-cloud-cms-managed-content.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-cms-managed-content.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-experience-cloud-connect-communities.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-connect-communities.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-experience-cloud-graphql.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-graphql.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-experience-cloud-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-experience-cloud-sites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-sites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-experience-cloud-templates.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-templates.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-experience-cloud-user-interface.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-experience-cloud-user-interface.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/showcase/salesforce-experience-cloud)
- [Portal](https://developer.salesforce.com/)
- [Documentation](https://developer.salesforce.com/docs)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.communities_dev.meta/communities_dev/communities_dev_intro_before.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm)
- [Blog](https://developer.salesforce.com/blogs)
- [Changelog](https://developer.salesforce.com/blogs/2026/01/developers-guide-to-the-spring-26-release)
- [Status Page](https://status.salesforce.com/)
- [Support](https://help.salesforce.com/)
- [Terms of Service](https://www.salesforce.com/company/legal/sfdc-website-terms-of-service/)
- [Privacy Policy](https://www.salesforce.com/company/privacy/full_privacy/)
- [GitHub Organization](https://github.com/salesforce)
- [Community](https://trailhead.salesforce.com/trailblazer-community/topics/salesforcedeveloper)
- [Website](https://www.salesforce.com/products/experience-cloud/overview/)
- [Login](https://login.salesforce.com/)
- [Sign Up](https://developer.salesforce.com/signup)
- [Rate Limits](https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/)
- [S D Ks](https://developer.salesforce.com/developer-centers/lightning-web-components)
- [Trailhead  Learning](https://trailhead.salesforce.com/)
- [Postman  Collection](https://www.postman.com/salesforce-developers/workspace/salesforce-developers)
- [A P I  Library](https://developer.salesforce.com/docs/apis)
- [Developer  Center](https://developer.salesforce.com/developer-centers/experience-cloud)
- [J S O N- L D  Context](json-ld/salesforce-experience-cloud-context.jsonld)
- [J S O N  Schema](json-schema/salesforce-experience-cloud-site-schema.json)
- [J S O N  Schema](json-schema/salesforce-experience-cloud-managed-content-schema.json)
- [J S O N  Schema](json-schema/salesforce-experience-cloud-feed-element-schema.json)
- [J S O N  Schema](json-schema/salesforce-experience-cloud-community-user-schema.json)
- [J S O N  Schema](json-schema/salesforce-experience-cloud-cms-channel-schema.json)
- [J S O N  Schema](json-schema/salesforce-experience-cloud-sobject-record-schema.json)
- [Spectral Rules](rules/salesforce-experience-cloud-rules.yml)
- [Capabilities](capabilities/site-management.yaml)
- [Capabilities](capabilities/community-engagement.yaml)
- [JSON Structure](json-structure/salesforce-experience-cloud-structure.json)
- [Vocabulary](vocabulary/salesforce-experience-cloud-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
