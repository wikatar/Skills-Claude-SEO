# SEO Master Skill

> Version 2.0 | Last Updated: January 2026

A comprehensive SEO and AI SEO (GEO) skill for auditing pages, optimizing content, and generating strategies.

---

## Quick Command Reference

| Command | What It Does |
|---------|--------------|
| `/seo audit <url>` | Full SEO audit of a page |
| `/seo optimize` | Optimize content for a keyword |
| `/seo strategy` | Generate comprehensive SEO strategy |
| `/seo prioritize` | Decide what to work on first |
| `/seo technical` | Technical SEO checklist |
| `/seo local` | Local SEO optimization |

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

- **v2.0** (Jan 2026): Added Local SEO, E-E-A-T details, Technical checklist, Search intent, Competitor analysis, Image SEO, URL structure, AI crawler management, Scoring rubric, Version tracking
- **v1.1** (Jan 2026): Added Prioritization mode, Cannibalization guidance
- **v1.0** (Jan 2026): Initial release
