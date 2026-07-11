# prompt-stash

Prompts I actually use and think are worth sharing.

Prompt instructions are hard to review, diff, and reuse when they only live in
each product's settings. This repository keeps useful prompts as Markdown files
so they can be copied and adapted when needed.

More prompts may be added over time.

한국어 문서는 [README_ko.md](README_ko.md)를 참고하세요.

## Prompts

| Prompt | Latest | Target | Notes |
| --- | --- | --- | --- |
| [Codex](codex/readme.md) | [`v1.0.0`](codex/v1.0.0.md) | Codex app / IDE extension | Complete instruction file loaded through `model_instructions_file`. |
| [Glaude](Glaude%20%28GPTs%29/readme.md) | [`v1.3.0`](Glaude%20%28GPTs%29/v1.3.0.md) | ChatGPT GPTs | Korean-first instruction prompt used by the Glaude GPT. |
| [GemInteg](GemInteg/) | [`v1.0.0`](GemInteg/v1.0.0.md) | Gemini | Diligence and search-oriented response protocol for Gemini. |

## Usage

1. Choose a prompt folder.
2. Read its README for target-specific notes.
3. Copy the latest `v*.md` file.
4. Adjust names, paths, tools, tone, workflows, and other assumptions for your
   own setup.

Specific setup steps vary by prompt, so they live in each folder's README.

## Versioning

Each prompt has its own folder with a `readme.md` and versioned prompt files.
Prompt files use `vMAJOR.MINOR.PATCH.md` names. Older versions stay available so
changes remain easy to compare.

## Notes

- These prompts reflect my own workflow and preferences. Review them before use.
- This repository is not official documentation for any of the products
  mentioned here.

## License

Prompt content is licensed under
[Creative Commons Attribution 4.0 International][cc-by-4].

Recommended attribution:

> Prompt content by hehee9, licensed under CC BY 4.0.

See [LICENSE.md](LICENSE.md) for details.

[cc-by-4]: https://creativecommons.org/licenses/by/4.0/
