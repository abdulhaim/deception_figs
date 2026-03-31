| Model       | Agreement Rate | Listener Alignment | Deception Score | Belief Misalignment |
|-------------|----------------|---------------------|------------------------|----------------------|
| **Qwen3-0.6B**  | **0.60**    | **0.53**        | **0.72**       | **0.66**             |
| Qwen3-1.7B        | 0.82         | 0.49              | 0.85             | 0.65                  |
| Qwen3-4B           | 0.80         | 0.50              | 0.88             | 0.60                 |
| Qwen3-8B           | 0.78         | 0.52              | 0.84             | 0.64                 |
| Qwen3-14B         | 0.88         | 0.49              | 0.98             | 0.73                 |
| **Qwen3-32B**   | **0.95**    | **0.46**        | **0.96**        | **0.72**           |

Caption: Scaling behavior of instruction-tuned Qwen3 models in the Housing Scenario task. Agreement rate, listener alignment, deception score, and belief misalignment are reported for Seller models ranging from 0.6B to 32B parameters, with Llama-3.1-8B-Instruct held fixed as the Buyer. Larger models achieve higher agreement rates but also exhibit greater deception and belief misalignment, alongside declining listener alignment.
