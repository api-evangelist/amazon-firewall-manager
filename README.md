# Amazon Firewall Manager (amazon-firewall-manager)

AWS Firewall Manager is a security management service that allows you to centrally configure and manage firewall rules across your accounts and applications in AWS Organizations. It makes it easier to bring new applications and resources into compliance with security policies.

**URL:** [https://raw.githubusercontent.com/api-evangelist/amazon-firewall-manager/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/amazon-firewall-manager/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Compliance, Firewall, Network Security, Security

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### AWS Firewall Manager API
The AWS Firewall Manager API provides programmatic access to create and manage security policies, compliance status, and protection configurations for AWS WAF, Shield, and VPC security groups across your organization.

**Human URL:** [https://aws.amazon.com/firewall-manager/](https://aws.amazon.com/firewall-manager/)

#### Tags:

 - Firewall Management, Network Security, Security

#### Properties

- [Documentation](https://docs.aws.amazon.com/fms/latest/APIReference/Welcome.html)
- [OpenAPI](openapi/amazon-firewall-manager-openapi.yml)
- [JSONSchema](json-schema/amazon-firewall-manager-policy-schema.json)
- [JSONSchema](json-schema/amazon-firewall-manager-compliance-violator-schema.json)
- [JSONSchema](json-schema/amazon-firewall-manager-resource-set-schema.json)
- [JSONSchema](json-schema/amazon-firewall-manager-security-service-policy-data-schema.json)
- [JSONSchema](json-schema/amazon-firewall-manager-tag-schema.json)
- [JSONStructure](json-structure/amazon-firewall-manager-policy-structure.json)
- [JSONStructure](json-structure/amazon-firewall-manager-compliance-violator-structure.json)
- [JSONStructure](json-structure/amazon-firewall-manager-resource-set-structure.json)
- [JSONStructure](json-structure/amazon-firewall-manager-security-service-policy-data-structure.json)
- [JSONStructure](json-structure/amazon-firewall-manager-tag-structure.json)
- [Example](examples/amazon-firewall-manager-policy-example.json)
- [Example](examples/amazon-firewall-manager-compliance-violator-example.json)
- [Example](examples/amazon-firewall-manager-resource-set-example.json)
- [Example](examples/amazon-firewall-manager-security-service-policy-data-example.json)
- [Example](examples/amazon-firewall-manager-tag-example.json)
- [GettingStarted](https://aws.amazon.com/firewall-manager/getting-started/)
- [Pricing](https://aws.amazon.com/firewall-manager/pricing/)
- [FAQ](https://aws.amazon.com/firewall-manager/faqs/)
- [APIReference](https://docs.aws.amazon.com/fms/latest/APIReference/Welcome.html)

## Common Properties

- [Portal](https://aws.amazon.com/firewall-manager/)
- [Website](https://aws.amazon.com/firewall-manager/)
- [Documentation](https://docs.aws.amazon.com/waf/latest/developerguide/fms-chapter.html)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/security/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/wafv2/fmsv2/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/aws-firewall-manager)
- [SpectralRules](rules/amazon-firewall-manager-spectral-rules.yml)
- [NaftikoCapability](capabilities/shared/firewall-manager.yaml)
- [NaftikoCapability](capabilities/amazon-firewall-manager-security-governance.yaml)
- [Vocabulary](vocabulary/amazon-firewall-manager-vocabulary.yaml)
- [JSON-LD](json-ld/amazon-firewall-manager-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Centralized Policy Management | Define and enforce WAF, Shield Advanced, Network Firewall, and security group policies from a single pane of glass across all AWS accounts. |
| Automatic Remediation | Automatically remediate non-compliant resources so that new accounts and resources are always protected. |
| Multi-Account Support | Manage security policies across hundreds of AWS accounts within an AWS Organization. |
| Compliance Visibility | View policy compliance status per account and resource with detailed violation reports. |
| Resource Sets | Group AWS resources by type for targeted policy application and management. |
| Tag-Based Targeting | Apply policies to resources based on AWS resource tags for fine-grained scope control. |
| Third-Party Firewall Support | Deploy and manage third-party firewall appliances through AWS Marketplace with Firewall Manager. |

## Use Cases

| Name | Description |
|------|-------------|
| WAF Rule Standardization | Enforce standard WAF rule sets across all CloudFront distributions and ALBs organization-wide. |
| DDoS Protection Baseline | Mandate Shield Advanced protection for all internet-facing resources across accounts. |
| Security Group Governance | Audit and remediate overly permissive security group rules across EC2 and VPC resources. |
| Network Firewall Deployment | Deploy and manage AWS Network Firewall across VPCs in multiple accounts from a central policy. |
| Compliance Reporting | Monitor and report on firewall policy compliance for SOC 2, PCI DSS, and regulatory requirements. |
| New Account Onboarding | Automatically apply security policies to new AWS accounts as they join the organization. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Organizations | Manage Firewall Manager policies across all accounts in the organization hierarchy. |
| AWS WAF | Centrally create and deploy WAF rule groups and web ACLs across accounts. |
| AWS Shield Advanced | Enable and manage Shield Advanced protection for all DDoS-sensitive resources. |
| AWS Network Firewall | Deploy centrally managed network firewall policies across VPCs. |
| Amazon Route 53 Resolver | Manage DNS Firewall rule groups for Route 53 Resolver across accounts. |
| Amazon CloudWatch | Monitor compliance metrics and set alarms for non-compliant resources. |
| AWS Security Hub | Send Firewall Manager compliance findings to Security Hub for centralized security posture management. |
| AWS IAM | Control who can create, modify, and view Firewall Manager policies using IAM permissions. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-firewall-manager-openapi.yml](openapi/amazon-firewall-manager-openapi.yml)

### JSON Schema

- [amazon-firewall-manager-compliance-violator-schema.json](json-schema/amazon-firewall-manager-compliance-violator-schema.json)
- [amazon-firewall-manager-policy-schema.json](json-schema/amazon-firewall-manager-policy-schema.json)
- [amazon-firewall-manager-resource-set-schema.json](json-schema/amazon-firewall-manager-resource-set-schema.json)
- [amazon-firewall-manager-security-service-policy-data-schema.json](json-schema/amazon-firewall-manager-security-service-policy-data-schema.json)
- [amazon-firewall-manager-tag-schema.json](json-schema/amazon-firewall-manager-tag-schema.json)

### JSON Structure

- [amazon-firewall-manager-compliance-violator-structure.json](json-structure/amazon-firewall-manager-compliance-violator-structure.json)
- [amazon-firewall-manager-policy-structure.json](json-structure/amazon-firewall-manager-policy-structure.json)
- [amazon-firewall-manager-resource-set-structure.json](json-structure/amazon-firewall-manager-resource-set-structure.json)
- [amazon-firewall-manager-security-service-policy-data-structure.json](json-structure/amazon-firewall-manager-security-service-policy-data-structure.json)
- [amazon-firewall-manager-tag-structure.json](json-structure/amazon-firewall-manager-tag-structure.json)

### JSON-LD

- [amazon-firewall-manager-context.jsonld](json-ld/amazon-firewall-manager-context.jsonld)

### Examples

- [amazon-firewall-manager-compliance-violator-example.json](examples/amazon-firewall-manager-compliance-violator-example.json)
- [amazon-firewall-manager-policy-example.json](examples/amazon-firewall-manager-policy-example.json)
- [amazon-firewall-manager-resource-set-example.json](examples/amazon-firewall-manager-resource-set-example.json)
- [amazon-firewall-manager-security-service-policy-data-example.json](examples/amazon-firewall-manager-security-service-policy-data-example.json)
- [amazon-firewall-manager-tag-example.json](examples/amazon-firewall-manager-tag-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [firewall-manager.yaml](capabilities/shared/firewall-manager.yaml)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [amazon-firewall-manager-security-governance.yaml](capabilities/amazon-firewall-manager-security-governance.yaml) | Amazon Firewall Manager API | — | Platform Engineers, DevOps |

## Vocabulary

- [Amazon Firewall Manager Vocabulary](vocabulary/amazon-firewall-manager-vocabulary.yaml)

## Rules

- [amazon-firewall-manager-spectral-rules.yml](rules/amazon-firewall-manager-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
