# Contributing

Thank you for helping improve X Algorithm Content Strategist.

This project is a practical editorial workflow packaged as a Codex skill. Contributions should make the skill more useful, safer, clearer, or easier to evaluate.

## Good Contributions

Useful pull requests include:

- clearer skill instructions
- better scoring rubrics
- safer source verification rules
- better real-photo and licensing guidance
- platform-specific adaptation patterns
- multilingual examples
- evaluation prompts and test cases
- bug fixes in metadata or formatting

## Before Opening A Pull Request

1. Keep `skills/x-algorithm-content-strategist/SKILL.md` concise.
2. Put detailed scoring, examples, and long references in `references/`.
3. Do not add unrelated documentation inside the skill folder.
4. Avoid copyrighted long-form examples unless you own them or they are clearly licensed.
5. Do not add claims about private platform ranking systems.
6. Keep examples factual and label assumptions.

## Development Checklist

Before submitting:

- The skill folder still contains a valid `SKILL.md`.
- `SKILL.md` has only `name` and `description` in YAML frontmatter.
- `agents/openai.yaml` still matches the skill purpose.
- Any current-event examples use verifiable sources.
- Any image guidance respects licensing and attribution.
- New reference files are linked from `SKILL.md`.
- The language is clear enough for another agent to follow.

## Pull Request Style

Use a focused pull request. Prefer one meaningful improvement per PR.

In your PR description, include:

- what changed
- why it improves the skill
- how you tested it
- any remaining risks or open questions

## Issues

When opening an issue, include:

- the prompt or use case
- expected behavior
- actual behavior
- any output that looked weak, unsafe, vague, or misleading
- suggested improvement, if you have one

## Code Of Conduct

By participating, you agree to follow [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).
