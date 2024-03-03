# Cognitive Walkthrough—method for theory-based evaluation

Cognitive walkthrough aims to provide a new tool for usability early in the design process.
Allows designers to
anticipate some learnability problems prior to implementation.
A design author presents his proposed design to a group of peers
who evaluate using an explicit set of criteria.
Evaluate the ease with which users can perform a task with little or no
formal instruction.

Step through actions user,
consider the behavior of the interface, and user's thoughts with attention to those tasks that
might be challenging.

## Application of cognitive theory

Focus on ease of learning.

## Theory of learning by exploration

Users of a system must guess what to do.

Based on Kitsch's construction integration model - users integrate a representation of text or other input to construct
a representation to perform a task.

An initial goal structure is constructed from a description; these are then

Represented by propositions, linked to other goals, background knowledge, environment, actions.

Responses by the system
are observed and interpreted.
This results in new goals, changes in environment. 
These are linked to other propositions
and new actions occur.

### Link between Goals and Actions

We need the associative path of connections between user's goal and the representation of the action.
Let users follow a label.

The associative path between goal and action has four linked propositions:

1. The representation of the user's currently active goal
2. The button label
3. The button description, including its location
4. The action of pressing the button

Walkthrough helps make sure that we are translating invisible labels into explicit labels.
Consider the needs of novice and expert users alike.

## Management of goal Structure

Our users do not have a complete goal—they aren't sure of the whole chain of representations and subtasks.

### Goal Structure Generation

Generating the goal structure is done through prompting the user or other feedback from the interface.
The walkthrough determines
whether user's background knowledge and the interface cues are sufficient to construct a goal structure
necessary to generate the action sequence required to complete the task.

### Generating goals for actions

The lowest level goal is to execute some physical action, which achieves the sub-goal, and sequences of these allow
users to complete their main goal.

### Interpreting Feedback

The Goal structure is revised in response to action and feedback from the system. 
User needs to interpret the system response to determine if goal is accomplished.

### "And then" goal structures

Goals are often parts of broader sequences—once a small goal is accomplished, we make it part of a larger chain
containing want-to actions that need done, and done-it nodes that have been accomplished already.

Super-goal kill-off is when we incorrectly think we are done with our main goal, but need one other thing.

When doing walkthrough, make sure that the super-goal is not killed off early.

## Cognitive Walkthrough Procedure

Simulate user's processes as they interact with interface to accomplish a particular task.

Two phases:

1. Preparation - representative tasks are selected with an initial interface state, action sequence used, and the
   initial goals
2. Evaluation—interaction between user and interface is examined in depth. 
3. Check each action to determine goals that
   the user should have leading up to the action, whether the prompts and labels of the interface induce the user to
   take the correct action.
4. Additionally, how the user's goals may change in response to the feedback that they receive from the
   interface.

### Phase 1: Preparation

#### Choose Tasks to Analyze

To do cognitive walkthrough, have to first select the tasks that are going to be analyzed.
These tasks need to represent
what the user is actually going to do, and should make up sequences of elementary tasks.

#### Provide task description

Task must be described from the view of first time user, with assumptions about the state of the system noted. 
Tasks must be described in realistic, non-system-specific terms.

#### Determine action sequence


For each task, determine a sequence of actions that will be critiqued.
Select the sequence that is going to offer the
fewest obstacles to the user.
If there are alternative, acceptable sequences, analyze all of them!.
Start with thinking
about actions as very finely divide them and then work to collapse them into larger units if it is clear that no
potential problems could be hidden.

#### Identify the anticipated user population

Analysts must make detailed predictions about the users of the interface, their goals, their skills, their difficulties,
what changes they want.

Need a uniform population of potential users

#### Describe user's initial goals

Note the goals the user will have when starting—with notes about whether it is based on task description, cues present
on the screen, and any and-then structures should be listed.

### Phase 2: Evaluation

Do a complete analysis for each required action identified in the preparation phase.

Divide form into three sections for walkthrough: the relationship between goals needed to operate interface and actual
user goals, the problems in selecting an action and analysis of how the user's goals are likely to change after making
the correct action and receiving feedback.

#### Goal structure for current step

Divide problems into goal problems and action problems. 
In goal problems, user wants to do the wrong thing.
In action problem, user is trying to do the right thin but cannot figure out the way to do it.

At every step, analysts should indicate what the correct goals from the steps are. 
Check to see if users have them or not.

#### Choosing and performing the action

When users have appropriate goals, will they select the right action.
Check that the action is available and the user
knows that it is possible.
Actions must be linked to the current sub-goal.
There must be no competing incorrect action
that is connected to the current sub-goal.

The user must have time to make the necessary choice. 
The action should be
easy to execute.

#### Modifications of the goal structure


Assuming the user has made the correct action, what changes to their current goals will they need to take.
Check whether
the user has enough feedback to know that
progress has been made.
Identify current goals that have been accomplished and should be dropped; that users realize
as accomplished.
Look for goals that aren't accomplished but may appear to be, as these can cause problems. 
Check if any
goals are and-then structures, and see if there is an additional sub-goal or if everything has been tacked off.
Make sure
the super-goal has not been killed too early.

## Comparison with Other Methods

### GOMS/CCT

GOMS and Cognitive Complexity Theory deal with routine cognitive skills, capable of making quantitative predictions of
 performance time and training time.
These can be used to supplement cognitive walkthroughs.
Analysts must write executable specifications of mental operations required to use the system, knowledge, edge

### PUM

Programmable user models are similar to CCT
in requiring analyst to write executable specifications of mental operations.
Based on SOAR.
Predicts conceptual problems new users will have during their attempts to learn.

Construct a set of instructions to interpret with a model of the user's problem-solving behavior.
These supply the knowledge necessary to guide the problem-solving model to use interface.


### Comparisons with cognitive walkthrough


Both cognitive and PUM attempt to expose the way in which mental processes can succeed or fail tasks—in PUMs,
users know a
lot about the system while cognitive walkthroughs involve little system knowledge. 
Cognitive walkthroughs also focus specifically on the interface being analyzed,
while PUM considers the user's knowledge and reasoning in general.
Cognitive walkthroughs direct analyst to think through the sequence of mental operations needed, while PUM does this
apriori - PUM tries to determine what instructions are necessary.
PUM involves an executable simulation, while cognitive
walkthroughs don't.

### Problems with executable simulations

Simulations are hard to do, is hard to accommodate subprocesses, can be challenging to relate problems in the simulation
to the real interface.


## Other walkthroughs

Nielsen advocates for aggregating different reviewers' findings together.
Heuristic evaluations don't ask evaluators to
consider mental operations, like goal formations.
They are also not tied to any theoretical model of user-system
interaction.

## Iterative design

Use user testing, cognitive walkthroughs to iterate.
Complement user testing, provide explanations for problems found in
user-testing.

## Differences with other methods:

1. Role of simulation - no executable simulation.
2. Focus on mental operations
3. Use of task context
4. Links to the interface
5. Role of theory
