
# Agile a la carte menu

A reference for organizations that are intellectually-honest and problem-oriented.

## Because we've all been there

<img src='http://bits.owocki.com/3G42451C1J0u/Image%202016-04-11%20at%204.16.14%20PM.png' />

## or here

<img src='https://d3vv6lp55qjaqc.cloudfront.net/items/0u3d3w0k1r2y0L1e2Y1J/Image%202016-09-16%20at%2011.48.01%20AM.png?X-CloudApp-Visitor-Id=1478655' />

## Table of contents

- [Types](#types)
  - [Scrum](#scrum)
  - [Kanban](#kanban)
  - [Extreme programming (XP)](#extreme-programming-xp)
  - [Agile Manifesto](#agile-manifesto)
- [Vocab](#vocab)
  - [Agile](#agile)
  - [Ticket](#ticket)
  - [Abnormal Termination](#abnormal-termination)
- [Roles](#roles)
  - [Scrum::product backlog](#scrumproduct-backlog)
  - [Scrum::sprint backlog](#scrumsprint-backlog)
  - [Scrum::sprint burndown chart and release burndown chart](#scrumsprint-burndown-chart-and-release-burndown-chart)
    - [Sprint burndown](#sprint-burndown)
    - [Release burndown](#release-burndown)
  - [Scrum::Product Owner](#scrumproduct-owner)
  - [Scrum::Scrumaster](#scrumscrumaster)
  - [Scrum::daily standup](#scrumdaily-standup)
  - [Scrum::Sprint Review](#scrumsprint-review)
  - [Scrum::Product backlog](#scrumproduct-backlog)
  - [Scrum::Team velocity](#scrumteam-velocity)
  - [Scrum::retrospective](#scrumretrospective)
  - [Scrum::Scrum team](#scrumscrum-team)
  - [Scrum:: Team structure](#scrum-team-structure)
    - [Squads](#squads)
    - [Tribes](#tribes)
    - [Dependancies](#dependancies)
    - [Chapters and guilds](#chapters-and-guilds)
  - [XP: Testing](#xp-testing)
  - [XP: Listening](#xp-listening)
  - [XP: Values](#xp-values)
  - [XP: Principles](#xp-principles)
  - [XP: Pair programming](#xp-pair-programming)
  - [Code smells](#code-smells)
  - [Acceptance Testing](#acceptance-testing)
  - [Cross-Functional Team](#cross-functional-team)
  - [Stakeholder](#stakeholder)
  - [Domain model](#domain-model)
  - [Technical Debt](#technical-debt)
  - [Epic](#epic)
  - [Fail fast](#fail-fast)
  - [Inspect and adapt](#inspect-and-adapt)
  - [Product Vision](#product-vision)
  - [Self Organization](#self-organization)
  - [Release](#release)
  - [Vanity Metric](#vanity-metric)
  - [Chicken](#chicken)
  - [Pig](#pig)
  - [Timebox](#timebox)
  - [Refactoring](#refactoring)
- [FAQ](#faq)
    - [Kanban: Physical or virtual](#kanban-physical-or-virtual)
- [People Management](#people-management)

#Agile

<img src='http://bits.owocki.com/2O142o430j3w/Image%202016-04-03%20at%209.54.53%20PM.png' />

# Types

## Scrum

Scrum is an iterative and incremental agile software development framework for managing product development.   It enables teams to self-organize by encouraging physical co-location or close online collaboration of all team members, as well as daily face-to-face communication among all team members and disciplines in the project.

<img src='http://bits.owocki.com/32313s330w3q/Image%202016-04-03%20at%209.52.57%20PM.png' />

## Kanban

Kanban (which means signboard or billboard in Japanese) is a scheduling system for lean manufacturing and just-in-time manufacturing.  One of the main benefits of kanban is to establish an upper limit to the work in progress inventory, avoiding overloading of the manufacturing system. 

<img src='http://bits.owocki.com/3y411E383G3T/Image%202016-04-03%20at%209.39.53%20PM.png' />

##Waterfall

The waterfall model is a sequential design process.  Progress is seen as flowing steadily downwards (like a waterfall) through the phases of conception, initiation, analysis, design, construction, testing, production/implementation and maintenance.

<img src='http://bits.owocki.com/100v0d3J2p1j/Image%202016-04-03%20at%209.56.50%20PM.png' />

## Extreme programming (XP)

Advocates frequent "releases" in short development cycles, which is intended to improve productivity and introduce checkpoints at which new customer requirements can be adopted.  Is intended to improve software quality and responsiveness to changing customer requirements.

<img src='http://bits.owocki.com/3K2h0k3k3l0l/Image%202016-04-11%20at%203.46.53%20PM.png' />

## Agile Manifesto

```
Individuals and interactions over processes and tools
Working software over comprehensive documentation
Customer collaboration over contract negotiation
Responding to change over following a plan

```

The things on the right matter, but the things on the left are more important.

## Core Values

In order for an agile system to be implemented successfully, the agile coach must have buy in to transformation up and down the organization.  A team cannot implement agile if executives are not bought in, and executives cannot implement agile if the team is not bought in.

##Tools

These tools all solve problems:

| Problem  | Solution  |  Comment  | 
|:-:|---|---|---|---|
| Forecasting  | Estimates  |  Many estimation systems use Fibonacci numbers (1,2,3,5,8).  If an item is > 8, it is often broken down into multiple tasks.  It is VERY IMPORTANT that estimates are not treated as deadlines.  | 
| Changing Specs  | Sprints  |  A sprint is a get-together of people involved in a project to further a focused development of the project. Sprints typically last from one week up to three weeks, and cannot be interupted with out-of-scope work without an *abnormal termination*.  | 
| Scheduling  | Sprint Planning  |  In scrum, sprint Planning is a meeting that marks the beginning of a sprint.  The team commits to a certain amount of work, without influence from outsiders.  | 
| Visibility  | Kanban Board  |  Kanban = workflow visualization tool that enables you to optimize the flow of your work  | 
| Feedback  | Retrospective  |  The sprint retrospective is an important mechanism that allows a team to continuously evolve and improve throughout the life of a project. It includes three main questions/points for discussion: 1) What went well during the sprint cycle? 2) What went wrong during the sprint cycle? 3) What could we do differently to improve? | 
| Specifications  | Stories  |   Short, simple descriptions of a feature told from the perspective of the person who desires the new capability, usually a user or customer of the system. They typically follow a simple template: `As a <type of user>, I want <some goal> so that <some reason>. `  | 
| Agility  | Standups  |  A sync-ing meeting (usually daily) in which attendees typically participate while standing. The discomfort of standing for long periods is intended to keep the meetings short.  | 
| Dependancy Management  | Dependancy Mapping  |  Sometimes done with just a piece of string between two stories.  | 

# Vocab

## Agile

A conceptual framework for undertaking software projects. Agile methods are a family of development processes, not a single approach to software development

## Ticket

<img src='http://bits.owocki.com/2e1e423l3A40/Image%202016-04-03%20at%209.40.57%20PM.png' />

## Abnormal Termination

Abnormal termination is essentially blowing up the sprint and starting a new sprint instead. 

# Roles

## Scrum::estimates

_Traditional_ software teams give estimates in a time format: days, weeks, months. 

In contrast, _Agile_ estimation is a team sport.  Everyone who builds software is involved.  The product owner typically is involved but does not get to vote on estimation.

In scrum, estimation systems are called 'story points' and use Fibonacci numbers (1,2,3,5,8).  If an item is > 8, it is often broken down into multiple tasks.  

Estimates are relative to other work within a team.  They *cannot* be transcribed to hours, wdays, weeks.  It is VERY IMPORTANT that estimates are not treated as deadlines. 

And ideal feature is that a team learns from past estimates.


## Scrum::product backlog

The product backlog is another artifact of Scrum. This is the complete list of the functionality that remains to be added to the product. The product owner prioritizes the backlog so the team always works on the most valuable features first.

## Scrum::sprint backlog

The sprint backlog is the list of tasks the team needs to perform in order to deliver the functionality it committed to deliver during the sprint.

## Scrum::sprint burndown chart and release burndown chart

### Sprint burndown

Plots burn-down using effort remaining is the most effective and efficient way of using burn-down charts

<img src='http://bits.owocki.com/2b0D0V0H3b0T/Image%202016-04-03%20at%209.49.27%20PM.png' />

### Release burndown

The horizontal axis of the sprint burndown chart shows the sprints; the vertical axis shows the amount of work remaining at the start of each sprint. Work remaining can be shown in whatever unit the team prefers -- story points, ideal days, team days and so on.

<img src='http://bits.owocki.com/1H1T3p1d2t26/Image%202016-04-03%20at%209.49.48%20PM.png' />

## Scrum::Product Owner

The Product Owner (PO) is the member of the team responsible for defining Stories and prioritizing the Team Backlog so as to streamline the execution of program priorities.

## Scrum::Scrumaster

A scrum master is the facilitator for a product development team that uses scrum, a rugby analogy for a development methodology that allows a team to self-organize and make changes quickly. The scrum master manages the process for how information is exchanged.

A good ScrumMaster shelters the team from outside distractions, allowing team members to focus maniacally during the sprint on the goal they have selected.

While the ScrumMaster focuses on helping the team be the best that it can be, the product owner works to direct the team to the right goal. The product owner does this by creating a compelling vision of the product, and then conveying that vision to the team through the product backlog.

The third and final role in Scrum project management is the Scrum team itself. Although individuals may join the team with various job titles, in Scrum, those titles are insignificant. Scrum methodology states that each person contributes in whatever way they can to complete the work of each sprint.

## Scrum::daily standup

Each day the Scrum Master leads the team in the Daily Scrum Meeting. This meeting designed to provide status on the progress of the sprint. Each team member speaks to three questions: what did I do yesterday, what did I do today, and what impediments got in my way.

## Scrum::Sprint Review

Each Sprint is followed by a Sprint review. During this review the software developed in the previous Sprint is reviewed and if necessary new backlog items are added.

## Scrum::Product backlog

Acts as a repository for requirements targeted for release at some point. These are typically high level requirements with high level estimates provided by the product stakeholders. The requirements are listed on the backlog in priority order and maintained by the product owner.

## Scrum::Team velocity

A relative number which describes how much work the team can get done per sprint.   Velocity in scrum is measured in [story points / estimates](https://github.com/owocki/agile_a_la_carte#scrumestimates).

## Scrum::retrospective

No matter how good a Scrum team is, there is always opportunity to improve. Although a good Scrum team will be constantly looking for improvement opportunities, the team should set aside a brief, dedicated period at the end of each sprint to deliberately reflect on how they are doing and to find ways to improve. This occurs during the sprint retrospective.

The sprint retrospective is usually the last thing done in a sprint. Many teams will do it immediately after the sprint review. The entire team, including both the ScrumMaster and the product owner should participate. You can schedule a scrum retrospective for up to an hour, which is usually quite sufficient. However, occasionally a hot topic will arise or a team conflict will escalate and the retrospective could take significantly longer.

Although there are many ways to conduct an agile sprint retrospective, our recommendation is to conduct it as a start-stop-continue meeting. This is perhaps the simplest, but often the most effective way to conduct a retrospective. Using this approach each team member is asked to identify specific things that the team should:

* Start doing
* Stop doing
* Continue doing

From the [Retrospective Prime Directive](http://www.retrospectives.com/pages/retroPrimeDirective.html): 

One of the most obvious fears people have when first trying a retrospective is that the ritual will become a negative gripe session, interspersed with blame and counter blame.

Clearly such an event will not contribute to much learning.  The key to a constructive successful ritual is assuring that all the participants adhere to the Retrospective Prime Directive.

> Regardless of what we discover, we understand and truly believe that everyone did the best job they could, given what they knew at the time, their skills and abilities, the resources available, and the situation at hand.	

At the end of a project everyone knows so much more. Naturally we will discover decisions and actions we wish we could do over. This is wisdom to be celebrated, not judgement used to embarrass.


## Scrum::Scrum team

Within the Scrum Framework all work delivered to the customer is done by dedicated Scrum Teams. A Scrum Team is a collection of individuals working together to deliver the requested and committed product increments.

To work effectively it is important for a Scrum Team that everyone within the team
follows a common goal
adheres the same norms and rules
shows respect to each other

## Scrum:: Team structure

<img src='http://bits.owocki.com/0E0S060p1J38/Image%202016-04-03%20at%209.44.35%20PM.png' />

### Squads

The basic unit of development is Squad.

<img src='http://bits.owocki.com/3R1r08040E0W/Image%202016-04-03%20at%209.45.11%20PM.png' />

### Tribes

<img src='http://bits.owocki.com/1w3j382T0e2f/Image%202016-04-03%20at%209.45.30%20PM.png' />

### Dependancies

<img src='http://bits.owocki.com/0S3B1J0v3E2Q/Image%202016-04-03%20at%209.45.47%20PM.png' />

### Chapters and guilds

<img src='http://bits.owocki.com/2d0g1o2Z370P/Image%202016-04-03%20at%209.46.04%20PM.png' />

## XP: Testing

Extreme programming's approach is that if a little testing can eliminate a few flaws, a lot of testing can eliminate many more flaws.

* Unit tests determine whether a given feature works as intended. A programmer writes as many automated tests as they can think of that might "break" the code; if all tests run successfully, then the coding is complete. Every piece of code that is written is tested before moving on to the next feature.
* Acceptance tests verify that the requirements as understood by the programmers satisfy the customer's actual requirements.

## XP: Listening

Programmers must listen to what the customers need the system to do. They must understand these needs well enough to give the customer feedback about the technical aspects of how the problem might be solved, or cannot be solve

## XP: Values

* Communication
* Simplicity
* Feedback
* Courage
* Respect

## XP: Principles

* Feedback
* Assuming simplicity
* Embracing change

## XP: Pair programming

Pair programming is an agile software development technique in which two programmers work together at one workstation. One, the driver, writes code while the other, the observer or navigator, reviews each line of code as it is typed in. The two programmers switch roles frequently.

Why pair program:

* Economics
* Design quality
* Satisfaction
* Learning
* Team building

## Code smells

Any symptom in the source code of a computer program that indicates something may by wrong

## Acceptance Testing

Formal testing conducted to determine whether or not a system satisfies its acceptance criteria and to enable the customer to determine whether or not to accept the system.

## Cross-Functional Team

Team comprised of members with all functional skills and specialties necessary to complete a project from start to finish.

## Stakeholder

Anyone external to the team with a vested interest in the outcome of the team’s work.

## Domain model

Information model describing the application domain that creates a shared language between business and IT.

## Technical Debt

The obligation that a software organization incurs when it chooses a design or construction approach that’s expedient in the short term but that increases complexity and is more costly in the long term. Whether or not to incur technical debt is a tradeoff decision that ideally is made in a deliberate manner at the point that work occurs.

## Epic

A very large user story that is eventually broken down into smaller stories.

## Fail fast

A fail-fast system is designed to immediately report at its interface any failure or condition that is likely to lead to failure

## Inspect and adapt

The idea of discovering over the course of a project emergent software requirements and ways to improve the overall performance of the team. It neatly captures the both the concept of empirical knowledge acquisition and feedback-loop-driven learning.

## Product Vision

A product vision is a brief statement of the desired future state that would be achieved through the project initiative.

## Self Organization

Self-organization is a property of complex adaptive systems, whereby the organization of the system emerges over time as a response to its environment. 

## Release

The movement of a software product or system from development into production.

## Vanity Metric

A metric that is not actionable, and exists to make us feel better or show off

## Chicken

Slang for someone who is interested in a project but has no responsibility for working on a task in the active iteration.

## Pig

Scrum slang. Someone who is responsible for doing a task on an active iteration. It comes from the joke, “A chicken and a pig talk about breakfast. The chicken says, ‘Let’s have bacon and eggs.’ The pig replies, ‘That’s fine for you. You are just making a contribution, but I have to be fully committed.'” Pigs are actively involved in the project.

## Timebox

A timebox is a time period of fixed length allocated to achieve some objective. In agile development, iterations and sprints are examples of timeboxes that limit work in process and stage incremental progress. Timeboxes are often used to avoid over-investing in tasks such as estimating development tasks.

## Refactoring

Changing existing software code in order to improve the overall design. Refactoring normally doesn’t change the observable behavior of the software; it improves its internal structure.

# FAQ

### Kanban: Physical or virtual

Some teams prefer physical Kanban boards over virtual ones. A physical board uses sticky notes or index cards for the Kanban cards, and the board is drawn on a whiteboard or wall.  

## References

* https://en.wikipedia.org/wiki/Scrum_(software_development)
* https://en.wikipedia.org/wiki/Kanban
* https://en.wikipedia.org/wiki/Waterfall_model
* https://en.wikipedia.org/wiki/Extreme_programming
* http://agilemanifesto.org/
* http://www.allaboutagile.com/
* https://en.wikipedia.org/wiki/Sprint_(software_development)
* http://leankit.com/learn/kanban/kanban-board/
* https://www.scrumalliance.org/community/articles/2014/april/key-elements-of-sprint-retrospective
* https://www.mountaingoatsoftware.com/
* https://en.wikipedia.org/wiki/Stand-up_meeting
* http://www.telerik.com/teampulse/agile-vocabulary
* https://www.versionone.com/scrum-project-management/
* http://scaledagileframework.com/product-owner/
* http://whatis.techtarget.com/definition/scrum-master
* https://www.captechconsulting.com/blogs/learning-the-agile-vocabulary
* http://www.scrum-institute.org/Scrum_Roles_The_Scrum_Team.php
* Scaling Agile * Spotify
* https://en.wikipedia.org/wiki/Code_smell
* http://www.construx.com/10x_Software_Development/Technical_Debt/

# People Management

## Goal setting: Sticky Note Game

Here's a blog post explaining it  http://www.tablexi.com/developers/xi-to-eye-the-sticky-note-game/, but TLDR is 

```
STEP 0 
Schedule
* 1 employee
* 1 manager
* 1 or 2 advocates for employee (employee choses them)
We bring lots of sharpies + sticky notes.  Sponsors get diff colored sticky notes than Employee.

STEP 1
We Start by just asking "What does success look like in the next 6 months for you?"
It's totally open ended, that could mean anything:
	Community related
	Project related
	Skill related
	Work life balance related

STEP 2
Then we put the sticky notes on the board and talk through them.  
	1. Which are top priority?
	2. What are specific action items SOON you could take to reach them?

STEP 3
Take notes into medium you decide upon: a google doc, trello, pivotal tracker, etc.

STEP 4
Optional: Follow up between advocate and employee a few weeks later

```

## One on ones

1:1s are about people & their happiness, not product management.  Some assorted links:

* [Update, Vent, the Disaster](http://randsinrepose.com/archives/the-update-the-vent-and-the-disaster/)
* [First one on one questions](http://larahogan.me/blog/first-one-on-one-questions/)
* [1 on 1 topic generator](https://veryhappythings.github.io/101-questions/)

## TODO: Fill out the people management section with more ideas (PRs welcome)



<!-- Google Analytics --> 
<img src='https://ga-beacon.appspot.com/UA-1014419-15/owocki/agile_a_la_carte' style='width:1px; height:1px;' >


