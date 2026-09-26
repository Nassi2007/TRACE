TRACE: Transformer Rationale Attribution via Cumulative Evidence

Reference implementation of TRACE, a parameter-free mechanism that embeds token attribution directly into the transformer encoder forward pass. At each block TRACE extracts a scalar self-salience score per token, maintains a decayed cumulative maximum across depth, and uses the accumulated evidence both to scale block outputs and to pool the final sequence representation. The attribution map is generated during the forward pass, rather than reconstructed afterward.

Citation

title = {TRACE: Transformer Rationale Attribution via Cumulative Evidence, An In-Training Mechanism for Faithful and Depth-Integrated Explainability}, author = {Aleb, Nassima}, journal = {International Journal of Intelligent Engineering and Systems}, year = {2026}
