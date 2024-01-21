# Section 3 Notes (Week 2) - Methods

## Table of Contents
1. [3.1 Intro to Methods](#3.1-intro-to-methods)

## 3.1 Intro to Methods

We are always designing to better meet the needs of existing designs. We need to incorporate user needs at every stage of the design process. Novelty should have a purpose.

### User Centered Design
Consider the needs of the user throughout the design process. Functional specifications should be considered after the real needs of the user. 
User needs are prioritized - and not known. They need to be involved at **every** stage of the process.
The user needs to be asked and observed prior to starting a project, and should be checked with frequently related to prototypes.
Users should evaluate the quality of a design.

Interact with users, understand their needs, and involve them!

#### Six principles:
1. Design is based on explicit understanding of users, tasks, environments. Use this knowledge throughout the design process
2. Users are involved throughout the design process - they can give feedback, but also perhaps work on the design team directly.
3. The design is driven and refined by user evaluation. they get to decide
4. iterative process - constant interation and improvement of designs
5. design addressses the whole user experience - entire ux should be considered
6. design team contains multidisciplinary skills and perspectives - computer science, domain experts, psychologists.


#### Who are the users?
All three types of users should be considered when creating/refining designs.

**Primary Stakeholders:** Those who use the tool directly
**Secondary Stakeholders:** Those who interact with tools output, but not the system itself
**Tertiary Stakeholders**: Affected by the existence of the system.

---

In many jobs, the software engineers are often required to design the interface themselves.

There are a lot of new tools that allow us to have a new, different ux for old tasks! these are products that create a major differentiator.

---

#### How to have an effective UCD?

We need to know two things:
1. Who the user is?
2. How to integrate the user into each phase?
 
---

### Design Life Cycle

Four phases. Iterative process... even after launch
1. Need finding - who the user is? why they are doing the task? any context?
2. Design multiple design alternatives - different ideas about different ways to approach a task
3. prototyping - take the ideas with the most potential, build into prototypes and show the user.
     - might start with lo fi
     - develop into hi fi
4. user evaluation - get user feedback from real users. then we start over


We are always gathering info from the user... need some methods!

#### Methods
Feedback cycles are important to HCI. Based on the output of evaluations, we design more, then test, then design more. try to make a better interface.

1. Quantitative data - objective comparisons, calculative. but is narrow view. provides the what? do after starting qualitative

2. The type of data we have determines our methods - we use the same types of approaches for nominal and ordinal - interval and ratio. rarely come across interval, ratio more common
     1. nominal - categorical - number of instances of different **categories**. number of people in each category.
          1. single nominal, multinominal (multiple categories).
          2. binary vs non binary (y/n vs multiple options to pick from)
     2. ordinal data - specific order of answers for each category. we don't know the gaps between categories. (highly satisfied, slightly satisfied, not satisfied, very disatisfied)
          1. single nominal, multinominal (multiple categories).
          2. binary vs non binary (fail/pass vs multiple options to pick from)
     3. interval data - we know the specific difference between each category. the interval is constant between the categories. we don't know the ratio... no zero point either
          1. discrete - countable - whole number
          2. continuous - not easily countable, more exact - can inform type of specific methods
     4. ratio data - like interval, but has a zero point. we can use ratios to understand.
          1. discrete - countable - whole number
          2. continuous - not easily countable, more exact - can inform type of specific methods 
4. Qualitative data - descriptions, observations. flexible. broader and more general. harder to generate formal conclusions. have to fight biases. sometimes we can convert qualitative into quantitative data. provides the why? do first!
   Typically determined by how it is gathered. it is a large set of possibilities.
   More expensive to analyze and prone to bias. can convert to quantitative for analysis.
   Code the qualitative data into nominal, quantitative data. We lose some of the rich data, but gain a numeric representation. Provides documentation and support for our data, by showing how we derived the quantitative data from the qualitative data. We need to maintain a mix!!
   Types:
     1. Transcripts
     2. Field Notes
     3. Artifacts
5. Mixed method - mix quantitative and qualitative data together to get a better picture of the reuslts
---

## 3.2 Ethics and Human Research

Milgram experiment, Tuskegee Syphillis Experiment, and Stanford Prison Experiment led to the National Research Act of 1974.
The NRA of 1974 led to the Belmont Report - outlining ethical practices that research must follow.
Institutional Review Boards (IRBs) are responsible for overseeing research, if govt support will be provided. Benefits to society must outweigh risks to subjects. Subjects must be selected fairly. Rigorous informed consent procedures are required. Positive results need to outweigh negatives, and participant rights need to be a primary concern.

IRB makes sure that benefits of studies are useful. Sensitive about participation coerced. Sensitive about bias.

Need IRB approval to get approval to do studies...
CITI training is required. Then we can use IRB Wise after taking training.

Should know about the protocols:
- Starts with title of protocol and associated personel, select each person
- primary investigator (faculty member) must be added first.
- protocol description - description, goal of study
- Protcol: methods of study - participant experiment
- data collection methods, understand participant requirements, benefits of study and risks
- plan for stats analysis
- start/end dates - separate data collection and analysis fields
- subject details - we are doing human interaction, so we need to describe subjects and data that we will collect. how many subject. how many genders.
-   - are we targetting vulnerable populations - might need special considerations
    - number of subjects - want to make sure that we aren't wasting the time of participants.
    - inclusion criteria - who is the target audience
    - exclusion criteria - who are we specifically excluding from being able to participate.
- steps to protect vulnerable populations, their rights.
- describe recruitment procedures - how subjects will be found and selected.
- compensation? is there some money being given to participants?

 can sometimes get a waiver (if subjects are not directly affected by resesarch - like already existing data that we will reanalyze).
 simple observations that do not identify anyone could be waived also.
 waiver of documentation of consent can be done for low risk research, where the waiver would be the only documentation of participation. this is the only way we could idenitfy someone
 describe plan for getting informed consent - provide it at the start and make sure they know they can withdraw. might need other things for other languages. check continual consent.
 we want to get to implied continued consent...

 Sometimes we need to deceive participants to get better research data - we need to indicate...
data management section - describe how we keep participant info safe and how it will be protected.



 upload consent forms! can use the GATech templates.

 usually 3 week turnaround time for acceptance of studies... 


 ---
 Private research does not require an IRB. Companies may do research on their users. A lot of rapid ab experiments.

 **Experimental Evidence of massive scale emotional contagion through social networks** - FB tested out tweaks to news feed to manipulate user needs. They argue that it is consistent with their use policy. Some people think that they violated informed consent principles. Coercion?

Might need separate principles and practices for industry research - a separate set of standards may need to be created. 
Facebook has their own IRB - they defer to a research expert. Companies are required to govern themselves in the absence of legislation.


We should only:
1. keep respect for participants at the forefront - don't waste their time, respect their position in the design process.
