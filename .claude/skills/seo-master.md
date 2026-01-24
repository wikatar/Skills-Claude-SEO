# SEO Master Skill

A comprehensive SEO and AI SEO (GEO) skill for auditing pages, optimizing content, and generating strategies.

## Description

This skill helps you:
- **Audit** websites and pages for traditional SEO and AI SEO issues
- **Optimize** content for both Google and AI search engines (ChatGPT, Perplexity, Gemini)
- **Generate** comprehensive SEO strategies tailored to your goals

## Usage

Invoke this skill when you need help with:
- SEO audits and recommendations
- Content optimization for search
- AI SEO / GEO optimization
- SEO strategy development
- Technical SEO analysis
- E-E-A-T improvements

## Modes

### Mode 1: Page Audit (`/seo audit <url>`)

When auditing a page, analyze:

**Traditional SEO:**
- Title tag (length, keyword placement, clarity)
- Meta description (length, CTA, keyword inclusion)
- Header structure (H1-H6 hierarchy)
- Content quality and search intent match
- Internal linking
- Schema markup presence
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

### AI SEO Readiness
- [Assessment of GEO optimization]

### Quick Wins
1. [Immediate action]
2. [Immediate action]
3. [Immediate action]
```

### Mode 2: Content Optimization (`/seo optimize`)

When optimizing content, consider the user's:
- Target keyword(s)
- Search intent
- Current content
- Target audience

**Provide:**

1. **Title Tag Optimization**
   - Current analysis
   - Optimized version(s)
   - Reasoning

2. **Meta Description**
   - Current analysis
   - Optimized version(s)

3. **Header Structure**
   - Recommended H1
   - Suggested H2/H3 outline

4. **Content Enhancements**
   - Missing topics to cover
   - FAQ suggestions (4-8 questions)
   - Statistics/data to add
   - Internal linking opportunities

5. **AI Optimization**
   - TL;DR summary to add
   - Quote-worthy statements to include
   - Schema markup recommendations

### Mode 3: Strategy Generation (`/seo strategy`)

When generating strategy, gather information about:
- Business type and goals
- Current website state
- Target audience
- Competitors
- Resources available
- Timeline

**Provide:**

1. **Situation Analysis**
   - Current state assessment
   - Competitor landscape
   - Opportunities

2. **Keyword Strategy**
   - Target keyword clusters
   - Priority topics
   - Content gap analysis

3. **Content Strategy**
   - Pillar pages to create
   - Content cluster plan
   - Publishing cadence
   - Refresh schedule

4. **Technical Priorities**
   - Critical fixes
   - Quick wins
   - Long-term improvements

5. **AI SEO (GEO) Strategy**
   - Schema implementation plan
   - Content structure changes
   - AI crawler policy
   - Visibility monitoring

6. **Link Building Approach**
   - Linkable asset ideas
   - Digital PR opportunities
   - Outreach priorities

7. **Measurement Plan**
   - KPIs to track
   - Tools to use
   - Reporting cadence

## Knowledge Base

### Core Ranking Factors (2025)

1. **Content Quality & E-E-A-T**
   - Experience, Expertise, Authoritativeness, Trustworthiness
   - Helpful, people-first content
   - Matches search intent

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

**Key Differences:**
- LLMs cite only 2-7 sources per response (vs 10+ in Google)
- Domain authority matters more than individual page ranking
- Content freshness critical (decay starts in 2-3 days for some platforms)
- Perplexity cites more sources; ChatGPT favors Wikipedia and authority

### Schema Markup Priority

**High Impact for AI:**
1. `FAQPage` - Q&A pairs
2. `HowTo` - Step-by-step instructions
3. `Article` - Content identification
4. `Person` - Author credentials
5. `Organization` - Company info

**Format:** Always use JSON-LD

### Content Structure Best Practices

**For AI Readability:**
- Short paragraphs (2-3 sentences)
- Clear headers that describe content
- Bullet points and numbered lists
- FAQ sections (4-8 questions with 1-3 sentence answers)
- TL;DR summaries at top or bottom
- Statistics with citations
- Quote-worthy definitive statements

### Internal Linking Guidelines

- 3-10 contextual links per page
- Descriptive anchor text (not "click here")
- Pillar pages should receive many internal links
- All cluster pages link to pillar
- Fix orphan pages (pages with no internal links pointing to them)

### Content Refresh Schedule

| Content Type | Frequency |
|--------------|-----------|
| High-priority AI visibility | Every 2-3 days |
| Fast-moving topics (tech, SEO) | Every 3-6 months |
| Evergreen content | Every 6-12 months |

### Title Tag Formula

```
[Primary Keyword]: [Benefit/Hook] | [Brand]
```
- Under 60 characters
- Primary keyword as early as possible
- Promise concrete outcome

### Meta Description Formula

```
[Hook addressing user intent]. [Key benefit]. [CTA].
```
- 150-160 characters
- Include primary keyword naturally
- End with call to action

## Response Guidelines

1. **Be Specific**: Give exact recommendations, not vague advice
2. **Prioritize**: Always rank recommendations by impact
3. **Be Actionable**: Every suggestion should be implementable
4. **Consider Both**: Always address traditional SEO AND AI SEO
5. **Use Data**: Reference statistics and benchmarks when relevant
6. **Show Examples**: Include example implementations when helpful

## Example Prompts

- "Audit this page for SEO: [URL]"
- "Optimize this content for the keyword 'best project management software'"
- "Create an SEO strategy for a B2B SaaS company targeting enterprise customers"
- "How should I structure my content for AI search engines?"
- "What schema markup should I add to my product pages?"
- "Help me create a content cluster around 'email marketing'"
