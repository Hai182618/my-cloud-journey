
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

This reduces context-switching and improves productivity for engineers and DevOps professionals. Amazon Q Developer plugins help consolidate operational information into **a single interface**.

---

## How Q Developer Plugins Work

Amazon Q Developer uses the prefix in your query (`@datadog`, `@wiz`) to route requests to the appropriate plugin. The process includes:

1. **Intent Recognition**  
2. **API Invocation** (no AWS context or prompt data is sent externally)  
3. **Response Generation**  
4. **Guardrails** to ensure safety and best practices  

This enables Q Developer to understand your request and provide accurate operational insights.

---

# Amazon Q Developer Plugin for Datadog

Datadog provides real-time observability. With **@datadog**, you can query monitoring data directly inside AWS Console.

---

## Using Datadog APM on EC2

Example query:  
`@datadog how do I use APM on my EC2 instance?`

{{< figure src="/images/blog3/Datadog-APM-1.gif" caption="Using Q Developer to ask about Datadog APM on EC2." >}}

---

## Retrieve & Summarize Cases and Monitors

{{< figure src="/images/blog3/Datadog-Cases-1.gif" caption="Listing all Datadog cases." >}}

{{< figure src="/images/blog3/Datadog-Top-Cases-1.gif" caption="Summarizing top Datadog cases." >}}

---

## Check & List Alarmed Monitors

{{< figure src="/images/blog3/Datadog-Monitors-1.gif" caption="Listing all Datadog monitors." >}}

{{< figure src="/images/blog3/Datadog-Alarms-1.gif" caption="No active alarms detected." >}}

---

# Amazon Q Developer Plugin for Wiz

Wiz enables cloud security posture management and risk analysis. Using **@wiz**, you can inspect vulnerabilities, severity levels, and resource security posture.

---

## View Critical Severity Issues

{{< figure src="/images/blog3/Wiz-top-5-critical-res-1.gif" caption="Critical issues detected by Wiz." >}}

---

## Identify High-Risk Resources

{{< figure src="/images/blog3/Wiz-critical-resources-1.gif" caption="High-risk resources identified by Wiz." >}}

---

## List Issues by Property

{{< figure src="/images/blog3/Wiz-due-next-1.gif" caption="Upcoming due issues." >}}

{{< figure src="/images/blog3/Wiz-due-soon-1.gif" caption="Recently created issues." >}}

---

# Getting Started

To enable third‑party plugins in Amazon Q Developer:

1. Subscribe to **Amazon Q Developer Pro Tier**  
2. Create an **Amazon Q Administrator Role/User**  
3. Open the **Plugins** tab in Amazon Q Developer Console  
4. Provide Datadog and Wiz credentials (stored in AWS Secrets Manager)

{{< figure src="/images/blog3/Q-Dev-Dashboard.png" caption="Amazon Q Developer dashboard showing Plugins section." >}}

---

## Configure Datadog Plugin

{{< figure src="/images/blog3/Datadog-Plugin.png" caption="Datadog plugin configuration screen." >}}

{{< figure src="/images/blog3/Datadog-integration.png" caption="Datadog API configuration page." >}}

---

## Configure Wiz Plugin

{{< figure src="/images/blog3/Wiz-Plugin.png" caption="Wiz plugin configuration screen." >}}

{{< figure src="/images/blog3/Wiz-Integration.png" caption="Wiz credentials: Client ID, Secret, and Endpoint." >}}

---

# Querying the Plugins

You can run these queries directly inside Amazon Q:

````txt
@datadog list my current monitors
@wiz list the issues with critical severity
@datadog summarize my top cases
@wiz what issues are due next?
````

These queries allow you to quickly gather alert information, incidents, risk levels, and security posture insights.

---

# Conclusion

Amazon Q Developer plugins for Datadog and Wiz provide engineers with visibility and security insights without switching tools. By centralizing operational information, these plugins greatly enhance troubleshooting efficiency and overall productivity.

---

{{< figure src="/images/blog3/Profile_pic.jpg" caption="Author: Shardul Vaidya" >}}
