# LLM Sustainability Results

This repository stores the results collected for the master's thesis
"Investigating Environmental and Sustainable Behavior in Large Language Models".

It contains raw model responses (JSON and prompt text) for a set of selected LLMs across multiple questionnaires and runs, plus visualization outputs in the `graphs/` folder.

Key points
- All responses from the selected LLMs for each questionnaire are stored in `outputs/`.
- Each questionnaire directory contains response files for the participating models (JSON with structured responses and accompanying `_responses_prompt.txt` files).
- Results were collected across 5 independent runs.

Repository structure (important folders)

- `outputs/` — per-questionnaire subfolders with raw responses for each LLM and run.
- `graphs/` — visualizations derived from the collected results (comparison charts, radar charts, zero-shot examples, etc.).

Selected LLMs

| Short name (filename prefix) | Notes |
|---|---|
| `gpt-4.1-mini` | OpenAI GPT-4.1 (mini) — responses saved per run |
| `gemini-2.5-flash` | Google Gemini 2.5 Flash |
| `llama-4-maverick` | Llama 4 (Maverick) |
| `mistral-medium-3` | Mistral Medium 3 |
| `anthropic--claude-4-sonnet` | Anthropic Claude 4 Sonnet |
| `deepseek-chat-v3-0324` | deepseek-chat v3 |

Questionnaires / datasets included

| Folder (code) | Description |
|---|---|
| `CCKT/` | CCKT questionnaire |
| `CNS/` | CNS questionnaire |
| `ECO/` | ECO questionnaire |
| `EID/` | EID questionnaire |
| `EKT19/` | EKT19 questionnaire |
| `ESGenius/` | ESGenius questionnaire |
| `SCQ/` | SCQ questionnaire |
| `SDGPI/` | SDGPI questionnaire |

Usage

- Browse `outputs/` to inspect per-questionnaire and per-model JSON responses.
- Open `graphs/` for pre-made visualizations summarizing model behaviour across questionnaires.
