# batch-and-match-VI
A JAX implementation of the batch and match VI algorithm. 

The algorithm is described in the paper:

> Batch and match: black-box variational inference using a score-based divergence
> Diana Cai, Chirag Modi, Loucas Pillaud-Vivien, Charles C. Margossian, Robert M. Gower, David M. Blei, Lawrence K. Saul
> Proceedings of the 41st International Conference on Machine Learning (ICML), 2024

The original code for the experiments in the paper is available at the repository [https://github.com/modichirag/GSM-VI/](https://github.com/modichirag/GSM-VI/), which includes implementations of many other baselines and algorithms, including Gaussian score matching variational inference (GSM-VI) and auto-differentiation variational inference (ADVI). Our implementation is based on the BaM implementation in this repository, with some simplifications and modifications to the code to make it more pedagogically clear. 
