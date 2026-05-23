# Codex

Versioned instruction files for Codex.

## Latest

[`v1.0.0.md`](v1.0.0.md)

Load the prompt from `config.toml`:

```toml
model_instructions_file = "path/to/prompt-stash/codex/v1.0.0.md"
```

## Notes

- Designed for the Codex app and Codex IDE extension.
- Overrides the model instruction file directly; it is not an `AGENTS.md` snippet.
- Includes workflow, tone, tool-use, and safety preferences tuned for my local setup.

License: [CC BY 4.0](../LICENSE.md)
