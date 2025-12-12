---
title: What The Wurzels Taught Me About DevOps
date: 2025-10-06 00:00:00
tags:
  - DevOps
  - Culture
  - CI/CD
  - Hexo
  - Philosophy
---

![A west country band playing instruments](/images/devops/wurzels-devops.png)

---

As anyone who knows me can tell you, I am a very proud **West Country resident**. Yorkshire may be god's own country, but the West Country is the heart; it's old, wild, and where nature and legend meet to form a magical, mystical region. Where else can you find a giant horse carved into the hillside, an ancient druid monument, and Camelot? Nothing is more West Country than **The Wurzels** (except maybe scrumpy). While listening to some of their songs recently, I thought to myself: _Is there any way I can combine my love of The Wurzels with my love of technology?_ And so, this article was born.

In the world of technology and DevOps, with the need and desire to constantly go faster, it's easy to forget the simple, foundational principles that make systems work efficiently. Oddly enough, I found my most important lessons in these principles not in conferences or the latest shiny tool, but listening to the great and legendary band **The Wurzels**.

For those who are unfamiliar (and I don't know why you would be), The Wurzels, best known for their song, "**The Combine Harvester**," sing about the joys, trials, and tribulations of rural life, often with a good dose of humour. Their music, on the surface, seems worlds away from continuous delivery, idempotent configuration, and immutable infrastructure. Yet, their most popular songs reveal **four core DevOps truths**.

<!--more -->

---

### 1. "The Combine Harvester" and the Power of Re-Use

The Wurzels' biggest hit is a re-work of Melanie's 1971 song "**Brand New Key**," with the lyrics changed to recount a farmer's efforts to acquire a combine harvester. This practice—taking an existing structure (the tune) and rapidly adapting it to a new domain (West Country farming)—is pure, distilled DevOps.

- **Don't reinvent the wheel:** In DevOps, we call this **Infrastructure as Code** templates, Kubernetes manifests, or Helm charts. Why spend weeks building a logging stack from scratch when you can take a battle-tested Terraform module or Helm chart, parameterize it, and deploy it?
- **Focus on the value:** By re-using the tune, The Wurzels focused their creative energy entirely on the new, farming-based lyrics. In tech, re-using a standard deployment pipeline means your team can focus on writing better, more feature-rich code, not on fiddling with CI/CD syntax.
- **Velocity:** It's faster to adapt than to create. The song’s rapid success was partly due to the familiarity of the melody; it was already known to be popular and validated. Our templates and modules are already "validated" by the community, reducing time to deployment and risk of failure.

---

### 2. "Don't Tell I Tell Ee" and the Culture of Openness

"**Don't Tell I Tell Ee**" is a song about gossip and how news, despite intentions to keep it secret, inevitably spreads through a close-knit community. The essence of the song lies in the inherent **transparency of human interaction**.

- **Information flow is inevitable:** Just as news travels fast in a village, information about system changes, incidents, and improvements should travel fast within a DevOps team. Trying to hoard information or keep things secret often leads to misunderstandings, errors, and increased incident time.
- **Documentation as shared gossip:** Instead of whispered secrets, think of well-maintained **documentation, runbooks, and architectural diagrams** as the official and beneficial "gossip" of your systems. It ensures everyone has access to the most accurate information at all times.
- **Collaboration over silos:** The song highlights how information moves between people. DevOps breaks down traditional silos between Development and Operations, fostering a culture where knowledge is shared freely, and problems are solved together as a squad, rather than being trapped within individual teams.

---

### 3. "I Am A Cider Drinker" and the Importance of the Feedback Loop

Many Wurzels songs, particularly "**I Am A Cider Drinker**," are known for their massive, easy-to-sing, and highly participatory choruses. They are built for concerts, pubs, and parties, thriving on **immediate feedback**.

- **Immediate feedback is vital:** Just as The Wurzels know instantly if the crowd is engaged, our systems need to tell us instantly if a deployment is causing issues. We don't wait until the customer complains; we use **observability** (logs, metrics, traces) to shout "**Alert!**" right away.
- **Simplicity and clarity:** A Wurzel’s chorus is simple enough for everyone to join in. A good DevOps dashboard should be equally simple, clear, and focused—with metrics that anyone (from engineer to product manager) can understand quickly. **Complexity obfuscates problems.**
- **The shared experience (blameless culture):** Everyone in the audience is a part of the song's success. Similarly, DevOps fosters a **blameless culture** where Development, Operations, and Security teams are all invested in the performance of the system, not in finger-pointing.

---

### 4. "Drink Up Thy Zider" and Sustainable Practices

The famous Wurzels anthem "**Drink Up Thy Zider**" isn’t about excess alcohol; quite the contrary, it’s a deep-rooted celebration of the local, natural, and traditional process of cider making. It’s about working with what you have and cherishing the **sustainable, seasonal rhythm** of the environment.

- **Work with the natural rhythm:** The Wurzels work with the apple harvest. We work with our capabilities. **Sustainable DevOps** means having realistic Service Level Agreements (SLAs), Service Level Objectives (SLOs), and Service Level Indicators (SLIs), avoiding engineer burnout, and ensuring a healthy "**error budget**." You can’t rush the harvest, and you can’t rush quality code.
- **Pragmatism over purity:** Scrumpy is rough, traditional cider. It's not perfect in the same way bottled cider is, but it gets the job done and is naturally, authentically good. DevOps often requires pragmatic choices: is this complex, bleeding-edge tool truly needed, or will a simpler, proven solution work? Sometimes, the basic, rough-around-the-edges tool is the most reliable one.
- **Local knowledge and ownership:** The song is an ode to Somerset. In DevOps, this translates to **local team ownership**. The team that builds the service owns the operational running of the service ("You build it, you run it"). This deep local knowledge fosters better design and faster resolution.

The next time you’re fighting with a deployment pipeline or troubleshooting a tricky production issue, remember the simple, rustic wisdom of The Wurzels: **Re-use proven tools, embrace transparency, listen to immediate feedback, and adopt a sustainable, pragmatic work rhythm**. Above all, make sure you slow down and don't burn yourself out and take time to enjoy yourself.

```

```
