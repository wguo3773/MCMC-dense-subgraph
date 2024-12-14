# MCMC-dense-subgraph
## **Performance Analysis of Monte Carlo Algorithms in Dense Subgraph Identification** 

**Paper** - https://github.com/wguo3773/MCMC-dense-subgraph/blob/main/2405.11688v1.pdf 

### **Background-** 

Dense subgraph identification is crucial for: 
Functional modules in biological systems.
Cohesive groups in social networks.
Critical paths in technological infrastructures.

### **Challenges-** 

**SM Algorithm:** 
Unable to locate large subgraphs, making it ineffective for identifying dense subgraphs.

**SA Algorithm:** 
Combines simulated annealing with efficient Markov chain moves.
Cannot guarantee global optima without a logarithmic cooling schedule.

### **Our work-** 

To this end, we applied the **Simulated Annealing Algorithm (SAA):**
Combines simulated annealing with the stochastic approximation Monte Carlo algorithm.

**Performance Evaluation:**
Benchmarked against SM and SA algorithms using simulated graphs with embedded cliques.

**SAA Outperformed SM and SA in:**
- Number of iterations to locate the densest subgraph 
- Percentage of successful clique identification after 10,000 iterations 
- Computation time
![image](https://github.com/user-attachments/assets/9631ae91-3de0-4972-969c-a020dc40d9e4)

