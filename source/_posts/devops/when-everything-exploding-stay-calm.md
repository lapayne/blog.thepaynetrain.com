---
title: When Everything’s Exploding, Stay Calm and Reload.
date: 2025-11-03 00:00:00
tags:
  - IncidentManagement
  - Postmortem
  - SRE
  - DevOps
  - PsychologicalSafety
---

![Borderlands characters infront of an incident screen](/images/devops/borderlands-incidentmanagement.png)
Incident management, by the very nature of the beast, is never clean. It’s noisy, confusing, fraught with danger, and full of people with strong opinions on the best way to resolve the issues. Which, coincidentally, is also the opening of _Borderlands_ (you can pick your favorite in the franchise—they are all relevant).

_Borderlands_ is one long, barely-contained disaster, a futuristic world that's broken down, with science gone mad, and the heroes improvising solutions. If that doesn’t sound like a war room during a Severity-1 outage, I don't know what is (if you know, you know).

Beneath the chaos, however, there is a method to the madness, a rough wisdom about how to survive and thrive when everything’s gone awry and there is a hoard of angry customers demanding to know what's happening and how you will fix it.

## <!--more -->

### 1. Claptrap and the Comedy of Failure

Every incident has a **Claptrap**—the well-meaning automation that’s technically "helping," but mostly making things worse, or the manual change or IaC (Infrastructure as Code) that’s had unexpected consequences (just ask AWS).

Claptrap embodies what happens when **process takes over purpose**: systems trying to be useful while generating noise, alerts, and confusion, providing too much information, and completing the work exactly as they've been instructed to but not always helpfully.

The trick isn’t to silence them; it’s to understand them. Every useless alert, every misfire, every false positive is **data**, and that data needs to be tamed and tuned to provide valuable insights. A good incident commander knows how to mute the noise without muting the insight. You don't need fewer Claptraps, you need smarter filters and the people who understand the data.

---

### 2. The Vault Hunters and the Power of Chaotic Collaboration

The _Borderlands_ crew is a walking HR nightmare: a sniper with trust issues, a demolitions expert who thinks subtlety is a crime, and a hacker who refuses to document anything. Their secret isn’t harmony, it’s **clarity**. Everyone knows their role, their strengths, weaknesses, and, more importantly, **when to shut up and let someone else take the shot**.

That’s incident management at its finest: highly individual experts acting in coordinated chaos. It shouldn't work, but it does. A good incident commander doesn’t suppress personality; they **harness it**. You don’t manage a team by demanding order, you manage it by building trust and knowing when to listen to their expertise and when to guide them in a different direction.

---

### 3. The Loot System: Lessons in Postmortem Culture

In _Borderlands_, every firefight ends with **loot**. Sometimes it’s brilliant. Sometimes it’s garbage. But you always stop, sift through it, and decide what’s worth keeping—nobody likes an inventory full of useless "loot." That’s your **postmortem**. Every incident drops “loot”: new insights, near-misses, monitoring gaps, process tweaks—the list goes on. The best teams collect those lessons deliberately. The worst teams just grab the shiniest bit and move on, or, even worse, keep everything regardless of its value.

**Loot discipline**—knowing what to keep, what to drop, and what to improve—is the heart of a well-functioning learning culture.

---

### 4. Tannis and the Value of Controlled Madness

Dr. Patricia Tannis is the archetype of the brilliant but unstable scientist and the perfect symbol for the engineering mindset under stress. She’s obsessive, socially unfiltered, and occasionally right in ways no one else could see.

During incidents, you need a little **Tannis energy**: the curiosity to question everything, the willingness to dive into the unknown and emerge with an answer. But the art of leadership is **containment**, giving that madness purpose. If curiosity is unbounded, it becomes chaos and unfocused; if it’s directed, it becomes innovation.

---

### 5. The Respawn Point: Psychological Safety and Recovery

Everyone dies in _Borderlands_. A lot. But thanks to **respawn points**, failure isn’t fatal—it’s part of progress.

That’s how you build **resilient teams**. Mistakes aren’t shameful; they’re expected and recoverable. The only real shame is pretending they never happened. If your engineers are afraid to fail, they’ll play safe. And in complex systems, playing safe is the riskiest move of all. Giving people the **psychological safety** to fail is key; we don’t need blame, we need restoration.

---

### In the End, It’s About Controlled Chaos

_Borderlands_ teaches one thing better than any management textbook: **order and chaos aren’t opposites, they’re partners.**

You don’t tame chaos; you learn to dance with it.
You don’t eliminate risk; you respawn smarter next time.
And you don’t build resilience through control, you build it through trust, humor, and a healthy respect for the absurd.

Because in both Pandora and production, as the vault hunters would put it: **Everything explodes eventually. The only thing that matters is who’s still standing and who’s still laughing when the smoke clears.**

---

I've created the new Hexo post file for you. Would you like me to now draft a social media post (e.g., for Twitter or LinkedIn) to help **promote** this new article?
