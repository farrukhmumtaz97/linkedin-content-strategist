# LinkedIn Content Strategist — Claude Skill

An elite LinkedIn content strategy skill for [Claude](https://claude.ai). Built for founders, marketers, and operators who want to grow audience, authority, and inbound leads — not just post content.

> **One skill. Five modes. Zero generic output.**

---

## What this does

This skill turns Claude into your personal LinkedIn ghostwriter, virality analyst, and weekly content planner. It analyzes why posts work at a psychological level, then recreates those principles in your voice — not someone else's.

**Five modes:**

| Mode | Trigger |
|---|---|
| **Analyze + Rewrite** | Paste any LinkedIn post |
| **Generate** | Ask for a post on a topic |
| **Plan** | Ask for a weekly content plan |
| **Personal Story** | Mention a Wednesday post or a real moment |
| **Rewrite** | Ask to improve an existing draft |

---

## Why this skill exists

Most LinkedIn advice tells you to post more. This skill tells you to post better.

The difference between a post that gets ignored and one that generates inbound is not effort. It is understanding why people stop scrolling, why they keep reading, and why they share something. This skill applies those principles — hook psychology, retention mechanics, CTA rotation, humanizer pass — to every post it produces.

---

## What makes it different

- **Brand profile system.** Fills from `references/brand-profile.md` on every run. Your voice, credibility anchors, forbidden phrases, and CTA channels are baked in — not re-explained each time.
- **CTA rotation logic.** Three-tier system (Soft / Medium / Direct) with a decision tree. Never two direct CTAs in a row. Wednesday personal stories always get soft CTAs. The skill tracks and explains every choice.
- **Humanizer pass.** Before any post ships, it scans for AI tells: em-dashes, symmetric rhythm, inflated symbolism, vague attributions, filler phrases. If found, it rewrites before delivering.
- **Personal story protection.** The skill never invents a personal story. It always asks for your rough version first, then improves structure, hook, pacing, and payoff — without fabricating facts.
- **Virality scoring.** Full 10-point breakdown across hook, retention, readability, authority, relatability, emotional impact, shareability, comment potential, save potential, and lead-gen potential.

---

## File structure

```
linkedin-content-strategist/
├── SKILL.md                          ← Main skill (the brain)
└── references/
    ├── brand-profile.md              ← YOUR voice, niche, numbers, CTAs (fill this in)
    ├── hook-library.md               ← 9 pattern-break hook techniques with psychology
    ├── post-anatomy.md               ← How high-performing posts are built
    └── cta-library.md                ← 3-tier CTA system, decision tree, rotation rules
```

---

## Setup (5 minutes)

### 1. Download or clone

```bash
git clone https://github.com/YOUR_USERNAME/linkedin-content-strategist.git
```

Or download the ZIP from the releases page.

### 2. Fill in your brand profile

Open `references/brand-profile.md` and complete every section:

- Identity and current role
- Content pillars (what you post about)
- Audience (be specific — not "marketers" but "B2B SaaS founders in the UK")
- Voice description (adjectives that describe your tone)
- Real credibility anchors (specific numbers, real results)
- Real moments for personal stories
- Forbidden phrases (things that don't sound like you)
- CTA channels (newsletter URL, DM preference, email)
- Hashtag pool (10-15 tags to rotate from)

The more specific this file is, the less generic the output will be.

### 3. Upload to Claude

In Claude, go to **Projects** → create a new project → upload the entire `linkedin-content-strategist/` folder.

Or use Claude's [Skills feature](https://claude.ai) if available in your plan.

### 4. Use it

Start any message with what you want:

- Paste a post → analysis + rewrite
- "Write me a Monday post about [topic]"
- "Plan my LinkedIn week — I'm posting Mon/Wed/Fri"
- "I have a story about [moment]. Help me write Wednesday's post."
- "Improve this draft: [paste draft]"

---

## Output format (Analyze + Rewrite mode)

```
POST ANALYSIS       — Why the post works (3-5 sentences)
HOOK ANALYSIS       — Psychological triggers in the first 80 words
RETENTION ANALYSIS  — Pacing, spacing, open loops, drop-off points
PSYCHOLOGY BREAKDOWN — Authority, identity, tension, curiosity, trust
FRAMEWORK           — Hook → Setup → Context → Conflict → Lesson → Payoff → CTA
WHY IT FEELS HUMAN  — Imperfections, rhythm variation, emotional honesty
CONVERSION ANALYSIS — Authority, trust, CTA tier used and why
VIRALITY SCORE      — 10-category scoring (/10 each)
REWRITTEN VERSION   — Original post in your voice
BEST IMAGE          — Type + psychological reasoning
HASHTAGS            — Maximum 3
IMPROVEMENTS        — 2-4 specific next steps
```

---

## The non-negotiable rules

These are enforced on every output:

1. Never invent personal stories. Always ask for the real moment first.
2. Never copy other creators' phrasing.
3. No emojis. No em-dashes. No corporate jargon.
4. Maximum 3 hashtags.
5. One humor beat max per post — dry, observational, never forced.
6. Every post gets a deliberate CTA from the three-tier system.
7. Newsletter links always go in the first comment, never the post body.

---

## Weekly cadence (default)

| Day | Post type | Goal |
|---|---|---|
| Monday | Authority + Insight | Position as experienced |
| Wednesday | Personal Story | Build trust and connection |
| Friday | Vision / Reflection / Industry Take | Depth and memorability |

5x/week adds Tuesday (Tactical) and Thursday (Contrarian/Debate).

**Content mix target:** 40% personal, 30% educational, 20% opinionated, 10% promotional.

---

## The CTA system (summary)

| Tier | Frequency | Example |
|---|---|---|
| Soft | 60-70% | Implied question, divisive reframe line |
| Medium | 20-30% | "DM me," reply prompt, micro-resource offer |
| Direct | 10-15% | Newsletter link (always in first comment) |

Never two direct CTAs in a row. Wednesday personal stories always get soft CTAs only.

---

## What this skill will not do

- Write fake personal stories
- Copy the voice of named creators
- Add more than 3 hashtags
- Put newsletter links in the post body
- Use emojis, em-dashes, or "game-changing"
- Produce content that sounds like it came from a content marketing course

---

## Customization

Everything about this skill is customizable through `references/brand-profile.md`.

- Change your voice description → outputs shift tone
- Add forbidden phrases → they disappear from all posts
- Update your CTA channels → direct CTAs link to the right place
- Add real moments → personal story prompts draw from your actual life
- Change your hashtag pool → skill rotates from your preferred tags

No code changes needed. The brand profile is the configuration layer.

---

## Contributing

Found a bug? Have a hook pattern that should be in the library? Spotted an AI tell the humanizer pass missed?

Open an issue or submit a pull request. Contributions to `hook-library.md`, `post-anatomy.md`, and `cta-library.md` are especially welcome — these are the core knowledge base.

**Contribution guidelines:**
- Keep the voice consistent with the existing files (direct, opinionated, no corporate jargon)
- Add psychological reasoning to any new hook pattern, not just examples
- Test changes against the humanizer pass rules before submitting

---

## License

MIT. Use it, fork it, adapt it for your niche. If you build something useful on top of it, link back here.

---

## Acknowledgements

Built on observed patterns from thousands of high-performing LinkedIn posts. Psychological principles drawn from behavioral economics, attention research, and direct content testing. No individual creators were copied. Principles were abstracted.

---

*The goal is not to create content. The goal is to build reputation at scale. Every post should feel like a real founder sharing thoughts people wish they said first.*
