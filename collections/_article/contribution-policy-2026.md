---
title: "Changes to our Contribution Policies"
excerpt: "Godot is growing fast, here is how we are dealing with the huge increase in contributions."
categories: ["news"]
author: Godot Foundation
image: /storage/blog/covers/godot-foundation-update-2024.webp
date: 2026-06-25 18:00:00
---

For the last several years we have become overwhelmed by the large number of
PRs, especially those from new contributors. The number of open PRs has become a
meme in the community. In part, the number of open PRs is a healthy sign that:

1.	People are interested in contributing to Godot and are willing to put in time to contribute,
2.	We are being cautious about feature creep,
3.	We are dedicated to high code quality.

But ultimately, a large part of the backlog comes from the fact that the number
of qualified reviewers is small, reviewing PRs is not fun, and we can't keep up
with everything new coming in. 

This problem is compounded by the recent increase in AI-generated contributions,
both by AI agents and by humans submitting AI generated code. The amount of
effort required to make a PR has gone down, while the amount of work to review
PRs and the amount of people available to review has stayed the same. This
reviewer shortage was already a problem, but it was one that we successfully
ignored. Now we can no longer ignore it.

AI contributions have the added pain of being demoralizing. Reviewing PRs is
already thankless work, but it is rewarding because reviewers generally feel
that their efforts are contributing to educating a new contributor (who may
become a future maintainer/reviewer). If your feedback on PRs is just being
absorbed by a machine and not going towards mentoring a potential future
maintainer, it becomes much harder to justify spending your free time on PR
review.

It is time for us to recognize that these problems aren't going away and
therefore we need to take steps to reduce the burden on maintainers while
ensuring we still have a pipeline to mentor new contributors to become future
maintainers. 

Accordingly, we are in the process of updating our contribution policies,
including adding a stricter policy on AI contributions. Our focus will be on:

- **Encouraging new contributors to become future maintainers, that involves teaching and growing the understanding of new contributors.**
    - LLMs (and new contributors heavily relying on AI) can't learn from specific feedback and thus can't benefit from maintainers providing feedback.
- **Ensuring all contributions are made by humans who can take responsibility for their code and be able and willing to fix it when needed.**
    - AI cannot take responsibility, and we can't trust heavy users of AI to understand their code enough to fix it.
- **Adding barriers to low-effort slop.**
    - Unfortunately, this means we need to add barriers to contribution, but want to do it in a way that does not cut off our maintainer pipeline.
- **Increasing the incentive to review PRs.**
    - PR review is the largest bottleneck in the engine right now. We need to ensure that people who choose to review PRs feel their time is well spent.

Our general [contributing
policy](https://contributing.godotengine.org/en/latest/engine/guidelines/index.html)
will be amended to include a prohibition on new features or significant
re-factoring from new contributors without explicit permission from maintainers.
This ensures that new contributors take the time to learn the codebase and
engage with maintainers to build trust by working on bug fixes and documentation
before diving into significant projects. We consider a new contributor to be
someone with 3 or fewer merged pull requests. 

Our AI policy will be amended to include that:
- **All AI use must be disclosed**
    - This is the same as in our [current policy](https://contributing.godotengine.org/en/latest/pull_requests/pull_request_guidelines.html#ai-assisted-contributions)
- **Only trusted contributors can use AI**
    - New contributors are not permitted to use AI to contribute until they have shown that they understand the codebase.
    - We don’t have an exact criteria for when someone becomes a trusted contributor, but at minimum it means:
        - Having several merged Pull Requests
        - Contributing regularly for at least 6 months
        - Being active on the Godot chat
- **Absolutely no AI generated comments on Github/issues/PR descriptions/discussions/chat messages** (e.g. all communication must be human-to-human)
    - This is basic principle of respect. Our maintainers are volunteering their time, so please be respectful.
    - Machine translations are still acceptable as long as the original content was written by a human.
- **No autonomous AI agent use or vibe coding**
    - This already leads to an auto-ban from our Github repository and will continue to do so. We simply don’t have the resources to review fully AI-generated code. 

Things change every day with respect to the current suite of AI tools available.
We will continue taking a conservative approach in our policies towards them,
but we will re-evaluate as things evolve. 
