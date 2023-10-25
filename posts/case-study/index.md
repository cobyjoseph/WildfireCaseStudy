---
title: ' '
date: 2023-10-23
---
<div style="margin-top: -35px; margin-bottom: -10px;">


_This case study was written in response to [this](https://forum.effectivealtruism.org/posts/idrBxfsHkYeTtpm2q/seeking-paid-case-studies-on-standards) call for proposals by Holden Karnofsky on safety standards to inform possible standards on leading AI labs. It represents ~60 hours of research and writing. I am grateful to Michael Wara (Stanford Law School professor and consultant for wildfire risk to the California Office of Energy Infrastructure Safety), Tom Long (Director of Legal Strategy at [TURN](https://www.turn.org/tlong)), Marc Joseph (former shareholder and President at _[Adams, Broadwell, Joseph, & Cardozo](http://www.adamsbroadwell.com/attorneys/marc-d-joseph1/)_ and my father), and one other expert with knowledge of the Office of Energy Infrastructure Safety who chose to remain anonymous to  allow me to interview them for this case study. _


## Background and overview 

This case study investigates safety standards applied to investor-owned electrical companies in California (‘utilities’) to reduce the risk of utility equipment igniting catastrophic  wildfires. California investor-owned utilities are regulated monopolies responsible for purchasing and distributing electricity across the state. Three utilities cover most of the state, with Pacific Gas and Electric (PG&E) being the largest. <a id="backref1" href="#note1" class="footnote-ref">[1]</a>

The field has many possible parallels to the current and possible future landscape for frontier AI labs. Some possible similarities are listed below (though some may become dissimilarities depending on how the AI field evolves).


* Catastrophic risk is posed by a small number of companies (three utilities cover most of the state).[^2]
* It is infeasible to fully eliminate catastrophic risk (at least in short-medium term).
* Risk has quickly increased in the past two decades.
* During this time, risk levels and the individual sources of risk have been highly uncertain (though they are better understood now). 
* The cost and effectiveness of risk mitigation strategies has also been largely unclear. 
* Safety standards partially resemble a licensing scheme, with approval based on a fairly subjective evaluation across a wide range of metrics. 
* Safety measures can accompany economic tradeoffs for the general public (namely higher electricity rates).
* Reputational risks play an important factor for utilities, as the largest utilities are well known by the general public and the risk posed by such companies is widely discussed in California media and politics.

This case study aims to highlight examples of company actions and regulator successes and challenges in this (potentially) similar environment, to help calibrate our expectations for AI company behavior and the risks and opportunities for safety standard strategies.

Based on my research, the following features of safety standard development on California utilities to prevent catastrophic wildfires should provide (further) caution for AI safety standard setting [link all]:

* Creating and enforcing standards while building regulator and company capacity has been a lengthy process (even after motivation among all parties was high).
* Companies and regulators did not sufficiently internalize and respond proactively to catastrophic risk as it rose (even when there were many indications that risk was growing).
* Events that look like warning shots in hindsight generally did not spark sufficient urgency around safety; only the largest and most direct disasters spurred significant regulation.  
* Motives have been mixed and varied, but reputational risk and concern for public welfare have not alone been as influential as profit motive for all companies. 
* Regulators were too slow to address uncertainty about the level and source of catastrophic risk (though sources of risk are much better understood now).
* It can be highly challenging for regulators to create a system with quick enough feedback loops that:
    * incorporates past utility performance into annual regulatory sign off, and 
    * allows for the regulator to update guidelines on safety best practices as evidence for the cost and effectiveness of various safety strategies is limited and changing.

This case study also explores possible benefits and challenges of several regulatory strategies that have been used to prevent wildfires that could be relevant for the AI safety field. [make this sentence more precise]

* Strict, no-fault, legal liability on utilities has been hugely important in shaping utility incentives. Still, it hasn't forced all utilities to take sufficient actions around safety. 
* In the face of legal liability, penalties (or their threat) have not played an important role in motivating utility behavior, though some suggest they could be used more frequently and strongly.  
* The State's dependence on utilities for (affordable) electricity has limited regulator leverage to extract safety actions.
* Tying executive pay to safety outcomes can be a replicable model.
* Establishing regulation of catastrophic risk in a different regulatory body from the body that authorizes funding has created a range of possible benefits and challenges. It may have:
    * helped raise the competence of the safety regulation and utility focus on safety practices,
    * contributed to limiting clarity among all parties on how utilities should best handle safety and economic tradeoffs,
    * created bureaucratic challenges that must be navigated between various regulators.
* (say anything about audits)?

Finally, the case study highlights:

* how private activists have seemingly played an important role in shaping safety standards, despite years of being rebuffed, and
* how voluntary safety actions by (primarily) one utility have helped inform safety policies and raised expectations for other utilities.

This case study is structured as follows:



* The problem that safety standards aim to address link 
* Current standards link 
* More details on each of the key findings listed above, organized by theme (e.g. proactivity vs reactivity, utility motives, etc. link ). [ maybe organize same way as above]

Each section contains bullet points that can be clicked to expand and reveal additional detail.



</div>


## The need for safety standards

Each bullet below can be clicked and expanded to show additional detail.

<div style="margin-top: -20px">

<details class="outerBullet">
  <summary > 
    <span style="margin-left: 4px">
  

California wildfires cause significant death and destruction.  
  </span>
  </summary>
   
  <div class="innerBullet">



 * [Since 2008](https://calmatters.org/california-wildfire-map-tracker/), California wildfires have killed 225 people and damaged or destroyed more than 50,000 structures. Since 2015, they have caused around $25 billion in “property and contents” loss (which does not include lost economic activity or fire suppression costs).


  </div>
</details>


<details class="outerBullet">
  <summary > 
    <span style="margin-left: 4px">

The risk of wildfires has significantly increased in recent decades, almost certainly due to climate change-induced droughts. 
  </span>
  </summary>
   
  <div class="innerBullet">

* Out of California’s [20 largest wildfires](https://calmatters.org/california-wildfire-map-tracker/) up to 2022, seven occurred in 2020 and 2021 alone.
* Climate change appears to be significantly exacerbating catastrophic wildfire risk by increasing drought frequency and severity.


  </div>

</details>


<!-- -------------------------------------- -->
<details class="outerBullet">
  <summary > 
    <span style="margin-left: 4px">

Equipment from California’s utilities is a significant source of wildfires that have killed hundreds of people and caused billions of dollars in damage.     
  </span>
  </summary>
   
  <div class="innerBullet">

* Utility equipment caused fires that burned a [similar number of acres](https://calmatters.org/california-wildfire-map-tracker/) as fires caused by humans or lightning in 2017, 2019, and 2021.
* PG&E, the state’s largest utility, [pleaded guilty](https://www.npr.org/2020/06/16/879008760/pg-e-pleads-guilty-on-2018-california-camp-fire-our-equipment-started-that-fire#:~:text=Hourly%20News-,PG%26E%20Pleads%20Guilty%20On%202018%20California%20Camp%20Fire%3A%20'Our%20Equipment,has%20been%20charged%20with%20homicide.) to 84 counts of involuntary manslaughter following the 2018 Camp Fire, the deadliest wildfire in the state’s history, which was caused by old PG&E equipment. PG&E equipment was [also responsible](https://www.cnbc.com/2022/01/05/california-finds-pge-equipment-responsible-for-massive-dixie-fire-.html) for starting the Dixie Fire, the state’s second largest fire by acreage, which destroyed more than 1,300 homes in 2021. PG&E filed for [bankruptcy in 2019](https://www.nytimes.com/2019/01/29/business/energy-environment/pge-file-bankruptcy.html) after facing liability claims for dozens of fires.



  </div>
</details>
<!-- -------------------------------------- -->

 <!-- -------------------------------------- -->
<details class="outerBullet">
  <summary > 
    <span style="margin-left: 4px">

There is no simple and affordable solution to eliminate wildfire risk from utility equipment.  
  </span>
  </summary>
   
  <div class="innerBullet">

* [Undergrounding](https://www.pge.com/pge_global/common/pdfs/customer-service/other-services/electric-undergrounding-program/PGE-Undergrounding-Fact-Sheet.pdf) sections of overhead power lines eliminates nearly all wildfire risk from those power lines. However, undergrounding all existing overhead distribution and transmission lines is [estimated](https://www.cpuc.ca.gov/industries-and-topics/electrical-energy/infrastructure/electric-reliability/undergrounding-program-description#:~:text=According%20to%20PG%26E%2C%20SCE%20and,to%20%246.072%20million%20per%20mile.) to cost more than $750 billion. Just undergrounding lines in the highest fire risk areas would cost substantially less, though still many hundreds of billions of dollars.



  </div>
</details>
<!-- -------------------------------------- -->
</div>

## Current standards 

* The California Public Utilities Commission (CPUC) is the primary regulator of utilities. In 2022, the Office of Energy Infrastructure Safety (‘Energy Safety’) was created outside of the CPUC to oversee utility processes related to reducing wildfire risk. _See this textbox _link _for more information about the creation of Energy Safety and its interaction with the CPUC._

<details class="outerBullet">
  <summary>
   
  <span style="margin-left: 4px;"> 


Energy Safety issues “[safety certifications](https://energysafety.ca.gov/what-we-do/electrical-infrastructure-safety/wildfire-mitigation-and-safety/safety-certifications/safety-certification-faqs/)'' to qualifying utilities. Failure to receive a safety certification would significantly harm a utility’s financial standing. _Click to show more_
  </span>

  </summary>

  <div class="innerBullet">

* Receiving a safety certification increases the chances that a utility could draw on the [California Wildfire Fund](https://www.cawildfirefund.com/#:~:text=The%20California%20Wildfire%20Fund%20exists,caused%20by%20the%20participating%20utility.) to repay victims of a wildfire caused by its equipment, for which the utility would be automatically liable. (_More information about legal liability facing utilities here_link _.) _Experts stressed that failure to receive safety certification would immediately cause a significant stock price drop for the utility, and would likely lead to a drop in its credit rating. 



  </div>
</details>

* Core requirements for a safety certification [include](https://energysafety.ca.gov/what-we-do/electrical-infrastructure-safety/wildfire-mitigation-and-safety/safety-certifications/safety-certification-faqs/):

<details class="outerBullet indent">
  <summary> 
    <span style="margin-left: 4px; margin-top: -20px">

a **safety culture assessment,**
 
   </span>
  </summary>
   
  <div class="innerBullet">

- Second level, first BULLET


  </div>
</details>


----------------
----------------









<!-- TEMPLATES ------------------------------------------------------------- -->
<!--  -->
<details class="outerBullet">
  <summary> 
    <span style="margin-left: 4px; margin-top: -20px">
      
TOP BULLET HERE
    </span>
  </summary>
   
  <div class="innerBullet">

- Second level, first BULLET


  </div>
</details>

<!-- ONE LEVEL OF NESTING -->

<details class="outerBullet">
  <summary> 
    <span style="margin-left: 4px">
      TOP BULLET HERE
    </span>
  </summary>
   
  <div class="innerBullet">

- Second level, first BULLET


  </div>
</details>

<!-- TWO LEVELS OF NESTING -->

<details class="outerBullet">
  <summary> 
    <span style="margin-left: 4px">
      TOP BULLET HERE
    </span>
  </summary>
  
 
  <div class="innerBullet">


- Second level, first BULLET


  </div>

  <details style="margin-bottom: 0px; margin-top: 12px; margin-left: 25px;">
    <summary>
      <span style="margin-left: 4px">
        Second level, COLLAPSABLE
      </span>

    </summary>

  <div  style="margin-left: 10px; margin-top: 12px">

- Third level, first BULLET


  </div>
  </details>
</details>

...

<div class="footnotes">
  <ol>
    <li id="note1">This is the content of the first footnote. <a href="#backref1" class="backref">↩</a></li>
    <!-- ... Other footnotes ... -->
  </ol>
</div>
