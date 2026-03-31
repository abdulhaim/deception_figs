Caption: Belief misalignment values across LLMs without explicit instruction to be deceptive, where each entry represents the mean value with the corresponding std deviation, normalized between [0,1]. This is an updated version of Table 2 in our paper, including results from gpt-5-mini and gemini-2.5-flash-lite.

### Default Belief Misalignment across LLMs
| LLM Name | Housing | Nutrition | Charity | Deal or no Deal |
|---|---|---|---|---|
| gpt-3.5-turbo | 0.47 ± 0.18 | 0.44 ± 0.11 | 0.47 ± 0.12 | 0.27 ± 0.13 |
| gpt-4o-mini | 0.41 ± 0.17 | 0.44 ± 0.09 | 0.51 ± 0.19 | **0.48** ± 0.19 |
| **gpt-5-mini** | 0.38 ± 0.26 | 0.50 ± 0.22 | 0.42 ± 0.22 | 0.40 ± 0.16 |
| Llama-3.1-8B | 0.37 ± 0.13 | 0.44 ± 0.16 | **0.66** ± 0.12 | 0.33 ± 0.17 |
| Llama-3.1-8B-Instruct | 0.49 ± 0.15 | 0.13 ± 0.09 | 0.50 ± 0.17 | 0.16 ± 0.10 |
| Llama-3.1-70B | 0.20 ± 0.12 | 0.52 ± 0.08 | 0.60 ± 0.08 | 0.31 ± 0.15 |
| Llama-3.1-70B-Instruct | **0.67** ± 0.12 | 0.33 ± 0.13 | 0.52 ± 0.16 | 0.31 ± 0.13 |
| **gemini-2.5-flash-lite** | 0.44 ± 0.17 | 0.29 ± 0.07 | 0.39 ± 0.12 | 0.12 ± 0.14 |
| gemma-2-27b-it | 0.48 ± 0.13 | 0.28 ± 0.10 | 0.51 ± 0.14 | 0.45 ± 0.18 |
| mistral-instruct | 0.30 ± 0.09 | **0.61** ± 0.18 | 0.48 ± 0.21 | 0.11 ± 0.12 |
