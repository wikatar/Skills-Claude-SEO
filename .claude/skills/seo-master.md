# SEO Master Skill

> Version 3.1 | Last Updated: January 2026

A comprehensive SEO and AI SEO (GEO) skill for auditing pages, optimizing content, and generating strategies.

---

## Quick Command Reference

| Command | What It Does |
|---------|--------------|
| `/seo <url>` | **Master mode** - Full auto-diagnosis and action plan |
| `/seo status` | Check progress against strategy |
| `/seo audit <url>` | Full SEO audit of a page |
| `/seo optimize` | Optimize content for a keyword |
| `/seo strategy` | Generate comprehensive SEO strategy |
| `/seo prioritize` | Decide what to work on first |
| `/seo technical` | Technical SEO checklist |
| `/seo local` | Local SEO optimization |

---

## Persistence & Memory

**SEO is a long-term game.** This skill maintains a `.seo/` folder to track strategy, progress, and learnings across sessions.

### Folder Structure

```
.seo/
├── strategy.md         # Master strategy document
├── inventory.md        # Content pages + their SEO status
├── tasks.md            # Tasks: pending, in-progress, completed
├── keywords.md         # Target keywords + current rankings
└── log.md              # Session log with dated entries
```

### How It Works

**First Session:**
1. Skill checks: Does `.seo/` folder exist?
2. If NO → Create folder + run full analysis → Save to `strategy.md`
3. If YES → Read existing strategy → Continue from where we left off

**Subsequent Sessions:**
1. Read `.seo/strategy.md` to understand current state
2. Check `tasks.md` for pending items
3. Update based on new information
4. Log session notes to `log.md`

### File Templates

**strategy.md:**
```markdown
# SEO Strategy: [Site Name]

> Last updated: [Date]
> Current score: [X/100]

## Overview
- Site: [URL]
- Primary goal: [Goal]
- Target audience: [Audience]

## Current State
[Summary of where we are]

## 90-Day Roadmap
[High-level plan]

## Key Metrics
| Metric | Baseline | Current | Target |
|--------|----------|---------|--------|
| Organic traffic | X | Y | Z |

## Competitors
- [Competitor 1]
- [Competitor 2]
```

**tasks.md:**
```markdown
# SEO Tasks: [Site Name]

## In Progress
- [ ] [Task] - Started [Date]

## Pending
- [ ] [Task] - Priority: High/Medium/Low

## Completed
- [x] [Task] - Completed [Date]
```

**log.md:**
```markdown
# SEO Session Log: [Site Name]

## [Date]
### What we did
- [Action taken]

### Findings
- [Discovery]

### Next session
- [What to focus on]
```

### Key Behaviors

1. **Always check for `.seo/` first** - Before any analysis, look for existing strategy
2. **Update, don't overwrite** - Build on previous work, don't start fresh
3. **Log every session** - Add dated entry to `log.md`
4. **Mark tasks complete** - Move finished items to Completed section
5. **Track metrics** - Note any ranking/traffic changes mentioned

---

## Description

This skill helps you:
- **Audit** websites and pages for traditional SEO and AI SEO issues
- **Optimize** content for both Google and AI search engines (ChatGPT, Perplexity, Gemini)
- **Generate** comprehensive SEO strategies tailored to your goals
- **Prioritize** what to work on for maximum impact

## When to Use This Skill

✅ **Use when:**
- Analyzing a page or site for SEO issues
- Optimizing content for search
- Building an SEO strategy
- Deciding between SEO priorities
- Need technical SEO guidance

❌ **Don't use when:**
- Pure web design/UX (no SEO angle)
- Paid advertising (PPC/SEM)
- Social media strategy (unless SEO-related)

---

## Modes

### Master Mode: Full Analysis (`/seo <url>` or "Help me with SEO for [site]")

**The autonomous mode.** Give it a URL and it figures out everything.

This mode automatically:
1. **Checks for existing strategy** in `.seo/` folder
2. Diagnoses current state across all SEO dimensions
3. Identifies the biggest problems and opportunities
4. Creates a prioritized action plan
5. **Saves/updates** the strategy files

**When to use:** When you want a complete picture without guiding the analysis yourself.

**Process:**

```
Step 0: CHECK MEMORY
├── Look for .seo/ folder
├── If exists: Read strategy.md, tasks.md, log.md
├── Understand where we left off
└── Continue from there (don't restart)

Step 1: DIAGNOSE
├── Fetch and analyze the page/site
├── Check traditional SEO elements
├── Check AI SEO readiness
├── Check technical fundamentals
├── Identify if local SEO applies
└── Assess E-E-A-T signals

Step 2: IDENTIFY
├── Score current state (0-100)
├── Find critical issues (blocking growth)
├── Find quick wins (high impact, low effort)
├── Find strategic gaps (missing opportunities)
└── Compare to what's needed to compete

Step 3: PLAN
├── Prioritize by impact × effort
├── Create immediate actions (this week)
├── Create 30-day roadmap
├── Create 90-day roadmap
└── Define success metrics

Step 4: PERSIST
├── Create .seo/ folder if needed
├── Write/update strategy.md
├── Update tasks.md with new tasks
├── Add session entry to log.md
└── Confirm files saved
```

**Output Format:**

```
## SEO Master Analysis: [Site/Page]

### Current State Score: [X/100]

| Dimension | Score | Status |
|-----------|-------|--------|
| On-Page SEO | X/20 | 🔴/🟡/🟢 |
| Technical SEO | X/20 | 🔴/🟡/🟢 |
| Content Quality | X/20 | 🔴/🟡/🟢 |
| AI SEO Readiness | X/20 | 🔴/🟡/🟢 |
| Authority/E-E-A-T | X/20 | 🔴/🟡/🟢 |

### Diagnosis Summary
[2-3 sentence overview of the site's SEO health and main issues]

### Critical Issues (Fix First)
1. [Issue] → [Why it matters] → [How to fix]
2. [Issue] → [Why it matters] → [How to fix]

### Quick Wins (High Impact, Easy)
1. [Action] → [Expected impact]
2. [Action] → [Expected impact]

### Strategic Gaps (Bigger Opportunities)
1. [Gap] → [Opportunity size] → [Approach]

### Action Plan

**This Week:**
- [ ] [Specific task 1]
- [ ] [Specific task 2]
- [ ] [Specific task 3]

**Next 30 Days:**
- [ ] [Task with brief description]
- [ ] [Task with brief description]
- [ ] [Task with brief description]

**Next 90 Days:**
- [ ] [Strategic initiative]
- [ ] [Strategic initiative]

### Success Metrics
| Metric | Current | Target (90 days) |
|--------|---------|------------------|
| [Metric] | [Value] | [Goal] |

### What I Need From You
[Questions to clarify or information needed to refine the plan]
```

**Key Behaviors:**

1. **Check memory first** - Always look for `.seo/` folder before starting analysis
2. **Be autonomous** - Don't ask what to analyze. Analyze everything relevant.
3. **Be specific** - Don't say "improve your titles." Say "Change title from X to Y."
4. **Be prioritized** - Always rank by impact. Don't overwhelm with 50 equal tasks.
5. **Be realistic** - Consider effort required. Quick wins first.
6. **Persist everything** - Save strategy, tasks, and session log
7. **Ask at the end** - Only ask questions after providing the analysis, not before.

---

### Status Mode: Check Progress (`/seo status` or "How's my SEO going?")

**Quick check on progress against the existing strategy.**

This mode:
1. Reads `.seo/` folder
2. Summarizes current state vs. goals
3. Shows completed vs. pending tasks
4. Identifies what to focus on next

**Output Format:**
```
## SEO Status: [Site Name]

### Progress Overview
- Strategy started: [Date]
- Current score: [X/100] (was [Y] at baseline)
- Tasks completed: [X/Y]

### Recent Wins
- [x] [Completed task] - [Date]
- [x] [Completed task] - [Date]

### Current Focus
- [ ] [In-progress task]

### Up Next
- [ ] [Next priority task]
- [ ] [Next priority task]

### Blockers / Notes
[Any issues or things to discuss]

### Metrics Trend
| Metric | Baseline | Last Check | Now | Target |
|--------|----------|------------|-----|--------|
| [Metric] | X | Y | Z | Goal |
```

**If no `.seo/` folder exists:** Prompt user to run Master Mode first.

---

### Mode 1: Page Audit (`/seo audit <url>`)

When auditing a page, analyze:

**Traditional SEO:**
- Title tag (length, keyword placement, clarity)
- Meta description (length, CTA, keyword inclusion)
- Header structure (H1-H6 hierarchy)
- Content quality and search intent match
- Internal linking
- External links (quality, relevance)
- Schema markup presence
- Image optimization (alt tags, compression)
- URL structure
- Mobile friendliness indicators
- Page speed indicators (if accessible)

**AI SEO (GEO):**
- Content structure for AI readability (Q&A, lists, steps)
- FAQ presence and quality
- Fact density (statistics, data, citations)
- Quote-worthy statements
- Schema markup for AI (FAQPage, HowTo, Article)
- Content freshness
- Author credentials visibility
- TL;DR presence

**Scoring Rubric (100 points):**

| Category | Points | Criteria |
|----------|--------|----------|
| **Title Tag** | 10 | Length ≤60, keyword front-loaded, compelling |
| **Meta Description** | 5 | Length 150-160, includes keyword, has CTA |
| **H1 Tag** | 10 | Present, unique, contains primary keyword |
| **Header Structure** | 5 | Logical H2-H6 hierarchy |
| **Content Quality** | 15 | Depth, intent match, originality |
| **Internal Links** | 5 | 3-10 relevant contextual links |
| **Schema Markup** | 10 | Appropriate types implemented correctly |
| **Images** | 5 | Alt tags, compression, descriptive names |
| **Technical** | 10 | HTTPS, mobile-friendly, fast loading |
| **AI Readability** | 15 | Structure, FAQs, facts, quotable statements |
| **E-E-A-T Signals** | 10 | Author info, credentials, citations |

**Score Interpretation:**
- 90-100: Excellent - minor tweaks only
- 70-89: Good - some optimization needed
- 50-69: Fair - significant improvements needed
- Below 50: Poor - major overhaul required

**Output Format:**
```
## SEO Audit: [Page Title]

### Score: [X/100]

### Critical Issues 🔴
- [Issue with fix recommendation]

### Warnings 🟡
- [Issue with fix recommendation]

### Opportunities 🟢
- [Improvement suggestion]

### AI SEO Readiness: [X/10]
- [Assessment of GEO optimization]

### Quick Wins
1. [Immediate action]
2. [Immediate action]
3. [Immediate action]
```

---

### Mode 2: Content Optimization (`/seo optimize`)

When optimizing content, consider the user's:
- Target keyword(s)
- Search intent (see Search Intent section)
- Current content
- Target audience
- Competitors ranking for this term

**Provide:**

1. **Title Tag Optimization**
   - Current analysis
   - 2-3 optimized versions
   - Reasoning

2. **Meta Description**
   - Current analysis
   - 2-3 optimized versions

3. **Header Structure**
   - Recommended H1
   - Suggested H2/H3 outline
   - Keyword placement opportunities

4. **Content Enhancements**
   - Missing topics to cover (content gaps)
   - FAQ suggestions (4-8 questions)
   - Statistics/data to add
   - Internal linking opportunities
   - External citation opportunities

5. **AI Optimization**
   - TL;DR summary to add
   - Quote-worthy statements to include
   - Schema markup recommendations (with example code)

6. **Image Optimization**
   - Suggested images to add
   - Alt text recommendations

---

### Mode 3: Strategy Generation (`/seo strategy`)

When generating strategy, gather information about:
- Business type and goals
- Current website state
- Target audience
- Competitors (ask for 2-3)
- Resources available
- Timeline

**Provide:**

1. **Situation Analysis**
   - Current state assessment
   - Competitor analysis (what they do well/poorly)
   - SWOT for SEO
   - Opportunities

2. **Keyword Strategy**
   - Target keyword clusters (grouped by intent)
   - Priority topics
   - Content gap analysis
   - Quick win keywords (low competition)

3. **Content Strategy**
   - Pillar pages to create
   - Content cluster plan
   - Publishing cadence recommendation
   - Refresh schedule for existing content

4. **Technical Priorities**
   - Critical fixes
   - Quick wins
   - Long-term improvements

5. **AI SEO (GEO) Strategy**
   - Schema implementation plan
   - Content structure changes
   - AI crawler policy (robots.txt)
   - Visibility monitoring approach

6. **Link Building Approach**
   - Linkable asset ideas
   - Digital PR opportunities
   - Outreach priorities
   - Timeline expectations (3-6 months)

7. **Local SEO** (if applicable)
   - Google Business Profile optimization
   - Local citations
   - Review strategy

8. **Measurement Plan**
   - KPIs to track
   - Tools to use
   - Reporting cadence

---

### Mode 4: Prioritization (`/seo prioritize`)

Help users decide what to work on first. This is critical for ROI.

**The Core Question:** Should I fix weak pages or double down on strong pages?

**Decision Framework:**

#### Double Down on Best Pages FIRST when:
- Pages ranking positions 4-20 (striking distance)
- High impressions but low CTR
- Best content is outdated (>6 months old)
- Limited resources (focus beats spread)

**Why:** Moving from position 8→3 = massive traffic jump. Content refresh can boost traffic 106%. AI search heavily favors recently updated authoritative content.

**Impact:** HIGH and FAST (weeks)

#### Fix/Remove Worst Pages FIRST when:
- Thin content (<300 words with no value)
- Duplicate/cannibalized pages competing for same keywords
- Pages with 0 traffic for 12+ months
- Site has quality drag from many low-value pages

**Why:** Removes quality signals that hurt domain. Consolidates link equity. Google's Helpful Content Update penalizes sites with lots of low-quality pages.

**Impact:** MEDIUM, slower (months)

#### The 80/20 Rule
Typically 20% of pages drive 80% of traffic. Identify and optimize those first.

**Recommended Priority Order (most sites):**
```
1. Optimize existing top performers (quick wins)
2. Create 1-2 high-value pillar pages for gaps
3. Audit and consolidate/remove weak pages
4. Build supporting content clusters
5. Ongoing: refresh cycle every 3-6 months
```

**Output Format:**
```
## SEO Prioritization Analysis

### Current State Assessment
- [Site health summary]
- [Top performing pages]
- [Underperforming pages]

### Recommended Priority
1. [First priority with reasoning]
2. [Second priority]
3. [Third priority]

### Quick Wins (This Week)
- [Immediate high-impact action]

### 30-Day Plan
- Week 1: [Focus]
- Week 2-3: [Focus]
- Week 4: [Focus]

### Pages to Consolidate/Remove
- [Page] → [Action: merge into X / delete / differentiate]
```

---

### Mode 5: Technical SEO (`/seo technical`)

Technical SEO checklist and diagnostics.

**Core Technical Checklist:**

| Check | Pass Criteria |
|-------|---------------|
| HTTPS | All pages secure, no mixed content |
| Mobile-friendly | Passes Google Mobile-Friendly Test |
| Core Web Vitals | LCP ≤2.5s, INP ≤200ms, CLS <0.1 |
| Robots.txt | Not blocking important content |
| XML Sitemap | Exists, submitted to GSC, <50k URLs |
| Canonical tags | Self-referencing on all pages |
| 404 errors | None on internal links |
| Redirect chains | No chains >2 hops |
| Duplicate content | Canonicals handle duplicates |
| Hreflang | Correct (if multi-language) |
| Structured data | Valid, no errors in GSC |
| Page speed | <3 seconds load time |
| Crawl depth | Important pages ≤3 clicks from home |

**AI Crawler Management:**

```
# Allow AI search, block AI training
User-agent: GPTBot
Disallow: /

User-agent: Google-Extended
Disallow: /

User-agent: ClaudeBot
Disallow: /

User-agent: PerplexityBot
Allow: /

User-agent: OAI-SearchBot
Allow: /
```

**Key AI Crawlers:**
- `GPTBot` - OpenAI training
- `OAI-SearchBot` - ChatGPT search
- `ClaudeBot` - Anthropic
- `PerplexityBot` - Perplexity indexing
- `Google-Extended` - Google AI training

---

### Mode 6: Local SEO (`/seo local`)

For businesses with physical locations or local service areas.

**Google Business Profile Checklist:**
- [ ] Claimed and verified
- [ ] Accurate NAP (Name, Address, Phone)
- [ ] Correct business category (primary + secondary)
- [ ] Complete business description with keywords
- [ ] Business hours accurate
- [ ] Photos (exterior, interior, team, products)
- [ ] Products/services listed
- [ ] Q&A section populated
- [ ] Posts published regularly
- [ ] Reviews being collected and responded to

**Local Citations:**
- Consistent NAP across all directories
- Priority directories: Yelp, Yellow Pages, industry-specific
- Local chamber of commerce, business associations

**Local Content Strategy:**
- Location pages for each service area
- Local keywords in title tags and content
- Local schema markup (LocalBusiness)
- Embed Google Map on contact page

**Review Strategy:**
- Ask satisfied customers for reviews
- Respond to ALL reviews (positive and negative)
- Don't incentivize reviews (against guidelines)

---

## Knowledge Base

### Search Intent Types

**Always match content to intent:**

| Intent | User Goal | Content Type | Example Query |
|--------|-----------|--------------|---------------|
| **Informational** | Learn something | Blog, guide, how-to | "what is SEO" |
| **Navigational** | Find specific site | Homepage, login page | "facebook login" |
| **Transactional** | Buy/take action | Product page, pricing | "buy iPhone 15" |
| **Commercial** | Compare before buying | Comparison, review | "best CRM software" |

**Tip:** Google the keyword and see what's ranking. That tells you the intent Google assigns.

### E-E-A-T Framework (Detailed)

**E**xperience, **E**xpertise, **A**uthoritativeness, **T**rustworthiness

**Trust is most important** - without it, nothing else matters.

#### How to Demonstrate Each:

**Experience:**
- First-hand accounts ("I tested this for 30 days")
- Original photos/videos from actual use
- Case studies from your work
- "Tested by [Name]" badges

**Expertise:**
- Author bios with credentials
- Bylines on all content
- Links to author's other work
- Credentials for YMYL topics (medical, financial, legal)

**Authoritativeness:**
- Backlinks from respected sites
- Mentions in industry publications
- Speaking engagements, awards
- Consistent publishing in your niche

**Trustworthiness:**
- HTTPS everywhere
- Clear contact information
- Privacy policy, terms of service
- Accurate, fact-checked content
- Transparent about affiliates/sponsorships
- Physical address (for local businesses)

**YMYL Topics** (Your Money or Your Life):
Health, finance, legal, news, safety topics require STRONGER E-E-A-T signals. Content should be by qualified professionals.

### Core Ranking Factors (2025)

1. **Content Quality & E-E-A-T**
   - Helpful, people-first content
   - Matches search intent
   - Comprehensive coverage

2. **Technical Foundation**
   - Core Web Vitals (LCP ≤2.5s, INP ≤200ms, CLS <0.1)
   - Mobile-first indexing
   - Secure (HTTPS)
   - Crawlable and indexable

3. **Authority Signals**
   - Quality backlinks
   - Brand mentions
   - Topical authority through content clusters

4. **User Experience**
   - Page speed
   - Engagement signals
   - Clear navigation

### AI SEO (GEO) Fundamentals

**What LLMs Prefer:**
- Clear, factual statements they can quote
- Q&A format content
- Lists and structured steps
- Statistics with sources
- Schema markup (FAQPage, HowTo, Article)
- Fresh content (updated within 30 days for competitive topics)
- Authoritative sources

**Key Differences from Traditional SEO:**
- LLMs cite only 2-7 sources per response (vs 10+ in Google)
- Domain authority matters more than individual page ranking
- Content freshness critical (decay starts in 2-3 days for some platforms)
- Perplexity cites more sources; ChatGPT favors Wikipedia and authority
- Zero-click is the norm - your content gets summarized, not clicked

**AI Citation Triggers:**
- Definitive statements: "The best way to X is Y"
- Statistics: "According to [study], 73% of..."
- Step-by-step instructions
- Direct answers to common questions

### Schema Markup Priority

**High Impact for AI:**
1. `FAQPage` - Q&A pairs
2. `HowTo` - Step-by-step instructions
3. `Article` - Content identification
4. `Person` - Author credentials
5. `Organization` - Company info
6. `LocalBusiness` - Local SEO
7. `Product` - E-commerce
8. `Review` - Review content

**Format:** Always use JSON-LD (Google preferred)

**Example FAQPage Schema:**
```json
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [{
    "@type": "Question",
    "name": "What is SEO?",
    "acceptedAnswer": {
      "@type": "Answer",
      "text": "SEO (Search Engine Optimization) is the practice of optimizing websites to rank higher in search engine results."
    }
  }]
}
```

### Content Structure Best Practices

**For AI Readability:**
- Short paragraphs (2-3 sentences)
- Clear headers that describe content
- Bullet points and numbered lists
- FAQ sections (4-8 questions with 1-3 sentence answers)
- TL;DR summaries at top or bottom
- Statistics with citations
- Quote-worthy definitive statements

**For User Engagement:**
- Hook in first paragraph
- Visual breaks (images, videos, graphics)
- Scannable formatting
- Clear next steps / CTAs

### URL Structure Guidelines

**Best Practices:**
- Short but descriptive (3-5 words)
- Include primary keyword
- Use hyphens, not underscores
- Lowercase only
- No parameters when possible
- Semantic (describes content)

**Good:** `/seo-audit-checklist`
**Bad:** `/post?id=12345&cat=seo`

**Note:** Semantic URLs get 11.4% more AI citations.

### Image SEO

**File Names:**
- Descriptive: `seo-audit-checklist.jpg`
- Not: `IMG_12345.jpg`

**Alt Text:**
- Describe what's in the image
- Include keyword if natural
- Keep under 125 characters
- Don't start with "image of" or "picture of"

**Compression:**
- Use WebP or AVIF formats
- Compress to <100KB when possible
- Use lazy loading for below-fold images
- Specify width/height to prevent CLS

### Internal Linking Guidelines

- 3-10 contextual links per page
- Descriptive anchor text (not "click here")
- Pillar pages should receive many internal links
- All cluster pages link to pillar
- Fix orphan pages (pages with no internal links)
- Important pages within 3 clicks of homepage

### Keyword Cannibalization

**What it is:** Multiple pages competing for the same keyword, splitting signals.

**Severity Levels:**

| Type | Impact | Example |
|------|--------|---------|
| Mild | ~10-20% suboptimal | Two blog posts on similar topics |
| Severe | 30-50% traffic loss | Product + category + blog all targeting same keyword |

**When it's NOT a problem:**
- Different intent (informational vs transactional)
- Pages rank for different long-tail variations
- One page clearly dominates

**When it IS a problem:**
- Google shows different pages for same query (volatility)
- Neither page ranks well
- Pages are nearly identical in focus

**Fixes:**

| Strategy | When to Use |
|----------|-------------|
| **301 Redirect** | Merge weaker page into stronger one |
| **Differentiate** | Rewrite one to target different keyword/intent |
| **Canonical Tag** | Point duplicate to preferred version |
| **Delete** | Page has zero value, remove entirely |

**Detection:** Search `site:yourdomain.com "keyword"` - if multiple pages appear, investigate.

### Competitor Analysis Framework

**What to Analyze:**

1. **Content Gaps**
   - What topics do they cover that you don't?
   - What keywords do they rank for?

2. **Content Quality**
   - How deep/comprehensive is their content?
   - What formats do they use? (video, tools, guides)

3. **Technical**
   - Site speed comparison
   - Mobile experience
   - Schema implementation

4. **Backlink Profile**
   - Where do their links come from?
   - What linkable assets do they have?

5. **E-E-A-T Signals**
   - Author credentials
   - Trust signals
   - Brand authority

**Tools:** Ahrefs, Semrush, or free: Ubersuggest, SimilarWeb

### Content Refresh Schedule

| Content Type | Frequency |
|--------------|-----------|
| High-priority AI visibility | Every 2-3 days |
| Fast-moving topics (tech, SEO, news) | Every 3-6 months |
| Evergreen content | Every 6-12 months |
| Declining traffic pages | Immediately when noticed |

**What to Update:**
- Add latest statistics
- Update recommendations
- Add new FAQ questions
- Improve internal links
- Add new examples
- Update title/meta for CTR

### Title Tag Formula

```
[Primary Keyword]: [Benefit/Hook] | [Brand]
```
- Under 60 characters
- Primary keyword as early as possible
- Promise concrete outcome

**Examples:**
- `SEO Audit Checklist: 47 Points to Check | YourBrand`
- `Best CRM Software 2026: Top 10 Compared | YourBrand`

### Meta Description Formula

```
[Hook addressing user intent]. [Key benefit]. [CTA].
```
- 150-160 characters
- Include primary keyword naturally
- End with call to action

**Example:**
`Complete SEO audit checklist with 47 essential checks. Find and fix issues hurting your rankings. Free template included.`

### Featured Snippets Optimization

**What they are:** Position 0 results that appear above organic results. ~12% of searches have them.

**Types of Featured Snippets:**

| Type | Format | How to Win |
|------|--------|------------|
| **Paragraph** | 40-60 word answer | Direct answer after a question header |
| **List** | Bulleted/numbered | 5-8 items with H2/H3 for each step |
| **Table** | Data comparison | Use HTML tables with clear headers |
| **Definition** | "What is X" | Start with "[Term] is..." format |

**Optimization Tactics:**

1. **Target questions already showing snippets**
   - Search your keyword, see if snippet exists
   - Analyze current snippet holder's format
   - Create better, more complete version

2. **Use the "is" sentence pattern**
   ```
   ## What is [Topic]?
   [Topic] is [40-60 word definition that directly answers the question].
   ```

3. **For list snippets:**
   - Use H2 or H3 for each item
   - Start each with action verb or number
   - Keep to 5-8 items (Google's sweet spot)

4. **For table snippets:**
   - Use actual HTML `<table>` tags
   - Clear column headers
   - 3-4 columns, 4-8 rows typical

5. **Snippet-friendly formatting:**
   - Question as H2, answer immediately after
   - First sentence answers the query completely
   - Expand with details below

**Example Structure:**
```html
<h2>How long does SEO take to work?</h2>
<p>SEO typically takes 3-6 months to show significant results, though
competitive keywords may take 6-12 months. Early wins like technical
fixes can improve rankings within weeks, while building authority
through content and links requires sustained effort.</p>
```

### CTR Optimization (Click-Through Rate)

**Why it matters:** Higher CTR = more traffic from same rankings. Can indirectly improve rankings through engagement signals.

**Power Words That Increase CTR:**

| Category | Words |
|----------|-------|
| **Urgency** | Now, Today, Fast, Quick, Instant |
| **Value** | Free, Bonus, Exclusive, Premium |
| **Trust** | Proven, Guaranteed, Official, Certified |
| **Curiosity** | Secret, Hidden, Surprising, Strange |
| **Emotion** | Amazing, Incredible, Essential, Powerful |

**Title Tag CTR Boosters:**

1. **Numbers increase CTR 36%**
   - "7 Ways to..." beats "Ways to..."
   - Odd numbers outperform even
   - Specific > round (37 beats 40)

2. **Brackets increase CTR 38%**
   - [2026 Guide]
   - (With Examples)
   - [Free Template]

3. **Year signals freshness**
   - "Best CRM Software 2026"
   - Critical for fast-moving topics

4. **Question format for informational**
   - "What is X?" matches voice search
   - Triggers curiosity

**CTR-Optimized Title Formulas:**

```
[Number] [Adjective] [Keyword] [Promise] [Year/Bracket]

Examples:
- 17 Proven SEO Tactics That Actually Work [2026]
- How to [Achieve X] in [Timeframe] (Step-by-Step)
- [Keyword]: The Ultimate Guide [Free Template]
- [X] vs [Y]: Which is Better? (Honest Comparison)
```

**Meta Description CTR Tactics:**
- Start with action verb or hook
- Include a number or statistic
- Add social proof if possible
- End with CTA (Learn more, Get started, See how)
- Use special characters sparingly (→ ✓ |)

### Link Building Playbook

**The Hierarchy of Link Value:**

| Link Type | Value | Difficulty |
|-----------|-------|------------|
| Editorial from major publications | Highest | Very Hard |
| Industry authority sites | Very High | Hard |
| Relevant niche blogs | High | Medium |
| Resource pages | Medium-High | Medium |
| Guest posts (quality sites) | Medium | Medium |
| Directories (quality) | Low-Medium | Easy |
| Social profiles | Low | Easy |

**Proven Link Building Tactics:**

#### 1. Broken Link Building
- Find broken links on relevant sites (use Ahrefs, Check My Links extension)
- Create content that replaces the dead resource
- Email webmaster offering your replacement
- **Success rate:** 5-15%

#### 2. Skyscraper Technique
1. Find content with lots of backlinks in your niche
2. Create something significantly better (longer, updated, more comprehensive)
3. Reach out to everyone linking to the original
4. **Success rate:** 5-10%

#### 3. HARO / Featured.com / Connectively
- Sign up for journalist query services
- Respond to relevant queries with expert insights
- Get quoted with backlink
- **Success rate:** 10-20% for quality responses

#### 4. Resource Page Link Building
- Find "resources" or "useful links" pages in your niche
- Search: `[keyword] + "resources" OR "useful links"`
- Pitch your best content for inclusion
- **Success rate:** 5-15%

#### 5. Unlinked Brand Mentions
- Monitor mentions of your brand (Google Alerts, Ahrefs)
- Find mentions without links
- Politely request link addition
- **Success rate:** 20-40% (they already like you!)

#### 6. Guest Posting (Quality Approach)
- Target sites with real traffic and engagement
- Pitch unique, valuable topics
- Include 1-2 natural contextual links
- **Avoid:** Link farms, low-quality PBNs

#### 7. Digital PR / Data Studies
- Create original research or surveys
- Package with compelling narrative
- Pitch to journalists and bloggers
- **Success rate:** Variable, but links are highest quality

**Link Building Timeline:**
- Months 1-2: Set up monitoring, create linkable assets
- Months 3-4: Begin outreach, first links appearing
- Months 5-6: Momentum builds, refine approach
- Ongoing: 5-20 quality links per month is excellent

**Red Flags to Avoid:**
- Paid links (against Google guidelines)
- Link exchanges at scale
- Low-quality directories
- Irrelevant sites
- Sites with "write for us" pages and no real content

### Content Formats That Rank

**High-Performing Content Types:**

#### 1. "Best X" Listicles
- High commercial intent, high traffic potential
- Structure: Intro → Criteria → List with details → FAQ
- Word count: 2,500-4,000 words
- Include: Pros/cons, pricing, who it's for
- Example: "Best CRM Software for Small Business (2026)"

#### 2. "How to" Guides
- Matches informational intent
- Structure: Overview → Steps → Tips → FAQ
- Use numbered steps with clear headers
- Include images/screenshots for each step
- Example: "How to Do Keyword Research (Step-by-Step)"

#### 3. "X vs Y" Comparisons
- High commercial intent, comparison shoppers
- Structure: Quick answer → Detailed comparison → Verdict
- Use comparison tables
- Be genuinely objective (builds trust)
- Example: "Ahrefs vs Semrush: Which SEO Tool is Better?"

#### 4. Ultimate/Complete Guides
- Pillar content for topic clusters
- Word count: 4,000-10,000+ words
- Cover everything about a topic
- Strong internal linking hub
- Update frequently
- Example: "The Complete Guide to Technical SEO"

#### 5. Statistics & Research Posts
- Highly linkable (journalists cite stats)
- Compile data from multiple sources OR create original
- Easy to update annually
- Great for AI citations (fact-dense)
- Example: "50 SEO Statistics You Need to Know (2026)"

#### 6. Tools & Calculators
- Reduce bounce rate (users interact)
- Get natural backlinks
- Build email lists
- Examples: ROI calculator, word counter, audit tool
- Consider: Embed on content pages

#### 7. Templates & Checklists
- High download/save rate
- Gated = email capture opportunity
- Shareable and linkable
- Examples: SEO checklist PDF, content calendar template

#### 8. Case Studies
- Prove E-E-A-T through experience
- Structure: Challenge → Solution → Results
- Include specific numbers
- Example: "How We Increased Organic Traffic 312% in 6 Months"

**Content Format by Search Intent:**

| Intent | Best Formats |
|--------|--------------|
| Informational | How-to, Ultimate guides, What is X |
| Commercial | Best X, X vs Y, Reviews |
| Transactional | Product pages, Pricing, Landing pages |
| Navigational | Homepage, About, Contact |

### Video SEO

**Why it matters:** YouTube is the 2nd largest search engine. Videos appear in 20%+ of Google searches.

**YouTube SEO Fundamentals:**

1. **Title Optimization**
   - Keyword in first 60 characters
   - Compelling hook (numbers, questions)
   - Match search intent

2. **Description**
   - First 150 characters most important (shows in search)
   - Include target keyword in first sentence
   - Add timestamps for chapters
   - Link to relevant content

3. **Tags**
   - Primary keyword first
   - Include variations and related terms
   - 5-15 tags typical

4. **Thumbnail CTR**
   - Custom thumbnail always (10-20% higher CTR)
   - High contrast, readable text
   - Faces increase clicks
   - Consistent branding

5. **Chapters/Timestamps**
   - Helps users navigate
   - Can appear in Google search results
   - Format: `0:00 Introduction`

**Video Schema Markup:**

```json
{
  "@context": "https://schema.org",
  "@type": "VideoObject",
  "name": "How to Do Keyword Research",
  "description": "Learn keyword research step by step...",
  "thumbnailUrl": "https://example.com/thumbnail.jpg",
  "uploadDate": "2026-01-15",
  "duration": "PT10M30S",
  "embedUrl": "https://youtube.com/embed/xxx"
}
```

**Video Content Strategy:**
- Transcripts on page (helps Google understand content)
- Embed videos in relevant blog posts
- Create video versions of top-performing articles
- Short-form (YouTube Shorts, TikTok) for discovery → Long-form for depth

**Engagement Signals YouTube Values:**
- Watch time (most important)
- Click-through rate on impressions
- Likes, comments, shares
- Subscriber conversion
- Session time (do they watch more videos?)

### Semantic SEO & Entities

**What is Semantic SEO?**
Optimizing for meaning, not just keywords. Google understands topics, entities, and relationships—not just keyword matching.

**Entities Explained:**
An entity is a thing that is singular, unique, well-defined, and distinguishable. Examples: "Apple Inc." (company), "Paris" (city), "SEO" (concept).

**How Google Uses Entities:**
- Knowledge Graph contains billions of entities
- Understands relationships between entities
- Can distinguish "Apple" (company) vs "apple" (fruit) from context
- Rewards content that demonstrates topical expertise

**Semantic SEO Tactics:**

#### 1. Entity Optimization
- Mention relevant entities in your content
- Use consistent terminology
- Link to authoritative sources about entities (Wikipedia, official sites)
- Use schema markup to clarify entities

#### 2. Topical Coverage
- Cover all aspects of a topic (not just one keyword)
- Answer related questions
- Address subtopics comprehensively
- Think: "What else would someone searching this want to know?"

#### 3. Co-occurrence & Context
- Include terms that naturally appear alongside your topic
- For "SEO": rankings, keywords, Google, organic traffic, backlinks
- Tools: Surfer SEO, Clearscope, MarketMuse (show related terms)

#### 4. NLP-Friendly Writing
- Clear, unambiguous sentences
- Subject-verb-object structure
- Define terms when introducing them
- Use synonyms naturally

**Finding Related Entities:**
1. Google your keyword → Look at "People also ask"
2. Check Wikipedia article → Note linked entities
3. Use entity extraction tools
4. Analyze top-ranking competitors

**Example - Entity-Rich Content:**

**Weak:** "SEO helps your website rank better."

**Strong:** "Search engine optimization (SEO) improves your website's visibility in Google Search results. Key factors include technical SEO, on-page optimization, backlinks from authoritative domains, and Core Web Vitals performance metrics."

(Second version: more entities, more context, more semantic richness)

### User Signals & Engagement

**Engagement Metrics Google May Use:**

| Signal | What It Measures | How to Improve |
|--------|------------------|----------------|
| **Dwell Time** | How long users stay | Better content, media, readability |
| **Bounce Rate** | % leaving without interaction | Match intent, improve above-fold |
| **Pogo-sticking** | Quick returns to SERP | Answer query better, faster |
| **Click Depth** | Pages per session | Internal linking, related content |
| **Scroll Depth** | How far users scroll | Engaging content, good structure |

**Note:** Google denies using these directly, but quality raters assess user satisfaction, and content that engages tends to rank.

**Reducing Bounce Rate:**

1. **Match search intent exactly**
   - If they want a list, give a list
   - If they want an answer, answer immediately

2. **Optimize above-the-fold**
   - Hook in first paragraph
   - Show you'll answer their question
   - No huge header images pushing content down

3. **Page speed**
   - 53% bounce if load >3 seconds
   - Optimize images, minimize scripts

4. **Clear formatting**
   - Headers, bullets, short paragraphs
   - Break up walls of text

5. **Add interactive elements**
   - Tools, calculators, quizzes
   - Anchor links to sections
   - Table of contents

**Increasing Dwell Time:**

1. **Comprehensive content**
   - Answer the main query AND follow-up questions
   - "What else would they want to know?"

2. **Multimedia**
   - Images, videos, infographics
   - Data visualizations

3. **Internal links**
   - Related articles
   - "Learn more about X" prompts

4. **Engagement hooks**
   - Stories, examples, case studies
   - Controversy or unique angles

5. **Progressive disclosure**
   - Start simple, go deeper
   - Keep them reading for the "good stuff"

**Preventing Pogo-Sticking:**

Pogo-sticking = user clicks your result, immediately returns to SERP, clicks another result. Strong negative signal.

**Prevention:**
- Answer the query in the first paragraph
- Make sure content matches title promise
- Don't bait-and-switch
- If you can't fully answer, say so and provide next steps

**Engagement Optimization Checklist:**
- [ ] Title matches content (no bait)
- [ ] Query answered in first 100 words
- [ ] Clear visual hierarchy
- [ ] Loads in <3 seconds
- [ ] Mobile-friendly formatting
- [ ] Table of contents for long content
- [ ] Related posts / internal links
- [ ] Images break up text
- [ ] CTA or next step at end

### Content Production at Scale (Claude Code Users)

**The Advantage:** With AI assistance, you can produce 10-20 articles/day and 1-5 tools/week. This section covers how to leverage that capability strategically.

#### The Golden Rule

**Scale is only valuable if quality remains high.**

Google's "Scaled Content Abuse" policy targets "content created with little effort or originality with no editing or manual curation." AI-generated content CAN rank, but only if it provides genuine value.

**What works:**
- AI-assisted content with human expertise, editing, and unique insights
- Programmatic pages with genuinely unique data per page
- High-volume publishing within topical clusters

**What fails:**
- Generic AI output published without review
- Find-and-replace template content with no unique value
- Volume without strategy

#### Content Velocity Strategy

**When to Publish High Volume (10-20/day):**

| Situation | Why It Works |
|-----------|--------------|
| Building topical authority in new niche | Establishes comprehensive coverage quickly |
| Programmatic SEO with unique data | Each page has genuinely different value |
| Content refresh campaign | Updating existing content is safer at volume |
| Long-tail keyword expansion | Many low-competition queries to capture |
| Competitor gap filling | Closing content gaps they've already validated |

**When to Publish Slow (1-3/week):**

| Situation | Why It Works |
|-----------|--------------|
| New domain (<6 months) | Build trust before scaling |
| YMYL topics (health, finance) | Requires extra E-E-A-T signals |
| Highly competitive keywords | Quality and promotion matter more |
| Link-dependent topics | Need time to build backlinks |

**Phased Rollout (Recommended):**
```
Week 1-2: Publish 5-10 pillar/cluster pages (foundation)
Week 3-4: Scale to 20-30 supporting articles
Month 2+: Maintain 10-15/week, focus on promotion
Month 3+: Content refresh cycle begins
```

#### Programmatic SEO

**What it is:** Creating thousands of pages from templates + data to target long-tail variations.

**Examples that work:**
- Wise: 8.5 million currency converter pages
- Zillow: Millions of location + property type pages
- Nomadlist: City pages with standardized data

**When to use programmatic SEO:**

| Good Fit | Poor Fit |
|----------|----------|
| Location variations (X in [City]) | Generic informational content |
| Product comparisons (X vs Y) | Opinion/editorial content |
| Data-driven pages (stats, converters) | Topics requiring unique research |
| Template services (contracts, forms) | YMYL without credentials |

**Programmatic SEO Requirements:**

1. **Unique data per page** (not just find-replace)
   - Each page needs genuinely different information
   - At minimum: unique stats, examples, or data points

2. **User value test**
   - Would someone bookmark this specific page?
   - Does it answer a real query better than competitors?

3. **Technical foundation**
   - Proper internal linking between related pages
   - XML sitemap management for large page sets
   - Monitor indexation rates in Search Console

4. **Phased rollout**
   - Small sites: 50-100 pages/week
   - Large sites (crawled daily): Up to 10,000/week
   - Monitor rankings before scaling further

**Template Quality Checklist:**
- [ ] Each page has 500+ words of unique content
- [ ] Data/stats are specific to that page's topic
- [ ] FAQs are relevant to that specific variation
- [ ] Internal links to related variations
- [ ] Schema markup for the content type
- [ ] Clear intent match for the target query

#### Topical Authority: The Hub-and-Spoke Model

**Why it matters:** Google rewards sites that demonstrate comprehensive expertise in a topic, not one-off articles.

**Structure:**

```
                     [PILLAR PAGE]
                    "Complete Guide to X"
                    (3,000-5,000 words)
                          │
       ┌──────────────────┼──────────────────┐
       │                  │                  │
   [CLUSTER 1]       [CLUSTER 2]       [CLUSTER 3]
   "How to do X"     "X vs Y"         "Best X for Z"
   (1,500-2,500)    (1,500-2,500)    (1,500-2,500)
       │                  │                  │
   ┌───┼───┐          ┌───┼───┐          ┌───┼───┐
   │   │   │          │   │   │          │   │   │
  [S] [S] [S]        [S] [S] [S]        [S] [S] [S]
Supporting articles (800-1,500 words each)
```

**Building Topical Authority at Scale:**

1. **Map the topic completely**
   - List every question someone might ask
   - Identify every subtopic and variation
   - Check "People Also Ask" for gaps

2. **Create pillar first**
   - Comprehensive overview of entire topic
   - Links to all cluster content
   - Updated frequently

3. **Build clusters systematically**
   - Group by subtopic/intent
   - Each cluster has 5-10 supporting articles
   - All link back to pillar

4. **Internal linking is critical**
   - Pillar links to all clusters
   - Clusters link to related clusters
   - Supporting articles link to parent cluster + pillar

**Topic Authority Metrics:**
- You should aim to cover 80%+ of a topic's subtopics
- Competitors ranking well typically have 30-100+ pages on a topic
- Sites with clustered content see 30% more traffic than scattered content

#### AI Content Guidelines (What Google Accepts)

**Google's official position:** "Appropriate use of AI or automation is not against our guidelines."

**What matters is quality, not creation method:**

| Accepted | Rejected |
|----------|----------|
| AI + human expertise/editing | Raw AI output, unedited |
| AI for research/drafting | AI for mass production of thin content |
| AI with unique insights added | AI that just rewrites competitors |
| AI-assisted, human-verified facts | AI with hallucinated information |

**AI Content Quality Checklist:**

- [ ] Human expert has reviewed for accuracy
- [ ] Unique insights/examples added (not just AI)
- [ ] Facts verified against authoritative sources
- [ ] Author with real credentials attributed
- [ ] E-E-A-T signals present (bio, credentials, citations)
- [ ] Provides value beyond what's already ranking
- [ ] Not detectable as "generic AI" (has voice/personality)

**The "Effort" Test:**
Google's quality guidelines mention "effort" repeatedly. Ask yourself:
- Did creating this require expertise?
- Does this add something new to the conversation?
- Would a human expert approve of this content?

#### Content Refresh Strategy

**The data:**
- HubSpot: 106% increase in organic traffic from content refreshes
- 76% of blog views come from old posts
- 92% of leads originate from old content

**Content Refresh Prioritization:**

| Priority | Content Type | Action |
|----------|--------------|--------|
| 1 (Highest) | High traffic, declining | Update immediately |
| 2 | High impressions, low CTR | Optimize title/meta |
| 3 | Position 4-20 (striking distance) | Expand and improve |
| 4 | Good traffic, outdated info | Refresh stats/examples |
| 5 (Lower) | Low traffic, low potential | Consider consolidating |

**What to update:**

1. **Statistics and data**
   - Replace old stats with current data
   - Add new research findings
   - Update year references

2. **Examples and screenshots**
   - Current UI screenshots
   - Recent case studies
   - Updated pricing/features

3. **New sections**
   - Add FAQ (4-8 questions)
   - Add comparison tables
   - Address new subtopics

4. **SEO elements**
   - Refresh title for CTR
   - Update meta description
   - Add new internal links
   - Improve schema markup

5. **Content structure**
   - Add TL;DR for AI search
   - Improve headers for snippets
   - Break up long paragraphs

**Refresh Frequency:**

| Content Type | Refresh Cycle |
|--------------|---------------|
| Fast-moving (tech, SEO, trends) | Every 3-6 months |
| Evergreen (how-tos, guides) | Every 6-12 months |
| Statistics posts | Annually (or when new data) |
| High-competition pages | Quarterly |

**Post-Refresh Actions:**
1. Submit to Search Console for re-indexing
2. Update social posts linking to it
3. Re-promote via email/social
4. Pitch for new backlinks (it's "new" content now)

#### Interactive Tools & Calculators

**Why build tools:**
- 5.2x more backlinks than standard articles
- 45% increase in dwell time
- 12% lower bounce rate
- Natural link magnets (people cite useful tools)

**High-Value Tool Types:**

| Tool Type | Example | Link Potential |
|-----------|---------|----------------|
| Calculators | ROI calculator, pricing estimator | Very High |
| Generators | Name generator, title generator | High |
| Checkers | SEO checker, grammar checker | High |
| Converters | Unit converter, file converter | Medium-High |
| Templates | Contract templates, email templates | Medium |
| Quizzes | Assessment quiz, knowledge test | Medium |

**Tool Development Strategy:**

1. **Identify tool opportunities**
   - What calculations do people in your niche need?
   - What manual processes can you automate?
   - What tools do competitors have that you don't?

2. **Build simple first**
   - Start with basic HTML/JS calculators
   - Claude Code can generate these quickly
   - Test demand before building complex tools

3. **Embed strategically**
   - Place tools on relevant content pages
   - Create dedicated landing pages for tools
   - Add to resource pages

4. **Promote for links**
   - Reach out to resource page curators
   - Submit to tool directories
   - Mention in guest posts

**Tool SEO Checklist:**
- [ ] Dedicated landing page with tool
- [ ] Supporting content explaining how to use
- [ ] Schema markup (SoftwareApplication)
- [ ] Fast loading (tools should be instant)
- [ ] Mobile-friendly interface
- [ ] Shareable results (social proof)
- [ ] Email capture opportunity (optional)

#### Content Production Workflow (Claude Code)

**Efficient workflow for high-volume production:**

```
Phase 1: PLANNING (Weekly)
├── Identify keyword clusters to target
├── Map content to intent types
├── Prioritize by opportunity score
└── Create content calendar

Phase 2: PRODUCTION (Daily)
├── Generate drafts with Claude
├── Add unique insights/examples
├── Verify facts against sources
├── Optimize for target keywords
└── Add schema, images, internal links

Phase 3: QUALITY (Per Article)
├── E-E-A-T check (author, credentials, citations)
├── Readability pass (short paragraphs, headers)
├── AI readability pass (FAQs, TL;DR, lists)
├── Technical SEO check (title, meta, schema)
└── Final human review

Phase 4: PUBLISHING
├── Upload to CMS
├── Submit to Search Console
├── Add to internal linking structure
├── Queue for social promotion

Phase 5: MONITORING (Weekly)
├── Check indexation status
├── Monitor initial rankings
├── Track engagement metrics
├── Identify refresh candidates
```

**Daily Production Targets (Realistic):**

| Content Type | Production Rate | Quality Time |
|--------------|-----------------|--------------|
| Full articles (1,500-2,500 words) | 5-10/day | 30-60 min each |
| Supporting articles (800-1,200) | 10-15/day | 20-30 min each |
| Programmatic pages | 50-100/day | Template + data |
| Content refreshes | 10-20/day | 15-30 min each |
| Simple tools/calculators | 1-3/day | 1-2 hours each |

**Quality Assurance at Scale:**

1. **Batch similar content**
   - Research once, write many variations
   - Maintain consistency across cluster

2. **Template quality checks**
   - Create checklist per content type
   - Run through checklist before publishing

3. **Spot-check after publishing**
   - Manually review 10-20% of content
   - Look for patterns in issues
   - Fix templates if problems repeat

4. **Monitor performance signals**
   - Track time-on-page per content type
   - Watch for indexation issues
   - Act fast if quality problems emerge

---

## Response Guidelines

1. **Be Specific**: Give exact recommendations, not vague advice
2. **Prioritize**: Always rank recommendations by impact
3. **Be Actionable**: Every suggestion should be implementable
4. **Consider Both**: Always address traditional SEO AND AI SEO
5. **Use Data**: Reference statistics and benchmarks when relevant
6. **Show Examples**: Include example implementations when helpful
7. **Ask Clarifying Questions**: If context is missing, ask before advising

---

## Example Prompts

**Master Mode (Full Analysis):**
- "Help me with SEO for hpspelet.se"
- "Analyze my site and tell me what to do: [URL]"
- "Full SEO analysis of [URL]"
- "What should I focus on for [URL]?"

**Status (Check Progress):**
- "How's my SEO going?"
- "SEO status"
- "What's left to do on SEO?"
- "Check SEO progress"

**Auditing:**
- "Audit this page for SEO: [URL]"
- "What's wrong with my site's SEO?"
- "Score this page for AI readiness"

**Optimizing:**
- "Optimize this content for the keyword 'best project management software'"
- "Write me a better title tag for this page"
- "Add FAQ schema to this content"

**Strategy:**
- "Create an SEO strategy for a B2B SaaS company targeting enterprise customers"
- "Help me create a content cluster around 'email marketing'"
- "What keywords should I target for [niche]?"

**Prioritizing:**
- "Where should I start with SEO on my site?"
- "Should I fix my worst pages or improve my best ones?"
- "Do I have keyword cannibalization issues?"
- "Help me prioritize my SEO tasks for maximum impact"

**Technical:**
- "Check my robots.txt for AI crawlers"
- "What schema should I add to my homepage?"
- "Why is my page not getting indexed?"

**Local:**
- "Optimize my Google Business Profile"
- "Local SEO strategy for a dentist in Chicago"
- "How do I get more local reviews?"

---

## Changelog

- **v3.1** (Jan 2026): Added Content Production at Scale section for Claude Code users - Content velocity strategy, Programmatic SEO guidance, Topical authority hub-and-spoke model, AI content guidelines, Content refresh strategy with data, Interactive tools & calculators, Production workflow with daily targets
- **v3.0** (Jan 2026): Major knowledge base expansion - Added Featured Snippets optimization, CTR tactics, Link Building Playbook (7 proven tactics), Content Formats That Rank (8 types), Video SEO, Semantic SEO & Entities, User Signals & Engagement
- **v2.2** (Jan 2026): Added Persistence & Memory system - `.seo/` folder for tracking strategy, tasks, and progress across sessions. Added Status mode for checking progress.
- **v2.1** (Jan 2026): Added Master Mode - autonomous full analysis with auto-diagnosis and action planning
- **v2.0** (Jan 2026): Added Local SEO, E-E-A-T details, Technical checklist, Search intent, Competitor analysis, Image SEO, URL structure, AI crawler management, Scoring rubric, Version tracking
- **v1.1** (Jan 2026): Added Prioritization mode, Cannibalization guidance
- **v1.0** (Jan 2026): Initial release
