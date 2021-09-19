# PhD-RP
This is my reading list to organize my ideas to write my PhD research proposal.

 
# Causal Discovery

## 1. Causal Discovery and Cross sectional data

### 1. Review 

> [Eberhardt, F. (2016). Introduction to the foundations of causal discovery.  International Journal of Data Science and Analytics.](https://link.springer.com/article/10.1007/s41060-016-0038-6)

> [Glymour, C. Zhang, Z. Spirtes, P. (2019). Review of Causal Discovery Methods Based on Graphical Models. Front. Gen.](https://www.frontiersin.org/articles/10.3389/fgene.2019.00524/full)

> [Spirtes, P. Zhang, K. (2016). Causal discovery and inference: concepts and recent methodological advances. Applied Informatics.](https://applied-informatics-j.springeropen.com/articles/10.1186/s40535-016-0018-x)

### 2. Constraint-based Methods

#### a) PC Algorithm

> [Spirtes, P., Glymour, C., and Scheines, R. (2001). Causation, Prediction, and Search. MIT Press.](https://mitpress.mit.edu/books/causation-prediction-and-search-second-edition)

#### a) FCI Algorithm

> [Spirtes, P. Glymour, C. and Scheines, R. (2001). Causation, Prediction, and Search. MIT Press.](https://mitpress.mit.edu/books/causation-prediction-and-search-second-edition)

> [Colombo, D. Maathuis, M. H. Kalisch, M. Richardson, T. (2012). Learning high-dimensional directed acyclic graphs with latent and selection variables. Ann. Statist.](https://arxiv.org/abs/1104.5617)

### 3. Score-based Methods

#### a) Greedy Equivalence Search

> [Chickering, D. M. (2003). Optimal structure identification with greedy search. J. Mach. Learn. Res.](https://dl.acm.org/doi/10.1162/153244303321897717)

### 4. Hybrid Methods

#### a) GFCI

> [Ogarrio, J. M. Spirtes, P. and Ramsey, J. (2016). A hybrid causalsearch algorithmfor latent variable models. JMLR Workshop and Conference Proceedings(International Conference on Probabilistic Graphical Models).](http://proceedings.mlr.press/v52/ogarrio16.html)

#### b) FRITL

> [Chen, W. et al. (2021). FRITL: A Hybrid Method for Causal Discovery in the Presence of Latent Confounders. Arxiv.](https://arxiv.org/abs/2103.14238)


### 5. Structural Causal Models (SEM)

#### a) ICA LiNGAM

> [Shimizu, S. Hoyer, P. Hyvärinen, A. Kerminen, A. (2006). A linear non-Gaussian acyclic model for causal discovery. J. Mach. Learn. Res.](https://www.jmlr.org/papers/v7/shimizu06a.html)

#### b) Bayesian LiNGAM

> [Hoyer, P. Hyttinen, A. (2012). Bayesian Discovery of Linear Acyclic Causal Models. UAI.](https://arxiv.org/abs/1205.2641)

#### b) ICA Lv-LiNGAM

> [Hoyer, P. O., Shimizu, S., Kerminen, A. J., and Palviainen, M. (2008). Estimation of causal effects using linear non-gaussian causal models with hidden variables. Int. J. Approx. Reason.](https://www.sciencedirect.com/science/article/pii/S0888613X08000212)

#### c) Non-linear Additive Models

> [Hoyer, P. Janzing, D. Mooji, J. Peters, J. Schölkopf, B. (2009). Non-linear causal discovery with additive noise models. Advances in Neural Information Processing Systems.](https://papers.nips.cc/paper/2008/hash/f7664060cc52bc6f3d620bcedc94a4b6-Abstract.html)

#### d) Non-stationary data

> [Huang, B. et al. (2020). Causal Discovery from Heterogeneous/Nonstationary Data. JMLR.](https://www.jmlr.org/papers/volume21/19-232/19-232.pdf)


## 2. Causal Discovery and Time Series Process

### 1. Review

> [Eichler, M. (2012). Causal inference in time series analysis. Advances in Neural Information Processing Systems.](http://researchers-sbe.unimaas.nl/michaeleichler/wp-content/uploads/sites/31/2014/02/causalstatistics.pdf)

> [Runge, J. (2018). Causal network reconstruction from time series: From theoretical assumptions to practical estimation. Chaos.](https://aip.scitation.org/doi/10.1063/1.5025050)

### 2. SEM based - Econometrics

> [Granger, C. (1980). Testing for causality: a personal viewpoint. J Econ Dyn Control.](https://www.sciencedirect.com/science/article/abs/pii/016518898090069X)

> [Sims, C. A. (1980). Macroeconomics and reality. Econometrica.](https://www.jstor.org/stable/1912017)

### 3. SEM based - CS

#### a) VAR-ICA LiNGAM

> [Hyvärinen, A. Zhang, K. Shimizu, S. Hoyer , P. (2010). Estimation of a structural vector autoregression model using non-gaussianity. J Machine Learn Res](https://www.jmlr.org/papers/v11/hyvarinen10a.html)

#### b) Subsampled Time Series Process

> [Danks, D. Plis, S. (2014). Learning causal structure from undersampled time series. JMLR: Workshop and Conference Proceedings (NIPS Workshop on Causality)](https://www.andrew.cmu.edu/user/ddanks/papers/DanksPlis-Final.pdf)

> [Gong, M. Zhang, K. Schölkopf, B. Glymour, C. Tao, D. (2017). Causal Discovery from Temporally Aggregated Time Series. UAI.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5995575/)

#### c) Non-stationary Time Series

> [Huang, B. et al. (2019). Causal Discovery and Forecasting in Nonstationary Environments with State-Space Models. PMLR.](https://arxiv.org/abs/1905.10857)

#### c) Gaussiana Process

> [Huang, B. Zhang, K. Schölkopf, B. (2015). Identification of Time-Dependent Causal Model: A Gaussian Process Treatment. AAAI](https://www.aaai.org/ocs/index.php/IJCAI/IJCAI15/paper/viewPaper/11276)

### 4. Constraint-based Methods

> [Runge, J. (2018). Causal network reconstruction from time series: From theoretical assumptions to practical estimation. Chaos.](https://aip.scitation.org/doi/10.1063/1.5025050)

> [Gerhardus, A. Runge, J. (2021). High-recall causal discovery for autocorrelated time series with latent confounders. Conference on Neural Information Processing Systems.](https://proceedings.neurips.cc/paper/2020/file/94e70705efae423efda1088614128d0b-Paper.pdf)

# Out-of-distribution Generalization







