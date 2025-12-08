
---
title: "Blog 3"
date: "2024-11-13"
weight: 3
chapter: false
pre: "<b> 3.3. </b>"
---

# Amazon Q Developer Plugins Now Generally Available for the AWS Management Console

Today, Amazon Web Services (AWS) announced the launch and general availability of **Amazon Q Developer plugins** for **Datadog** and **Wiz** in the AWS Management Console. With these plugins, customers can query Datadog and Wiz directly inside Amazon Q using natural language prompts such as:

- `@datadog do I have any active alerts?`
- `@wiz what are my top 3 security issues today?`

This reduces context-switching and improves productivity for engineers and DevOps professionals. Engineers frequently struggle with *tool sprawl*, and Amazon Q Developer plugins aim to create a **single pane of glass** for unified operational insight.

---

## How Q Developer Plugins Work

Amazon Q Developer uses the prefix in your query (`@datadog`, `@wiz`) to route requests to the correct plugin. The workflow includes:

1. **Intent Recognition**
2. **API Invocation** (no AWS context or prompt data is sent externally)
3. **Response Generation**
4. **Guardrails** to ensure safety and best practices

This enables Q Developer to understand your intent and provide accurate operational insights.

---

# Amazon Q Developer Plugin for Datadog

Datadog offers real-time observability for cloud applications. Using **@datadog**, you can fetch monitoring data directly from inside the AWS console.

---

## Learn to Use Datadog APM in Workloads

Example query:  
`@datadog how do I use APM on my EC2 instance?`

{{< figure src="/images/blog3/Datadog-APM-1.gif" caption="Using Amazon Q Developer to ask about Datadog APM on EC2." >}}

---

## Retrieve & Summarize Cases and Monitors

{{< figure src="/images/blog3/Datadog-Cases-1.gif" caption="Listing all Datadog cases in the connected instance." >}}

{{< figure src="/images/blog3/Datadog-Top-Cases-1.gif" caption="Summarizing top Datadog cases." >}}

---

## Check & List Monitors in Alarm

{{< figure src="/images/blog3/Datadog-Monitors-1.gif" caption="All Datadog monitors listed via Amazon Q Developer." >}}

{{< figure src="/images/blog3/Datadog-Alarms-1.gif" caption="No current alarms in Datadog." >}}

---

# Amazon Q Developer Plugin for Wiz

Wiz allows organizations to manage cloud security posture and identify risks across systems. Using **@wiz**, developers can explore vulnerabilities, severity levels, and resource risk posture.

---

## View Issues With Critical Severity

{{< figure src="/images/blog3/Wiz-top-5-critical-res-1.gif" caption="Wiz plugin showing critical severity issues." >}}

---

## Find Critical Resources

{{< figure src="/images/blog3/Wiz-critical-resources-1.gif" caption="Listing critical resources detected by Wiz." >}}

---

## List Issues Based on Properties

{{< figure src="/images/blog3/Wiz-due-next-1.gif" caption="Next issues due according to Wiz." >}}

{{< figure src="/images/blog3/Wiz-due-soon-1.gif" caption="Newest issues created in the last few days." >}}

---

# Getting Started

To enable third-party plugins in Amazon Q Developer:

1. Subscribe to **Amazon Q Developer Pro Tier**
2. Ensure an **Amazon Q Administrator Role/User** exists
3. Open the **Plugins** tab in the Amazon Q Developer console
4. Provide credentials for Datadog and Wiz (stored in AWS Secrets Manager)

{{< figure src="/images/blog3/Q-Dev-Dashboard.png" caption="Amazon Q Developer dashboard showing Plugins section." >}}

---

## Configure Datadog Plugin

{{< figure src="/images/blog3/Datadog-Plugin.png" caption="Datadog plugin configuration screen." >}}

{{< figure src="/images/blog3/Datadog-integration.png" caption="Datadog settings page showing API credentials." >}}

---

## Configure Wiz Plugin

{{< figure src="/images/blog3/Wiz-Plugin.png" caption="Wiz plugin configuration screen within Amazon Q Developer." >}}

{{< figure src="/images/blog3/Wiz-Integration.png" caption="Wiz settings showing Client ID, Secret, and API Endpoint." >}}

---

# Querying the Plugins

Here are example queries you can perform directly inside Amazon Q:

````txt
@datadog list my current monitors
@wiz list the issues with critical severity
@datadog summarize my top cases
@wiz what issues are due next?
````

These queries allow operators to quickly gather events, alerts, risk posture, severity levels, and other operational intelligence across third-party systems.

---

# Conclusion

Amazon Q Developer plugins for Datadog and Wiz help engineers understand infrastructure and security posture without switching tools. By unifying insights into a single interface, these plugins significantly improve **productivity**, **incident management**, and **operational efficiency**.

---

{{< figure src="/images/blog3/Profile_pic.jpg" caption="Author: Shardul Vaidya" >}}
