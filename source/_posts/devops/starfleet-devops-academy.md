---
title: The DevOps Academy and Starfleet
date: 2026-08-05 00:00:00
tags:
  - DevOps
  - DevOps Academy
  - Star Trek
  - Continuous Learning
  - Tech Training
---

![Starfleet Academy as a DevOps Academy](/images/devops/starfleet-devops-academy.png)

---

Starfleet Academy doesn't graduate finished officers. Neither does our DevOps Academy, and that's the point.

## <!--more -->

## Not a finishing line

Starfleet's real education happens on **starships**, in first contact, in crises and battles nobody rehearsed for. The Academy just gives you the grounding to survive long enough to learn the rest on the job.
That's the exact philosophy behind our DevOps Academy, especially when it comes to the landing zone. It's not a PowerPoint slide or a client qualification item. It's a safe, sandboxed environment that lets you build out workloads in a predictable, repeatable way, with all the guardrails you choose to put in (ask anybody who's been through the academy about my scrumpy analogy: **guardrails** can be overridden at a lower level, i.e., the fleet's standard ration is rum, but the Bristol fleet gets an exception to drink scrumpy instead, I don’t apologise for the analogy it’s the pirate farmer in me). We even used our own landing zone to vend the accounts our engineers used for the academy, giving them their own "holodeck" where they could experiment without breaking anything critical.
The parallels don't stop there. Teaching engineers Terraform, Kubernetes, containers, and GitHub, we found Starfleet's culture of continual learning mapping onto our own almost exactly. Here's what I mean.

---

## Terraform: Writing the Ship's Blueprints

Every Starfleet vessel is built from a defined, versioned design (feel free to argue about your favourite below, but the obvious answer is the sovereign class). You don't build the **USS Enterprise** by improvising. Infrastructure as Code (IaC) works the same way. With Terraform, they learned to define environments declaratively: reproducible, reviewable, and disposable. Mistakes aren't catastrophic; they can easily be fixed by modifying your code and applying it or at worst a terraform destroy away.
This is a completely different mindset from **"click-ops"** ("manual, ad hoc changes") infrastructure management, and it mirrors something central to Starfleet: the blueprint is never final. Ships get refit, just as the constitution class was refit. Designs evolve. Nobody assumes the current version is the last version, we know changes happen, needs evolve and that's precisely the mentality we want engineers to bring to infrastructure.

---

### Kubernetes: The Fleet Command Structure

If Terraform is the blueprint, Kubernetes is Starfleet Command, it’s the **orchestration layer** deciding what gets deployed where and how, it can self-heal and decide how resources get allocated when conditions change. A pod going down isn't a crisis; it's a routine event that’s expected to happen; the same way a fleet reroutes when one ship needs repairs.
Teaching Kubernetes means teaching engineers to think in terms of desired state, not manual intervention, like a fleet commander doesn't micromanage individual controls, they define the mission parameters and trust the system (and the crew) to execute those orders.
Our engineers built their own cluster, deployed **real** applications to it and then learned how to troubleshoot the system when it went wrong, we were very keen on ensuring that anyone who’s been through the academy can fix common problems as well as deploy new things.

---

### Containers: Modular, Portable, Mission-Ready

Shuttlecraft, tricorders, phasers, Starfleet technology is built to be **modular** and operable across ships, planets, and away missions across the entire United Federation of Planets. Containers bring that same portability to software: package once, run anywhere, with **consistent** behaviour regardless of the underlying system.
For our engineers, this was an in-depth module, they built from a **simple** application, building more complex ones, learned how to use multistage builds to keep them small, how to interrogate and interact with individual containers ahead of the Kubernetes module. Once you've containerized an application, the conversation shifts from "will this work on the target system" to "how do we orchestrate this at scale"

---

## GitHub: The Ship's Log and Single Source of Truth

In Starfleet, every decision, course correction, and away-mission report is logged. The captain's log is **not** bureaucracy; it is institutional memory, helping everyone understand what happened and why.
GitHub plays that role in our Academy: pull requests as decision records, commit history as a timeline of intent, code review as the peer-learning mechanism that turns individual knowledge into team knowledge. When something goes wrong, we don't just fix it, we document the fix in the code, the same way a competent first officer files a report so the whole fleet benefits from one ship's lesson.

Our engineers learned how git worked, created pull requests and merged code, more importantly than that they used GitHub actions to **make things happen**, starting with simple information from a runner and building it up until they were building applications, running tests against it and preparing it for deployment into a live environment.

### The Real Lesson: Learning Is the Culture, Not an Event

The thing I keep coming back to is that Starfleet doesn't treat learning as a phase that ends at graduation. It's continuous, built into progression, built into how missions are debriefed, built into how failures are treated as data rather than shame.
That's the culture we're trying to build with the DevOps Academy. Terraform, Kubernetes, containers, and GitHub aren't just tools we teach, they're the way through which engineers practice a mindset: build it, break it safely, learn from it, document it, and go again. Just like Starfleet, we're not trying to produce people who "know DevOps." We're trying to produce people who never stop learning and improving.

As one of my favourite quotes from the ever-eloquent Q which fits DevOps very well **“If you can't take a little bloody nose, maybe you ought to go back home and crawl under your bed. It's not safe out here. It's wondrous, with treasures to satiate desires both subtle and gross. But it's not for the timid.”**
