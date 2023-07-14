---
title: Cloud Security Management
kind: documentation
aliases:
  - /security_platform/cloud_security_management/
further_reading:
  - link: "https://app.datadoghq.com/release-notes?category=Security%20%26%20Compliance"
    tag: "Release Notes"
    text: "See What's New in Datadog Security Compliance"
  - link: "/security/cspm/setup"
    tag: "Documentation"
    text: "Start tracking misconfigurations with Cloud Security Posture Management"
  - link: "/security/cloud_workload_security/setup"
    tag: "Documentation"
    text: "Uncover kernel-level threats with Cloud Workload Security"
  - link: "https://www.datadoghq.com/blog/cyber-attack-simulation-with-stratus-red-team/"
    tag: "Blog"
    text: "Elevate AWS threat detection with Stratus Red Team"
  - link: "https://www.datadoghq.com/blog/kubernetes-security-best-practices/"
    tag: "Blog"
    text: "Best practices for securing Kubernetes applications"
  - link: "https://www.datadoghq.com/blog/security-context-with-datadog-cloud-security-management/"
    tag: "Blog"
    text: "Add security context to observability data with Datadog Cloud Security Management"
  - link: "https://www.datadoghq.com/blog/security-labs-ruleset-launch/"
    tag: "Blog"
    text: "Fix common cloud security risks with the Datadog Security Labs Ruleset"
  - link: "https://www.datadoghq.com/blog/securing-cloud-native-applications/"
    tag: "Blog"
    text: "Best practices for application security in cloud-native environments"
  - link: "https://www.datadoghq.com/blog/custom-detection-rules-with-datadog-cloud-security-management/"
    tag: "Blog"
    text: "Customize rules for detecting cloud misconfigurations with Datadog Cloud Security Management"
---

Datadog Cloud Security Management (CSM) delivers real-time threat detection and continuous configuration audits across your entire cloud infrastructure, all in a unified view for seamless collaboration and faster remediation. Powered by observability data, security teams can determine the impact of a threat quickly by tracing the full attack flow and identify the resource owner where a vulnerability was triggered.

CSM includes:

- [**Threats**][1]: Monitors file and process activity across your environment to detect threats to your infrastructure, like AWS EC2 instances, and workloads, like Kubernetes clusters, in real time at the kernel level. Cloud Workload Security uses the unified Datadog Agent, so if you're already using Datadog to monitor your environment, there's no need to provision additional resources.
- [**Misconfigurations**][2]: Tracks the security hygiene and compliance posture of your production environment, can automate audit evidence collection, and catch misconfigurations that leave your organization vulnerable to attacks. See security posture scores across your infrastructure and trace each score back to the applicable benchmark or framework criteria.
- **Vulnerabilities**: 
- **Identities**:

{{< img src="security/csm_overview.png" alt="Cloud Security Management in Datadog" width="100%">}}

To get started with CSM, navigate to the [**Security** > **Setup**][3] section in Datadog, which has detailed information for single or multi-configuration, or follow the getting started sections to learn more about each area of the platform.

Important issues

Dashboards

Explorers

## Further reading

{{< partial name="whats-next/whats-next.html" >}}

[1]: /security/cloud_workload_security/
[2]: /security/cspm/
[3]: https://app.datadoghq.com/security/configuration
