# Section 3 Notes (Week 2) - Methods

## Table of Contents
1. [3.1 Intro to Methods](#3.1-intro-to-methods)
2. [3.2 Ethics and Human Research](#3.2-ethics-and-human-research)
3. [3.3 Needfinding and Requirements Gathering](#3.3-needfinding-and-requirements-gathering)

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

### Mackenzie Chapter 4

#### What is research?
Providing credibility.

Three definitions:
1. careful/diligent search (like looking for files).
2. collecting information about a particular subject, like political surveying.
3. investigation/experimentation aimed at the discovery and interpretation of facts and revision of accepted theories or laws in light of new facts. Theories are more general than laws. We have some laws, like **Fits Laws** - a model describing the time it takes to do point-select tasks.

We want to have a formal and standardized methodology for doing research in HCI - more standardization. Empirical research encompasses experimental and non-experimental methodologies.

HCI research **does not prove** things. We just gather facts and formulate and test evidence.

Research must:
1. be published
   -  Research must be published! Knowledge gained through research needs to be shared, to refine and extend the existing body of knowledge in the field. Need high scrutiny in peer-reviewed journals. Patents are also a publication  - company can retain ownership and also make it public
2. use citations, work within body of research
   - Research papers use citations and references to connect papers together. Creates and connects a body of research. At the end of a paper, references are provided that provide the full resource, not just a brief citation. Citing previous work acknowledges that research continues, extends, and refines other research. Allows us to backup questionable assertations. More citations = more significant. **H index** is used to measure the impact of a researcher's publication record -  point where rank equals the number of citations. quantifies research productivity and impact of a body of work.
3. be replicable
    - need to be able to replicate it. standardized method makes it easier, provide methods in paper.


 Resarch vs design?
 - Engineers, designers create stuff and work on products. Research is more narrowly focused. Small ideas are focused on in resarch, prototyped, tested, and advanced or discarded. New ideas in research are incremental, building on others. Research prototypes are early on - and won't appear directly in products usually.Prototypes should not be too finished - don't waste time making too perfect or you won't benefit from feedback. Research is slower than design or engineering and may only be incorporated later. Researchers provide raw materials and processes for engineers.


#### Empirical Resarch
Based on observation or experience - don't just follow existing theory. Should be capable of being verified or disproved by observation or experiment - need hypotheses. Assertions should be narrow and clear.

#### Research Methods

##### Observational Methods
observe humans interacting with computers. examples: interviews, field investigations, contextual inquiries, case studies, field studies, focus gorups, think aloud protocols, storytelling, walkthroughs, cultural probs.

QUALITATIVE DATA - not precise but VERY RELEVANT. 

directly observe in natural setting - not in a lab.

discover the why/how of an interaction - reasons for behaviors - focus on thoughts, feelings, emotions, attitudes, reflection, sentiment, style, approach , etc.

not many measuements - a lot of notes, photos, videos, recordings. Measurements are categorical.

##### Experimental Method
controlled experiments in a lab.

QUANTITATIVE DATA - precise, but not very relevant.

Need two variables: manipulated and response variable.
- manipulated variable is shown to participants in different configurations. **indepdendent variable**
- response variable is human behavior property that is observable, quantifiable, measurable. like time! something measurable... **dependent variable**

need to have two configurations at least. usability evaluation and user testing are not experimental methods, because there is not a manipulated variable. A User study does typically involve multiple configurations are tested and compared. Usability evaluation is usually just a single interface and config, so not experimental.

Experimental methods still involve some observation.

Experimental methods, that are well designed, allow powerful conclusions to be drawn. Cause/effect.

##### Correlational Method
- looks for relationships between variables - quantification of multiple variables. categories
- data collected through observations, interviews, surveys, questionnaires, measurements.
- work in conjunction with experimental methods.
- balance b/w relevance nad precision. not controlled, but can connect better to real-life experiences.
- data is curcumstantial - not cuase/effect like experimental




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

## 3.3 Needfinding and Requirements Gathering

### Needfinding Intro
What is needfinding?? The first stage of the design process. understand the user, their task, their why.
We need to abandon our preconceived notions. Abandoned our pre-designed solutions. Avoid these.

Process:
1. Define questions about who the user is, what they need
2. Generate answers to these questions
3. Formalize models of user into unique requirements for the ui.

### Data Inventory
Gather data as we go along and store our data.

1. Who are the users?
2. Where are the users? Environment
3. What is the context of the task?
4. What are the goals of the user?
5. What do users need, right now? Info? Collabotors
6. What are their tasks? 
7. What are the subtasks? How do they accomplish them?

### Problem Space
Where is the task occuring, what else is going on, what are the needs of the user?

We need to understand the scope of our problem. Take a broad approach. not too narrow.

### User Types

Get an idea of the space of the user. Who are we designing for? Get the full range! Walkman did a great job of this.

### Avoding Bias

Five biases:
1. Confirmation Bias - we see what we want to see! We have preconceived notions and only see these. Test beliefs empirically, involve multiple people in the design process, looking for signs we are wrong
2. Observer bias - we might bias users based on our input, how we phrase questions, etc. Separate experimentors from motives, heavily scripting interactions, and having someone else review scripts for leading questions
3. Social desirability bias - people tend to be nice. If participants know that we are teh designer, we might have just polite responses. Try to hide the social desirable response, conduct more naturalistic observations, and record more objective data.
4. voluntary response bias - people with stronger opinions will respond more often to surveys, skew feedback. quantitative risks oversampling extreme views. limit this by limiting how much content is shown to users when they begin the survey, and confirming any conclusions with ohter methods
5. recall bias - people aren't good at recalling what they did or how they felt if it was in the past. study tasks in context, have users think aloud during activities, oor conducting interviews during the activity itself.

### Naturalistic Observation
Just watching. observe in natural contexts. limited, in that we cannot ask questions.

5 tips:
1. take notes - gather targetted info
2. start specific, then abstract - don't summarize too soon
3. spread out session - repeated, shorter sessions better than just one big
4. find a partner - observe with someone else. compare notes.
5. look for questions

### Participant Observation
Try doing it yourself! and see what you figure out...
but remember, you are not the user!

### Hacks/Workarounds/errors
Check to see what non-intended ways users may create to make tasks easier. ask them why they have a workaround
Errors are a great source for informing methods - see what errors users run into often. this will help us understand our user model.

### Apprenticeship/Ethnography
Become a participant, learn to be a user! integrate self into area and beceome an expert. learn about things as you go.

### Interviews/Focus Groups
Just talk to users and ask them questions. can be 1:1 or group.  groups might promote group think

Tips:
1. 6 ws - who? what? when? where? Why? How? avoid yes/no questions. ask open ended, semi-structured questions
2. be aware of bias
3. listen! do not predispose them and don't talk too much
4. organize - intro phase, lighter questions to build trust, and a summary to teach purpose.
5. practice interviewing and questions on others.

### Think Aloud
Ask users to talk about their perceptions of the task, while they perform it! Ask them to think aloud and doing the task. encourage users to think about more deliberately - which may change the way that they act.
do a post event protocol - get the thoughts right after they finish. still fresh, but performance not impacted as much

### Surveys
Allow us to get some broader data without super intensive time sinks. quick interpretation and can be done async. can be useful to build interview/focus group questions.

Tips:
1. Less is more - don't ask too much. impacts response rate and reliability of data. keep q to minimum.
2. be aware of bias - look at question phrasing for pressure, bias
3. tie them to the inventory - every question should connect to data that we want to gather. start with goals, then questions
4. test it out - have coworkers or colleagues test it out, pretend that they are real users
5. iterate - make sure to constantly improve survey after testing. let the respondents give feedback

Surveys are used often, but can only be useful if we are writing good questions.

Advice for good questions:
1. Be clear  - user should understand what we are asking. if giving a number number, make sure to provide some labels for the values. avoid overlapping ranges, they should be separate. if in doubt if user will understand, give extra information about what you are asking. if asking about frequency, timebox the question. give specific numbers, ask frequency within a certain period of time.
2. Be concise - ask plain language. need to balance b/w clear and consise
3. Be specific - questions should not be massive. break into separate smaller questions. avoid double barrel questions -ask just one question at a time. don't allow internal conflict...
4. Be expressive - allow the user to be expressive - emphasize their opinions with how we are asking questions. use ranges, not yes/no. with levels of frequency/agreement, provide a lot of levels (at least 5). allow multiple selections, if possible. Let them add new categories if possible
5. Be unbiased - allow open ended responses at times. give other boxes. maybe just leave open-ended questions, open.... avoid leading questions
6. Be usable - give a progress bar to users. make page lengths consistent. order questions logically. alert users about unanswered questions. preview the survey yourself and fill it out.

### Other methods
1. critique existing designs
2. Look at reviews about existing products - see what people like and dislike.
3. Data logs - check data for what goes wrong, how users actually utilize the app.

### Iterative Needfinding

Just like the design process should be iterative, needfinding can also be iterative. 
We can bounce from naturalistic observation -> participant observation -> ethnography -> interviews -> hacks&errors -> surveys -> focus groups -> think-aloud and then start the cycle over again. Constant iteration and learning from the new research we have gathered. 

### Revisting Inventory
- after combining approaches, pay attention to where data seems to conflict. places where you might not understand the task well enough. compare against interview
- who are the users
- where are the users
- what is the context of the task
- what are the goals of the user
- right now, what do users need
- what are their tasks
- what are their substasks

what more might we need to know to figure this out?


### Represent the need
after resaerch, we want to formalize our research. get a step by step outline of tasks, break down to subtasks - hierarchical or linear series of tasks. make a structural diagram of the tasks, how the various pieces interact and create loops. flowchart with decisions


### Define Requirements
determine the requirements, that are unique and measurable, that we must meet. They may be outside user tasks. Define:
1. Functionality - what the interface can do
2. usability - how interactions must work
3. learnability - how fast is it for a new user to learn
4. compatibility - where it can run
5. compliance
6. cost
7. 
