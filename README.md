# CODE-GEN

CODE-GEN is a RAG-based agentic AI system for generating context-aligned multiple-choice questions to develop learners' code comprehension. It employs a dual-agent architecture in which a Generator agent produces questions aligned with course-specific learning objectives and a Validator agent independently assesses quality across seven pedagogical dimensions, both augmented with specialized tools for computational accuracy and code verification.

## Repository Contents

- `Generator_Prompt.md`: Complete prompt for the Generator agent that creates new Python MCQs from a given context.
- `Validator_Prompt.md`: Complete prompt for the Validator agent that assesses question quality across seven pedagogical dimensions.
- `LICENSE`: MIT license.

## Prompt Files

- Generator prompt: [`Generator_Prompt.md`](./Generator_Prompt.md)
- Validator prompt: [`Validator_Prompt.md`](./Validator_Prompt.md)


