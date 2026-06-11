# Goal Machine v5.0

**Goal in. Result out — by default, not by willpower.**

A plug-and-play goal achievement system that turns any measurable goal into a high-probability execution loop. Built on decision theory, systems thinking, game theory, and gradient descent optimization.

**[Launch the Goal Machine →](https://lvvphole.github.io/Goal-Machine)**

-----

## What It Does

The Goal Machine treats your goal as a system input, not a wish. You define the goal, the system handles the structure — daily quotas, action ranking, progress tracking, correction signals, and circuit breakers.

It works for any goal with a number and a deadline: weight loss, revenue targets, exam prep, skill acquisition, savings milestones, or anything else you can measure.

## How It Works

The system runs in four views:

**Setup** — Input your goal, deadline, success metric, target and starting values, daily action quota, priority-ranked actions, and pre-built if-then correction rules. Three validation checks run before the machine activates.

**Dashboard** — Live progress ring, days remaining, pace comparison (actual vs. needed), streak counter, gradient correction dial (fine-tune / adjust / rebuild based on gap size), and a trend chart plotting actual trajectory against target.

**Daily Loop** — Today’s action checklist with dual validation (did it + done right), consecutive-blanks counter with circuit breaker alert at 5, and end-of-day state save capturing output value, best action, one system improvement, and notes.

**History** — Bar chart of daily action completion, if-then rules reference card, and scrollable log of every day’s data.

## Core Architecture

```
Validation Gate  →  Is the goal measurable? Do people succeed this way? Daily action exists?
Setup            →  Daily quota, action priority stack, if-then correction rules
Daily Loop       →  Sort targets → best hours on best work → do → check 60s → fix to size → next
Circuit Breaker  →  5 consecutive blanks → halt, switch method or targets
Gradient Correction → Big gap = rebuild | Medium gap = adjust | Small gap = fine-tune
State Checkpoint →  Save full state nightly; tomorrow starts from notes, not memory
Weekly Eval      →  Same effort, better results? System improving or just lucky?
Stop Conditions  →  Goal hit | Plan broken 3 weeks | Path too unlikely | No improvement 3 weeks
```

## Key Principles

- **The harness does more work than the model.** The system carries you on the days you can’t carry yourself.
- **One goal, one loss function, one convex surface.** Convergence is guaranteed with sufficient iterations.
- **The denominator kills systems.** People quit when the daily cost (time delay × effort) gets too heavy — not when the goal stops mattering. Lower the cost first.
- **You don’t rise to the level of your goals. You fall to the level of your system.**

## Tech Stack

Zero dependencies. Zero build step. Single HTML file.

- React 18 via CDN
- Pure SVG charts (no charting library)
- localStorage for persistence
- Deployable anywhere as a static file

## Deploy Your Own

Fork this repo, enable GitHub Pages (Settings → Pages → main branch / root), and your instance is live. All data stays on the user’s device.

-----

Built with systems thinking, decision theory, and gradient descent optimization.