---
name: soleio-design-hiring
description: "Strategic sourcing playbook for hiring great designers OR getting hired as a designer. Based on Soleio Cuervo's framework. Two modes: Hiring Mode (for founders, hiring managers, recruiters sourcing design talent) and Designer Mode (for designers positioning themselves to get hired by great companies). Triggers on: hire designer, source designer, find designer, recruit designer, design talent, get hired as designer, designer job search, designer positioning."
argument-hint: "[hire|designer] [optional context]"
---

# Soleio's Design Talent Playbook

Strategic framework for connecting great designers with great companies. Based on Soleio Cuervo's sourcing playbook, reverse-engineered into an actionable process.

**Two modes:**
- **Hiring Mode** — For founders, hiring managers, and recruiters sourcing design talent
- **Designer Mode** — For designers positioning themselves to get hired by great companies

## Quick Start

**Hiring Mode:**
> `/soleio-design-hiring hire` — Start the hiring strategy workflow
> `/soleio-design-hiring hire -- I'm a founder building an AI product and need a product designer`

**Designer Mode:**
> `/soleio-design-hiring designer` — Start the designer positioning workflow
> `/soleio-design-hiring designer -- I'm a product designer targeting AI startups like Cursor and Perplexity`

Mode can also be detected from context if not specified directly.

---

## MODE DETECTION

Check `$ARGUMENTS` for mode:
- Contains "hire", "source", "recruit", "find", "hiring", "founder", "recruiter" → **Hiring Mode**
- Contains "designer", "get hired", "job", "position", "career" → **Designer Mode**
- Ambiguous → Ask:

> "Are you looking to **hire a designer** or are you **a designer** looking to get hired?"

---

## The "Game Film" Mental Model

This concept is central to both modes. Soleio describes himself as "the John Madden of design — I'm always watching what designers are posting. I'm always watching game film." He follows designers on X, watches what they share, and builds mental dossiers — no interactions, no DMs, just watching. When the right moment comes, he's already primed to move fast.

**Proof:** Tom Johnson cold DM'd Soleio referencing a specific tweet. They'd never interacted, but Soleio already followed him. Within 2 hours they were texting. Within 3 hours, on Zoom — not an interview, a conversation about design, football, camping. Within 3 days, Tom was talking to Vercel's leadership (who were already familiar with his work — it had traveled through Vercel's Slack). Within a month, he was hired as Staff Product Designer.

The DM wasn't cold. It was the payoff of months of public sharing. "You never know who's paying attention."

**For hirers:** Watch game film systematically. When someone signals openness, move in hours, not weeks.
**For designers:** Your posts ARE the game film. Create work worth watching consistently, until the right people are already paying attention.

---

## HIRING MODE

### STEP 1: Role Identification

Ask the user to identify their role. This shapes the strategy.

| Role | Primary Advantage | Primary Challenge |
|------|------------------|-------------------|
| **Founder** | Can sell vision directly, equity upside | Unknown brand, competing with big names |
| **Hiring Manager** | Can show team culture from inside | Limited control over comp/brand |
| **Recruiter** | Volume and network breadth | Credibility gap — most cold outreach gets ignored |

### STEP 2: Target Identification

Ask: **"Do you already have specific designers in mind that you'd like to attract?"**

#### PATH A: Yes — Specific Designers in Mind

Ask the user to provide X/Twitter handles, portfolio URLs, or any public profiles.

**For each designer provided, use available tools to research:**
1. **What they're sharing** — Topics, interests, design philosophy
2. **What tools/communities they follow** — Signals about taste and values
3. **What they've shipped** — Recent work, side projects, career trajectory
4. **What they seem to care about** — Craft? Impact? Culture? Autonomy?
5. **Their current situation** — Exploring? Recently shipped something big? Seem restless?

**Present a profile for each designer:**

```
DESIGNER PROFILE: [Name]

Current role: [Where they are now]
Design identity: [What kind of designer they are]
What they value: [Based on what they share/follow]
Signals of interest: [Are they open to opportunities?]
Best approach angle: [What would resonate with them specifically]
Risk factors: [What might turn them off]
```

Then proceed to Step 3 with these profiles informing the strategy.

#### PATH B: No — Looking for a Type

Ask: **"Can you point me to 2-3 designers who represent the TYPE of person you want to hire?"**

If they provide reference designers:
1. Research each reference designer (same process as Path A)
2. **Synthesize a candidate persona** from patterns across the references:

```
IDEAL CANDIDATE PERSONA

Design archetype: [e.g., "Craft-obsessed product designer who ships side projects"]
Career stage: [Junior/Mid/Senior/Lead]
Key traits: [3-5 defining characteristics]
Tools & communities: [What they likely use and follow]
Values: [What they optimize for in a role]
Where they hang out: [Online and offline spaces]
What attracts them: [Types of opportunities, culture signals]
What repels them: [Red flags they'd avoid]
```

If they can't provide references, ask open-ended questions:
- What kind of work should they have shipped?
- Craft-focused or business-impact-focused?
- Builder (ships side projects) or collaborator (thrives in teams)?
- What seniority level?
- Any specific tools, frameworks, or design sensibilities?

**Present the persona for review.** Wait for confirmation before proceeding.

### STEP 3: Strategy Generation

Generate a strategy using these six channels, weighted by relevance to the user's role and target:

#### Channel 1: Social Sourcing (X/Twitter)
> *"I spend a lot of time on X watching what designers are making and sharing."*

- **Who to follow and watch** — Specific handles, communities, design tool accounts
- **What signals to look for** — Active sharing, side projects, engagement with design discourse
- **High-signal pools** — Followers of cutting-edge design tools (Paper, MagicPathAI, Diagram, etc.) are "stocked ponds" not the open ocean
- **How to engage authentically** — Comment on work, share their projects, build familiarity before reaching out. The goal is to be primed when the moment comes — like Soleio was with Tom Johnson.

#### Channel 2: Community Presence
> *"When you organize meetups and talks that are tailored to this community, you're fishing out of a barrel of your own making."*

- **Events to attend or host** — Design meetups, tool-specific communities, invite-only dinners. Vercel hosts design talks at their HQ; South Park Commons runs curated conversations between people like Julie Zhuo and Soleio. Small rooms with the right people > big stages.
- **Content to create** — Share your company's design challenges publicly, write about your design culture
- **Communities to join** — Where does the target persona spend time?

#### Channel 3: Job Page as Product
> *"Create an opinionated job page that is memorable and vivid. A great one works for you while you sleep."*

Your design hiring page should be the strongest design artifact your company has ever produced. The medium IS the message.

- **Take a stance.** Profound's page says "exceptional design isn't merely a nice-to-have, it's foundational" and names specific craft elements. That's conviction, not a platitude.
- **Express that you "get" design** (Julie Zhuo's framework): show attention to detail in your product, describe the role with understanding not HR boilerplate, name design work you admire, have design-forward people on your cap table.
- **Make it shareable, not just findable.** Notion's 2019 "Designer Who Can Code" tweet — with its emoji equation and playful "(btw they do exist)" — is still referenced 7 years later. It became design culture. That's a posting working while you sleep.
- **Study:** [Profound's /design page](https://www.tryprofound.com/design), [Notion's tweet](https://x.com/NotionHQ/status/1105905796095696897)

#### Channel 4: Referral Nodes
> *"The most valuable sourcing channel I have is a small number of people who know great designers and think to send them my way."*

- **Identify your 3-5 nodes** — Design leads, design-minded investors, other founders, community organizers. Soleio named his publicly: @henrymodis, @benjitaylor, @ryolu_, @samstphenson, @jenny_wen, @benblumenrose, @gabrielvaldivia, @josephcohen, @niclasernst.
- **Activate them** — Make sure they know what you're building and what you're looking for. Soleio's "greatest pain" is when a designer he knows makes a career move without talking to founders he'd connect them with — that's a node that wasn't activated.
- **Maintain the relationship** — This isn't transactional. Stay connected, share opportunities back.

#### Channel 5: Recruiters (Selective)
> *"A mediocre recruiter is worse than no recruiter. The important bit is to make sure you're contracting with someone credible, someone who I'd respond to cold outreach from."*

- **The credibility test** — Would Soleio respond to their DM? Would a top designer? That's your bar.
- **The new model: content-creator recruiters** — @ridd_design (Dive Club podcast — design leader interviews) and @designertom (Tommy Geoco — portfolio advice, designer spotlights, Perplexity documentary). Their content proves they understand design. DesignerTom: "Hiring managers spend 55 seconds on portfolios. Designers who build playgrounds get 10+ minutes of my time."
- **Specific recommendation:** Meg Rye at Good Maven (goodmaven.com) for London-based design talent
- **Red flags** — Generic outreach, no design taste, spray-and-pray, can't name a designer they admire

#### Channel 6: The Conversation Opener
> *"Ask them: 'If I could guarantee you interviews with any 2-3 companies, which would they be and why?'"*

- **Why this works** — Shows courage, reveals what they optimize for, tells you if you can compete
- **When to use it** — Early in conversation, not after they've already committed
- **How to respond** — If your company isn't on their list, that's data. Use it to position differently or move on.

### STEP 4: Action Plan

Synthesize everything into a prioritized action plan:

```
SOURCING STRATEGY — [Company/Role]

IMMEDIATE (This week):
1. [Highest-impact action]
2. [Second action]
3. [Third action]

SHORT-TERM (Next 2 weeks):
4. [Action]
5. [Action]

ONGOING (Build over 30 days):
6. [Action]
7. [Action]

KEY METRICS:
- Designers identified: [target number]
- Conversations started: [target]
- Referral nodes activated: [target]

OUTREACH TEMPLATES:
[Provide 2-3 personalized outreach message drafts based on the target persona/profiles]
```

### STEP 5: Outreach Drafting (Optional)

If the user has specific designers (Path A), draft personalized outreach for each one:
- Reference their specific work — no generic flattery
- Connect it to what the company is building
- Be honest about why you're reaching out
- Keep it short — respect their time

---

## DESIGNER MODE

The framework flipped: use Soleio's playbook to position yourself where great companies will find you.

### STEP 1: Designer Profile

Gather context:
- Current role and experience level
- What kind of design they do (product, visual, design engineering, brand, etc.)
- What they want next (role type, company stage, industry)
- Portfolio URL and X/Twitter handle if available

### STEP 2: Target Companies

Ask: **"What types of companies do you want to work at? You can name specific companies or describe the type."**

If they name specific companies:
- Research each company's design culture, recent hires, what their design team shares publicly
- Identify what those companies look for based on their job pages, team posts, and hiring patterns

If they describe a type:
- Build a company persona and identify 3-5 real companies that match

### STEP 3: Visibility Strategy

The best designers get found because they're visible in the right places.

#### Where to Spend Time
> *"X is a great watering hole for designers who are popping their heads up and exploring startup opportunities."*

- Which communities and platforms to be active on
- Which design tool accounts and leaders to follow and engage with
- Which events to attend (or organize) — be in the rooms where referral nodes gather
- How to show up in the "stocked ponds" that hiring managers are fishing from

#### What to Share — The Game Film Playbook

> *"I spotted his work on X and made a note to reach out."*

People like Soleio are watching game film constantly. Your posts ARE the game film. A complete picture requires a mix of content types:

1. **Opinionated takes with reasoning** — Not safe consensus. Stances that reveal values and how you think. Tom Johnson wrote long threads on why accessibility score tyranny holds back good design, why Apple "massacred" macOS. Conviction, not controversy.

2. **Real work shown publicly** — WIP, not just polished case studies. Tom shared "zombie UI" — a UX pattern he invented at Vercel — explaining his reasoning and noting "it's live now." Shows you ship, think about craft, and aren't precious.

3. **Side projects that signal builder mentality** — Tom built WhatThePort (a Swift menubar app), forked a terminal for UX improvements, remade his portfolio in v0. Not portfolio pieces — evidence you build things when you see problems.

4. **Process transparency** — Publicly wrestling with how your work is evolving. "I don't know what my design process is anymore" isn't weakness — it's sophistication. It shows you're on the frontier.

5. **Taste stated plainly** — "The single most important visual design skill for a portfolio is typography. If that's off... it's all off." No hedging. Clear point of view.

6. **Community generosity** — Sharing others' work, portfolio advice, promoting open roles. Generosity as positioning — this is how you become a referral node yourself.

7. **Being a whole person** — Tom's weekly "weekends aren't meant for pixels" outdoor photos, RV shopping, ice storms. Soleio talked with him about football and camping on their first Zoom. People connect with people, not portfolios.

#### How to Be Memorable

Apply the opinionated job page principle to your own presence:
- Your portfolio should take stances, not be generic
- What do you believe about design? What do you reject?
- Make your online presence work for you while you sleep

#### Network Positioning
> *"Most self-aware designers don't broadcast their availability. They move quietly through trusted networks."*

- Cultivate relationships with referral nodes — design leads, investors, community connectors
- Make sure 3-5 well-connected people know you're exploring
- Soleio's named nodes: @henrymodis, @benjitaylor, @ryolu_, @samstphenson, @jenny_wen, @benblumenrose, @gabrielvaldivia, @josephcohen, @niclasernst
- Content-creator recruiters worth knowing: @ridd_design (Dive Club), @designertom (Tommy Geoco)

#### The Self-Assessment
> *"If I could guarantee you interviews with any 2-3 companies, which would they be and why?"*

Turn this on yourself:
- Which 2-3 companies would you choose? Why?
- What does that reveal about what you're optimizing for?
- How does your current positioning align with what those companies look for?
- What gaps exist between where you are and where you need to be?

### STEP 4: Positioning Plan

```
DESIGNER POSITIONING STRATEGY

Target: [Company type / specific companies]
Current gaps: [What's missing]
Positioning angle: [Your unique value prop]

VISIBILITY ACTIONS:
1. [Platform/community to be active on]
2. [Content to create/share]
3. [Side project to ship]
4. [People to connect with]
5. [Events to attend]

PORTFOLIO PRIORITIES:
- [What to add/change/remove]

NETWORK ACTIONS:
- [Referral nodes to cultivate]
- [Communities to join]

TIMELINE:
- This week: [Quick wins]
- This month: [Build momentum]
- Ongoing: [Sustain presence]
```

---

## Core Principles (Both Modes)

1. **Great designers don't respond to generic postings.** Generic attracts generic.
2. **Speed matters.** Great designers don't stay on the market long. Move in hours, not weeks.
3. **Fish in stocked ponds, not the ocean.** High-signal communities > job boards.
4. **Your presence works while you sleep.** Invest in things that compound — job pages, portfolios, content.
5. **Referral nodes are the highest-value channel.** 3-5 well-connected people > 500 LinkedIn connections.
6. **Honesty and authenticity rule.** No time for chicken shit. The world is sailing past us.
7. **Credibility is everything.** A mediocre recruiter/outreach is worse than none.
8. **Be plugged in before you need it.** Build networks and presence before the urgent hire or job search.

---

## Attribution

Based on [Soleio Cuervo's sourcing framework](https://x.com/soleio/status/2032284102322495604), March 2026.

Enriched with context from: [Tom Johnson's Vercel story](https://x.com/tomjohndesign/status/1990811892139372899), [Julie Zhuo's hiring advice](https://x.com/joulee/status/1952386829287899374), [Profound's design page](https://www.tryprofound.com/design), [Notion's 2019 tweet](https://x.com/NotionHQ/status/1105905796095696897), [Hannah Hearth on Tom at Vercel](https://x.com/hannah_hearth/status/2026806264513310755), and Tom Johnson's X history demonstrating the game film pattern.
