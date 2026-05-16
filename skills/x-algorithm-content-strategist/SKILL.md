---
name: x-algorithm-content-strategist
description: Create and optimize social content using X/Twitter recommendation-system logic. Use when Codex needs to plan or improve posts, threads, articles, thumbnails, cover images, scripts, campaigns, or content calendars by applying X-style candidate sourcing, filtering, engagement prediction, ranking, real-source validation, image strategy, and final recommendation-fit scoring.
---

# X Algorithm Content Strategist

Use this skill to turn a topic into executable social content designed for X/Twitter-style recommendation dynamics, then adapt it for other social and media platforms.

Core model: treat content production like a recommendation pipeline:

1. Source candidates from broad information pools.
2. Enrich with facts, audience context, emotional signals, and media assets.
3. Filter weak, risky, stale, misleading, or visually unsupported ideas.
4. Predict click, dwell, reply, repost, like, bookmark, and follow signals.
5. Rank content variants by expected platform fit.
6. Apply diversity, credibility, and quality checks before final output.

## Workflow

### 1. Clarify Inputs

Use these inputs when available:

- Account positioning
- Target audience
- Topic, product, event, or raw material
- Target platform
- Desired outcome: reach, followers, conversion, authority, discussion, bookmarks
- Available facts, cases, data, links, photos, or brand assets
- Tone constraints and forbidden expressions
- Output type: topic list, title set, cover image direction, article, thread, script, calendar

If inputs are missing, make reasonable assumptions and state them briefly.

### 2. Build An Information Radar

For current events, public figures, products, prices, schedules, regulations, news, sports, or any unstable facts, verify with current sources before writing.

Use a five-layer source model:

- Official facts: official sites, event pages, company pages, filings, organizers.
- News media: reputable outlets for context, disputes, numbers, and timelines.
- Social platforms: X, TikTok, Instagram, YouTube, Reddit, Threads, Facebook groups, local forums for sentiment and questions.
- Search demand: Google Trends, YouTube/TikTok search suggestions, platform autocomplete, recurring user questions.
- Visual assets: official media kits, licensed press photos, Wikimedia Commons, public-domain or commercially usable stock, user-authorized images.

Treat social posts as sentiment signals unless independently verified.

Prefer real photos for news, sports, travel, product, city, and event content. Do not imply an AI-generated or unrelated image is a real scene.

### 3. Generate And Score Topics

Generate at least 20 candidate topics unless the user asks for fewer.

Score each topic from 1-5 on:

- Pain or desire intensity
- Freshness or timing
- Audience size
- Discussion potential
- Deliverability: whether the article can prove or teach something concrete

Prioritize topics scoring 22-25. Improve or discard topics below 18.

### 4. Create Title Variants

Generate variants across these patterns:

- Counterintuitive
- Benefit/result
- Avoiding mistakes
- Breakdown/analysis
- Comparison
- Trend explanation
- Checklist/toolkit
- Postmortem/lesson

Score titles by:

- Click desire
- Clarity
- Information density
- Credibility
- Differentiation

Avoid cheap hype words such as "shocking", "must-see", "viral everywhere", or claims the body cannot prove.

### 5. Design Cover Image Or Thumbnail Direction

For each major content piece, propose 3-5 visual directions:

- Real-photo background
- Primary text, ideally 6-14 Chinese characters or a short English phrase
- Supporting text
- Composition
- Color and contrast
- Why it improves stopping power
- Licensing/source recommendation

Use authentic photos when the topic depends on trust, reality, place, people, event, product, or news value.

### 6. Draft Or Rewrite The Content

Use this structure unless another format is requested:

1. Three-second hook: conflict, fresh fact, pain point, or counterintuitive claim.
2. Compressed context: why this matters now.
3. Core thesis: one clear sentence.
4. Evidence: facts, cases, observations, or examples.
5. Actionable framework: 3-7 steps, categories, or criteria.
6. Application: how the reader can use it.
7. Interaction close: one specific question or choice that invites replies.

Write with high information density. Reduce empty motivational language, broad claims, and vague generalities.

### 7. X-Style Recommendation Fit Check

Before finalizing, score the output with this 100-point rubric:

- Topic demand: 25
- Freshness, tension, timing: 15
- Title click fit: 15
- Image stopping power: 15
- Body completion value: 15
- Interaction trigger: 10
- Account consistency: 5

Subtract risk:

- Mismatched title and body
- Unsupported claims
- Misleading image
- Weak evidence
- Overly promotional opening
- Generic advice
- Copyright or licensing risk

Target 85+ before recommending publication.

Read `references/scoring-rubric.md` when a detailed rubric, template, or final checklist is useful.

## Output Defaults

For a full content package, output:

1. Source radar summary
2. Topic matrix
3. Best topic recommendation
4. Title set and recommended title
5. Real-photo cover image directions
6. Draft article/thread/script
7. X-style score and revision notes
8. Platform adaptations

Keep the final user-facing answer concise, but create or update files when the user asks for durable artifacts.
