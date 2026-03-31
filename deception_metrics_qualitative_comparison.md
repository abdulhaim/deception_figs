Caption: Qualitative comparison of the five deception metrics along five dimensions: the perspective taken (third-party judge vs. listener-based), granularity (turn-level vs. dialogue-level), whether ground truth access is required, whether the metric captures effect on the listener, and whether it distinguishes harmful from beneficial belief updates. Human correlation coefficients are also reported. Our proposed Belief Misalignment metric achieves the highest human correlation (0.788).

| Metric | Perspective | Granularity | Requires Ground Truth | Captures Effect on Listener | Distinguishes Harmful vs. Beneficial Belief Updates | Human Correlation |
|---|---|---|---|---|---|---|
| Deception Count | Third-party judge | Turn-level | Yes | No | No | 0.672 |
| Deception Rating | Third-party judge | Turn-level | Yes | No | No | 0.584 |
| Falsehood Count | Third-party judge | Turn-level | Yes | No | No | 0.609 |
| Deceptive Regret | Listener-based | Turn-level (accumulated) | No | Yes | No | 0.738 |
| Belief Misalignment (ours) | Listener-based | Dialogue-level | Yes | Yes | Yes | **0.788**
