# Amazon Firewall Manager (amazon-firewall-manager)

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

AWS Firewall Manager is a security management service that allows you to centrally configure and manage firewall rules across your accounts and applications in AWS Organizations. It makes it easier to bring new applications and resources into compliance with security policies.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/amazon-firewall-manager/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/amazon-firewall-manager/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- AWS
- Compliance
- Firewall
- Network Security
- Security

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### AWS Firewall Manager API

The AWS Firewall Manager API provides programmatic access to create and manage security policies, compliance status, and protection configurations for AWS WAF, Shield, and VPC security groups across your organization.

- **Human URL:** [https://aws.amazon.com/firewall-manager/](https://aws.amazon.com/firewall-manager/)
- **Base URL:** `https://fms.amazonaws.com`

#### Tags

- Firewall Management
- Network Security
- Security

#### Properties

- [Documentation](https://docs.aws.amazon.com/fms/latest/APIReference/Welcome.html)
- [OpenAPI](openapi/amazon-firewall-manager-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amazon-firewall-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amazon-firewall-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/amazon-firewall-manager-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-firewall-manager-compliance-violator-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-firewall-manager-resource-set-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-firewall-manager-security-service-policy-data-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-firewall-manager-tag-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/amazon-firewall-manager-policy-structure.json)
- [JSON Structure](json-structure/amazon-firewall-manager-compliance-violator-structure.json)
- [JSON Structure](json-structure/amazon-firewall-manager-resource-set-structure.json)
- [JSON Structure](json-structure/amazon-firewall-manager-security-service-policy-data-structure.json)
- [JSON Structure](json-structure/amazon-firewall-manager-tag-structure.json)
- [Example](examples/amazon-firewall-manager-policy-example.json)
- [Example](examples/amazon-firewall-manager-compliance-violator-example.json)
- [Example](examples/amazon-firewall-manager-resource-set-example.json)
- [Example](examples/amazon-firewall-manager-security-service-policy-data-example.json)
- [Example](examples/amazon-firewall-manager-tag-example.json)
- [Getting Started](https://aws.amazon.com/firewall-manager/getting-started/)
- [Pricing](https://aws.amazon.com/firewall-manager/pricing/)
- [F A Q](https://aws.amazon.com/firewall-manager/faqs/)
- [API Reference](https://docs.aws.amazon.com/fms/latest/APIReference/Welcome.html)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://aws.amazon.com/firewall-manager/)
- [Website](https://aws.amazon.com/firewall-manager/)
- [Documentation](https://docs.aws.amazon.com/waf/latest/developerguide/fms-chapter.html)
- [Terms of Service](https://aws.amazon.com/service-terms/)
- [Privacy Policy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/security/)
- [GitHub Organization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/wafv2/fmsv2/)
- [Sign Up](https://portal.aws.amazon.com/billing/signup)
- [Status Page](https://health.aws.amazon.com/health/status)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/aws-firewall-manager)
- [Spectral Rules](rules/amazon-firewall-manager-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-firewall-manager-vocabulary.yaml)
- [JSON-LD](json-ld/amazon-firewall-manager-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://aws.amazon.com/marketplace)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
