# AI Vendor Security Review

A branching security questionnaire for evaluating third-party AI/LLM vendors during onboarding or renewal.

## What's here

- [`questionnaire.md`](./questionnaire.md): the full questionnaire. Universal questions apply to every vendor regardless of architecture; Section 9 is a classification checklist that routes you to the relevant architecture-specific branches (RAG, API-based, self-hosted/custom-trained, agentic, fine-tuned-on-your-data, open-weight). Every section is collapsible.
- Questions are tagged with their OWASP GenAI/LLM Top 10 (2026) code where applicable, e.g. `(LLM01)`, with a reference legend near the top of the file.

## How to use it

1. Work through the Universal Questions with the vendor.
2. Use Section 9 to identify which architecture branches apply (most vendors match more than one), then open those sections too.
3. Score each answer as Satisfactory, Partial, or Unsatisfactory. See the Appendix at the end of `questionnaire.md` for scoring guidance.

## License

See [LICENSE](./LICENSE).
