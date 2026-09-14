# Wayne Haber readme

This is a guide to how I work and what I expect, written so you don't have to figure it out by trial and error. It's a starting point, not a contract. If something here doesn't match what you see from me, tell me. I'd rather fix the gap than have you work around it.

It's long. That's on purpose. I'd rather you know why I do things than just what I do, so most sections explain the reasoning. Skim the headings, read the parts that matter to you, and come back to the rest if/when it's relevant.

## What I care about

I'm here to help the people on my teams do the best work of their careers, and to ship things that matter to our customers. Those two goals are the same goal. When I'm deciding what to spend time on, I ask whether it helps someone on my team grow or helps a customer, ideally both.

Customer outcomes are the scoreboard. Not story points, not velocity, not how elegant the architecture is. If we can't connect the work to something a customer feels, I'll ask why we're doing it.

We will be ambitious. Not reckless, but aiming at things that would matter if we pulled them off. I'd like us to be one of the teams doing big things rather than later reading about someone else doing it. Big goals are also more fun. Nobody remembers the quarter they hit their story point target.

I've been doing this for a while. That doesn't mean I'm right. I've seen a lot of ways things go wrong, so I'll sometimes flag a risk early. Push back if you think I'm pattern-matching to the wrong pattern.

## How we treat each other

**Assume positive intent.** When something a teammate did looks wrong, start from "they probably had a reason" and go ask. Almost every time, they did. When they didn't, it was almost always a mistake, not malice, and mistakes are how people learn.

**Positive feedback in public, constructive feedback in private.** If someone did something well, say so where others can see it. It costs nothing and it's the least expensive, most effective motivation there is. If someone needs to hear something difficult, tell them one-on-one. Nobody improves from being corrected in front of an audience; they just get defensive and/or resentful.

**Say thank you.** Specifically and often. "Thanks for catching that before it hit prod" beats "great job team" every time. I'll try to model this. If I miss something you did that deserved a thank you, it's an oversight, not a judgment.

**Blameless problem solving.** When something breaks, the question is what in the system let it break, not whose fault it was. People who are afraid of being blamed hide problems, and hidden problems are the expensive kind. If you hear me asking "who owns this," it's because I want to talk to the person who knows the most, not because I'm looking for someone to blame.

**Short toes.** This one needs a definition. Having short toes means it's hard to step on them. If someone from another team, a newer engineer, or I wander into your area and suggest a change or just make one, the right reaction is curiosity, not territoriality. Nobody owns code the way they own a car. Ownership here means responsibility for outcomes, not a fence around the work. The flip side is that when you wander into someone else's area, do it with respect: ask, explain, and don't be surprised if they know something you don't.

**Seek out different perspectives.** The best ideas on this team won't all come from the people who've been here the longest or who talk the most. I want to hear from everyone, especially people whose backgrounds, experiences, or ways of thinking are different from mine. We all carry biases we don't notice, about who sounds credible, whose ideas get built on, and who gets interrupted. I have them too. If you notice one in action, including in me, say something. If you're one of the quieter voices, I'll make room, and I'd like you to take it.

## The five things that kill teams

Patrick Lencioni wrote a book called The Five Dysfunctions of a Team. They stack, each one causing the next:

1. **Absence of trust.** People won't admit mistakes or ask for help because they're afraid of how it looks.
1. **Fear of conflict.** Without trust, people avoid real disagreement, so meetings become polite and nothing gets resolved.
1. **Lack of commitment.** Without honest debate, people don't buy in, so decisions are ambiguous and half-supported.
1. **Avoidance of accountability.** Without commitment, nobody feels able to call out a teammate who isn't delivering.
1. **Inattention to results.** Without accountability, people optimize for their own status or their own area instead of the team's outcome.

Most of what follows is, one way or another, about not letting these take hold. Trust comes from being open about mistakes and giving people room to own things. Healthy conflict comes from arguing openly and then committing. Accountability comes from writing promises down with a name and a date. Results come from measuring the things customers feel.

## Collaboration is not consensus

**We work together, and we argue.** Those aren't in tension. What I don't want is decisions by exhaustion, where we keep talking until everyone agrees or gives up. That's slow, and it produces mushy decisions that nobody owns nor is actually committed to.

**Everyone with something to contribute is heard.** The model is: everyone with something to contribute gets heard, the person responsible (the DRI) decides, and everyone commits. You can disagree loudly before the decision. After it, everyone rows the same direction, including the people who lost the argument. If new evidence shows up, bring it, and we'll reopen. Relitigating without new evidence is how teams stall.

**Push decisions down.** The person closest to the problem usually has the best information, so my default is to let them decide and set guardrails rather than make the call myself. If you're waiting on me for something you could decide on your own, you probably don't need to wait.

**Two way doors.** For the decisions that do come to me, I think about whether they're reversible. Two-way doors get a quick yes; let's try it and learn. One-way doors, the ones that are expensive or slow to undo, write a proposal and then let's have a real discussion. Most decisions are two-way doors. People treat far too many of them as one-way.

**Bring data and customer impact.** Opinions are tiebreakers, including mine. If you can show me a number, a customer quote, or a reproducible result, you'll win the argument far more often than if you tell me what you think.

## Ownership

**Every piece of work has one name on it, the DRI.** The DRI is the **Directly Responsible Individual* (also sometimes knows as the OAK).  Not a committee, not "the team," one person who is directly responsible for it landing. That person doesn't have to do all the work, but they own the outcome, make the calls, pull in who they need, and are the one I go to with questions. If you look at something and can't tell who owns it, that's a bug. 

**When you own something, you really own it.** You decide how it gets done. You set the plan. You tell the rest of us what you need. I'm not going to hover, and I'm not going to second-guess reasonable decisions after the fact. In exchange, I expect you to carry it: keep people informed, raise problems early, and see it through. Ownership without follow-through is just a name in a spreadsheet.

This goes both ways. If I've taken on something that should be yours, tell me and take it. If you've been handed something you don't think you can own well, say so before it becomes a problem, not after.

## Write it down

**If it isn't written down, it didn't happen.** Decisions, designs, meeting outcomes, the reason we chose A over B, the thing you figured out at 11pm that saved the deploy. Put it somewhere the team can find it.

This isn't bureaucracy. It's how a team of ten stays in sync without ten meetings a day, how new people ramp without shadowing someone for a month, and how we avoid relitigating decisions because nobody remembers why we made them. It also means the information isn't stuck in someone's head, which is good for the team and better for the person. The most senior engineer on a team should be the one people can most easily do without for a week.

**Promises especially.** If you commit to something, write it down with a date. If I commit to something, hold me to the same. "We'll look into it" isn't a commitment. Every commitment has a name and a when. If you can't give a date, give a date for when you'll know the date.

**One place for each fact: SSOT (Single Source of Truth)**. When the same information lives in three places, two of them are wrong. Pick the one source of truth for each thing, link to it from everywhere else, and update it there. If you find a duplicate, delete it or turn it into a link.

**Findability matters as much as writing.** A doc nobody can find is the same as no doc. Use obvious names. Put things where people would look first. Link from the places people already go. When someone asks you a question that's answered in a doc, answer with the link, not a paraphrase, so the next person finds the doc.

**Record and transcribe meetings.** If a meeting includes a decision or a design discussion, record it and get a transcript. It lets people who couldn't attend catch up, clarifies "what did we actually agree to," and lets the person taking notes participate instead of typing. Nobody should have to be in a room to know what happened in it.

**Default to open.** Write in the shared channel, not the DM. Put the doc in the team space, not your drive. Share the half-finished design, not the polished one. If there's a reason something needs to be private, that's fine, but private should be the exception you choose, not the default you fall into. I'll hold myself to this too: what I know about priorities, org changes, and what's coming, you'll know as soon as I'm able to share it.

**Say why, not just what.** "We're moving to feature flags" is an instruction. "We're moving to feature flags so we can deploy every merge without waiting for a release train" is something people can reason about, disagree with, and apply to the next decision without having to ask. I'll try to always give you the why. Ask if I don't.

## Speed

*MVC** I'd rather ship something small this week than something complete next quarter. The small thing teaches us something real. The big thing is a guess that gets more expensive the longer it goes unshipped.

So: find the smallest version a customer or teammate can react to, get it out, learn, repeat. A design that's 60% right and in front of users beats one that's 95% right in a doc. If a piece of work has been in progress for more than a couple of weeks without anything landing, that's a signal to cut scope, not to work harder. The minimum viable version is the goal, not a compromise.

**Bias for action.** When you're not sure, do the smallest reasonable thing and see what happens, rather than waiting for certainty. Certainty isn't coming. Most of the cost of a wrong decision lies in how long it takes you to notice it's wrong, and you notice it faster when you're doing than when you're deliberating.

**Sense of urgency**. Things matter, and time matters. Customers are waiting, competitors are moving, and the problem we're solving this quarter is someone's real problem today. Move like it matters. That's different from working late or cutting corners; it's about not letting things sit. If a decision can be made today, make it today. If a review can be done this hour, do it this hour.

**Limit the blast radius.** Speed is only safe when mistakes are small. Ship behind flags. Roll out to a slice before everyone. Make changes that are easy to undo. When you're about to do something risky, ask "if this goes wrong, how many people does it hurt and how fast can I reverse it," and shrink both numbers before you go.

**Embrace change.** Priorities will shift. Requirements will turn out to be wrong. The tool we picked will get replaced. This is what it looks like to work on something that matters in a field that's moving fast, not a sign that something went wrong. The teams that win are the ones that treat a change of direction as new information rather than a betrayal.

**Process** The same goes for process. If something about how we work is bad, change it a little this week rather than designing the perfect system. We can change it again next week.

## Don't waste it

Time, attention, and compute are all finite. Before doing something, ask whether it needs to be done at all. Before building something, ask whether it already exists. **Before scheduling a meeting, ask whether it can be a message.** Before writing a long doc, ask whether a short one would do.

There's a five-step process I use when looking at any system or workflow, borrowed from SpaceX, Tesla, etc. The order matters, because people always want to skip to the end:

1. **Challenge the requirements.** Every requirement should come with the name of the person who set it, and it should be questioned, especially those from smart people, because nobody questions them. Most requirements are wrong or at least sloppier than they look.
1. **Delete the part or process.** If you aren't occasionally adding things back, you aren't deleting enough. The best code is the code you didn't write.
1. **Simplify and optimize what's left.** Only after deleting. Optimizing something that shouldn't exist is the one of the most common engineering mistakes.
1. **Speed up the cycle time.** Once it's simple, make it fast.
1. **Automate last, not first.** Automating a bad process just makes it bad faster.

**Only healthy constraints.** Some constraints are real: the customer's data has to stay in their region, the audit trail has to be complete, security review has to happen. Those are healthy. They protect something that matters. A lot of other constraints are just habits: the approval that exists because someone got burned once in 2019, the meeting that's on the calendar because it's always been, the sign-off from a team that stopped caring years ago. If a constraint isn't protecting something you can name, question it. If nobody can say what it protects, remove it.

**Boring solutions are usually right.** Reach for the tool we already have before adding a new one. Solve the problem in front of you, not the one you imagine we might have next year. If a shortcut gets us the learning faster and we can clean it up after, take the shortcut and write down that we did.

**Bias toward async.** A Slack thread that five people read on their own time beats a meeting that five people attend at the same time. Meetings are for things that need real-time back-and-forth: hard decisions, emotional conversations, brainstorming. Status, updates, questions, and most reviews are better in writing. And a message in a channel helps more people than a message to me.

## If it isn't measured, it doesn't exist

I mean this literally. If you tell me the system is faster and there's no number, I'll believe you as a person and not as an engineer. Measure the things that matter: what customers experience, and what would change what you do next. Latency a reviewer feels. Accuracy on a real case. Time from merge to production. How many incidents, how fast they're resolved.

Don't measure things that just look good on a slide. Lines of code, story points, number of PRs, hours logged. These are vanity metrics. Nobody reads the slide, and if they did, it wouldn't tell them anything they could act on.

**The test for a metric is: if this number moved, would someone do something different? If not, stop collecting it.**

## Growth

I want everyone here to be better at this job a year from now than they are today, including me. That means trying things you're not sure you can do, being bad at them for a while, and getting better. Skills aren't fixed. The engineer who's struggling with something today and the one who's an expert at it are usually the same person, a year apart.

If you want to try something you've never done, tell me. I'll usually find a way to make room for it. If you tried and it didn't go well, that's what learning looks like from the inside. What I care about is that you noticed, wrote down what you learned, and would do it differently next time.

## Engineering standards

This is the part that applies to how we build, not just how we work together. They're not aspirations; they're the baseline.

- **Regression testing is 100% automated.** If a human has to click through something before a release, that release will happen less often and with more fear, and fear is the enemy of speed. Anything worth testing before a release is worth automating.
- **Regression tests run on every build.** Not nightly, not before a release. Every build. A test that runs every two weeks tells you something broke in the last two weeks. A test that runs on every build tells you which commit.
- **If the unit and regression tests pass, the code deploys to production automatically.** No release train, no manual gate, no "we'll ship Thursday." The tests are the gate. If you don't trust them enough to let them deploy, fix the tests, not the process.
- **New features and major changes ship behind a feature flag, default off.** This is what makes continuous deployment safe. Code goes to production dark, gets turned on for a slice, and gets turned off if something's wrong. 
- **Rollback is 100% automated and validated.** Not documented, not "we know how." Tested on a schedule so that when you need it at 2am, it works. If you've never rolled back, you don't have a rollback; you have hope.
- **When a release causes a production incident, the blameless review asks how to prevent recurrence by improving the architecture and adding automated tests.** It never concludes that we should ship less often. Slowing down feels safer and makes things worse: bigger releases, more changes per release, harder to find what broke. The fix for a painful release is more releases, each one smaller, with better tests around them.

## How to reach me

Teams/Slack is the front door. Post in the team channel and tag me, unless it's something confidential; then DM me. I read everything, though not always immediately. Most things don't need a meeting.  I have a daily AI scheduled task to look for things I didn't respond to that I should have.

If something needs real discussion, send me a *short* written doc before we talk. A page is plenty. Half a page is often better. Writing it down forces the thinking, and it means we spend our time together on the hard parts instead of me catching up. I'll read it ahead of time.

If it's urgent, say so and I'll respond fast. If it isn't, I may batch it. Both are fine.

I ask a lot of questions. That's curiosity, not doubt. If I'm asking "why" three times in a row it's because I'm trying to understand, not because I've already decided you're wrong. If it starts to feel like an interrogation, tell me and I'll back off.

## 1:1s

If you report to me, we meet weekly and the agenda is yours. Bring what's on your mind: career, a decision you're stuck on, something bugging you about how the team works, a thing you want to learn. Status updates belong in Teams/Slack or a doc, not here. If the only thing on the agenda is status, we'll cancel and use the time for something better.

I'll bring things too, but I'll try not to crowd out yours. My job in that hour is to help you think, unblock you, and pay attention to where you want to go next.

## Feedback

I give feedback directly, in the moment, and in private. If I see something I think you should change, you'll hear it from me the same day, not in a review three months later. When it's substantive, I'll put it in writing first so it's concrete, and then we'll talk it through.

I want the same from you. If I've made a call you disagree with, handled something badly, or you're just not getting what you need from me, say it. In writing is fine. In person is better. I'd rather hear it awkwardly than not hear it.

I can come across as blunt. My intent is care, and I'm working on the delivery. If something I said landed wrong, tell me. I won't be defensive about it.

## Things that will frustrate me

**Surprises.** Bad news doesn't improve with age. If something is slipping, broken, or at risk, tell me as early as you know, even if you don't have a plan yet. "This might be a problem, I'm not sure yet" is a perfectly good message. I won't be upset about the problem. I will be upset if I find out from someone else.

**Vagueness.** No owner, no date, no metric. 

**Meetings that should have been a message.**  Focus time is valuable, and too meetings kill it.

**Information that lives in one head.** If you're the only one who knows how something works, you're not indispensable; you're a risk. Write it down.

## For peers and stakeholders

1. If you need something from my team, the fastest path is a Teams/Slack message to me with what you need, why, and when. I'll route it or tell you where it sits against what we've already committed to. I try hard not to say yes to things we can't deliver, so if I say no or not yet, it's so that the things we do say yes to actually ship.
2. You'll be able to see what we're working on and why without asking me. Our priorities, our plans, and our progress are written down somewhere you can read. I'd appreciate the same. If priorities are shifting on your side, the earlier I hear it the more I can adjust.
3. I'll assume you're acting in good faith, and I'll do the same when we disagree. I'll disagree with you openly if I think we're heading the wrong way, and I'll do it with you rather than about you. Then I'll commit to whatever we land on.
4. We often operate under different constraints, and we may not realize it, so we should not assume them and discuss them openly.

## A few things about me

I love learning new things, and I love watching other people learn. A lot of what I find satisfying about this job is seeing someone do something they didn't think they could.

I'm a fan of the idea that you start with why. If I ask what problem we're solving before we talk about how, that's where it comes from.

