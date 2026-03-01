# The Health System: AI-Powered Fitness Coach in Your Pocket

A complete health optimization system powered by Claude. It builds your personalized plan (calories, macros, training program, supplements), then runs as a daily macro tracker and meal solver you use in under 60 seconds.

**This is not an app.** It's a Claude Project — a persistent AI workspace with your health plan baked into its instructions. You talk to it in plain English. It does the math.

### Why this works

Most plans make you eat from a fixed meal list. This one doesn't. You eat whatever you want — the solver tells you exactly how to hit your targets with your final meal. Had pizza for lunch? Fine. The math still closes. That flexibility is why people actually stick with it.

Total time cost: ~10 hours a week. Three hours training, a few hours cooking, a few minutes a day talking to Claude. That's it. No meal prep Sundays. No spreadsheet wrestling. No willpower-dependent decisions about what to eat — just data and a solver that does the algebra for you.

---

## Before You Start: The Commitments

This system works. But it only works if you do. Read these commitments carefully. If you can't honestly say yes to at least the first five, this isn't the right time — and that's fine. Come back when you're ready.

### Non-Negotiable (The System Breaks Without These)

1. **3+ hours per week of training.** Three sessions, ~60 minutes each. You pick the days. You show up. Rain or shine, motivated or not. The program is designed to be the same simple workout every time — your only decision is whether to walk through the door.

2. **Daily food tracking for at least 90 days.** You will weigh your food with a kitchen scale and tell Claude what you ate. This takes 2-3 minutes per day. It feels tedious at first. By week 3 it's automatic. By month 3 you can eyeball portions and only spot-check with the scale. But you earn that intuition — you don't start with it.

3. **A kitchen scale.** $12 on Amazon. Non-negotiable. Eyeballing portions is how people eat 300-500 calories more than they think and wonder why nothing's changing. The scale is the single highest-ROI purchase in this entire system.

4. **Weekly weigh-ins.** Same day, same time, morning, after bathroom, before food. One number per week. You don't obsess over it. You use it as a data point to calibrate the system. If the trend isn't matching the target after 2-3 weeks, you adjust by 100-150 calories. That's it.

5. **6 months of consistency.** Not perfection — consistency. You will miss workouts. You will eat off-plan. You will have bad weeks. The system accounts for this. What matters is that you don't quit after a bad week. You just open Claude the next morning and say "count my macros" like nothing happened. Because nothing did — one bad day in 180 is noise.

### Strongly Recommended (The System Works Better With These)

6. **7+ hours of sleep per night.** Sleep is when your body actually builds muscle and regulates hunger hormones. Training on 5 hours of sleep is driving with the parking brake on. You can't out-supplement or out-train bad sleep. If you're consistently under 6 hours, fix that before optimizing anything else.

7. **Progress photos every 2 weeks.** Front and side, same lighting, same time of day. The mirror lies. The scale fluctuates. Photos don't. Looking back at week 1 from week 12 is rocket fuel for motivation. You don't have to share them — they're for you.

8. **A supplement budget of ~$45-80/month.** The core stack (creatine, vitamin D, magnesium, fish oil) costs ~$45-60/month. Condition-specific additions add $15-30. You can start with just creatine ($10/month) and add from there. Supplements are the least important thing on this list — but they're the easiest marginal gain available.

9. **Cooking or meal prep capability.** You don't need to be a chef. You need to be able to cook chicken, rice, and a vegetable. If you eat out for every meal, the tracking still works, but accuracy drops and your wallet suffers. Even 3-4 home-cooked meals per week makes a meaningful difference.

### The Honest Truth

This system asks for about 10 hours per week of your life: 3 hours training, 15 minutes daily tracking, 2-3 hours meal prep, and the rest is sleep discipline and showing up. That's roughly 6% of your waking hours.

In exchange, you get a body that works better, a brain that works better, more energy, better sleep, and a relationship with food based on data instead of guilt. The ROI is absurd. But only if you actually do it.

**If you read those commitments and thought "yes" — let's set you up.**

---

## What This System Does

**Phase 1: Build Your Plan (one-time, ~30 minutes)**

You have a conversation with Claude where it acts as your coach. It will:

- Ask for photos and basic stats (age, sex, height, weight)
- Estimate your body fat percentage
- Ask about your goals, equipment, schedule, and constraints
- Calculate your TDEE (how many calories you burn)
- Determine whether you should cut, bulk, or recomp
- Set your daily calorie and macro targets
- Build your training program (8 exercises, same workout every session)
- Design your supplement protocol with specific products and doses
- Generate a shopping list with links and costs

At the end, Claude produces a personalized health plan document. You paste this into the project — and now every future conversation knows your exact targets.

**Phase 2: Daily Operations (60 seconds per day, ongoing)**

Every day (or whenever you eat), you open the project and tell Claude what you ate:

> "Count my macros: 3 eggs, toast with butter, protein shake"

It instantly shows you a table: what you've eaten, your targets, and what's remaining. Then you can say:

> "Solve my last meal with chicken, rice, and almonds"

It runs a mathematical solver that tells you exactly how many grams of each ingredient to eat to perfectly hit your remaining macro targets. Weigh it out, eat it, done.

**That's the whole daily workflow.** List food → get numbers → solve final meal → eat.

---

## Installation

1. Go to [claude.ai/customize/skills](https://claude.ai/customize/skills)
2. Upload both `.skill` files from this repo:
   - [`health-strategy.skill`](health-strategy.skill) — one-time setup interview
   - [`daily-macros.skill`](daily-macros.skill) — daily macro tracker and meal solver

That's it. Both skills are now available in every Claude conversation.

---

## Setup Guide (Step by Step)

### What You Need

- A Claude account (free works, but Pro is better for daily use — higher message limits)
- 30 minutes for the initial setup conversation
- Photos of yourself (front + side, shirtless or fitted clothing) for body fat estimation
- Your basic stats: age, sex, height, current weight

### Step 1: Run the Health Strategy Interview (One-Time Setup)

This skill is your project builder. It interviews you once and generates your complete, personalized health plan.

1. Start a new [Claude project](https://claude.ai) — this will be your persistent health workspace
2. Open a conversation in that project and type: **"Set up my health plan"**
3. Claude will walk you through the interview:
   - It'll ask for photos and stats first
   - Then goals, equipment, schedule, constraints
   - It'll confirm its understanding before generating anything
4. At the end, Claude produces your personalized health plan — calorie targets, macro splits, training program, and supplement schedule
5. **Paste the generated plan into your project's instructions** — this is what makes every future conversation in that project aware of your targets

You only run this skill once (or again when you're ready for a new phase).

### Step 2: Use Daily Macros as Your Daily Driver

This is the skill you'll use every day. Open a conversation in your project anytime you eat:

- **"Count my macros: [list what you ate]"**
- **"Solve my last meal"** (after counting, to figure out your final meal)
- **"Solve my last meal with chicken, rice, and almonds"** (if you want to specify ingredients)
- **"Ate: [food list]. Solve remaining with chicken, rice, almonds"** (count + solve in one shot)

Because your health plan is in the project instructions, every conversation already knows your calorie and macro targets. You just talk to it.

That's it. You're running the system.

---

## Common Questions

**"What if I eat something and don't know the exact amount?"**
Just describe it naturally: "a chicken breast," "a bowl of rice," "two slices of pizza." Claude will estimate reasonable portions and note its assumptions. The weekly weigh-in corrects for any systematic error.

**"What if I want to change my solver ingredients?"**
Just say so: "Solve it with ground turkey instead of chicken" or "use cottage cheese and oats." The solver handles substitutions on the fly.

**"When do I re-run the health strategy?"**
When you finish your current phase (typically 3-6 months). Start a new conversation and say "I'm ready for my next phase" or "Re-run my health strategy." Claude will reassess and build your next phase.

**"Can I use this on mobile?"**
Yes. The Claude app works the same way. Your project syncs across devices.

**"What if I go off-plan for a day/week/vacation?"**
Open Claude the next day and count your macros like nothing happened. The system doesn't judge. It just gives you numbers. One off day is statistically irrelevant over a 6-month timeline.

**"I don't want to share photos with AI."**
If you have recent DEXA scan or BodPod results, Claude will accept those instead. Without either photos or clinical data, the body fat estimate will be less accurate, which may route you to the wrong phase. Photos are strongly recommended but not technically mandatory.

---

## Files in This Package

| File | What It Is |
|------|-----------|
| `README.md` | This guide (you're reading it) |
| [`health-strategy.skill`](health-strategy.skill) | Interviews you and builds your personalized health plan (one-time setup) |
| [`daily-macros.skill`](daily-macros.skill) | Daily macro tracker and meal solver (ongoing use) |

---

## Credits

Built as a Claude Skills system. The health strategy interview, macro tracking, and linear programming meal solver were designed as complementary tools: one builds the plan, the other operates it daily.

If you find this useful, the best thing you can do is actually use it for 6 months and tell someone else about it after you have results.
