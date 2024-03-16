<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Section 2.6 - Mental model and representation](#section-26---mental-model-and-representation)
    - [Mental Models](#mental-models)
    - [5 tips for learnable interfaces:](#5-tips-for-learnable-interfaces)
    - [Representations](#representations)
        - [Characteristics of Good Representations](#characteristics-of-good-representations)
    - [Analogies and metaphors](#analogies-and-metaphors)
    - [Learning Curves](#learning-curves)
    - [User Errors](#user-errors)
    - [Types of Slips](#types-of-slips)
    - [Types of Mistakes](#types-of-mistakes)
    - [Learned Helplessness](#learned-helplessness)
    - [Expert blind spot](#expert-blind-spot)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Section 2.6 - Mental model and representation

**Mental Model** - the understanding in your head that you hold about the world around you.

Good interfaces require good mental models.

**Representations** - are internal symbols for an external reality.

We need good representations to have good mental models.

## Mental Models

A mental model is a person's understanding of how the world works. It is how we generate predictions
and expectations, and we check against these to understand what has happened.

To make sure we provide users with a good mental model - we should:

1. design systems that work the way people expect them to act
2. design systems that teach people how they will act

Mental models are also important in education. We are the educator in our interface. Good
representations help teach users while they are using it.

## 5 tips for learnable interfaces:

1. Predictability - users should be able to predict what will happen from an action
2. Synthesizeability - users should also be able to see the sequence of actions that led to current
   statement
3. Familiarity - interface should leverage actions that are familiar to the users.
4. Generalizeability - knowledge of one interface should generalize to another. do things in a
   common fashion.
5. Consistency - similar tasks within an interface should behave the same way.

## Representations

Choose how things are visualized, which determines the mental model of users.

### Characteristics of Good Representations

1. Make relationships explicit
2. Bring objects and relationships together
3. Excludes extraneous details
4. Expose natural constraints

## Analogies and metaphors

Help build a foundation for users in something that they already know (like how newspaper websites
mirror the print editions).

However, users don't know when the analogy or metaphor ends . Using analogy may make the interface
more learnable, but might
restrict it to certain outdated
design decisions or commands.

Design Principles:

1. People reason by analogy to understand interfaces, so need to be consistent!
2. interface should teach the user how the system works, like affordances and signifiers.
3. representations are important because they map the interface to the task at hand. good
   representations allow the user to predict the mappings between interface and outside world.

When there is the new functionality with an old interface, it is hard to change the model.

## Learning Curves

Expertise vs experience - steeper is better, means we can learn it faster.
use analogies and representations that are familiar to they can learn more quickly - develop
expertise quickly.

use representations and affordances to help users understand how we see things. start them off with
initial expertise or help them grow their experience as fast as possible.

## User Errors

Error can happen because of stress or perhaps our interface is not really clear.

In design, there is no such thing as user error - instead, it is the failure of interface to guide
the user.

Two types of errors:

1. Slips - user has the right mental model, but does the wrong thing anyway.
2. Mistake - user has the wrong mental model, so does the wrong thing.

## Types of Slips

1. Action-Based slips - places where user performs wrong action, or right action on wrong object, even
   though they know what they really should do.
2. memory lapse - user forgets to do something they know to do.

## Types of Mistakes

1. Rule based - user correctly assesses the state of the world, but makes the wrong decision
2. Knowledge based - user incorrectly asses the state of the world
3. memory lapse - user forgets to do the fully executed plan.

We want to prevent all errors - leverage consistent practices to prevent routine errors, offload
cognitive load onto interface to help memory based errors, and leverage good representations and
affordances to help rule-based and knowledge-based errors.

## Learned Helplessness

User should learn from output what they should input in the future. Feedback loop from interface.

When there is no interaction between i/o - break in cycle, then learned helplessness occurs.

Human learns that they are helpless to learn to use the system - they cannot do anything in the
interface!

## Expert blind spot

When you are an expert at a task, and don't think about all the steps or just know what to do, you
have a blind spot!

Teaching user through the interface - you have to overcome the expert blind spot, because we are not
the user.
