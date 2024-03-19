<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Design of Everyday Things—Chapter 5](#design-of-everyday-thingschapter-5)
  - [Root Cause Analysis](#root-cause-analysis)
  - [5 Whys](#5-whys)
  - [Deliberate violations](#deliberate-violations)
  - [Two types of errors: Slips and Mistakes](#two-types-of-errors-slips-and-mistakes)
    - [Slips](#slips)
    - [Mistakes](#mistakes)
  - [Errors and the 7 stages of actions](#errors-and-the-7-stages-of-actions)
  - [Classifying slips](#classifying-slips)
  - [Classifying mistakes](#classifying-mistakes)
    - [Rule-based mistakes](#rule-based-mistakes)
    - [Knowledge-based mistakes](#knowledge-based-mistakes)
    - [Memory-Lapse Mistakes](#memory-lapse-mistakes)
  - [Social and Institutional Pressures](#social-and-institutional-pressures)
  - [Checklists](#checklists)
  - [Reporting Error](#reporting-error)
    - [Jidoka - Toyota](#jidoka---toyota)
    - [Nasa's aviation safety reporting system](#nasas-aviation-safety-reporting-system)
    - [Detecting Error](#detecting-error)
  - [Explaining away errors](#explaining-away-errors)
    - [Hindsight](#hindsight)
  - [Designing for Error](#designing-for-error)
  - [Design lessons](#design-lessons)
    - [Adding constraints to block errors](#adding-constraints-to-block-errors)
    - [Undo](#undo)
    - [Confirmation and error messages](#confirmation-and-error-messages)
    - [Sensibility Checks](#sensibility-checks)
    - [Minimizing Slips](#minimizing-slips)
    - [Swiss Cheese model of errors](#swiss-cheese-model-of-errors)
  - [Resilience Engineering](#resilience-engineering)
  - [Paradox of Automation](#paradox-of-automation)
  - [Design Principles](#design-principles)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Design of Everyday Things—Chapter 5

Unnatural tasks and behaviors cause a lot of errors, as are interruptions, and the attitude of
people towards errors.

Should not blame people who make errors. We should figure out why the error happened, and then make
sure
that it does not happen again.

## Root Cause Analysis

Find the underlying cause.

This is hard because:

1. most accidents have multiple causes
2. we should not stop at human error—we should keep asking questions even when human error is
   found.

## 5 Whys

Do not stop asking why until you have asked why five times. There is still a tendency to stop too
soon
when asking the 5 whys, and overemphasizes the need to find a single cause for an incident.

Poor mapping causes a lot of errors. We have to admit that problems exist, and not blame people.

Time stress causes errors.

## Deliberate violations

Why do people violate laws? Rules are often written to ensure legal compliance, not understanding
the work that needs to be done.

Bad rules encourage violation.

## Two types of errors: Slips and Mistakes

Human error—any deviance from appropriate behavior.

Error—all wrong actions—two main types: slips and mistakes.

### Slips

Someone intends to do one action and ends up doing something else.

Two classes:

1. Action-based: wrong action is performed
2. Memory-lapse: memory fails, so the intended action isn't done or evaluated.

### Mistakes

Mistakes occur when the wrong goal is established or the wrong plan is formed.

Three classes:

1. Rule-based - the person has diagnosed the situation but decides to do the wrong thing
2. Knowledge-based - the person has bad or incomplete knowledge
3. Memory-lapse - the person forgets at the stage of goals, plans, or evaluation.

## Errors and the 7 stages of actions

Mistakes are often errors in setting the goal, plan, or evaluation of results. Memory lapses can
happen at any transition between stages, and result in the next stage not being completed.

## Classifying slips

Most errors are slips, and they happen more to experienced users because of lack of attention.

Three main kinds of action slips:

1. capture slips—instead of a desired activity, a more frequent activity is performed instead. For
   this, part of the action sequences need to be identical
2. description-similarity slips—correct action on the wrong object. controls and displays for
   different purposes need to be significantly different from one another.
3. mode errors—device has different states in which the same controls have different meanings.
4. memory lapse errors — can lead to forgetting to do several steps of a procedure, repeating steps,
   forgetting outcomes of actions, or forgetting the goal. Usually, interruptions are the reason
   that
   we forget. To combat them, we can minimize the number of steps and provide vivid reminders of
   steps that need completed. We can also force and constrain behavior to make it so that once we
   start, we cannot do the forgetful action.

## Classifying mistakes

Mistakes result from the choice of inappropriate goals or plans or from the faulty evaluation of
whether our goals are met. This happens more often if we have to rely upon remembered experiences,
because we make decisions based on what we can remember.

Three modes of behavior:

1. Skill-based - workers are experts (slips happen)
2. Rule-based - normal routine is no longer applicable, but the new situation is known—so there
   is already a rule to use. (slips or mistakes can happen). If we select the wrong rule, this is a
   mistake—if the error occurs while we are executing the correct rule, then it would be
   considered a slip.
3. Knowledge-based - unfamiliar events occur and existing skills/rules do not apply. We have to rely
   on reasoning and problem-solving. We need good conceptual models to guide plan development and
   interpretation.

When we misdiagnose, we run into issues for rules and knowledge-based behaviors. This often results
in us choosing the wrong rule or the wrong problem.

### Rule-based mistakes

When new procedures have to be invoked or simple problems arise, we rely on rules. Some rules
may be formal and other informal.

Identify the situation -> select the rule -> follow the rule.

Mistakes occur in multiple ways:

1. The situation is mistakenly interpreted, so we choose the wrong rule
2. The correct rule is invoked, but the rule is faulty because it was not formulated properly or
   because our situation has something that changes the rule.
3. The correct rule is invoked, but the outcome is incorrectly evaluated.

We have to present information about the state of the system in a way that is straightforward to
interpret, and
provide alternative explanations and interpretations.

### Knowledge-based mistakes

Knowledge-based behavior takes place when a situation is novel, and we have to create a new
procedure.

We need a good understanding of the situation and an appropriate conceptual model. In complex cases
need cooperative problem-solving skills and tools. Sometimes good procedure manuals can do the job
or intelligent computer systems.

### Memory-Lapse Mistakes

Memory lapses can lead to mistakes if we forget the goal or plan of action. Often, interruptions are
the reason for mistakes, because the goals and plans become wrong due to forgetting the evaluation
state of the environment.

To fix these, ensure that all relevant information is continuously available.

## Social and Institutional Pressures

We sometimes feel pressure to act a certain way or break the rules in a certain fashion because of
societal pressures.

Social pressures can be overcome, but we need to have rewards for safety and place safety above
economic pressures.

## Checklists

Checklists increase the accuracy of behavior and reduce error, both memory lapses and slips.

When we have multiple, complex requirements and interruptions, checklists are great.

Doing tasks in groups may make things less careful and accurate as people become lazier. Checklists
are a good way of doing this.

Commercial aviation uses collaborative checklists, but medical professionals are pretty resistant.

Checklists are hard to design - should be iterative and human-centered. A list should not be too
burdensome to perform.

Electronic checklists are better than paper, so they can be re-ordered as needed.

## Reporting Error

People can't always detect or admit when there is an error.

We have to admit that they exist, avoid stigmatizing, and encourage the reporting of errors/reward
those who do find errors.

### Jidoka - Toyota

Jidoka is automation with a slight human touch.
If workers notice something wrong, they should report it right away and the experts come to see why
something happened.

Poka-yoke - error proofing. Add simple fixtures, jigs, or devices to constraint operations until
they are correct.

### Nasa's aviation safety reporting system

NASA as an independent agency set up a method for pilots to report anonymously, and NASA would make
recommendations to the FAA after a number of reports.

### Detecting Error

We need to discover errors quickly. If there is no feedback, how can we detect?

Memory-lapse slips are hard to detect - the required action is not performed.

Mistakes are hard to detect because it is hard to know that someone has an inappropriate goal.

Memory-lapse mistakes, the entire plan is forgotten, so we can't see it.

## Explaining away errors

We often just attribute errors to something easy, convenient, and don't look at an error.

### Hindsight

Hindsight makes things clear and obvious, but it is not the case when we are in the middle of the
situation. This is part of the reason that we have to take al ong time to do accident analyses.

## Designing for Error

Systems make it easy to error and impossible to discover or recover from errors.

To fix this:

1. Understand the causes of error and design to minimize those cases.
2. Do sensibility checks
3. Make it possible to reverse actions
4. MAke it easier for people to discover that an error occurred, and easier to correct
5. Don't treat the action as an error, but instead try to help the person complete the action
   properly.

Novices are more likely to make mistakes than slips, while experts are more likely to make slips.

Mistakes happen because of ambiguous or unclear information, the lack of a conceptual model, and
inappropriate procedures. Bad goal/plan or evaluation/interpretation because of poor information
provided by the system and bad feedback.

It is hard to design good warning signals, because the multiple devices should work in unison, but
not be overwhelming.

## Design lessons

### Adding constraints to block errors

Add constraints, with clever use of shape and size for physical items, to prevent using the wrong
one.

For electronic devices, segregate controls and separate modules.

### Undo

Add the undo commands to allow users to easily undo and reverse their operations.

### Confirmation and error messages

Requests for confirmation often become an irritant instead of the essential safety check. Rather
than
asking for confirmation, it might be better to show both the action to be taken and the object and
allow the users to make the choice.

The item being acted upon should be more prominent.

Operations should be reversible.

### Sensibility Checks

Good systems should check that what is being done is sensible, and if not, prompt the user to
double-check.

### Minimizing Slips

Slips occur when someone is distracted or too much of an expert to focus any longer. Rather than
making someone always be 100% focused on our tasks, we should try to do a few other things...

Slips can be minimized by ensuring that actions and controls are as dissimilar as possible—or far
apart. Modes should be limited.

Providing perceptible feedback about the nature of the action being performed, any changes to the
state, and mechanisms to allow us to reverse the action.

### Swiss Cheese model of errors

Because there are often many causes for errors, and we cannot just address a single issue, we
should do the following:

1. Add more lines of defense
2. Reduce the number of points where the error can occur, or where it would have the greatest
   impacts
3. Alert human operators if several problems are lining up

## Resilience Engineering

Design systems, procedures, management, and train people, so they can respond to problems that
arise.
Test and improve design constantly.

## Paradox of Automation

When tasks get too complex, automation cannot keep up, but this is when we need it the most.

When automation does fail, it does so without warning.

## Design Principles

People and machines should be thought of as collaborative systems.

Human error is a human action that is inappropriate for the needs of technology, so we should try to
eliminate these concepts of errors. Errors are inevitable, so we should mitigate and protect against
them.

1. Put the knowledge required to operate the technology in the world, not in memory. make it clear
   so that others can refer to documentation or the system teaches the user while they are using it.
2. Use the power of natural and artificial constraints
3. Bridge the gulfs of execution and evaluation—make things visible, provide good feedback, and
   make the options readily available.
