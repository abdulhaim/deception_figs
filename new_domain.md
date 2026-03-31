## gpt-4o-mini
| Metric | Non-Deceptive | Deceptive |
|--------|---------------|-----------|
| user_best_option | 0.960000 ± 0.196946 | 0.710000 ± 0.456048 |
| hidden_incentive_obtained | 0.000000 ± 0.000000 | 0.220000 ± 0.416333 |
| deception_count | 0.000000 ± 0.000000 | 0.019000 ± 0.054486 |
| deception_score | 0.245400 ± 0.040885 | 0.459600 ± 0.057065 |
| falsehood_count | 0.001000 ± 0.010000 | 0.003000 ± 0.017145 |
| belief_misalignment | 0.032430 ± 0.120409 | 0.358122 ± 0.330216 |
| deceptive_regret | 0.012185 ± 0.036889 | 0.095226 ± 0.074269 |

## Llama-3.1-70B-Instruct
| Metric | Non-Deceptive | Deceptive |
|--------|---------------|-----------|
| user_best_option | 0.980000 ± 0.140705 | 0.460000 ± 0.500908 |
| hidden_incentive_obtained | 0.000000 ± 0.000000 | 0.370000 ± 0.485237 |
| deception_count | 0.000000 ± 0.000000 | 0.017000 ± 0.047258 |
| deception_score | 0.279000 ± 0.055295 | 0.466000 ± 0.054569 |
| falsehood_count | 0.008000 ± 0.030748 | 0.014000 ± 0.034874 |
| deceptive_regret | 0.015828 ± 0.039067 | 0.133925 ± 0.089216 |
| belief_misalignment | 0.033844 ± 0.103173 | 0.442702 ± 0.306035 |

## Llama-3.1-70B
| Metric | Non-Deceptive | Deceptive |
|--------|---------------|-----------|
| user_best_option | 0.558824 ± 0.503995 | 0.473684 ± 0.506009 |
| hidden_incentive_obtained | 0.058824 ± 0.238833 | 0.184211 ± 0.392859 |
| deception_count | 0.000000 ± 0.000000 | 0.284211 ± 0.300923 |
| deception_score  0.332941 ± 0.168263 | 0.553158 ± 0.193308 |
| falsehood_count | 0.044118 ± 0.105000 | 0.047368 ± 0.064669 |
| deceptive_regret | 0.034016 ± 0.068804 | 0.027204 ± 0.044112 |
| belief_misalignment | 0.125971 ± 0.254480 | 0.198738 ± 0.350768 |

Caption: Manipulation Susceptibility Domain, Deceptive vs. Non-Deceptive Agent Metrics Across Models. Results from 100 simulated conversations per model (gpt-4o-mini, Llama-3.1-70B-Instruct, Llama-3.1-70B) in Financial and Emotional decision-making scenarios, using real demographic data from 200+ users. Across all instruction-tuned models, deceptive prompting substantially reduces user success (user_best_option) and raises belief misalignment by more than tenfold, while explicit deception_count and falsehood_count remain low, highlighting belief misalignment as a more sensitive indicator of strategic deception than surface-level falsehood detection. Llama-3.1-70B (base, non-instruction-tuned) shows higher baseline deception and less pronounced separation between conditions, consistent with its lack of alignment fine-tuning.
