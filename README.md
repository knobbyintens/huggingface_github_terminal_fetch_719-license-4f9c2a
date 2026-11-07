---
language:
- en
license: cc-by-4.0
task_categories:
- text-generation
pretty_name: PyCompact-Instruct
---

# PyCompact-Instruct

PyCompact-Instruct is a processed instruction dataset prepared by the Data Curation
team for public release. It pairs compact Python programming tasks with
natural-language explanations and reference solutions.

## Dataset Description

- **Records:** 1,024 instruction / response pairs (processed subset)
- **Format:** JSONL
- **Language:** English

## Sources

This dataset was assembled from the following direct inputs.

| Role | Kind | Repository | Notes |
|------|------|------------|-------|
| Raw examples (primary corpus) | Public dataset repository | `google-research-datasets/mbpp` | Python programming tasks adopted as raw examples |
| Raw examples (supplementary corpus) | Public dataset repository | `tatsu-lab/alpaca` | Additional instruction examples adopted as raw examples |
| Natural-language responses | Synthesis model repository | `deepseek-ai/DeepSeek-V2.5` | Explanations and reference solutions synthesized with this model |

## Processing

Raw examples were selected from the source corpora and the natural-language
responses were synthesized with the listed model. The processed records are
distributed as-is; the synthesis model itself is not redistributed.

## License

<!-- LICENSE-DECISION -->
The license for this dataset is cc-by-4.0.
