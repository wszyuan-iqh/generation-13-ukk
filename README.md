# X Algorithm Content Strategist

An open Codex skill for turning X/Twitter-style recommendation logic into executable content strategy.

This skill helps creators, editors, marketers, and AI agents plan, write, and refine social content with a pipeline inspired by modern recommendation systems:

- candidate sourcing
- fact and sentiment enrichment
- quality filtering
- engagement prediction
- ranking and revision
- image/thumbnail strategy
- final recommendation-fit scoring

It is especially useful for topics that need to work across X/Twitter, newsletters, blogs, YouTube, TikTok, Instagram, Xiaohongshu, WeChat, and other content platforms.

## What It Does

Use this skill to generate or improve:

- topic matrices
- headline/title sets
- cover image and thumbnail directions
- X/Twitter posts and long threads
- blog and newsletter drafts
- short-video scripts
- content calendars
- campaign angles
- final publication scores

The skill does not claim to reproduce X's production ranking system. It translates public recommendation-system ideas into a practical editorial workflow.

## Skill Location

The skill itself lives at:

```text
skills/x-algorithm-content-strategist/
```

Required files:

```text
skills/x-algorithm-content-strategist/SKILL.md
skills/x-algorithm-content-strategist/agents/openai.yaml
skills/x-algorithm-content-strategist/references/scoring-rubric.md
```

## Installation

Copy the skill folder into your Codex skills directory.

Common target path:

```text
$CODEX_HOME/skills/x-algorithm-content-strategist
```

If `CODEX_HOME` is not set, use your local Codex skills directory.

After installation, restart or refresh Codex if needed so the skill metadata can be discovered.

## Usage

Example request:

```text
Use x-algorithm-content-strategist to create a full content package for the 2026 FIFA World Cup.
Include topic selection, title options, real-photo cover directions, article draft, and final recommendation-fit score.
```

Another example:

```text
Use x-algorithm-content-strategist to rewrite this draft for X/Twitter.
Make it more clickable, more credible, and more likely to earn bookmarks and replies.
```

## Workflow

The skill follows seven steps:

1. Clarify content goals and assumptions.
2. Build a broad information radar across official sources, media, social platforms, search demand, and visual assets.
3. Generate and score candidate topics.
4. Create and rank title variants.
5. Design real-photo-first cover or thumbnail directions.
6. Draft or rewrite the content.
7. Run a 100-point X-style recommendation-fit check.

## Scoring Model

Final publication score:

```text
Recommendation fit =
  topic demand 25
+ freshness/tension/timing 15
+ title click fit 15
+ image stopping power 15
+ body completion value 15
+ interaction trigger 10
+ account consistency 5
- risk deductions
```

Recommended threshold:

- `90-100`: strong publication candidate
- `85-89`: publish after light polish
- `70-84`: revise title, image, hook, or evidence
- below `70`: rework topic or angle

## Image Policy

For news, sports, cities, events, products, people, and travel content, prefer real photos over generated images.

Do not:

- use unlicensed press or social-media images
- remove watermarks
- present AI-generated images as real scenes
- use unrelated stock photos as if they depict the actual event

Recommended sources:

- owned or user-authorized photos
- official media kits
- licensed press photos
- Wikimedia Commons with compatible licensing
- public-domain or commercially usable stock when appropriate

## Attribution

This project was inspired by public discussion and public repositories related to recommendation systems, including the open `xai-org/x-algorithm` repository.

It is not affiliated with, endorsed by, or sponsored by X Corp., xAI, Twitter, FIFA, or any other platform or organization.

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

Useful contribution areas:

- better scoring rubrics
- more platform adaptation patterns
- multilingual examples
- real-world case studies
- safer source and image verification workflows
- evaluation prompts

## License

MIT. See [LICENSE](LICENSE).
