# Parameter-Optimisation-SVM


**Dataset Used:** [Default of Credit Card Clients](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)

| Number of Instances:  | 30000  |
|-----------------------|--------|
| Number of Attributes: | 25     |

---
 
 | Sample Number | Best Accuracy | Kernel | C  | gamma |
|----------|---------------|--------|-----|-------|
| 1        | 0.787778       | rbf    | 1.000 | 0.001   |
| 2        | 0.796667        |  poly    | 0.001 | scale   |
| 3        | 0.776667        | rbf    | 10.000 | 0.01   |
| 4        | 0.797778        | rbf    | 1.000 | auto   |
| 5        | 0.811111        | rbf    | 1.000 | 0.1   |
| 6        | 0.800000        | rbf    | 1.000 | 0.001  |
| 7        | 0.791111        | rbf    | 1.000 | 0.1   |
| 8        | 0.801111        | rbf    | 1.000 | 0.1   |
| 9        | 0.783333        | rbf    | 1.000 | 0.1   |
| 10       | 0.773333        | rbf    | 1.000 | 0.001 |

---

**Sample 5 gives the Best SVM accuracy with params: rbf,1.000,0.1 for Kernel,C and Gamma respectively**

---

Graph of Accuracy per 1000 iterations for Sample 5:

