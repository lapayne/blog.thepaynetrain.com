---
title: Chaos Engineering, Why the Orruk Warclans are the Ultimate SREs
date: 2026-02-27 00:00:00
tags:
  - DevOps
  - SRE
  - ChaosEngineering
  - AgeOfSigmar
  - Orruks
  - CloudResilience
published: true
---

![Orruks as Chaos Engineers](/images/devops/orruks-chaos-engineers.png)
In the Mortal Realms of Age of Sigmar, **stability is an illusion**. Civilizations rise only to be tested by the encroaching tide of destruction and all too often fall. For the Orruk Warclans, the "Waaagh!" isn't just a battle cry, it’s a rigorous, unscripted stress test of the environment which is the heart of chaos engineering.

If you want to move beyond basic uptime and achieve true Systemic Resilience, you need to stop thinking like a timid scribe in Azyr and start thinking like a Megaboss.

## <!--more -->

### Whats is Chaos Engineering?

For those who do not know Chaos engineering is the discipline of performing controlled experiments to uncover weaknesses before they cause a outage.

Instead of waiting for a random failure, SREs proactively create "Chaos" into the system such as server crashes, network latency, or database disconnects, into a production-like environment (Only the very brave or foolhardy would do it directly into production, but you can!). The goal is to prove that the system’s automated recovery processes and procedures (e.g., circuit breakers, auto-scaling, or failover) works as designed and keeps your systems running.

### The Ironjawz and the "Blast Radius"

The **Ironjawz** don't care about "graceful degradation." They care about what's left standing after the impact. An Ironjawz Brute doesn't just tap on a fortress wall; he smashes the main gate to see if the whole structure collapses.

For an SRE, this mirrors the critical need to minimize the blast radius. An Ironjawz charge is a perfect metaphor for using Chaos Engineering practices like Canary Deployments or Network Partitioning. By simulating a region-wide outage in a controlled way, we find out if our "fortress" (infrastructure) has a single point of failure that could bring down the entire Realm, ensuring the damage from any one attack is contained.

### The Kruleboyz: Testing the "Grey Failures"

The **Kruleboyz of the Ghurish swamps** are masters of the "Muck-trick." They don't kill you instantly; they weaken you, slow your pulse, and let your own systems fail you. In tech, we call this a **Grey Failure**.
For an SRE, these are the most dangerous threats: latency and partial failures. It's the slow, creeping doom where database locks get longer and response times increase until everything grinds to a halt. A total server crash is easy to detect, the monitoring turns red. But a Kruleboyz-style "brownout," where a service is technically "up" but responding with 2-second latency, is a silent killer.

This is where Chaos Engineering helps you fight back. By proactively injecting packet loss and jitter, you can test if your circuit breakers trip correctly before the "poison" spreads to your upstream services.

### The Bonesplitterz: The Primitive Power of Chaos

The **Bonesplitterz** are driven by the "Spirit of Gorkamorka." They strip away the "civilized" to find the raw power underneath. For an SRE, this is the essence of Continuous Verification.
For an SRE this is looking at Continuous Verification, looking for weaknesses and any points of failure constantly as we continue to build and develop systems.

esilience isn't a feature you add; it's the inherent "spirit" of your application. By constantly "hunting" for vulnerabilities in production, you ensure your application is strong enough to survive even when its protective "armor" (ideal operating conditions) is stripped away. This includes practices like:

- Killing random pods

- Throttling CPU

- Simulating disk exhaustion

### Gorkamorka’s Law: The Steady State Hypothesis

Every Waaagh! begins with a baseline of "normal" Orruk rowdiness (if normal can be used for anything orruks do). To measure chaos, you must first define order. For Orruks if the "boyz" aren't fighting them something is wrong, war is their baseline.
For SRE's this means defining the Steady State, what is normal? what does database load look like, what peaks and troughs are usual, how fast are response times under usual load etc.. without knowing what "good" looks like you wont be able to spot when something goes wrong. If you don't have high-fidelity Observability, you aren't doing Chaos Engineering; you’re just breaking things in the dark and cosplaying Chaos Engineering. 

### Final Thought's: Faith in the "Big Green"

Chaos Engineering is often feared because it feels like inviting destruction into your house. But the Orruks know a truth that many executives miss: The storm is coming if you're ready or not. 
You can either wait for a random, catastrophic failure to test your system in the middle of the night with only your on-call engineer around, or you can be the "Big Green Waaagh" yourself. 
Break it on your terms. Smash the gates. Poison the network. Attack with full force. Only then will you know if your own "Mortal Realm" is truly built to last or will join the many other failed kingdoms when Chaos comes for you.
