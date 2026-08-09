# Claude Courses — Intensive Group Study Plan

*Six courses from [claude.com/resources/courses](https://claude.com/resources/courses), reorganized into 8 study sessions — each with a discussion quiz ordered by difficulty — for a small group studying together, fast.*

**8 sessions · ~13 hrs of video total · all six courses are free to register for**

---

## Before you start (Day 0 checklist)

Set this up once, as a group, so you don't lose a live call to setup problems later:

- **Everyone**: a free Skilljar account (just needs an email).
- **Before Session 3 (Claude Code 101)**: a code editor + terminal, and a Claude account (Pro/Max/Enterprise) or an API key.
- **Before Session 4 (Claude Platform 101)**: Node.js + npm installed (the demos use the TypeScript SDK), an Anthropic Console account, an API key, and a small amount of prepaid API credit.
- **Before Sessions 5–8 (Building with the Claude API)**: Python installed and basic comfort with JSON — the same API key from Session 4 works here too.

**What actually costs money, and how much**
- The 6 courses, all Skilljar registration, and all quizzes: **completely free**, no payment anywhere.
- **Claude Code (Session 3)** needs either a paid Claude.ai plan (Pro and up, roughly $20/month) or an Anthropic Console API key with credit loaded — the free Claude.ai tier doesn't include Claude Code at all.
- **The API-based sessions (4, 5–8)** just need an Anthropic Console account with an API key — no subscription required. Minimum top-up is $5, and new accounts often get a small starter credit; either should comfortably cover a group's worth of course exercises.
- **You don't all need to pay separately.** The API/Console route is naturally shareable — one person funds a Console account (or invites the group to one workspace) and generates a key the group uses during the live screen-share parts; only whoever's "driving" that session needs it open. For Claude Code, the cheapest shared setup is the same: one funded Console account + API key, rather than everyone buying a separate Pro subscription.
- **Going fully free isn't possible for the hands-on parts** — a real API call or Claude Code session always draws on paid infrastructure. But total group cost can realistically stay around $5–10: watch the videos for free, rotate who's "driving" on one shared key for Level 3 tasks, and only that account needs credit.
- Numbers shift — confirm current pricing at [claude.com/pricing](https://claude.com/pricing) and [platform.claude.com](https://platform.claude.com) before committing.

- Pick one shared doc/channel for notes — you'll use it as a running "confusion log" (see Recommendations).

## How this plan works

- **Solo, individually**: everyone watches the assigned material on their own time. Where a course has its own built-in Skilljar quiz, take it solo first — instant feedback — and bring anything you missed into the group call.
- **Group video call**: once everyone's done with the material, discuss the chapter, then work through *this plan's* discussion quiz together. It's separate from Skilljar's quiz and built for talking, not clicking.
- **Every quiz has 3 levels, easiest to hardest:**
  - **Level 1 — Warm-up**: quick recall, everyone should be able to answer.
  - **Level 2 — Apply**: discussion questions and problems with no single right answer — this is where real understanding shows up.
  - **Level 3 — Screen-share**: someone actually does the thing live while the rest of the group watches and pushes back.
- **Why grouped this way**: Claude 101 and AI Fluency for Builders are both short (~1 hr) and non-technical, so they share a call. Cowork, Claude Code 101, and Platform 101 each get their own call — short too, but each introduces a genuinely different way of working. Building with the Claude API is 8+ hours with its own quiz checkpoints already built in every couple of modules, so it's split into 4 sessions along those same natural boundaries instead of one marathon call.
- **Suggested pace**: 1 session/day keeps everyone fresh for the screen-share part — that's genuinely where most of the learning happens — so about 8 days. To move faster, 2 sessions/day works; just avoid stacking two "Building with the API" sessions on the same day, they're dense.

## The 8-session roadmap

| # | Session | Covers | Runtime |
|---|---|---|---|
| 1 | Claude 101 + AI Fluency for Builders | Using Claude day-to-day + the 4D collaboration framework | ~2 hrs |
| 2 | Introduction to Claude Cowork | Multi-step, hands-on work on real files | ~1 hr (est.) |
| 3 | Claude Code 101 | AI coding agent, terminal-first | ~1 hr |
| 4 | Claude Platform 101 | API foundations, agent loop, tools, MCP (TypeScript) | ~1 hr |
| 5 | Building with the API — Part 1 | Accessing the API, prompt evals, prompt engineering | ~2 hrs |
| 6 | Building with the API — Part 2 | Tool use, RAG & agentic search | ~2 hrs |
| 7 | Building with the API — Part 3 | Extended features, Model Context Protocol | ~2 hrs |
| 8 | Building with the API — Part 4 | Claude Code/computer use, agents & workflows, final assessment | ~2 hrs |

---

## Session 1 — Claude 101 + AI Fluency for Builders

**Solo study**
- [Claude 101](https://anthropic.skilljar.com/claude-101) — all 4 modules: Meet Claude, Organizing your work and knowledge, Expanding Claude's reach, Putting it all together (no built-in quiz — this session's discussion quiz is your assessment)
- [AI Fluency for Builders](https://anthropic.skilljar.com/ai-fluency-for-builders) — the 4D Framework applied to building; take its built-in quiz solo first
- *Optional*: the course page itself recommends *AI Fluency: Framework & Foundations* as a deeper prerequisite. Not one of your six, but ~1 hr, if the framework feels rushed (see Recommendations)

**Group call — discussion quiz**

*Level 1 — Warm-up*
1. In your own words, what's the difference between a plain conversation and a Project in Claude?
2. Name the 4 D's of the AI Fluency framework, one line each.

*Level 2 — Apply*
3. Pick a real task from your own coursework or life. Decide together what parts you'd delegate fully vs. keep for yourself — justify the split using Discernment and Diligence.
4. Debate it: is there a task where you'd trust Claude's output without checking it? Whoever disagrees has to argue the other side for a minute.
5. When would "connecting your tools" or "research for deep dives" actually change how you work, vs. when is a plain chat enough?

*Level 3 — Screen-share*
6. Each person shares their screen for ~5 minutes: start a new Project with a short custom instruction, then produce one Artifact from a real prompt. The group critiques the prompt using the "Description" D — could it be tighter?

---

## Session 2 — Introduction to Claude Cowork

**Solo study**
- [Introduction to Claude Cowork](https://anthropic.skilljar.com/introduction-to-claude-cowork) — full course: setup, your first task, plugins & skills, Claude in Chrome / Microsoft 365, safety practices
- Take the built-in "Quiz on Claude Cowork" solo first

**Group call — discussion quiz**

*Level 1 — Warm-up*
1. In one sentence, what actually makes Cowork different from a normal Claude chat?
2. What's the difference between a Skill and a Plugin, as the course defines them?

*Level 2 — Apply*
3. Name one real, repeatable task from your student life you'd hand to Cowork instead of doing turn-by-turn in chat, and say why.
4. The course covers working safely on real files. As a group, list 3 things you'd check before letting Cowork touch something that actually matters to you.

*Level 3 — Screen-share*
5. One person shares their screen, sets up one Skill or a global instruction, and hands Cowork a real multi-step task on their own files (e.g. "reorganize these notes and summarize each folder"). The group watches how it plans the work and steers it live.

---

## Session 3 — Claude Code 101

**Solo study**
- Prereqs: a code editor + terminal, and a Claude account or API key
- [Claude Code 101](https://anthropic.skilljar.com/claude-code-101) — full course
- Take the built-in "Course quiz" solo first

**Group call — discussion quiz**

*Level 1 — Warm-up*
1. What's the agentic loop, and how is it different from a normal chat-based tool?
2. Name the four steps of Explore → Plan → Code → Commit and what each is actually for.

*Level 2 — Apply*
3. When would you use Plan Mode vs. auto-accept? What's the real risk of always leaving auto-accept on?
4. What breaks on a real project if it doesn't have a CLAUDE.md file?
5. Problem: your context window is filling up mid-task. Name at least two ways to handle it, and what you lose or gain with each.

*Level 3 — Screen-share*
6. Pick one small, real coding task from anyone's own project. One person drives: run the full Explore → Plan → Code → Commit workflow, and set up one custom subagent or hook live. Before accepting Claude's plan, the group discusses what they'd change about it.

---

## Session 4 — Claude Platform 101

**Solo study**
- Prereqs: comfort with code in one language, CLI basics, an Anthropic Console account + API key + a little prepaid credit
- [Claude Platform 101](https://anthropic.skilljar.com/claude-platform-101) — full course (demos use the TypeScript SDK)
- Take the built-in "Claude Platform 101 Quiz" solo first

**Group call — discussion quiz**

*Level 1 — Warm-up*
1. What's the actual difference between chatting with Claude and sending a request through the Platform?
2. Name Claude's three model sizes from the course, and one thing you'd trade off between them.

*Level 2 — Apply*
3. What does the agent loop do that a single API call by itself can't?
4. Compare: when would you reach for a built-in tool (web search / code execution / web fetch) vs. a custom tool vs. an MCP server?
5. Problem: you're building something that has to stay on a budget. Which 2–3 course concepts would you combine to manage cost, and why those?

*Level 3 — Screen-share*
6. One person shares their screen: send a first real API request, then extend it with one tool call. Read the raw response together and identify each part of it (stop reason, content blocks, etc.).

---

## Sessions 5–8 — Building with the Claude API

This course alone is 84 lectures and 8+ hours, with quizzes built in roughly every couple of modules — so treat it as a 4-part mini-course. [Course link](https://anthropic.skilljar.com/claude-with-the-anthropic-api). Prereqs: Python and basic JSON.

### Session 5 — Foundations: accessing the API, prompt evaluation, prompt engineering

**Solo study**
- Modules: Introduction, Anthropic overview, Accessing Claude with the API, Prompt evaluation, Prompt engineering techniques
- Take the three built-in quizzes for these modules solo first, bring anything you missed to the call

**Group call — discussion quiz**

*Level 1 — Warm-up*
1. Step by step: what happens between calling the API and getting a response back?
2. What does `temperature` actually change, mechanically?

*Level 2 — Apply*
3. Why evaluate prompts against a test dataset instead of just eyeballing a few outputs? Where does model-based grading fall short of code-based grading, and vice versa?
4. Problem: take a vague one-line prompt from your own coursework and rewrite it as a group using at least two techniques from the course (XML structure, examples, being specific). Compare before/after out loud.

*Level 3 — Screen-share*
5. One person shares their screen and builds a tiny eval — 3–5 test cases plus one grading method — for the prompt the group just rewrote. Run it live.

### Session 6 — Extending Claude: tool use, RAG & agentic search

**Solo study**
- Modules: Tool use with Claude, RAG and Agentic Search
- Take the built-in "Quiz on tool use with Claude" solo first

**Group call — discussion quiz**

*Level 1 — Warm-up*
1. What's the difference between a tool's schema and its function?
2. In RAG, what's a chunk, and why not just hand Claude the whole document?

*Level 2 — Apply*
3. Walk through what happens on the turn after Claude requests a tool and you send back a `tool_result`. What breaks if the message blocks are in the wrong order?
4. Compare embedding-based retrieval to BM25 lexical search — where does each one fail?

*Level 3 — Screen-share*
5. In pairs: build one real custom tool (function + schema) for a small use case from your own work, wire it into a multi-turn conversation, and demo the full round trip live.

### Session 7 — Claude's extended features & Model Context Protocol

**Solo study**
- Modules: Extended thinking, image/PDF support, citations, prompt caching, code execution & Files API, Model Context Protocol
- Take the built-in "Quiz on features of Claude" and "Quiz on Model Context Protocol" solo first

**Group call — discussion quiz**

*Level 1 — Warm-up*
1. What is extended thinking for, and when would you deliberately not use it?
2. In MCP, what's the actual difference between a tool, a resource, and a prompt?

*Level 2 — Apply*
3. What has to stay identical for prompt caching to actually hit? Where in a real app would caching save you the most?
4. Problem: you need Claude to reach three different internal data sources. Would you write three custom tools or build one MCP server? Defend it.

*Level 3 — Screen-share*
5. One person shares their screen, stands up a minimal MCP server exposing one tool or resource, and connects a client to it live — inspect it together with the server inspector.

### Session 8 — Anthropic apps, agents & workflows, final assessment

**Solo study**
- Modules: Anthropic apps (Claude Code & computer use), Agents and workflows
- Take the built-in "Quiz on Agents and Workflows" solo, then the course's own **Final Assessment** individually, before the call

**Group call — discussion quiz**

*Level 1 — Warm-up*
1. In the course's own terms, what's the difference between a workflow and an agent?
2. Name the three workflow patterns covered (parallelization, chaining, routing), one-line example each.

*Level 2 — Apply*
3. Is your final project (below) a workflow or an agent? Defend it as a group.
4. Problem: sketch, on a shared screen, which pattern(s) you'd combine for the final project's architecture.

*Level 3 — Screen-share*
5. Compare Final Assessment answers as a group. Whoever missed a question explains, live and on screen, what they'd change and why.

---

## Final group project

Pick this up once Session 8 is done — it's designed to touch something from all six courses.

### Course Copilot — a small Claude-powered assistant, built end-to-end

**Concept**: pick one real, small problem you actually have — a Q&A assistant over your own class notes, a research helper for one topic, or a tool for organizing your own study logistics. Keep the scope narrow: one job, done well, not a platform.

**Requirements:**

1. **Working assistant** — a script or simple app with a clear system prompt defining its role (Sessions 5–8)
2. **One custom tool** — at least one function + schema the model can actually call (Session 6)
3. **A small RAG layer** — retrieval over a real, small set of your own documents; simple chunking + embeddings, or even BM25, is enough (Session 6)
4. **One MCP server** — expose the tool or the retrieval search as an MCP server, and connect a real client to it, even a minimal one (Sessions 4 and 7)
5. **Built partly with Claude Code** — use the Explore → Plan → Code → Commit workflow for at least part of the build, with a CLAUDE.md for the project and at least one subagent or hook (Session 3)
6. **A tiny eval** — 3–5 test cases and one grading method proving the assistant does what it's supposed to (Session 5)
7. **A 1-page reflection** — apply the 4D framework from AI Fluency for Builders: one paragraph each on how Delegation, Description, Discernment, and Diligence actually showed up while building this (Session 1)
8. **Live demo** — each person walks through the piece they owned, then the group runs real queries against the finished thing together

**Suggested role split** (adjust to your group's size): tool/function owner, RAG owner, MCP server owner, Claude Code/CLAUDE.md owner, eval owner. Everyone contributes to the reflection.

This is meant to be scrappy and fast, not a production system — the point is touching every skill once, not building something polished.

---

## Recommendations & extras

- **If the AI Fluency framework feels rushed in Session 1**: *AI Fluency: Framework & Foundations* is the course Anthropic itself recommends first. Not one of your six, but ~1 hr and it directly deepens Session 1.
- **Sort out tooling on Day 0, not mid-sprint**: Node.js/npm for Session 4, Python for Sessions 5–8, and an API key with a little prepaid credit loaded before either — nothing kills momentum like debugging `pip install` mid-call.
- **Rotate three roles every call**: driver (screen-share), notetaker (logs the group's answers and open questions in your shared doc), timekeeper. Keeps it from being the same one or two people doing all the hands-on work.
- **Keep a running "confusion log"**: whenever solo study leaves something unclear, drop it in the shared doc as you hit it. Start each call with that log instead of a generic recap — it keeps discussion time on your actual sticking points.
- **Do a 5-minute retro after each call**: what worked, what didn't, adjust the next session's format if needed. You're optimizing for speed, so tighten the process as you go rather than sticking rigidly to this plan.
- **If you want an external credential afterward**: Anthropic runs an official "Claude Certified Architect – Foundations" exam that overlaps a lot with what's in Building with the Claude API, Claude Code, and MCP. It's a separate, more formal thing (a proctored exam) — worth a look once you're done, not something to fold into this sprint.
