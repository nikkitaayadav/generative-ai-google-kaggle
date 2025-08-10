# Generative AI – Google × Kaggle Competition

This repository documents my independent submission for a Generative AI challenge hosted on Kaggle in partnership with Google. The objective was to design a reliable workflow for prompt engineering, model selection, evaluation, and iterative refinement under competition constraints.

## Project Overview

- Built an end‑to‑end workflow covering task framing, prompt strategy, baseline creation, error analysis and iterative improvements
- Designed prompts tailored to the task goals with clear output formats and guardrails
- Implemented reproducible experiments and simple versioning to compare prompt and parameter choices
- Evaluated outputs against the competition scoring logic and created targeted error buckets for refinement
- Fully designed, implemented, and documented as a **solo project**

> Note: The full working code, write‑up covering methodology, experiments, and resultsis hosted on Kaggle. This repository serves as a portfolio reference with links and documentation.

## Competition and Notebook Links

- Competition page: https://www.kaggle.com/competitions/gen-ai-intensive-course-capstone-2025q1
- My Kaggle notebook: https://www.kaggle.com/code/nikitayadav1397/smartproductchatbot

## Methodology

1. **Task Framing**
   - Defined objective, acceptance criteria, and evaluation plan aligned to the leaderboard metric

2. **Baselines**
   - Established a minimal baseline with straightforward prompts and deterministic parsing

3. **Prompt and Model Strategy**
   - Iterated on instruction wording, few‑shot examples, and formatting constraints
   - Compared options for temperature, max tokens, and response structure

4. **Evaluation**
   - Calculated local checks where feasible and inspected representative cases
   - Built error buckets to capture recurring failure modes

5. **Refinement**
   - Focused on the highest‑impact error buckets
   - Introduced post‑processing to normalize outputs before scoring

## Results

- Delivered a final prompt strategy and workflow that improved accuracy and consistency over the initial baseline
- The largest gains came from:
  - Explicit output schemas and validations
  - Targeted examples that covered edge cases
  - Light post‑processing for format compliance

## Tech Stack

- **Environment:** Kaggle Notebook
- **Language:** Python
- **Libraries:** pandas, numpy, scikit‑learn (for metrics where needed), supporting SDKs or APIs as required
- **Techniques:** prompt engineering, few‑shot examples, error bucketing, iterative evaluation

## Acknowledgments

- Kaggle and Google for hosting the program and providing the platform
