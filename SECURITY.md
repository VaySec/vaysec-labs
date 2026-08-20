# Security Policy

## Purpose

This repository contains publicly available cybersecurity labs, examples, scripts, configurations, and documentation published by VaySec for educational and professional development purposes.

The labs are intended to be used only in environments that you own or are explicitly authorised to test.

## Reporting a Security Issue

If you discover a security issue in this repository, please do not disclose sensitive details in a public GitHub issue.

Instead, report the issue privately to the repository maintainer.

When reporting an issue, please include:

* A description of the issue
* The affected file, lab, or component
* Steps to reproduce the issue, where appropriate
* Potential security impact
* Any suggested remediation

## Secrets and Sensitive Information

Do not commit any of the following to this repository:

* Passwords
* API keys
* Access tokens
* Client secrets
* Private keys
* Certificates containing private material
* Cloud credentials
* Tenant-specific secrets
* Personally identifiable information (PII)
* Customer or production data
* Confidential organisational information

Use placeholders or example values instead, such as:

```text
<YOUR-TENANT-ID>
<YOUR-CLIENT-ID>
<YOUR-CLIENT-SECRET>
<YOUR-SUBSCRIPTION-ID>
<YOUR-USER-UPN>
```

The `.gitignore` file provides basic protection against accidentally committing common secret and temporary files, but it should not be considered a security control.

## Lab Environment

Before running a lab, verify that you are working in an environment where you have appropriate authorisation.

Do not use these labs to:

* Access systems without permission
* Test third-party systems without authorisation
* Circumvent security controls
* Obtain or expose credentials
* Access or disclose another person's data
* Conduct unauthorised security testing

Where a lab involves potentially sensitive security functionality, use a dedicated test or lab environment.

## Sample Data

Sample data included in this repository should be synthetic or otherwise suitable for public distribution.

Do not replace sample data with real customer, employee, production, or other confidential information before publishing or sharing the repository.

## Responsible Disclosure

VaySec supports responsible disclosure of security vulnerabilities.

Please allow reasonable time for a reported issue to be investigated and addressed before publicly disclosing details that could create security risk.

## Scope

This security policy applies to the contents of this repository and its associated lab materials.

It does not grant permission to test or access any third-party service, Microsoft tenant, cloud environment, application, or infrastructure referenced by a lab.

## Disclaimer

The labs are provided for educational and authorised testing purposes. VaySec does not provide permission to use the materials against systems or environments for which you do not have explicit authorisation.

Users are responsible for ensuring that their use of the lab materials complies with applicable laws, regulations, contractual obligations, and the terms of the services being tested.
