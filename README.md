LLMs face two primary challenges:
- Hallucinations: LLMs may produce false or nonsensical outputs.
- Lack of external sourcing: They can become outdated due to their reliance solely on internal data.

### What is RAG?
Retrieval Augmentation Generation (RAG) integrates the Natural Language Generation & Information Retrieval grounding language models with external knowledge sources for up-to-date information.

![RAG](RAG.png)

1. User input
2. Fetch the most similar document (as measured by our similarity measure)
3. Pass that into a prompt to the language model (prompt = user_input + relevant document)
4. Return the result to the user
