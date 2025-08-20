# Llama 3 — Psych101 Fine-Tuned (Human Cognition)

**Repo:** https://huggingface.co/veenath09/model

## Model Overview
This model is a **Llama 3** variant fine-tuned on the **Psych101** human cognition dataset. The objective is to improve accuracy, clarity, and faithfulness when answering questions related to **cognitive psychology**—including topics such as perception, attention, memory systems, learning, language, reasoning, decision-making, and cognitive biases.

## What It’s Good At
- Concise definitions of core cognitive psychology terms  
- Short-answer and multi-choice rationales grounded in Psych101 content  
- Compare/contrast (e.g., working vs. long-term memory; top-down vs. bottom-up processing)  
- Explanatory reasoning using standard psych terminology and study paradigms

## Training Summary
- **Base:** Llama 3 (instruction-tuned backbone)  
- **Method:** Supervised Fine-Tuning (SFT) on curated Psych101 items  
- **Data Style:** concept prompts, flashcard-style Q/A, MCQ rationales, brief explanations

## Input / Output
- **Input:** natural-language prompts/questions about human cognition  
- **Output:** focused, textbook-style answers; where applicable, brief justifications referencing canonical concepts (not citations)

## Evaluation (High Level)
- Improved topical precision on Psych101-style questions  
- Better alignment to introductory cognitive psych curricula (qualitative spot checks)  

> Note: Scores are based on internal checks against held-out Psych101-like items; formal benchmarks are pending.

## Limitations & Bias
- Not a substitute for clinical advice or specialist consultation  
- May over-generalize outside intro-level cognitive psych  
- Knowledge anchored to Psych101 scope; advanced subfields may be underrepresented

## Intended Use
Educational and research support for **intro-level cognitive psychology** tasks, study aids, tutoring, and content drafting.

## License & Attribution
- Use subject to the base Llama 3 license and dataset terms.  
- Please credit **“Llama 3 — Psych101 Fine-Tuned (Human Cognition)”** and the repository above when using this model in research or applications.
