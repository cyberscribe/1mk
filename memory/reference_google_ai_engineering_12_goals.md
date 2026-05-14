---
name: Google's 12 goals for AI-driven engineering (LinearB summary)
description: Reference article + Google/EDC research mapping the 12 core goals and 6-step AI usage pattern that distinguish AI-native developers — to be cross-referenced with 1MK concepts as the manifesto develops
type: reference
---

**Source:** https://linearb.io/blog/google-ai-engineering-12-core-goals
**Underlying research:** https://arxiv.org/pdf/2506.00202 (Google × Education Development Center, DACUM methodology, 21 expert AI-native developers, 5-month study, June 2025)

**Purpose for 1MK:** Robert wants to map 1MK concepts (current and future) onto this framework. Use as a touchstone when introducing or refining vocabulary and frameworks in the manifesto — both to find resonance (where 1MK aligns with empirically-observed senior practice) and contrast (where 1MK takes a different stance).

## The 12 goals (organised by SDLC phase)

**Planning and investigation**
1. Contextualize work comprehensively — synthesise user feedback, competitors, system architecture
2. Locate relevant information — research technologies, libraries, docs
3. Explore technical solutions — optimise performance, complexity, cost, maintainability
4. Develop documented plans — implementation roadmaps with AI assistance

**Implementation and quality**
5. Produce high-quality code — convert designs to code, reduce complexity
6. Create holistic test coverage — identify failure points, generate tests
7. Generate assets — images, captions, resources
8. Produce up-to-date documentation

**Compliance and operations**
9. Ensure legal/privacy compliance
10. Monitor and generate insights — anomaly detection
11. Investigate production issues — analyse logs, traces, error patterns
12. Improve system reliability — proactive failure identification

(75 underlying tasks mapped to SDLC in the source diagram.)

## The 6-step AI usage pattern (applied at every stage)

1. **Identify** — what does the AI need to know
2. **Engage** — express needs with proper context, problem statements, desired outcomes
3. **Evaluate** — critically check AI artifacts against domain knowledge (sandbox, compare)
4. **Calibrate** — guide with feedback, additional context, trade-offs
5. **Tweak** — improve against expected standards
6. **Finalize** — produce final docs, communicate decisions

## Headline claims worth engaging with

- "The future developer looks like today's senior developer" — AI productivity gains require senior-level judgement; juniors need extra scaffolding before AI helps them.
- Planning work is *expanding*, not shrinking, because AI removes repetitive execution.
- Soft skills (knowing when to seek human help, building relationships) become more critical, not less.
- T-shaped model: deep SWE fundamentals + broad knowledge of adjacent domains (security, regulation) + non-engineering context (business, users, market).

## Mapping notes for 1MK (to develop)

Resonance candidates:
- Goal 4 "Develop documented plans" maps cleanly to **Outcome** + **State of Play** (1MK insists planning is the human job).
- The 6-step pattern — especially Evaluate/Calibrate/Tweak — matches 1MK's stance that the human owns judgement on AI output, not the AI.
- "Planning work is expanding" is congruent with 1MK's argument that mind dumps and weekly retrospectives become *more* important in the AI era, not less.

Contrast candidates:
- Google's frame is org/team-scale engineering. 1MK is the *single operator* analogue — the 12 goals collapse onto one person, which is the central tension.
- 1MK's AI/no-AI split (working memory and mind dumps stay human) is a stronger claim than the article's "evaluate critically" — worth naming the gap.
- The article treats AI as a productivity multiplier inside an existing role; 1MK treats it as a force that reshapes what an Outcome and Deliverable even *are*.

When introducing a new 1MK concept, check: which of the 12 goals does this serve, and where in the 6-step pattern does it live? If a 1MK concept has no analogue in the Google framework, that's either a genuine novelty (worth flagging) or a gap (worth questioning).
