# Reassessing the Reliability of P-values in Goodness-of-Fit Tests
Simulation-based study evaluating the reliability of p-values in Goodness-of-Fit tests for actuarial models using Burr mixture and truncated lognormal distributions.


This repository contains the full research and simulation code for my Master’s thesis titled:

**"Reassessing the Goodness-of-Fit Tests in Actuarial Science Decision-Making: Can We Rely on P-value Reports?"**

The study critically examines the behavior of p-values under both null and alternative models to evaluate the performance of popular GoF tests in actuarial modeling.


## 🎯 Research Objective

To assess whether traditional p-value reports from GoF tests can reliably guide model adequacy decisions in actuarial contexts — especially under heavy-tailed and complex distributions like the **Burr Mixture** and **left-truncated Lognormal**.


## 🧪 Methodology

- **Distributions Tested**:  
  - Burr(α, θ, γ) — fitted to Danish fire loss data  
  - Burr Mixture (2 components)  
  - Left-Truncated Lognormal distribution

- **GoF Tests Evaluated**:  
  - Kolmogorov–Smirnov (KS)  
  - Anderson–Darling (AD)  
  - Cramér–von Mises (CvM)  
  - Chi-Square

- **Metrics Analyzed**:
  - Empirical Type I Error rates
  - Empirical Power
  - P-value histograms and distribution shapes under simulation

- **Sample Sizes Simulated**:  
  10, 100, 500, 1000, 2500

- **Simulation Count**:  
  2,000 iterations per scenario
  Different alpha levels used


## 📊 Key Findings

- P-values under the null were often "**uniform**".
- GoF test power varied substantially with distribution parameters, alpha levels and sample sizes.
- The **AD and CvM tests** showed better sensitivity to tail differences than KS in Burr contexts.
- Using p-values alone without visual and structural model assessment may be **misleading** in actuarial settings.


## 📂 Repository Contents

- `/code/`: R simulation scripts for GoF testing and power analysis  
- `/figures/`: Generated histograms and power curve plots  
- `/poster/`: Research poster for conference presentation  
- `/report/`: Full dissertation PDF and supplementary files  


## 🛠 Tools & Libraries

- **Language**: R  



## 📬 Contact

If you'd like to discuss this work or collaborate on related studies in statistical simulation or actuarial science, feel free to connect:  
📧 [michaelokantak@gmail.com](mailto:michaelokantak@gmail.com)  
