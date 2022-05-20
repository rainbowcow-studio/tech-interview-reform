## Software engineer hiring is broken and it’s time to fix it.

For years, the tech industry has settled on giving interviewees live coding challenges to evaluate their technical skill. Those who fail the challenge are rejected, and those who pass move on to potentially receive an offer to join the company. Unfortunately, coding challenges are an ineffective tool for measuring an individual's skill level and exclude entire classes of people from employment. **It's time to rethink the status quo.**

### What's wrong with coding challenges?

Live coding challenges do not effectively model the day-to-day work of a software engineer. In practice, we generally do not implement standard computer science algorithms or data structures, and we certainly don't do it under active scrutiny from a stranger. Instead, we assess business requirements, implement appropriately-scoped solutions, and iteratively refine them. This process typically takes anywhere from a few hours to a few days depending on the scale and nature of the problem.

This disconnect between the interview process and the role it is meant to fill does everyone a disservice. It makes hiring slower and more expensive for companies, and it disadvantages individuals who don't fit the stereotypical mold. This industry is filled with many capable engineers who struggle to show their strengths without an opportunity for adequate preparation. To standardize on such an exclusionary and disconnected process for hiring is a broken system design.

## Introducing: The Reformed Tech Interview

It's time for a standardized and superior engineer interview process. We call this the **Reformed Tech Interview**. The Reformed Tech Interview is predicated on one concept: **Interviews should model the roles they are designed to hire for and set candidates up for success**. This can take on many forms in practice and will vary from company to company.

### What does a Reformed Tech Interview look like?

To more effectively evaluate candidates, consider the job you're hiring for and what a vertical slice of it might look like in the form of 45-minute group exercises. If a candidate can successfully navigate high-fidelity exercises that resemble your business's day-to-day work, you can have high confidence that they will be a strong addition to your team.

The following is a set of blueprints for exercises that you can do with candidates. You could consider challenging them with some or all of these exercises, depending on the hiring need and seniority level. Feel free to create your own exercises, but take care to model the daily work of a software engineer and not simply develop contrived puzzles or other tasks. 

Note that these exercises are strictly alternatives to traditional technical challenges, not behavioral interviews. Those should exist as an additional component of the overall interview process.

#### The Ticket

If engineers in your company often do ticketed work, provide candidates a prepared ticket that simulates this work. It should resemble the sort of tickets that engineers at your company actually work on. It should be designed in such a way that it doesn't expose your company's IP (and thus avoid the need for an NDA). If you are unable to prepare a code repository that is tailor made for candidates, then the ticket could be designed around making a change to a forked open source project. The ticket should have clear acceptance criteria and be small in scope, as the exercise should be mostly achievable inside of 45 minutes. 

Outliers may complete the ticket within 45 minutes, but be sure to indicate that this is not the expectation. Simply getting to the end of the challenge should not necessarily count in the candidate's favor, as they could conceivably meet the stated requirements in an ineffective way (such as by taking implementation shortcuts, introducing security vulnerabilities, or failing to ask good clarifying questions). Make it clear to the candidate that quality is more important than completeness, as 45 minutes is not a reasonable amount of time to produce a large amount of high-quality work.

The goal of this exercise is to expose how candidates perform defined work and how mature their engineering habits are. If the candidate runs out of time (which should be expected in most cases), ask them what they would have done if they had more.

#### The Code Review

If your company does peer-reviewed pull requests, provide candidates with a realistic but simulated pull request for them to evaluate and critique. Again, you can use a pull request on a forked open source project for this. The pull request should have a mix of obvious and non-obvious areas for improvement. See what they think of the code and what they would change.

The goal of this exercise is to expose how candidates read others' code and how they maintain quality on a project that is worked on by a team. It also reveals how effectively they communicate their thoughts. This exercise is particularly valuable because it reveals the candidate's ability to empower and educate others. A less effective engineer might simply point out issues with the code and not consider the context that caused them (such as a tight deadline or experience level). A more effective engineer is likely to have helpful and thoughtful comments that educate team members and foster team cohesion.

#### The Collaboration

If your team culture involves a lot of collaborative problem solving, have candidates lead a working session to solve a problem relevant to your business's domain. This should not take the form of a traditional system design challenge, as systems are almost never built from scratch in practice. Instead, provide candidates with a preexisting system (even if it only exists on paper or in theory) that can be explained and understood inside of a few minutes. Then, propose a new feature that would require a substantive change to that existing design. Provide a few constraints such as resource and timeline requirements. From there, have the candidate lead the team to develop a strategy to change the system such that the feature can be delivered.

The goal of this exercise is to expose how candidates break down business problems in a given space and work within practical limitations to deliver business value. It also reveals their leadership and communication skills.

### Interview group size

Interview session groups can vary in size. Generally, there should be two or three interviewers. More than three can feel overwhelming, but one can lead to a single team member's implicit biases or interviewer errors being unfairly held against the candidate. Having at least two team members in the room can act as a counterbalance to a single outlier interviewer's perception.

### Leveling

Avoid giving more experienced candidates more difficult challenges. Technical challenges should be very open-ended, and thus everybody will develop a solution differently. The more effectively the candidate completes the challenge, the higher of a level they justify getting an offer for. By giving all candidates the same set of challenges, you can avoid inconsistencies when evaluating their performance. Here are some signs you can look for to gauge an engineer's effectiveness:

* Did the candidate ask questions to inform their solution before starting to implement it?
* Did they consider the performance implications of their solution? 
* Did they focus on getting a basic solution working first and then refactoring, or did they try to make some ultimate solution at the outset? 
* Was the solution easy to understand, or was it needlessly complex?
* Did they consider (or write) tests?

To determine experience level, dig deeply into the candidate's past projects. Probe to find out what exactly their contributions were and what kind of impact they had on their project, team, and organization. Ask for specifics and try to (respectfully) poke holes in their past decisions in order to validate their claims. The more experienced the candidate is, the more they will have to speak to and the deeper they will be able to go.

### One size does not fit all

Every candidate will have a different area of expertise that they can navigate well on the spot. Rather than developing a singular set of challenges to be given to all candidates, develop a set of interview options that candidates can select from. Some candidates will be more into the idea of doing a code review on the spot, and others will prefer to work through a ticket. Candidates should know what sorts of challenges will set them up to show their strengths. Allowing them to tailor their interview experience will result in a strong signal of what their strengths are and how they perform at their best.

--------------------

This document was drafted by [Jeremy Kahn](https://github.com/jeremyckahn/) with valuable input from [Luke Stebner](https://github.com/lstebner/) and Dana Logalbo.
