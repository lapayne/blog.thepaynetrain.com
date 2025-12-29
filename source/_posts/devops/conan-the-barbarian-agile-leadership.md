---
title: conan's guide to agile leadership
date: 2026-01-05 00:00:00
tags:
  - conan
  - leadership
  - agile
  - devops
  - digitalTransformation
  - engineeringCulture
published: true
---

![Conan, Thulsa, Valeria, Subotai, Akira on a battle field](/images/devops/conan-leadership.png)

---

## The Hyborian Guide to Agile Leadership: Lessons from Cimmeria

### What is best in ~~life~~ DevOps?

In the chaotic landscape of modern software development and platform support, the "Kingdoms of Monolith" are falling. To survive, those old legacy "kingdoms" must embrace the speed of Agile and the cold hard steel of DevOps. But tools alone don't win battles; leadership does.

To understand how to lead a transformation of the scale of transforming a "kingdom", we look to the rugged age of **High Adventure.** What better way to start off the year than by examining one of my favorite films, the cult classic Conan the Barbarian, at first glance it doesn't seem like this fantasy tale of swords and sorcery has much to do with the modern world of Devops, but as you've seen from previous articles I can make anything about Devops and enjoy using pop culture to broaden understanding of the concepts and tenets of DevOps and Agile leadership. Why not learn about Devops leadership while indulging in some campy fun with a classic Christmas film (Don't fact check me on this) thats the greatest since Gremlins.

## <!--more -->

For those who don't know about the Conan books or films, let’s talk about our protagonist. Created by Robert E. Howard in 1932, **Conan the Cimmerian** is the quintessential "Self-Made Man." He was born on a battlefield and spent his life as a prisoner toiling on the wheel of pain (and what better metaphor for toil and manual processes than the wheel of pain), thief, pirate, mercenary, and eventually, a King all by his own hand. He is the perfect mascot for **DevOps** because he is ruthlessly efficient, highly adaptable, and driven by results, just as any good DevOps engineer should be. He doesn't care about legacy processes or "the way we've always done things", if a wall is in his way, he climbs it; if a god is a bottleneck, he kills it.

\* **Conan: The Empowered "T-Shaped" Contributor**

Conan isn't just a dumb brute; he is a thief, a pit-fighter, a strategist, and eventually a king. In DevOps, Conan represents the Cross-Functional Lead.

![Conan's T-shaped skills](/images/devops/conan-leadership-tshape.png)

A leader shouldn't just delegate; they must understand the "Steel.", the weapons they wield to accomplish their goals, Conan doesn't wait for a specialized "Wall-Climbing Department" to get into the Tower of Serpents. He has the skills to do it himself but knows when to leverage his team. This is a perfect depiction of the T-Shaped individual, they will not be the expert in all areas but they do have a wide range of skillsand experiences to draw from so they can bind a team together and be able to work with everyone to accomplish the goal.

Leaders must encourage "T-shaped" skills, where developers understand operations and Ops folks understand code. Don't be a specialist in a silo, be a warrior of the full stack.

\* **Thulsa Doom: The Peril of the Top-Down Monolith**

If Conan represents the future of Agile, Thulsa Doom is the embodiment of the "Command and Control" legacy manager. He sits in his mountain, distant and god-like, demanding total obedience. In the film, he famously tells a follower to "jump" off a cliff just to prove his power.

High-control, low-trust environments (like Doom’s cult) create a "Single Point of Failure." When the leader is removed, the entire system collapses because the "nodes" (followers) weren't empowered to think for themselves, this is the type of manager who insists on a full CAB (Change Advisory Board) meeting to fix a simple typo in a webpage. Instead of this model the leader should be empowering their **commanders** (DevOps leads) to implement the overall strategy and intent the leader devises, if you can't trust your commanders to follow your intent without you constantly whispering in their ears; you haven't built leaders, you've built a single point of failure with extra steps.

Modern leadership is about autonomy. If your team requires your permission for every deployment, you aren't Thulsa Doom, you’re just a bottleneck, like Thulsa if you follow this route your systems end up like the giant snake he turns into: it looks intimidating, but it’s actually slow, inflexible, and has no legs.

\* **Subotai: The Platform Engineer**

You can’t have a solo hero in DevOps. You need the person who makes the hero look good while delivering one-liners about being a "thief and an archer." Subotai is the Platform Engineer who helps make Conan the hero.

While Conan is busy being the "Feature Developer" and getting all the screen time, Subotai is in the background providing the IaC (Infrastructure as Code). This is the "Ops" in DevOps and is unfortunately all too often overlooked. Subotai is the one who scouts the perimeter, brings the horses, and provides the cover fire. He doesn't just "support" Conan; he enables him. Without Subotai’s reliable "archery pipeline," Conan would have been **"deprecated"** by a dozen arrows in the first act, in our world Subotai would be the one providing compute power, the kubernetes platforms, the API gateways, security guardrails, cost management and much more.

Don't treat your Ops or Platform folks like "sidekicks." In a 80s movie, the sidekick often has the best lines and saves the hero's life three times before the end. In DevOps, your "Subotais" are the ones who ensure your 99.9% uptime while the Devs are busy swinging their swords at the latest framework (and I'm not at all biased being the ops side of Devops myself).

\* **Valeria: The Spirit of Iterative**

If Subotai is the infrastructure, **Valeria** is the heart of the team’s agility. Her philosophy is simple: "Do you want to live forever?" She pushes for action, takes calculated risks, and understands that in the Hyborian market, the greatest reward requires the greatest speed.

In DevOps, Valeria represents **Continuous Integration and Deployment (CI/CD).** She doesn't spend years planning a single heist (or as we would call it a deployment); she scouts, moves, and adapts in the moment. She understands that a "deployment" (or a tower raid) is better handled in small, fast increments than in one massive, risky event.

To allow for this kind of speed, leaders must foster a "Psychological Safety" zone where teams feel empowered to take risks. If a deployment fails and the "serpents" sound the alarm, you don't punish the team. You conduct a Blameless Post-mortem. We aren't looking for a scapegoat to throw into the snake pit; we’re looking for a technical solution. We succeed as a team, or we get **deprecated** as a team.

\* **The Wizard (Akiro): The Data-Driven Observer**

Last and by no means least we have **Akiro the Wizard** who chronicles the journey. He doesn't swing the sword, he doesn't manage logistics but he remembers the history and understands the "magic" (the complex telemetry and metrics). Leadership requires Observability. You need a chronicler to measure lead time, cycle time, and mean time to recovery (MTTR). Someone who doesn't work by gut but who uses the hard facts of metrics to tell the story of progress and who can warn the team when the the spirits (system bugs) are coming.

We can model the real world from those experienced by the world of Conan

| Hyborian Concept         |                   DevOps Metric                    |
| :----------------------- | :------------------------------------------------: |
| Chronicle of the Journey |      Lead Time (How long from idea to king?)       |
| Pace of the March        |    Deployment Frequency (How often do we raid?)    |
| Warning of the Spirits   | Change Failure Rate (How often do the snakes win?) |
| Banishment of Ghosts     |    MTTR (How fast do we recover from a curse?)     |

Without a Wizard, you are flying blind. A leader must value the data-driven story as much as the sword-swinging action feature work. If you aren't measuring it, it didn't happen, and you're likely to get cursed by a "ghost in the machine" you didn't see coming, as we often say in operations "If there's no ticket the work never happened", bringing everything to the light and showing everything warts and all is the only way to ensure we have a robust system.

### The Conan 9 box model

You may be asking yourself how can I determine which type of Conan character each member of my DevOps team is? well finally you can answer that most important question using a 9 box model. This is the model you've likely seen a hundred times, this shows where people fit in your organisation, not everyone can be a superstar and nor would you want that.

![9 box Model](/images/devops/conan-9box.jpg)

Now with a Conan twist which should help you identify where each member of your team fit.

![Conan's 9 box Model](/images/devops/conan-9box-custom.png)

### The War Room: Mapping Your Mercenaries

Every leader must eventually look at their team and decide who is ready to storm the castle and who is just taking up space around the campfire.

#### High Potential

**The King (Conan)** [High Performance]: Your absolute "Star." Consistent, high-impact, and ready to lead the entire kingdom. He doesn't just do the work; he changes the world. Give him autonomy and get out of his way.

**The Emerging Thief** [Moderate Performance]: Growing fast and highly adaptable. They are learning the ropes but show flashes of brilliance. They are ready for more complex "heists" (sprints) to test their mettle.

**The Young Cimmerian** [Low Performance]: High raw talent but lacks discipline. They have the "Steel" in them, but it hasn't been forged yet. They need a mentor to show them the path.

#### Moderate Potential

**The Shield Maiden (Valeria)** [High Performance]: A high-impact performer who knows the current system inside and out. She is reliable in a fight but might be more focused on the current "raid" than long-term kingdom-building.

**The Reliable Mercenary** [Moderate Performance]: Your solid "core" contributor. They keep the campfire burning and the code flowing. They do the day-to-day work with no complaints, but they aren't looking to wear the crown.

**The Cultist [Low Performance]**: Follows orders but lacks initiative. At high risk of becoming a "Thulsa Doom" sycophant if not challenged to think for themselves.

#### Low Potential

**The Chronicler (Akiro)** [High Performance]: A vital specialist with deep knowledge, but they have reached their peak growth in this domain. They are your "Subject Matter Expert" (SME)—keep them happy, but don't force them into leadership.

**The Village Guard** [Moderate Performance]: Capable of routine tasks but highly resistant to new "magic" or automation. They are comfortable with the status quo and will resist the DevOps transformation.

**The Camel [Low Performance]**: (The one Conan punched). Adding no value and actively hindering the journey through "toil" and negativity. They need to be offboarded before they slow down the entire party.

### Conclusion: The Riddle of Steel

At the end of the film, **Thulsa Doom** tries to gaslight Conan, claiming that "Steel is not strong, boy... flesh is stronger." In DevOps, we know the truth: The tools (Steel) are only as strong as the culture (Flesh) that wields them.

You can have the most expensive Kubernetes cluster in the world, the best in breed CI/CD and obserability platforms but if your culture is a "Snake Cult" of top-down fear, you **will** fail. If you don't empower your T-shaped warriors, support your platform sidekicks, and listen to your data-driven wizards, your "kingdom" will fall to the next agile barbarian at the gates.

Now master the steel, empower the flesh, and go forth to conquer your technical debt. "Between the years when the oceans drank Atlantis, and the rise of the sons of Aryas, there was an age undreamed of. And unto this, Conan, destined to wear the jeweled crown of Aquilonia upon a troubled brow..." And was destined to maintain a 99.9% uptime.

Always Remeber Crom is watching... but he **doesn't** provide tech support.
