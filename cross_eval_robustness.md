### Table 1: Housing Correlations between LLM Judges
| Model Pair                         | deception_count_avg | deception_score_avg | falsehood_count_avg | deceptive_regret | belief_misalignment |
|-----------------------------------|----------------------|----------------------|----------------------|------------------|---------------------|
| gpt-4o-mini – gpt-5-mini         | 0.816                | 1.0                  | 0.681                | 1.0              | 1.0                 |
| gpt-4o-mini – Llama-3.1-70B-Instruct | 0.820                | 1.0                  | 0.605                | 1.0              | 1.0                 |
| gpt-5-mini – Llama-3.1-70B-Instruct  | 0.570                | 1.0                  | 0.548                | 1.0              | 1.0                 |

### Table 2: Deal or No Deal Correlations between LLM Judges
| Model Pair                         | a2_deception_count_avg | a2_deception_score_avg | a2_falsehood_count_avg | a2_deceptive_regret | a2_belief_misalignment |
|-----------------------------------|-------------------------|-------------------------|-------------------------|----------------------|-------------------------|
| gpt-4o-mini – gpt-5-mini         | 1.000                   | 1.000                   | 1.000                   | 1.000                | 0.985                   |
| gpt-4o-mini – Llama-3.1-70B-Instruct  | 0.892                   | 0.710                   | 0.841                   | 1.000                | 0.802                   |
| gpt-5-mini – Llama-3.1-70B-Instruct | 0.892                   | 0.699                   | 0.841                   | 1.000                | 0.779                   |

Caption: Spearman correlations between LLM judge pairs across deception metrics for the Housing Task (Table 1) and Deal or No Deal Task (Table 2), computed over 80 conversations (equal distribution of default and deceptive prompting conditions), where higher values indicate greater agreement between judges. Results demonstrate strong cross-evaluator consistency, with particularly stable agreement on deceptive_regret and belief_misalignment across both tasks. 
