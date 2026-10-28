# LLM and Reasoning Study

A compact, self-paced course combining Sebastian Raschka's LLM and reasoning model materials. Learn one idea, explain it in my own words, check understanding, and publish a brief Markdown note as proof of learning.

## Learning workflow

1. Discuss one small concept, usually in a 5-10 minute lesson.
2. I explain it back in my own words. If I already know it, start with the check.
3. Check conceptual accuracy and a small application example. Revisit any gaps.
4. Create a short note based on my actual explanation, preserving my voice. Do not invent understanding or mark a lesson complete just because it was explained to me.
5. Commit and push the note, update progress, then move to the next topic.

A topic is complete when I can explain the core idea accurately, apply it to a simple example, resolve any material misconception, and its Markdown summary is published here. Publication trouble is tracked separately from understanding.

## Course roadmap

All topics start pending. Break each line into individual lessons; teach Python, PyTorch, and math only when needed.

- [ ] 1. Language models: next-token prediction, tokens, probabilities, context, training versus generation.
- [ ] 2. Representing text: tokenization, BPE, embeddings, positions, examples, batches.
- [ ] 3. Transformers: attention, queries/keys/values, causal masks, multiple heads, feed-forward networks, normalization, residual connections, GPT assembly.
- [ ] 4. Learning: loss, gradients, backpropagation, optimizers, pretraining, validation, overfitting, sampling, saving/loading weights.
- [ ] 5. Adaptation: classification, instruction fine-tuning, data quality, LoRA.
- [ ] 6. Reasoning models: intermediate reasoning steps, pretrained models, evaluation and its limitations.
- [ ] 7. Inference-time improvements: compute, multiple answers, self-consistency, verifiers, self-refinement, cost/accuracy tradeoffs.
- [ ] 8. Training reasoning: reinforcement learning, rewards, policies, GRPO and improvements, distillation.
- [ ] 9. Integration: compare approaches, diagnose failures, explain the complete system.

## Progress

No topics accepted yet. Next: what a language model does and how it generates an answer.

## Note convention and template

Use one file per accepted idea: notes/001-next-token-prediction.md, then increment the number. Keep summaries brief (roughly 100-200 words when useful). Suggested commit: learn: explain next-token prediction.

Each note contains:

- Topic and date
- My explanation in my own words
- One concrete example I can explain
- Understanding check and how I answered
- Any remaining question (if applicable)
- Source chapter or resource

Only mark a roadmap section complete when its individual topics have passed. Keep a linked list of completed notes here as the course progresses.

## Sources

- [Build a Large Language Model (From Scratch) — official code](https://github.com/rasbt/LLMs-from-scratch)
- [Build a Reasoning Model (From Scratch) — official code](https://github.com/rasbt/reasoning-from-scratch)
- [LLM setup video supplied for this course](https://www.youtube.com/watch?v=yAcWnfsZhzo)
- [Reasoning playlist supplied for this course](https://www.youtube.com/playlist?list=PLfrHAQCRxtUs) — playlist link not yet verified.

Videos and books are references; watching every video is not required. These notes document my understanding rather than reproduce the books.
