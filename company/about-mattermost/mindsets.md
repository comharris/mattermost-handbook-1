# Mindsets

NOTE: This section is currently being imported from: [https://docs.mattermost.com/process/training.html\#mindsets](https://docs.mattermost.com/process/training.html#mindsets)

Mindsets are “tool sets for the mind” that help us find blindspots and increase performance in specific situations. They’re a reflection of our shared learnings and culture in the Mattermost community and at Mattermost Inc.

To make the most out of mindsets, remember:

* **Mindsets are tools** - Use common sense to find the right mindset for your situation. Avoid using ones that don’t fit.
* **Mindsets are temporary** - Try on a mindset the way you’d try a tool. You can always put it down if it doesn’t work.
* **Mindsets are not laws** - Mindsets are situation-specific, not universal. Don’t use them to debate.

When you read about great leaders, they share mindsets relevant to success in their specific situations, which differ from their peers. Remember that “advice is personal experience generalized” so be mindful about what you apply.

In this context, here are mindsets for Mattermost:

## Learn, Master, Teach

**Learn** a new topic quickly, develop **mastery** \(be the smartest person at the team/company/community on the topic\), then **teach** it to someone who will start the cycle over.

If you’re a strong teacher, their mastery should surpass yours. This mindset helps us constantly grow and rotate into new roles, while preventing “single-points of failure” where only one person is qualified for a certain task.

## Slow is smooth, smooth is fast

When you rush to get something done quickly, it can actually increase the time and cost for the project.

Rushing means a higher chance of missing things that need to be done, and the cost of doing them later is significantly higher because you have to re-create your original setup to add on the work.

## Emotion, Assumption, and Priority

Consider when two rational people disagree, the cause often comes from one of three areas:

1. **Emotion** - There could be an **emotion** biasing the discussion. Just asking if this might be the case can clear the issue. It’s okay to have emotions. We are humans, not robots.
2. **Assumption** - People may have different underlying **assumptions** \(including definitions\). Try to understand each other’s assumptions and get to agreement or facts when you can.
3. **Priorities** - Finally people can have different **priorities**. When everyone’s priorities are shared and understood it’s easier to find solutions that satisfy everyone’s criteria.

While the emotions, assumptions, priority mindset won’t work for everyone in every case, it’s helped resolve complex decisions in our company’s history.

## Likes and Wishes

An easy way to check in with team members about how things are going.

* What do you _like_ about how things are going?
* What do you _wish_ we might change?

Use these one-on-one or in a group as a way to open conversations about what to keep and what to change in how we do things.

## Drafts at 1%, 50%, 99%

Being clear on expectations when asking for someone’s review can help speed and smooth the process. In this mindset, there are three types of review:

* 1% Draft - Completely open to ideas and changes in direction. Rework is inexpensive.
* 50% Draft - Half complete work. There is structure, but also a lot of room for change. Some rework is inexpensive, some is expensive.
* 99% Draft - Nearly completed work. Rework at this point is very expensive.

## Shoulder Check

When a new owner takes over a process or a project from a previous owner, there are a finite number of “blindspots” of which the original owner is aware and the new owner will need to understand.

Using the analogy of changing lanes while driving a vehicle and learning to do a “shoulder check” for information that is not visible from standard controls, we have a process for the new owner and previous owner to jointly review processes until the transfer is complete.

This process is similar to [Mini-boss, End-boss](https://docs.mattermost.com/process/training.html#mini-boss-end-boss), except that the mini-boss is also the new owner of a process, and not only a reviewer. Shoulder checks should be requested by new owners to avoid “crashing”:

> * Making changes to systems that break existing processes and may lose data and hurt the productivity of others downstream without notice and without a replacement system in place \(behavior known as [“Dead Tarzan”](https://docs.mattermost.com/process/training.html#dead-tarzan)\).
> * Repeatedly investing in mis-prioritized projects due to a misunderstanding of requirements from project stakeholders and insufficient confirmation of intended outcomes.

Even when not crashing, as part of our [Self Awareness value](https://docs.mattermost.com/process/handbook.html#values), top team members will constantly be seeking feedback and review from people around the company.

## Brown M&Ms

A “brown M&M” is a mistake that could either signal dangerous oversights in the execution of a project, or be a completely innocuous and unimportant error. When a brown M&M is found, aim to rule out a dangerous error as quickly as possible. Do fast drilldowns and systematic checks to see if more brown M&Ms are found, and if so, an entire project may need to be reviewed.

Examples of brown M&Ms may include:

1. Significant mistakes in process, consistency or documentation suggesting lack of review or lack of understanding of the pre-existing system
2. Ambiguous definitions that would make completion of a procedure difficult or unpredictable

The name brown M&M comes from a safety technique used by the American music band Van Halen, who had to set up large, complex concert stages in third tier cities, where few local workers had experience with the safety standards vital to construction. In the [contract rider](https://en.wikipedia.org/wiki/Van_Halen#Contract_riders) with each venue, Van Halen required a bowl of M&M candies with all brown M&Ms removed. Failure to provide the bowl was grounds for Van Halen’s stage crew to inspect all of the local vendor’s work for safety issues, because it meant the vendor had not paid attention to detail, and safety could be at risk.

## Correct Minimums: Medic, Field Surgeon, Plastic Surgeon

When making project investment decisions, we optimize for high impact in the context of customer obsession, empowered by ownership, while being constrained by “be proud of what you build”.

The failure case is over-investing in processes and infrastructure, stealing mana from higher priority work, reducing speed and agility for the company and unnecessarily increasing cost and bureacracy.

The objective of optimization is to invest at minimal levels for efficiency and safety while maximizing impact.

In making these trade-offs, consider the following mindsets:

* **Correct Minimum 1: Medic**

  > Safely fix something that is important, broken and dangerous as fast as possible. Speed is critical - do not worry about “leaving a scar” in our architecture or business process, just own it and get it done. Solve the problem, **do not overbuild**.
  >
  > _Example:_ Something incorrect on our public website with more than 100 page views a month should be fixed immediately and not delayed to be done with a longer term project, such as a website re-design. If the staging server cannot be pushed, this means manually fixing production and duplicating that change on staging, rather than trying to fix staging.

* **Correct Minimum 2: Field Surgeon**

  > Triage tasks that are important and broken but not dangerous, and fix the most important things with a minimum time and cost. Scarring should be a low-priority consideration–it is fine to leave scars and it is fine to spend a little energy to avoid big ones. Solve the problem for the next stage of growth, but don’t solve it in two to three stages ahead.
  >
  > _Example:_ In Mattermost, spend 2 mana to enable automated messages over 4000 characters to be broken into multiple posts instead of being rejected, which is a problem every developer hits when they attempt to output log information via curl commands.

* **Correct Minimum 3: Plastic Surgeon**

  > Fix and optimize critical, high volume flows in our customer experience and product with heavy investment if needed to make high impact changes. Scars can be avoided and removed to produce a high impact result.
  >
  > _Example:_ Click-tracking traffic on about.mattermost.com and optimizing flows to direct visitors to learn about the product and downloading it is a flow that should be continually optimized.

## Mini-boss, End-boss

After completing the initial draft of a project, there may often be more than one reviewer to approve changes. This may be for different disciplines to review the work \(for example, both development and design teams reviewing code changes to the user experience\) and it may also be for reviewers with different levels of experience to share feedback.

When reviewing significant user interface changes, code changes, responses to community or customers, or changes to systems or marketing material changes, it is ideal to have at least two reviewers:

* **Mini-boss**: Reviewer less experienced in domain or Mattermost standards for the first review
* **End-boss**: Reviewer more experienced in domain or Mattermost standards for the final review for the discipline \(e.g. development, design, documentation, etc.\)

This system has several benefits:

1. The Mini-boss provides feedback on the most obvious issues, allowing the End-boss to focus on nuanced issues the Mini-boss didn’t find.
2. The Mini-boss learns from the End-boss feedback, understanding what was missed, and becoming a better reviewer.
3. Eventually the Mini-boss will be as skilled at reviewing as the End-boss, who will have nothing futher to add after the Mini-boss review. At this point, the Mini-boss becomes an End-boss, ready to train a new Mini-boss.

The naming of this term comes from video games, where a person submitting material for review must pass a “mini-boss” challenge before a “end-boss” challenge for different disciplines.

