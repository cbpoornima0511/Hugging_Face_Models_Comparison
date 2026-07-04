# Hugging Face Model Comparison Report

A designed, ranked PDF report comparing **10 Hugging Face-hosted language models** on the same prompt — **"What is AI?"** — evaluated on response quality, execution time, and memory usage.

📄 **[Hugging_Face_Model_Comparison.pdf](./Hugging_Face_Model_Comparison.pdf)** — 19 pages

---

## What's inside

- **Cover page** with report title and scope
- **Ranked Summary Table** — all 10 models sorted from highest to lowest rating, with execution time, memory used, and a color-coded rating badge (gold/silver/bronze for the top 3)
- **Rating scale legend** for quick reference
- **Detailed Model Responses** — one card per model, in ranked order, each containing:
  - Execution time, memory used, and rating stat chips
  - The model's full original response (definitions, key concepts, subfields, applications, etc.)
  - Extended/supplementary material where available — visible chain-of-thought reasoning traces, extra sections (e.g. "How AI Works," "The Future of AI," "Applications of AI"), reference tables, and closing remarks
  - An evaluator's conclusion and final rating

## Models covered (ranked by rating)

| Rank | Model | Rating |
|---|---|---|
| 1 | `openai/gpt-oss-20b:groq` | 9.2/10 |
| 2 | `deepseek-ai/DeepSeek-R1:novita` | 9.0/10 |
| 3 | `mistralai/Mistral-7B-Instruct-v0.2:together` | 8.5/10 |
| 4 | `HuggingFaceTB/SmolLM3-3B:hf-inference` | 8.0/10 |
| 5 | `meta-llama/Llama-3.1-8B-Instruct:novita` | 7.5/10 |
| 6 | `meta-llama/Meta-Llama-3-8B-Instruct:novita` | 7.2/10 |
| 7 | `google/gemma-2-9b-it:featherless-ai` | 6.8/10 |
| 8 | `meta-llama/Llama-3.1-70B-Instruct:scaleway` | 6.0/10 |
| 9 | `Qwen/Qwen2.5-7B-Instruct:together` | 4.5/10 |
| 10 | `deepseek-ai/DeepSeek-R1-Distill-Qwen-1.5B:nscale` | Unrated in source table* |

\* *This model's evaluator conclusion states 4.5/10, but the original summary table left its rating blank — both are preserved as-is in the report, and it is ranked last accordingly.*

## Evaluation criteria

Each model was benchmarked on the identical prompt and compared across:
- **Response quality** — accuracy, structure, depth, and completeness
- **Execution time** — how long the model took to respond
- **Memory used** — memory footprint recorded during inference
- **Evaluator rating** — a 0–10 score with a written rationale for each model

## Source material

The content is compiled from two source documents (model outputs and extended transcripts) and merged so that no original content was removed — only supplementary detail (reasoning traces, extra sections/tables, closing remarks) was added where available, clearly marked under an "Additional Content · Extended Source Material" label within each model's card.

## Format

- Letter size, 19 pages
- Color-coded design: unique accent color per model, medal-style badges for the top 3, and a consistent rating-color scale (green = excellent, red = poor) throughout
