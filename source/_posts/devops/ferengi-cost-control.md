---
title: Controlling your cloud costs like a Ferengi
date: 2026-06-01 00:00:00
tags:
  - star trek
  - ferengi
  - finops
  - cloud
  - devops
  - sre
  - cost optimisation
published: true
---

## The Rules of Acquisition and the cloud.

![Ferengi monitoring cloud costs using finops](/images/devops/ferengi-cloud.png)

Most cloud cost problems are not finance problems.

They’re architecture problems, operational problems, and occasionally ego problems.

A few Ferengi Rules of Acquisition map surprisingly well to cloud cost optimisation.

## <!--more -->

Most organisations treat cloud costs as unavoidable overhead. That’s a mistake. In modern infrastructure, cloud spend is one of the few operational costs engineers can directly influence in real time. By adopting the ethos of the Ferengi and their Rules of Acquisition, DevOps and SRE engineers and leaders can transform cost optimisation from a reactive chore into a strategic driver of efficient resource utilisation.

Without further ado, here are 5 Rules of Acquisition that can save you money.

## Rule 8: Small print leads to large risk.

> "Small Print leads to large risk"

In cloud infrastructure, the "small print" lives in service level agreements (SLAs) and technical specifications. One common example is the use of burstable instance families for EC2/Virtual Machines.
Engineers frequently pivot to burstable instance types (e.g., AWS T-series) to lower monthly costs, only to face performance degradation when CPU credits expire.
I ran into this with antivirus scanning workloads. On paper, T-series instances looked sufficient. In reality, sustained CPU demand exhausted credits quickly, and scan performance degraded sharply. The savings disappeared once latency and operational instability were factored in.
Before migrating any service, audit your telemetry carefully to ensure the "cheap" instance can actually sustain your baseline workload. Otherwise, you may end up paying for those savings in outages and degraded performance.

## Rule 9: Opportunity plus instinct equals profit.

> "Opportunity plus instinct equals profit"

Cloud providers offer multiple ways to commit to capacity: Savings Plans, committed-use discounts, and Reserved Instances (RIs). These are not administrative checkboxes; they are financial levers.
The key is understanding your workloads well enough to commit confidently.
Experienced engineers usually know what “good” looks like. They understand normal utilisation patterns, expected performance, and which services represent stable baseline demand. When that operational knowledge is combined with long-term capacity planning, it can significantly reduce monthly cloud spend.
Every correctly sized commitment transfers margin away from the cloud provider and back into your own budget.

## Rule 22: A wise man can hear profit in the wind.

> "A wise man can hear profit in the wind"

Cloud environments are dynamic by nature. Providers constantly adjust pricing models, launch more efficient silicon (such as ARM-based Graviton instances or TPU-backed learning models), and introduce new storage classes.
An infrastructure that never evolves is a leaking bucket.
Efficiency-focused engineers monitor release notes, beta programs, and industry shifts to identify when a new offering renders an older architecture obsolete. The "wind" of cloud innovation carries savings for teams positioned to pivot quickly.
A good example was the move from GP2 to GP3 storage. While it seemed like a “boring” migration, it delivered better performance at a lower cost and was relatively straightforward to implement.

## Rule 59: Free advice is seldom cheap.

> " Free advice is seldom cheap"

Every major cloud provider offers built-in, "free" cost-monitoring tools. While these tools provide baseline visibility, relying exclusively on them can become a trap.
These interfaces are designed to simplify things, often at the expense of granular control or multi-cloud visibility. They may also steer you toward purchasing models that increase vendor lock-in and reduce future flexibility.
When evaluating cost-management tooling, always assess whether the "free" guidance today could introduce technical debt or ecosystem dependency tomorrow.

## Rule 190: Hear all, trust nothing.

> "Hear all, trust nothing"

The discipline of FinOps has generated a surplus of "best practices." Every consultant, vendor, and whitepaper has a strategy for improving your bottom line.
Apply healthy scepticism to all of it.
When was the recommendation made? Is it still relevant? Under what conditions did it work?
What optimises a massive monolithic legacy application is rarely ideal for a modern microservices architecture.
Listen to the broader community, but validate everything against your own environment, constraints, telemetry, and billing data. In the cloud, your metrics are the only real source of truth.

## Conclusions

The Ferengi viewed every transaction as negotiable, every inefficiency as exploitable, and every assumption as dangerous.
Cloud infrastructure should be approached the same way.
The teams that manage cloud costs effectively are not necessarily the teams spending the least. They are the teams continuously questioning whether their architecture, commitments, and tooling still make financial sense.

If you want to know more about FinOps here are some great further reading:

[Finops Foundation Framework](https://www.finops.org/framework/?utm_source=x.finops.org&utm_medium=global-nav&utm_name=global-nav)

[AWS Savings Plans](https://aws.amazon.com/savingsplans/)

[FinOps on Azure](https://azure.microsoft.com/en-us/solutions/finops/)

[Google Cloud Savings Plans](https://cloud.google.com/pricing)
