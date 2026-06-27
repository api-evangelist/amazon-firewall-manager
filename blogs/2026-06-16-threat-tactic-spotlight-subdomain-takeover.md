---
title: "Threat tactic spotlight: Subdomain takeover"
url: "https://aws.amazon.com/blogs/security/threat-tactic-spotlight-subdomain-takeover/"
date: "2026-06-16"
author: "Matt Gurr"
feed_url: "https://aws.amazon.com/blogs/security/feed/"
---
This guide explains subdomain takeover attacks where threat actors exploit dangling DNS records pointing to deleted resources. It details how CNAME records targeting S3 buckets, CloudFront distributions, or Elastic Beanstalk environments become vulnerabilities when underlying resources are removed but DNS records persist, and provides detection using AWS Config custom rules, prevention through proper deprovisioning workflows, and remediation including automated notifications and Security Hub integration.
