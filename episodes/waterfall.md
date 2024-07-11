---
title: "The Waterfall Model"
teaching: 10
exercises: 20

---

::::::::::::::::::::::::::::::::::::::: objectives

- Understand the Waterfall model.
- Practice using the Waterfall model.
- Learn when the Waterfall model works well.

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::: questions

- What is the Waterfall model?
- How is the Waterfall model used in practice?
- When is it appropriate to use the Waterfall model?

::::::::::::::::::::::::::::::::::::::::::::::::::


## The Waterfall Model

![](fig/waterfall.png){alt='The Waterfall model. Image from Wikimedia Commons.'}

The Waterfall model consists of various stages that follow sequentially -- one after the other.
The idea of having defined phases is to try to complete each phase before
the next phase begins.
This is generally referred to as the waterfall model, e.g., "Progress flows
downwards through the phases, like a waterfall."
Each phase produces specific deliverables, which feed into the next phase with
the assumption that the artifacts from the previous phases are actually correct.

Ideally, each phase will also identify any issues or flaws in the previous phase.
When this happens, you are supposed to iterate between phases to fix any issues that arise.

Waterfall has either five or six stages, depending on the source, but for our purposes,
we will consider the phases to be:

1. Requirements
1. Design
1. Implementation
1. Verification
1. Maintenance

::::::::::::::::::::::::::::::::::::::: challenge

## Let's Build a House

![](fig/house.png){alt='A house icon - created by VectorMachines on Flaticon.'}

0. Split into 4 groups and grab a set of LEGOs :tm:.
1. (6 min) Gather requirements from your customer. Ask important questions to help you determine what needs to be done to build their dream house!
2. (4 min) Determine your design. How can you satisfy the requirements with your LEGOs?
3. (8 min) Build the house!
4. (2 min) Show it to your customer and see how you did.

:::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::: discussion

How was that experience? What did you like? What did you dislike?

::::::::::::::::::::::::::::::::::::::::::::::::::


## The Waterfall Model in Real Life

It is very common in real life scenarios that there is a miscommunication of software requirements.
These miscommunications may not even be identified until the software is demonstrated
for clients or formal acceptance testing is completed.
In traditional waterfall models, the client is often only involved in requirements
phase and in acceptance-testing (or later phases).

If mistakes occur using the waterfall model, very significant amounts of work
may need to be reviewed, revised, or even discarded.

::::::::::::::::::::::::::::::::::::::::::  discussion

## What do you require?

"It's 50x to 200x less expensive to get a requirement right in the first place
than to fix a requirement after implementation." - Boehm and Papaccio, 1988

::::::::::::::::::::::::::::::::::::::::::::::::::::::


The Waterfall model works well when:

- Software requirements are very clear, well understood, and unchanging
- Technical implementation details are also very well understood (generally considered more suited to manufacturing, but this is also changing with rapid prototyping!)

Inversely, waterfall model works terribly when these things aren't present and
can lead to greatly exceeding time and financial budgets.
Waterfall-based models don't handle lack of knowledge, or change, very effectively.
Poorly understood or changing software requirements, technology, or
architecture choices can negatively impact the performance of the waterfall-model.
Though, it should be noted that a lack of software-engineering discipline virtually negates all approaches.

:::::::::::::::::::::::::::::::::::::::: keypoints

- The Waterfall model consists of stages that happen sequentially, one after another.
- The Waterfall model is helpful when requirements are very clear and well understood.
- The Waterfall model is difficult if requirements and technologies are unclear or change frequently.

::::::::::::::::::::::::::::::::::::::::::::::::::
