---
title: ' '
date: 2023-10-23
---

## Background:

This case study was written in response to [this](https://forum.effectivealtruism.org/posts/idrBxfsHkYeTtpm2q/seeking-paid-case-studies-on-standards) call for proposals by Holden Karnofsky on safety standards to inform possible standards on leading AI labs. It represents ~50 hours of independent research. I am grateful to Michael Wara, Tom Long, Marc Joseph, and one expert with knowledge of the Office of Energy Infrastructure Safety (who chose to remain anonymous) for allowing me to interview them for this case study.

This case study investigates safety standards applied to investor-owned electrical companies in California (hereafter referred to as ‘utilities’) to reduce the risk of utility equipment igniting wildfires. California investor-owned utilities are regulated monopolies responsible for purchasing and distributing electricity across the state. Three utilities cover most of the state, with Pacific Gas and Electric (PG&E) being the largest. The industry has many possible parallels and lessons for AI regulation.

## The need for safety standards

- California wildfires cause significant death and destruction. (more)
- The risk of wildfires has significantly increased in recent decades, almost certainly due to climate-change induced droughts.
- Equipment from California’s utilities is a significant source of wildfires that have killed hundreds of people and caused billions of dollars in damage.
- There is no simple and affordable solution to eliminate wildfire risk from utility equipment.

# Current standards (summary)

- The California Public Utilities Commission is the primary regulator of utilities. In 2022, the Office of Energy Infrastructure Safety (‘Energy Safety’) was created to oversee utility processes related to reducing wildfire risk.
- Energy Safety issues “[safety certifications](https://energysafety.ca.gov/what-we-do/electrical-infrastructure-safety/wildfire-mitigation-and-safety/safety-certifications/safety-certification-faqs/)'' to qualifying utilities. Failure to receive a safety certification would significantly harm a utility’s financial standing.
- Core requirements for a safety certification include:
  - a **safety culture assessment,**
  - and an **approved executive compensation structure** that ties compensation to safety performance.
  - an annually approved **Wildfire Mitigation Plan** (WMP). Utilities have significant freedom to propose a range of strategies and levels of investment to reduce risk in its WMP. WMP evaluation is based on the expected level of safety reduction and the utility’s capacity to execute it.
- Auditing includes field inspections, independent evaluations, and annual assessments of compliance with the WMP. Energy Safety can recommend to the PUC to impose penalties on utilities “for noncompliance with its approved plan.”

## Key findings (summary)

_This section summarizes the most interesting and relevant points. Each header links to a corresponding section in the appendix containing a more detailed description. _

### <span style="text-decoration:underline;">Proactivity vs. reactivity </span>

**Key points:**

- Wildfire risk has risen quickly and substantially over the past ~20 years.
- In the late 2000s, activists pushed for stricter regulation to prevent wildfires from utility equipment. Two of the three largest utilities fought most efforts to increase safety standards.
- Utility regulators lacked sufficient expertise in wildfire safety prevention for most of the 2000s and 2010s, and failed to meaningfully raise standards until the late 2010s/early 2020s, after utilities (mainly PG&E) caused several catastrophic wildfires.

**Possible lessons:**

- When starting from a low base, creating and enforcing standards can be a lengthy process – it took roughly 5-10 years after it was clear that catastrophic risk was rising for standards to be created and have a meaningful impact. This included several years for regulators to determine an appropriate regulatory framework and build internal expertise, followed by several years during which regulators approved substandard safety plans on the condition that utilities would build capacity for improving safety over time.
- Amid a changing risk landscape, it appears unlikely that companies will take tail risk sufficiently seriously until they experience it first hand, even when such risk would threaten company profits. Some events that look like** ‘warning shots’ in hindsight did not sufficiently spur urgent safety improvements.**
  - Possible ‘warning shots’: SDG&E sparking a fatal wildfire did not sufficiently spur action among other utilities. Further, while regulators forced PG&E to address unsafe practices in its gas department that led to a catastrophic explosion, this explosion did not cause regulators to require improvements to PG&E’s (deficient) safety culture and practices related to electrical equipment.
  - Michael Wara believes this pattern has been played out for utilities across the country, too. In Hawaii, for example, [Hawaiian Electric](https://twitter.com/michaelwwara/status/1709717342115057841?s=48&t=jvABLpmiJy24m6BINifJrQ) decided against using Public Safety Power Shutoffs (as is used by California utilities) as it deemed its coverage area to be less prone to catastrophic fires than California. Its equipment then caused the Lahaina fire that killed about 100 people. [maybe mention oregon, too]

### <span style="text-decoration:underline;">Utility motives</span>

**Key points:**

- Utilities are allowed by regulators to make a profit on approved capital expenditures, but not operating expenditures, which can be covered 1:1 by revenues (although they can increase profits by spending less on operations than was approved). **This business model has been a principal reason for consistent underspending on maintenance**, which has (fairly directly) led to catastrophic fires.
- Due to a California Supreme Court Decision, utilities are legally required to reimburse wildfire victims for fires started by utility equipment _regardless of whether the utility was at fault_. **The** **threat of legal liability has significantly (though not always sufficiently) motivated utilities to reduce wildfire threat**, once the utility acknowledged the risk.
  - PG&E declared bankruptcy in 2019 (verify) because it faced hundreds (THOUSANDS?) of lawsuits and was liable for tens of billions of dollars after its (sometimes very old, and inadequately inspected and maintained) equipment caused several catastrophic wildfires. This included the Camp Fire that killed 85 people in Paradise, California.
  - Following PG&E bankruptcy, the PUC created a wildfire insurance fund (REPHRASE) that utilities can draw from if they face legal liabilities. Utilities that have been issued a safety certification are assumed (unless shown otherwise) to have acted reasonably in considerations of accessing the insurance fund.
- Experts believe that utilities spend very large amounts of effort to create a compliant WMP (especially in recent years), as they are highly concerned about the threat of not receiving a safety certification. Still, utilities are aware that Energy Safety is likely reluctant to deny certification, as it would lead to higher energy prices and thus be highly undesirable for all parties.
- Experts believe public welfare concerns have also motivated utilities to improve safety practices. This is partially due to altruistic concerns, but also a desire from PG&E to improve its terrible reputation, including among the general public in communities where employees live (and sometimes receive death threats).
- Executive pay is approved if it is shown to be dependent on safety outcomes (though utilities have some freedom on how to interpret this).

**Possible lessons:**

- California utility regulation shows the challenge of using a licensing scheme to regulate companies that become ‘too-important-to-fail.’ In this case, failing to issue safety certifications to utilities that insufficiently mitigate catastrophic risk could lead to significantly higher electricity prices. This may make regulators reluctant to pull this lever. A similar challenge could emerge if governments and businesses become dependent on (updates to) AI systems.
- Legal liability – established by courts, rather than the legislature, in this case – can be dramatically more influential on company behavior than public penalties (at least when the size of such penalties are capped by laws), but can still be insufficient to motivate sufficient safety improvements.
- Tying executive pay to safety outcomes can appear to meaningfully influence utility behavior, but the mechanism matters. One expert suggested such a program would be much more influential if executive pay was also required to follow a long term (e.g. 10+ year) vesting schedule, such that executives would lose significant pay if the company failed to avert long term catastrophic risks.

### <span style="text-decoration:underline;">Activists and third parties</span>

Key points:

- Activists and third parties have played a significant role in pushing for and crafting safety standards.
- Regulators rely on third parties for technical expertise. For example, risk modeling.

**Possible lessons:**

- The PUC has a third party payment program– which pays individuals and organizations when their input has been found to be useful to a PUC decision (FIX) – could be a useful model to build the ecosystem of third party expert organizations and individuals.
- Even when activists concerned about tail risks have little early success, nuanced proposals can set the foundation for later standards.

### <span style="text-decoration:underline;">Regulatory structure and capacity </span>

Key points:

- There are significant delays and
- The significant length of some audits and investigations limits regulators’ ability to track and require rapid safety improvements.
- Separation between safety and economic regulators
  - Splitting economic and safety regulation was deliberate and appears to have been somewhat effective at ….
  - STILL, Energy Safety likely influenced
  - AND there may also be benefits of a single entity
  - Energy Safety has a tight balancing act to play because pulling their biggest lever would also hurt customers
    - Experts (with possible bias) thought that they have been walking this balance well and that utilities feel substantial pressure.
    - This is just generally the problem with being really dependent on a company
- The interplay also creates issues with flexibility toward safety, because rate case are once per 4 years.

**Possible lessons:**

- There may be benefits from splitting regulatory responsibilities, such that one agency is (in principle) only concerned with safety outcomes, with others focusing on
- Energy safety did not try to incorporate past performance in approval process.
- However, Energy Safety does have flexibility to move the goal posts as it wants and as it better understand what is feasible.

### <span style="text-decoration:underline;">Regulatory structure, process, and capacity</span>

**Key points: **

- Regulatory bodies are split. Energy Safety just safety, PUC electric
- PUC approved rate case every four years. Energy Safety every year.
- Utilities have lots of discretion in what they propose
- For many years, risk levels have been unclear. Risks are now much better mapped and understood, though modeling may still focus more on median fire than tail risk.
- Similarly, the cost and effectiveness of various safety strategies are unclear and disputed. \*\* \*\*
- In 2020, Energy Safety approved PG&E’s WMP despite calling it deficient as it argued that holding the utility to a higher standard would be unrealistic and result in denied WMPs for years - ultimately delaying its progres. [consider moving to earlier section about lack of leverage]
- PG&E proposed dramatic spending increases (on which they would make a regulated profit, as a capital expense) to move XX lines underground, while many experts believe cheaper ‘hardening’ techniques are more appropriate (despite them doing slightly less to reduce risk) as utility savings would result in cheaper electricity rates.

**Possible lessons: **

- There may be advantages to having a regulatory body solely focused on reducing (sometimes catastrophic) risk, with other oversight tasks left to separate bodies. In this case, this has helped build regulatory capacity and focus on safety.
- Still, the lack of a unified directive to provide a tolerable risk level, preferred safety strategies, and an appropriate balance between public tradeoffs has created challenges for safety initiatives, and can lead to inefficient, profit maximizing mechanisms for reducing risk.
- Typical regulatory feedback loops can be insufficiently responsive when the cost and effectiveness of safety-enhancing strategies is highly uncertain.
  - Lengthy periods for auditing, incident investigation reduce regulators’ ability to quickly update oversight strategies. This is especially costly.

### <span style="text-decoration:underline;">Influence of voluntary safety actions</span>

Key points:

- Utilities have significant discretion

**Possible lessons:**

- Voluntary actions to improve safety above and beyond minimum requirements by some utilities (primarily SDG&E) has increased pressure and expectations on other utilities.

<details style="margin-bottom: 0px; margin-top: 12px; margin-left: 10px;">
  <summary> 
    <span style="margin-left: 5px">
      TOP BULLET HERE
    </span>
  </summary>
   
  <div style="margin-left: 20px; margin-top: 12px">

- Second level, first BULLET


  </div>
</details>

<!-- ONE LEVEL OF NESTING -->

<details style="margin-bottom: 0px; margin-top: 12px; margin-left: 10px;">
  <summary> 
    <span style="margin-left: 5px">
      TOP BULLET HERE
    </span>
  </summary>
   
  <div style="margin-left: 20px; margin-top: 12px">

- Second level, first BULLET


  </div>
</details>

<!-- TWO LEVELS OF NESTING -->

<details style="margin-bottom: 0px; margin-top: 12px; margin-left: 10px;">
  <summary> 
    <span style="margin-left: 5px">
      TOP BULLET HERE
    </span>
  </summary>
  
 
  <div style="margin-left: 20px; margin-top: 12px">


- Second level, first BULLET


  </div>

  <details style="margin-bottom: 0px; margin-top: 12px; margin-left: 25px;">
    <summary>
      <span style="margin-left: 10px">
        Second level, COLLAPSABLE
      </span>

    </summary>

  <div style="margin-left: 20px; margin-top: 12px">

- Third level, first BULLET


  </div>
  </details>
</details>

Now that that's out of the way, let's learn about how to make posts.

## Creating a Post
