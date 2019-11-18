# Introduction

__History__

We made our first attempt at formalising and defining the carwow engineering principles in January 2019. To compile the first draft, we asked all engineers that had been at carwow for at least 2 years to try and capture the engineering culture that had contributed to our success.
In October 2019 the wider product team have been thinking about shared
principles too, so we aligned the engineering principles to the wider
product team ones.

__Contributing__

To be true to our values of self-improvement our principles should and will evolve over time. We've decided to write them down so that the process of changing them is tracked, and clear to everybody.
If you wish to add something to the principles, or modify some of the existing principles please **open a pull request.**
We'd like to see at least 10 people agreeing to a change before merging into master, so please contribute to PR discussions.

David Santoro (Co-Founder/CTO) will be the one merging any changes, for now.

__How to use the principles__

In engineering there are many correct ways of doing things, to avoid unnecessary debates when possible we'd like to pick solutions that conforms to this principles. You can use this principles as guidance, or you can refer to them when giving feedback on someone else behaviour or work.
They will also be used when interviewing, and shown to potential candidates so they can figure out if carwow is the right place for them

__WIP__

This page is in constant WIP, please refer to it regularly.

# The carwow Engineering Principles

__Think *big* and take small steps to learn fast__

  * Breaking down big features in small steps doesn’t mean we work only on small incremental improvement. A longer term vision or objective help us achieve great things without sacrificing short term value.
  * We also use several practices that give us fast feedback loop like:
    TDD, pairing, code reviews, continuous delivery, vertical slicing,
AB tests, customer feedback, etc.
  * Example: Feature-specific toggles are a good way to release early and often. By coupling each well-defined feature with its own toggle, we can better control when and where to activate it. We currently use [LaunchDarkly](https://launchdarkly.com) to manage feature flags.


__Be ruthlessly focused__

  * Engineering effort is a scarce commodity. It should only be applied to problems that “move the needle” for the company
  * The biggest achievement of an Engineer at carwow is to provide positive business impact with no line of code written (maybe even removing some)
  * We always question and challenge the value of work instead of following blindly; and then we commit to delivering early and often.
  * We don't manage our own server, or have a self hosted continuous integration software.


__Follow a scientific but pragmatic process__

  * We start with a well defined hypothesis, we outline our assumptions,
    we define our success metrics and use quant data when possible. If
quant is not available we use qualitative data and intuition
  * We are comfortable taking decisions with incomplete or imperfect
    information


__Simple and clear Engineering__

  * We value simple and clear solutions that solve problems without unnecessary complexity. At the same time we keep the long term vision in mind and don’t just build for today.


__Outside in ownership__

  * We value shipping early and observing in production; we are fearless. We believe a developer is responsible for owning their work all the way through to delivering value, including monitoring and performance.


__Sustainable pace__

  * Panic and rushing leads to bad decisions, we believe in aggressive scoping and focussing on value. It leads to better results; with a happier and healthier team.


__Collaborate!__

  * Product development is a team effort, we give each other feedback early and often, always respectfully
  * Example: If you touch a new area of the codebase, ask for help
  * Example: When a feature is too complicated, pair
  * Example: Don’t get stuck for too long, ask for help.


__Evolutionary Architecture__

  * We evolve our architecture and technology constantly as our business evolves. We experiment with new technologies at the edges of our systems and adopt carefully and for real business value.
  * Example: elm
  * Example: single page css
  * Example: some architecture decisions


__Continuous Improvement__

  * We leave code better than we found it. We refactor before developing a feature, to ease its development.


__Reduce code and people dependencies__

  * We practice shared code and project ownership. Any team member should be able to work on any project interchangeably and we aim to rotate teams to ensure people have exposure to all parts of the codebase.



__Healthy conflict__

  * We believe in a blameless culture; which includes holding each other accountable through respectful feedback
