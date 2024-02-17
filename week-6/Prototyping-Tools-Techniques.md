<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Prototyping Tools & Techniques](#prototyping-tools--techniques)
  - [What is a prototype?](#what-is-a-prototype)
  - [Prototypes as Design Artifacts](#prototypes-as-design-artifacts)
    - [Representation](#representation)
    - [Precision](#precision)
    - [Interactivity](#interactivity)
    - [Evolution](#evolution)
  - [Prototypes and Design Process](#prototypes-and-design-process)
    - [User-Centered Design](#user-centered-design)
    - [Participatory Design](#participatory-design)
    - [Design Space](#design-space)
    - [Expanding Design Space-Generating Ideas](#expanding-design-space-generating-ideas)
    - [Contracting Design Space—Selecting Ideas](#contracting-design-spaceselecting-ideas)
  - [Prototyping Strategies](#prototyping-strategies)
    - [Horizontal Prototypes](#horizontal-prototypes)
    - [Vertical Prototypes](#vertical-prototypes)
    - [Task-Oriented Prototypes](#task-oriented-prototypes)
    - [Scenario-Based Prototypes](#scenario-based-prototypes)
  - [Rapid Prototyping](#rapid-prototyping)
    - [Off-line Rapid Prototyping Techniques](#off-line-rapid-prototyping-techniques)
      - [Paper & Pencil Prototypes](#paper--pencil-prototypes)
      - [Mock-up Prototypes](#mock-up-prototypes)
      - [Wizard of Oz](#wizard-of-oz)
      - [Video Prototypes](#video-prototypes)
    - [On-line Rapid Prototyping Techniques](#on-line-rapid-prototyping-techniques)
      - [Non-Interactive Simulations](#non-interactive-simulations)
      - [Interactive Simulations](#interactive-simulations)
      - [Scripting Languages](#scripting-languages)
  - [Iterative Prototypes](#iterative-prototypes)
    - [Software Tools](#software-tools)
      - [Graphical Libraries and Windows Systems](#graphical-libraries-and-windows-systems)
      - [UI Toolkits](#ui-toolkits)
      - [UI Builders](#ui-builders)
      - [Application Framework](#application-framework)
      - [Model-Based Tools](#model-based-tools)
      - [UIDE-User Interface Development Environments](#uide-user-interface-development-environments)
  - [Evolutionary Prototypes](#evolutionary-prototypes)
    - [Software Architecture](#software-architecture)
      - [Seeheim and Arch](#seeheim-and-arch)
      - [MVC and PAC](#mvc-and-pac)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Prototyping Tools & Techniques

## What is a prototype?

__Concrete representation__ of part or all of an interactive system.

Tangible design activity. Use software engineering to ensure prototypes evolve into a sound, working system and
scientific methods to study the effectiveness of designs.

## Prototypes as Design Artifacts

Characteristics of prototype as design artifacts:

- Prototypes support creativity - idea generation, idea exploration, and learning about users.
- Prototypes encourage communication and collaboration amongst different disciplines.
- Prototypes permit early evaluation.

Four dimensions for analyzing prototypes:

1. Representation—form of the prototype
2. Precision—level of detail
3. Interactivity—the extent to which a user can interact with the prototype
4. Evolution—expected lifecycle of the prototype

### Representation

Off-line and on-line representation make up the two main forms. Representation deals with the form/medium of the
prototype.

1. Off-line prototypes (paper)—no computer required. Paper sketches, story boards, cardboard mock-ups.
    - quick to create
    - rapid iteration
    - throw away
    - Pros:
        - rapid iteration. explore the whole design space.
        - don't constrain designer thought.
        - off-line prototypes can be created by anyone!
    - Cons:
        - Not great for interfaces requiring rapid feedback to users or complex visualizations.
2. On-line prototypes (software)—computer required. Wireframes, interactive prototypes.
    - more expensive to create
    - more effective at later stages of design

### Precision

Relevance of details with respect to the purpose of the prototype. Tension between what the prototype states (relevant
details) and what the prototype leaves open (irrelevant details).

A detailed representation need not be precise. Maybe only some parts are precise.

Precision usually increases as more prototypes have been tried

Form of prototype (representation) helps dictate precision - harder to be precise with off-line than on-line prototypes.

### Interactivity

In off-line prototypes, one person plays the role of the interactive system.

In on-line prototypes, parts of the software are implemented and others are played by a person (__wizard of oz__).

**Fixed prototypes** are non-interactive. Used for quick tests or scenarios.

**Fixed-path prototypes** support limited interaction. Used for scenarios, horizontal, and task-based prototypes.

**Open prototypes** support full interaction with small feature-set. Used for vertical prototypes. Limited performance
and error-handling compared to the real system.

### Evolution

Rapid prototypes vs. iterative prototypes.

1. Rapid Prototypes—important at the beginning, quick, cheap. Throw away and build another.
2. Iterative prototypes—developed as a reflection of a design in progress. Iterate several times and refine.
    - Evolutionary Prototypes—special kind of Iterative prototypes in which the prototype evolves into part or all of
      the final system. XP uses this. Needs a lot of planning and practice.

## Prototypes and Design Process

### User-Centered Design

User at the center of the design process, at all stages. Driving iterative design!

Prototypes let users see and experience the final system, provide feedback, identity problems. Identifies the strength
and
weaknesses of design and helps to contextualize the proposed designs.

### Participatory Design

Cooperative/Participative design is a form of user-centered design. Users are partners throughout the design. Users and
designers work together. Prototypes are shared, concrete artifacts and foster collaboration/communication.

### Design Space

Design space is the possible space of all designs, with constraints, allowances. Design space is constantly refined in
an iterative fashion. Start with a design problem, identify constraints, set the design space.

Designs should challenge and change the design problem as we go along and better understand things.

Building and constraining design space should be done as two distinct phases to avoid stiffing creativity.

### Expanding Design Space-Generating Ideas

Brainstorming.

Generate as many ideas as possible. Split into generation and reflection phase. Have a moderator and limit discussion
with rules. Have a scribe.

Can have everyone write down ideas and share, or do video brainstorming to have participants act out ideas in 2–5 minute
clips.

### Contracting Design Space—Selecting Ideas

Prototypes can help with evaluation. Select alternatives, design experiments, and construct tasks that represent how the
system would be used. Do analysis with both quantitative and qualitative data.

When alternatives of complex, can use heuristic evaluation, ergonomic evaluation, or other alternatives.

Can do video prototyping to force designers to consider how users will react with the design within its context. Same as
video brainstorming, but contracts the design space.

## Prototyping Strategies

### Horizontal Prototypes

One entire layer of the design is developed at once.

Common in large teams. Get an overall picture of the system.

Address:

1. Consistency
2. Coverage—all required functions are covered
3. Redundancy—the same function is accessible through different commands

It requires some scaffolding or simulation of the system, so these are often evolutionary and transformed over time into
the final system.

### Vertical Prototypes

Implement the full, working system.

High-precision software prototypes.

Thrown away—create early.

Focus on one design question.

### Task-Oriented Prototypes

Organized as a series of tasks.

Includes functions needed to implement a specific set of tasks.

Breadth of horizontal prototypes and depth of vertical prototypes combined.

### Scenario-Based Prototypes

More realistic scenarios than task-oriented prototypes. Stories that describe a sequence of events.

Users should create scenarios—use these to create design scenarios.

## Rapid Prototyping

Develop and iterate quickly.

### Off-line Rapid Prototyping Techniques

#### Paper & Pencil Prototypes

Fastest form. Low cost.

Begin with sketches and progress to carefully drawn screen images.

Good starting point for horizontal, task-based, and scenario-based prototyping strategies.

#### Mock-up Prototypes

Mock-ups or scaled prototypes for 3d representations.

Focus on the physical design of the device. Help envision how a system will be incorporated into physical space.

#### Wizard of Oz

Give users the impression of a real system.

A person acts like the system and fills in the gaps. Useful when rapid responses from users are not critical.

#### Video Prototypes

Use video to illustrate how users will interact with a system. Build on paper/pencil prototypes.

1. Create a use scenario
2. Create a storyboard showing sequence of rough sketches
    - helps refine ideas, generate what if scenarios, identify different approaches, and communicate ideas.
    - allows us to edit-in-the-camera as we go along.
3. Create prototype.
    - can use a second live camera as a wizard of oz tool. gives user a real sense of what use will be like.

### On-line Rapid Prototyping Techniques

Create higher-precision prototypes than off-line techniques. More useful to communicate with customers and fine-tuning
details. It Can be used early in the design process.

#### Non-Interactive Simulations

Animation of what a user would see if watching over the user's shoulder.

Used when off-line prototypes fail to capture the interaction.

Start with storyboards, then create prototypes.

Can use Macromedia Director to create sprites and define paths along which the user would move.

Can use any tool that generates images—make transparent layers and create little frames.

#### Interactive Simulations

Use photoshopping to create Wizard-of-oz prototypes. Do sequences of different states.

Attach behaviors to sprites and to frames of the animation.

#### Scripting Languages

Develop a quick throw-away system.

Languages like Tcl make it easy to build quick UIs. Has text widget and canvas widgets. Tags allow for scripts to be
called in response to user action.

## Iterative Prototypes

High-precision prototypes are usually developed with traditional software development tools. Shipped products are still
in refinement.

Because so much time is invested in UI development, we need software tools and develop software architectures that
produce effective UI.

### Software Tools

1. Graphical libraries—lowest level tools that allow painting pixels on the screen
2. Windows Systems provide an abstraction to allow us to structure the screen
3. UI toolkits-provide widgets
4. UI Builders-allow editing and use UI toolkits
5. Application framework—build on toolkits and ui builders to facilitate development
6. Model-based tools derive interface from domain objects
7. UIDE—User interface development environments—integrated collection of tools for developing interactive software.

High-level tools make it easier to maintain, port, and localize.

#### Graphical Libraries and Windows Systems

Provide API for drawing:

1. direct drawing—functions to draw shapes on the screen
2. scene graph—use a tree to represent the contents of the screen. used with 3d graphics

#### UI Toolkits

Provides widgets for MVC design pattern.

1. Presentation—graphical aspect of widget, size, shape, color
2. Behavior—user interaction, clicking, scroll
3. Application interface—how the widget communicates results of interactions to the application.
    - Callback functions
    - Active variables work only for data
    - Listeners listen for events to be fired off. Matches architectural models and avoids spaghetti of callbacks.

#### UI Builders

Use graphical editor to build UI quicker, save time. Focus on presentation.

Make it easy to create and change the interface, but don't always provide enough for a functional application.

#### Application Framework

MacApp is an example—these work with a UI builder to do routine tasks.

#### Model-Based Tools

Start with functional core and domain objects, then build the interface from that. Give high-level specifications and
derive.

Just in research. Useful for creating early horizontal or task-based prototypes.

#### UIDE-User Interface Development Environments

User interface development environment is a collection of tools.

## Evolutionary Prototypes

Special type of iterative prototypes—used to evolve into the final system. Extreme Programming.

### Software Architecture

#### Seeheim and Arch

UI separated from the functional core of the application.

The UI has three modules:

1. presentation—captures user input at low level. generates output to the user
2. dialogue controller—assembles user input into commands, provides feedback
3. application interface—interprets commands into calls to the functional calls and output for the user

Arch model has 5 components:

1. Interface toolkit—low-level button/menu library
2. Presentation—abstraction over ui toolkit to provide interaction
3. Functional core—functionality of the system
4. Domain adapter— provides extensions and notification services
5. Dialogue - handles translation between ui and domain

#### MVC and PAC

Model view controller.

1. Model—represents information that needs to be represented and interacted with
2. View—displays information to the user
3. Controller—interprets input on the view and transforms it into changes in the model

Presentation-Abstraction-Control model:

1. Presentation—takes care of capturing input and generating output
2. Abstraction—holds application data
3. Control—manages communication between the abstraction and presentation facets of the agent
