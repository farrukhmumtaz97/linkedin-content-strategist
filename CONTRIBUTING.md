# Contributing

Thanks for wanting to improve this. The goal is a skill that produces genuinely good LinkedIn content — not more generic advice dressed up in a system prompt.

---

## What's worth contributing

**High value:**
- New hook patterns in `hook-library.md` — must include psychological reasoning, not just examples
- New CTA patterns in `cta-library.md` — must include when to use and when not to
- Failure modes in `post-anatomy.md` — real patterns where posts break down and why
- Humanizer pass improvements — new AI tells that slip through the current checklist
- Bug fixes where the skill produces output that contradicts its own rules

**Medium value:**
- Brand profile template improvements — clearer instructions, better example prompts
- README improvements — clearer setup, better examples
- Industry-specific brand profile templates (see Planned section in CHANGELOG)

**Low priority right now:**
- Translations — possible later, not now
- Tooling / automation wrappers — good ideas, but out of scope for the core skill

---

## How to submit

1. Fork the repository
2. Create a branch: `git checkout -b feature/your-change`
3. Make your changes
4. Test against the humanizer pass rules — if the change would produce output that triggers AI tells, rework it
5. Submit a pull request with a clear description of what changed and why

---

## Voice rules for contributions

All reference files use a specific voice. Contributions should match it.

**Use:**
- Direct statements ("Hooks fail when they're predictable, not when they're boring.")
- Specific reasoning, not general advice
- One-sentence beats with deliberate line breaks
- Concrete examples before abstract principles

**Avoid:**
- "In today's world" or any temporal framing that will date the content
- Em-dashes
- Emojis
- Three-item parallel lists that feel mechanical
- Inflated language ("game-changing," "revolutionary," "unlock")

If your contribution uses any of the forbidden phrases from the skill itself, it won't be merged.

---

## Opening issues

Use issues for:
- Bug reports (skill produces output that contradicts its own rules)
- Feature requests (new mode, new reference file, new system)
- Discussions about the psychology behind a specific pattern

Don't use issues for:
- "Can you write me a LinkedIn post" — that's what the skill is for
- General LinkedIn advice questions

---

## Code of conduct

Be direct. Be specific. Don't be a marketer about it.
