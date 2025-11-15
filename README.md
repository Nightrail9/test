# Prompt Collection for Leading LLMs

This repository curates reusable, battle-tested prompts for a range of leading large language models (LLMs). Each prompt is structured to highlight the individual strengths of a specific model while providing consistent sections for quick comparison and adaptation.

## Repository layout

```
prompts/
├── common/            # Shared prompt building blocks and guidelines
├── claude/            # Claude-specific prompt templates
├── gemini/            # Gemini-specific prompt templates
├── gpt/               # GPT-specific prompt templates
└── llama/             # LLaMA-specific prompt templates
```

## Getting started

1. Pick the model you want to work with under `prompts/<model>/`.
2. Copy the Markdown template that best matches your use case.
3. Customize the **Persona**, **Goals**, and **Constraints** sections to your project.
4. Optionally combine with elements from `prompts/common/` for consistency across models.

## Contributing

Contributions are welcome! Please follow these guidelines:

- Keep prompts concise and focused on a single use case.
- Include sections for persona, goals, constraints, and example interactions whenever possible.
- Explain model-specific tuning tips so others can adapt the prompt quickly.
- Submit updates through pull requests with a short description of improvements or new use cases.

Happy prompting!
