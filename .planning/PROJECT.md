# LaunchLemonade Documentation Polish

## What This Is

A comprehensive audit and rewrite of LaunchLemonade's documentation site to make it clearer, warmer, and more accessible to non-technical users — small business owners, solopreneurs, creators, and marketing teams who want to build AI tools without coding.

## Core Value

**Readers should feel "I can do this!" after reading any page.** Every piece of documentation should build confidence, not intimidate.

## Requirements

### Validated

(None yet — ship to validate)

### Active

- [ ] Full audit document analyzing all 13 documentation pages
- [ ] Specific rewrite suggestions for each page
- [ ] Tone guidelines that match the playful "Lemonade" brand
- [ ] Jargon-to-plain-language translation guide
- [ ] Before/after examples showing the transformation
- [ ] Priority ranking (which pages to fix first)

### Out of Scope

- Restructuring the navigation/information architecture — staying with current page structure
- Creating new pages — focusing on improving existing content
- Technical accuracy changes — assuming current content is factually correct
- Mintlify component changes — keeping the same MDX components

## Context

**The problem:** People aren't using the doc site much. Unclear if it's discoverability, content quality, or both. The goal is to "freshen it up" so it serves three purposes:
1. Self-service support (people find answers instead of emailing)
2. Faster onboarding (new users get started without hand-holding)
3. Build confidence (readers feel empowered, not overwhelmed)

**Current state:**
- 13 MDX files in a Mintlify doc site
- Good structure and comprehensive coverage
- Tone is inconsistent — some pages warm, others cold/technical
- Heavy jargon in places (system prompt, tokens, OAuth, API, temperature)
- Tends to lead with features instead of user benefits

**Brand context:**
- LaunchLemonade has a playful brand identity — "sip.launchlemonade.app", "Lemonade", "Mix"
- Target audience is explicitly non-technical
- Should feel approachable, friendly, encouraging

**What's working (keep this):**
- Memory.mdx has the best tone — use as a model
- Card groups and step components work well
- Tips and warnings are helpful when used sparingly

## Constraints

- **Format**: Must remain MDX files compatible with Mintlify
- **Components**: Use existing Mintlify components (Card, Steps, Tip, Warning, etc.)
- **Pages**: 13 existing pages, no new pages to create
- **Delivery**: Audit document first, then decide on implementation

## Key Decisions

| Decision | Rationale | Outcome |
|----------|-----------|---------|
| Audit first, then rewrite | User wants to review suggestions before changes are made | — Pending |
| Use Memory.mdx as tone model | It's the warmest, most accessible page currently | — Pending |
| Focus on confidence-building | Success = readers feeling "I can do this!" | — Pending |

---
*Last updated: 2026-01-27 after initialization*
