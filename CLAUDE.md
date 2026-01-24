# Claude Code Project Instructions

This repository contains an SEO Master skill for Claude Code.

## Project Structure

```
.
├── README.md                    # Repository documentation
├── CLAUDE.md                    # This file - project instructions
├── SEO_STRATEGY_2025.md         # Complete SEO strategy framework
└── .claude/
    └── skills/
        └── seo-master.md        # The Claude skill file
```

## What This Project Does

This is a Claude Code skill that provides comprehensive SEO assistance:
- Page audits (traditional SEO + AI SEO)
- Content optimization
- Strategy generation

## Key Files

### SEO_STRATEGY_2025.md
The complete knowledge base covering:
- Traditional SEO fundamentals
- AI SEO (GEO/LLMO) strategies
- E-E-A-T framework
- Technical SEO
- Content strategy
- Link building
- Implementation checklists

### .claude/skills/seo-master.md
The actual skill definition that Claude Code uses. Contains:
- Skill description and usage
- Audit, optimize, and strategy modes
- Knowledge base summary
- Response guidelines

## How to Use

When working with SEO tasks, Claude will have access to this skill's knowledge and can:

1. **Audit pages**: Analyze URLs for SEO issues
2. **Optimize content**: Improve titles, metas, structure, schema
3. **Generate strategies**: Create comprehensive SEO plans

## Updating This Skill

When updating:
1. Keep SEO_STRATEGY_2025.md as the source of truth
2. Update seo-master.md skill with any new patterns
3. Test with real audit/optimize/strategy requests
4. Update version date in both files

## SEO Principles to Follow

1. **Dual optimization**: Always consider both traditional SEO and AI SEO
2. **E-E-A-T first**: Experience, Expertise, Authoritativeness, Trustworthiness
3. **User intent**: Match content to what users actually want
4. **Structure matters**: Clear hierarchy, schema markup, AI-readable format
5. **Freshness**: Content decay is real, especially for AI search

## Technical Notes

- Core Web Vitals targets: LCP ≤2.5s, INP ≤200ms, CLS <0.1
- Schema format: Always recommend JSON-LD
- Title tags: Under 60 characters, keyword front-loaded
- Meta descriptions: 150-160 characters with CTA
