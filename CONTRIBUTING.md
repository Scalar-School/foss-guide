Contributing to Scalar School
==============================

The development of Bitcoin demands a high-level of rigor, adversarial thinking, thorough
testing and risk-minimization. Any bug may cost users real money.

The Scalar School project operates an open contributor model where everyone is welcome to contribute. Contributions can take many forms, including peer review, documentation, testing, and patches. We invite participation from all individuals, regardless of technical experience, expertise, age, background, identity, or any other characteristic. Everyone's contributions are valued and appreciated.

The goal of Scalar School is to create a safe and supportive learning environment that prepares participants to actively contribute to Bitcoin FOSS projects.

Communication Channels
-----------------------

Communication about the development of Scalar School projects happens primarily on the [Scalar School Discord](https://discord.gg/YhpJJXB6fN) in the `#technical` channel.

Discussion about code base improvements happens in GitHub issues and on pull
requests.

Code of Conduct
---------------
See the Scalar School Code of Conduct repository [here](https://github.com/Scalar-School/code-of-conduct).


Getting Started
---------------

First and foremost, start small.

This doesn't mean don't be ambitious with the breadth and depth of your
contributions but rather understand the project culture before investing an
asymmetric number of hours on development compared to your merged work.

Browsing through the [curriculum](https://github.com/Scalar-School/curriculum)
is a good first step to get an idea of the full Scalar School curriculum.

Even if you have an extensive open source background or sound software
engineering skills, consider that the reviewers' comprehension of the code is as
much important as technical correctness.

It's very welcome to ask for review on the Scalar School Discord. And also for reviewers, it's nice to provide timelines when you hope to fulfill the request while bearing in mind for both sides that's a "soft" commitment.

If you're eager to increase the velocity of the dev process, reviewing other
contributors work is the best you can do while waiting review on yours.

Contribution Workflow
---------------------

The codebase is maintained using the "contributor workflow" where everyone
without exception contributes patch proposals using "pull requests". This
facilitates social contribution, easy testing and peer review.

To contribute a patch, the workflow is as follows:

  1. Fork repository
  2. Create topic branch
  3. Commit patches

In general commits should be atomic and diffs should be easy to read.
For this reason do not mix any formatting fixes or code moves with
actual code changes. Further, each commit, individually, should compile
and pass tests (if applicable).

When adding a new feature, thought must be given to the long term 
technical debt. Every new features should be covered by functional tests.

When refactoring, structure your PR to make it easy to review and don't
hesitate to split it into multiple small, focused PRs.

Commits should cover both the issue fixed and the solution's rationale. These
[guidelines](https://chris.beams.io/posts/git-commit/) should be kept in mind.

To facilitate communication with other contributors, the project is making use
of GitHub's "assignee" field. First check that no one is assigned and then
comment suggesting that you're working on it. If someone is already assigned,
don't hesitate to ask if the assigned party or previous commenters are still
working on it if it has been awhile.

Use GitHub labels, projects, and milestons when appropriate.

When creating a new branch, the naming convention should start with the year (`YYYY`),
followed by the month (`mm`), followed by a succient and present tense branch name, all
separated by a hyphen (`-`). For example, `2024-08-add-contributing-guide`.


Peer Review
-----------

Anyone may participate in peer review which is expressed by comments in the pull
request. Typically reviewers will review the code for obvious errors, as well as
test out the patch set and opine on the technical merits of the patch. PR should
be reviewed first on the conceptual level before focusing on code style or
grammar fixes.


References & Going Further
-------------
These contributing guidelines were based on the [`lightningdevkit/rust-lightning/CONTRIBUTING.md`](https://github.com/lightningdevkit/rust-lightning/blob/main/CONTRIBUTING.md) guide, it may be beneficial to explore this guide further to see how other projects operate.

You may be interested by Jon Atack's guide on [How to review Bitcoin Core PRs](https://github.com/jonatack/bitcoin-development/blob/master/how-to-review-bitcoin-core-prs.md)
and [How to make Bitcoin Core PRs](https://github.com/jonatack/bitcoin-development/blob/master/how-to-make-bitcoin-core-prs.md).

While there are differences between the projects in terms of context and
maturity, many of the suggestions offered apply to this project.

Overall, have fun :)
