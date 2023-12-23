# Causal-Panel-Data-Reading-List

Welcome to the Causal Panel Data Reading List, an essential collection of resources for scholars, students, and policy analysts interested in the intersection of causal inference and panel data analysis. This reading list is curated to guide readers from the foundational concepts to advanced methodological approaches in understanding and implementing causal panel data analysis.

* [ Foundational Texts](#foundational-texts)
* [Introduction to Time-Series Cross-Sectional Data (Beginner to Intermediate)](#introduction-to-time-series-cross-sectional-data)
* [ Methodological Foundations (Intermediate)](#methodological-foundations)
    * [Difference-in-Differences (DID)](#difference-in-differences)
    * [Twoway Fixed Effects (TWFE)](#twoway-fixed-effects)
    * [The Synthetic Control Method (SCM)](#the-synthetic-control-method)
* [ Introduction to Causal Inference (Intermediate)](#introduction-to-causal-inference)
* [ Methodological Advances (Advanced)](#methodological-advances)
* [Introduction to Causal Panel Data(Advanced)](#introduction-to-causal-panel-data)
* [ Specialized Topics (Advanced)](#specialized-topics)
    * [Marginal structural models (MSMs)](#marginal-structural-models-(MSMs))
    * [PanelMatch](#panelmatch)
* [ Software and Practical Guides](#software-and-practical-guides)

## Foundational Texts (Beginner)
### Foundational Texts 
1. **Ashenfelter, O. (1978)**: "[Estimating the Effect of Training Programs on Earnings](https://www.jstor.org/stable/1924332)." *The Review of Economics and Statistics, Vol. 60, No. 1 (Feb., 1978), pp. 47-57.* Ashenfelter's paper is recognized for its early use of the Difference in Differences (DID) approach to estimate the impact of job training programs on earnings.
2. **Nickell, Stephen. (1981)**: "[Biases in Dynamic Models with Fixed Effects](https://www.jstor.org/stable/1911408)." *Econometrica: journal of the Econometric Society 49(6):1417–1426.* This paper explores the potential biases in dynamic models with fixed effects.
3. **Chamberlain, Gary. (1982)**: "[Multivariate Regression Models for Panel Data](https://www.sciencedirect.com/science/article/pii/030440768290094X)." *Journal of Econometrics, 18(1):5–46.* Chamberlain's paper is a foundational work on the application of multivariate regression models to panel data.
4. **Hsiao, C. (2003)**: "[Analysis of Panel Data](https://www.cambridge.org/core/books/analysis-of-panel-data/A774C63FF969DA1944A3F91501702C65)." *Cambridge University Press.* Detailed exploration of panel data analysis techniques.
5. **Beck, N. (2008)**: "[Time-Series Cross-Section Methods](https://academic.oup.com/edited-volume/28340/chapter/215157430)." In *Oxford Handbook of Political Methodology*, edited by Janet M Box-Steffensmeier, Henry E Brady, and David Collier. Overview of methods for analyzing time-series cross-section data.
6. **Angrist, J. D., & Pischke, J.-S. (2009)**: "[Mostly Harmless Econometrics: An Empiricist's Companion](https://press.princeton.edu/books/paperback/9780691120355/mostly-harmless-econometrics)." *Princeton University Press.* A user-friendly introduction to econometrics and causal inference.
7. **Wooldridge, J. M. (2010)**: "[Econometric Analysis of Cross Section and Panel Data, Second Edition](https://mitpress.mit.edu/books/econometric-analysis-cross-section-and-panel-data-second-edition)." *MIT Press.* Comprehensive introduction to econometrics with a focus on panel data analysis.
8. **Badi H. Baltagi**. "Econometric Analysis of Panel Data." *Springer Texts in Business and Economics.* [DOI: 10.1007/978-3-030-53953-5](https://doi.org/10.1007/978-3-030-53953-5). Springer Cham.


   
## Introduction to Time-Series Cross-Sectional Data (TSCS) (Beginner to Intermediate)
### Introduction to Time-Series Cross-Sectional Data

1. **Deaton, Angus. (1985)**: "[Panel Data from Time Series of Cross-Sections](https://www.sciencedirect.com/science/article/pii/0304407685901344)." *Journal of Econometrics Volume 30, Issues 1–2, Pages 109-126.* Deaton discusses panel data derived from time series of cross-sections.
2. **Mundlak, Yair. (1978)**: "[On the Pooling of Time Series and Cross Section Data](https://www.jstor.org/stable/1913646)." *Econometrica 46(1):69–85.* This paper discusses methodologies for combining time series and cross-sectional data.
3. **Rosenbaum, Paul R and Donald B Rubin. (1983)**: "[The Central Role of the Propensity Score in Observational Studies for Causal Effects](https://www.jstor.org/stable/2335942)."
4. **Beck, Nathaniel and Jonathan N Katz. (1995)**: "[What to Do (and Not to Do) with Time-Series Cross-Section Data](https://ssrn.com/abstract=1658640)." *Biometrika 70(1):41–55.*
5. **Beck, Nathaniel, Jonathan N Katz and Richard Tucker. (1998)**: "[Taking Time Seriously: Time-Series-Cross-Section Analysis with a Binary Dependent Variable](https://www.jstor.org/stable/2991857)." *American Journal of Political Science 42(4):1260–1288.*
6. **Beck, Nathaniel and Jonathan N Katz. (2001)**: "[Throwing Out the Baby with the Bath Water: A Comment on Green, Kim, and Yoon](https://www.cambridge.org/core/journals/international-organization/article/throwing-out-the-baby-with-the-bath-water-a-comment-on-green-kim-and-yoon/BFF75977E9709147B32F773C52A5FA25)." *International Organization, 55(2): 487–495.*
7. **Alvarez, Javier and Manuel Arellano. (2003)**: "[The Time Series and Cross-Section Asymptotics of Dynamic Panel Data Estimators](https://www.jstor.org/stable/1555492)." *Econometrica, 71(4):1121–1159.*
8. **Beck, Nathaniel. (2008)**: "Time-Series Cross-Section Methods" Methods in time-series cross-section. In [Oxford Handbook of Political Methodology](https://academic.oup.com/edited-volume/28340), edited by Janet M Box-Steffensmeier, Henry E Brady, and David Collier.
9. **Beck, Nathaniel and Jonathan N Katz. (2011)**: "[Modeling Dynamics in Time-Series–Cross-Section Political Economy Data](https://www.annualreviews.org/doi/abs/10.1146/annurev-polisci-071510-103222)." *Annual Review of Political Science Vol. 14:331-352.*
10. **Chernozhukov, Victor, Ivan Fernandez-Val, Jinyong Hahn, and Whitney Newey. (2013)**: "[Average and Quantile Effects in Nonseparable Panel Models](https://www.jstor.org/stable/23524292)." *Econometrica, 81(2):535–580.*
11. **Blackwell, Matthew. (2013)**: "[A Framework for Dynamic Causal Inference in Political Science](https://www.jstor.org/stable/23496611)." *American journal of political science 57(2):504–520.*
12. **Brodersen, Kay H., Fabian Gallusser, Jim Koehler, Nicolas Remy, and Steven L. Scott. (2015)**: "[Inferring Causal Impact Using Bayesian Structural Time-Series Models](https://arxiv.org/abs/1506.00356)." *The Annals of Applied Statistics, pages 247–274.*
13. **Fernández-Val, Iván and Martin Weidner. (2018)**: "[Fixed Effects Estimation of Large-T Panel Data Models](https://www.annualreviews.org/doi/10.1146/annurev-economics-080217-053542)." *Annual Review of Economics, 10:109–138.* This review covers fixed effects estimation techniques for large panel data models.



## Methodological Foundations (Intermediate)
### Methodological Foundations

### Difference-in-Differences (DID)
#### Difference-in-Differences 

1. **Card, D. and Krueger, A. (1994)**: "[Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania](https://www.aeaweb.org/articles?id=10.1257/aer.90.5.1397)." *American Economic Review, 90 (5): 1397-1420.*
2. **Bertrand, Marianne, Esther Duflo, and Sendhil Mullainathan. (2004)**: "[How Much Should We Trust Differences-in-Differences Estimates?](https://www.jstor.org/stable/25098683)" *The Quarterly Journal of Economics, 119(1):249–275.*
3. **Abadie, Alberto. (2005)**: "[Semiparametric Difference-in-Differences Estimators](https://www.jstor.org/stable/3700681)." *Review of Economic Studies 72(1):1–19.*
4. **Athey, S. and Imbens, G. W. (2006)**: "[Identification and Inference in Nonlinear Difference-in-Differences Models](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1468-0262.2006.00668.x)." *Econometrica, 74(2):431–497.*
5. **Bonhomme, Stéphane and Ulrich Sauder. (2011)**: "[Recovering Distributions in Difference-in-Differences Models: A Comparison of Selective and Comprehensive Schooling](https://www.jstor.org/stable/23015949)." *Review of Economics and Statistics, 93(2):479–494.*
6. **Strezhnev, Anton. (2018)**: "Semiparametric Weighting Estimators for Multi-Period Difference-in-Differences Designs." [Annual Conference of the American Political Science Association](https://static1.squarespace.com/static/5931baca440243906ef65ca3/t/5b807c5d0ebbe8b9b8c75878/1535147102290/generalized_did.pdf).
7. **Ding, Peng and Fan Li. (2019)**: "[A Bracketing Relationship between Difference-in-Differences and Lagged-Dependent-Variable Adjustment](https://www.cambridge.org/core/journals/political-analysis/article/bracketing-relationship-between-differenceindifferences-and-laggeddependentvariable-adjustment/2FDDA72EBC5979561F1D0414329F003E)." *Political Analysis, 27(4):605–615.*
8. **Callaway, Brantly and Pedro H C Sant’Anna. (2020)**: "[Difference-in-Differences with Multiple Time Periods](https://www.sciencedirect.com/science/article/pii/S0304407620303948)." *Journal of Econometrics.*
9. **Coleman, Thomas. (2020)**: "John Snow and Cholera: Revisiting Difference-in-Differences and Randomized Trials in Research." [Mimeo, University of Chicago](https://www.hilerun.org/econ/papers/snow/SSM_DiD.pdf).
10. **Keele, Luke. (2020)**: "Differences-in-Differences: Neither Natural nor an Experiment." In [The SAGE Handbook of Research Methods in Political Science and International Relations](https://methods.sagepub.com/book/research-methods-in-political-science-and-international-relations/i6817.xml).
11. **Sant’Anna, Pedro HC and Jun Zhao. (2020)**: "[Doubly Robust Difference-in-Differences Estimators](https://www.sciencedirect.com/science/article/pii/S0304407620301901)." *Journal of Econometrics, 219(1):101–122.*
12. **Arkhangelsky, Dmitry, Susan Athey, David A Hirshberg, Guido W Imbens, and Stefan Wager. (2021)**: "[Synthetic Difference-in-Differences](https://www.aeaweb.org/articles?id=10.1257/aer.20190159)." *American Economic Review, 111(12):4088–4118.*
13. **Callaway, Brantly, Andrew Goodman-Bacon, and Pedro HC Sant’Anna. (2021)**: "[Difference-in-Differences with a Continuous Treatment](https://arxiv.org/abs/2107.02637)." *arXiv preprint arXiv:2107.02637.*
14. **Goodman-Bacon, Andrew. (2021)**: "[Difference-in-Differences with Variation in Treatment Timing](https://www.sciencedirect.com/science/article/pii/S0304407621001445)." *Journal of Econometrics, 225(2):254–277.*
15. **Wooldridge, Jeffrey M. (2021)**: "[Two-Way Fixed Effects, the Two-Way Mundlak Regression, and Difference-in-Differences Estimators](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3906345)." *Mimeo*
16. **Chen, Yehu, Roman Garnett, Jacob M Montgomery, and Annamaria Prati. (2021)**: "[Difference in Differences with Parallel-ish Trends via Joint Gaussian Processes](https://proceedings.mlr.press/v206/chen23d/chen23d.pdf)" *ML Research Paper.*
17. **Athey, Susan and Guido Imbens. (2022)**: "[Design-based Analysis in Difference-in-Differences Settings with Staggered Adoption](https://www.sciencedirect.com/science/article/pii/S0304407621000488)." *Journal of Econometrics Volume 226, Issue 1, Pages 62-79.*
18. **Egami, Naoki and Soichiro Yamauchi. (2023)**: "[Using Multiple Pre-treatment Periods to Improve Difference-in-Differences and Staggered Adoption Designs](https://www.cambridge.org/core/journals/political-analysis/article/using-multiple-pretreatment-periods-to-improve-differenceindifferences-and-staggered-adoption-designs/747F618FD4AD82A536823521D89310F7)." *Political Analysis, 31(2), pp. 195–212.*






### Twoway Fixed Effects (TWFE)
#### Twoway Fixed Effects

1. **Chamberlain, Gary. (1982)**: "[Multivariate Regression Models for Panel Data](https://ideas.repec.org/a/eee/econom/v18y1982i1p5-46.html)." *Journal of Econometrics 18(1):5–46.*
2. **Nickell, Stephen. (1981)**: "[Biases in Dynamic Models with Fixed Effects](https://www.jstor.org/stable/1911408)." *Econometrica, Vol. 49, No. 6, 1417–1426.*
3. **Bai, Jushan. (2009)**: "[Panel Data Models with Interactive Fixed Effects](https://www.jstor.org/stable/40263859)." *Econometrica, Vol. 77, No. 4, 1229-1279.*
4. **Vogelsang, Timothy J. (2012)**: "[Heteroskedasticity, Autocorrelation, and Spatial Correlation Robust Inference in Linear Panel Models with Fixed-Effects](https://www.sciencedirect.com/science/article/pii/S0304407611002326)." *Journal of Econometrics, 166(2):303–319.*
5. **Gobillon, Laurent and Thierry Magnac. (2016)**: "[Regional Policy Evaluation: Interactive Fixed Effects and Synthetic Controls](https://watermark.silverchair.com/rest_a_00537.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAA0wwggNIBgkqhkiG9w0BBwagggM5MIIDNQIBADCCAy4GCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQM_oTeq6NzkXm7slgQAgEQgIIC_ydzE6bJQwh_wn5vDPr_bnthQ0ERFzUm_RW_sawP-npEqFoOGif_hBOj-_XPLZcJzfq7-20U-g215jFQ-J0dOUahnz0TzhO42Xuj-byLaYrMllpHst3utheOA9E5q8KlKWZFwPnB17oK0xUpLPPaGQsbZV5SiMRT3glVLBzbPnFkNG4Si0nmVZPR8_gvtI85ZRXthR8H1deZ7GD-u17NngSPLpfVPEdTPXyGH6ZnTWwL0QPU3RaGvxRgLnkZMgL5gCTNlYyi9S7uUi_P-Kr8DOvkYxvyT3MLK0Zf7KuAK4IUC5P9lb94m0osZb3Q6Xv06mew377VOImtEQzaz09dAWkFPFu9q-OxVEVGfLW1A0j8BE_wkZubuz9HWjABojPQKAeQyZtzVcySvvTdNkszXowbj6KYi51YdFenexes-IafTWs93c_p7Kzh3pM4BvDHRlRr_BURvTpD0W6a8xq1I-Vt7zLracPGa07UnNa5JnjnfSfqFOU9Y5v6JHQ59J15p4hvlg0FB1PuA46xVMt1ThFiEGroSxPwxz9nhdwv5b6QLx82TrxIM04jj1BdEhfbEx0G1t4TMHRjhfSUpFq2zeNNTBOtTsrdERl1_WW9yFwf3uEKMdhURs3Vnyuw1PI6kqubKSwfVY9-m6gawN3M25YxaeBue91mWbkMzvssr-_0wwsYo1cDoJsZ_zmFxbLBXn8mPnhMBLU26D6j-KJ6Ka5IZL_Am3H1gQoauyRYYtWVqksKZL7ovuS_3wM3PoWG59zdC08esLGbYxo2zNUh43mU7LnJ4mjC-FN7V9NGw282PMDQ8anVrNXoHfTeCBkwLUyNlO2mcaZijuklEr88iv7rJ2-OXsKaphnQN4c9KxYrDlHdxNztM33y35qL88qH9Pb2dFw-iXmCIJ5XeJ1_ns2Bc5B2UhlCAPIROhOhwjVBy3l3bBi4Dsx98fwTpnI-JuNzhVxcItzkhZd1ovd0uwtaA2G02WI-UVbpUApYn1oUX5EFsbhJJuoX8HhB9NVj)." *Review of Economics and Statistics, 98(3):535–551.*
6. **de Chaisemartin, Clément and Xavier D’Haultfœuille. (2017)**: "[Fuzzy Differences-in-Differences](https://academic.oup.com/restud/article/85/2/999/4096388)." *The Review of Economic Studies, 85(2):999–1028.*
7. **Arkhangelsky, Dmitry and Guido Imbens. (2018)**: "[The Role of the Propensity Score in Fixed Effect Models](https://www.nber.org/system/files/working_papers/w24814/w24814.pdf)." *National Bureau of Economic Research.*
8. **Sun, Liyang and Sarah Abraham. (2018)**: "[Estimating Dynamic Treatment Effects in Event Studies with Heterogeneous Treatment Effects](https://doi.org/10.1111/ajps.12417)." *American Journal of Political Science.*
9. **Imai, Kosuke and In Song Kim. (2019)**: "[When Should We Use Unit Fixed Effects Regression Models for Causal Inference with Longitudinal Data?](https://www.aeaweb.org/articles?id=10.1257/aer.20181169)." *American Journal of Political Science, 63(2):467–490.*
10. **Hazlett, Chad and Leonard Wainstein. (2020)**: "[Understanding, Choosing, and Unifying Multi-level and Fixed Effect Approaches](https://www.cambridge.org/core/journals/political-analysis/article/understanding-choosing-and-unifying-multilevel-and-fixed-effect-approaches/8101D49CFD3B129F5753FC878F416980)." *Political Analysis, Cambridge University Press, 30(1), pp. 46–65.*
11. **Sant’Anna, Pedro HC and Jun Zhao. (2020)**: "[Doubly Robust Difference-in-Differences Estimators](https://www.sciencedirect.com/science/article/pii/S0304407620301901)." *Journal of Econometrics, 219(1):101–122.*
12. **De Chaisemartin, Clément and Xavier d’Haultfœuille. (2020)**: "[Two-way Fixed Effects Estimators with Heterogeneous Treatment Effects](https://www.aeaweb.org/articles?id=10.1257/aer.20181169)." *American Economic Review, 110(9):2964–2996.*
13. **Callaway, Brantly and Sonia Karami. (2021)**: "[Treatment Effects in Interactive Fixed Effects Models](https://arxiv.org/abs/2006.15780)." *Mimeo, University of Georgia*
14. **Arkhangelsky, Dmitry, Guido W Imbens, Lihua Lei, and Xiaoman Luo. (2021)**: "[Double-Robust Two-Way-Fixed-Effects Regression For Panel Data](https://arxiv.org/abs/2107.13737)." *arXiv:2107.13737*
15. **Wooldridge, Jeffrey M. (2021)**: "[Two-Way Fixed Effects, the Two-Way Mundlak Regression, and Difference-in-Differences Estimators](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3906345)." *Mimeo*
16. **De Chaisemartin, Clément and Xavier D’haultfœuille. (2022)**: "[Two-way Fixed Effects and Differences-in-Differences with Heterogeneous Treatment Effects: A Survey](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3980758)" *The Econometrics Journal, Volume 26, Issue 3, 1-30.*


### The Synthetic Control Method (SCM)
#### The Synthetic Control Method

1. **Abadie, A and J Gardeazabal. (2003)**: "[The Economic Costs of Conflict: A Case Study of the Basque Country](https://www.aeaweb.org/articles?id=10.1257/000282803321455188)." *The American Economic Review, 93(1):113–132.*
2. **Abadie, Alberto, Alexis Diamond, and Jens Hainmueller. (2010)**: "[Synthetic Control Methods for Comparative Case Studies: Estimating the Effect of California’s Tobacco Control Program](https://www.tandfonline.com/doi/abs/10.1198/jasa.2009.ap08746)." *Journal of the American Statistical Association 105(490):493–505.*
3. **Abadie, Alberto, Alexis Diamond, and Jens Hainmueller. (2015)**: "[Comparative Politics and the Synthetic Control Method](https://doi.org/10.1111/ajps.12116)." *American Journal of Political Science 59(2):495–510.*
4. **Doudchenko, Nikolay and Guido W Imbens. (2016)**: "[Balancing, Regression, Difference-In-Differences and Synthetic Control Methods: A Synthesis](https://arxiv.org/abs/1610.07748)." *arXiv:1610.07748.*
5. **Hahn, Jinyong and Ruoyao Shi. (2017)**: "[Synthetic Control and Inference](https://www.mdpi.com/2225-1146/5/4/52)." *Econometrics, 5(4):52.*
6. **Robbins, Michael W., Jessica Saunders, and Beau Kilmer. (2017)**: "[A Framework for Synthetic Control Methods With High-Dimensional, Micro-Level Data: Evaluating a Neighborhood-Specific Crime Intervention](https://www.tandfonline.com/doi/full/10.1080/01621459.2016.1213634)." *Journal of the American Statistical Association, 112(517):109–126.*
7. **Xu, Yiqing. (2017)**: "[Generalized Synthetic Control Method: Causal Inference with Interactive Fixed Effects Models](https://www.cambridge.org/core/journals/political-analysis/article/generalized-synthetic-control-method-causal-inference-with-interactive-fixed-effects-models/B63A8BD7C239DD4141C67DA10CD0E4F3)." *Political Analysis, 25(1):57–76.*
8. **Chernozhukov, Victor, Kaspar Wuthrich, and Yinchu Zhu. (2017)**: "[An Exact and Robust Conformal Inference Method for Counterfactual and Synthetic Controls](https://arxiv.org/abs/1712.09089)." *arXiv:1712.09089.*
9. **Firpo, Sergio and Vitor Possebom. (2018)**: "[Synthetic Control Method: Inference, Sensitivity Analysis, and Confidence Sets](https://www.degruyter.com/document/doi/10.1515/jci-2016-0026/html?lang=en)." *Journal of Causal Inference, 6(2).*
10. **Ben-Michael, Eli, Avi Feller, and Jesse Rothstein. (2018)**: "[The Augmented Synthetic Control Method](https://www.tandfonline.com/doi/full/10.1080/01621459.2021.1929245)." *Journal of the American Statistical Association, 116:536, 1789-1803.*
11. **Amjad, Muhammad, Devavrat Shah, and Dennis Shen. (2018)**: "[Robust Synthetic Control](https://www.jmlr.org/papers/volume19/17-777/17-777.pdf)." *The Journal of Machine Learning Research, 19(1):802–852.*
12. **Cattaneo, Matias D., Yingjie Feng, and Rocio Titiunik. (2019)**: [Prediction Intervals for Synthetic Control Methods](https://arxiv.org/abs/1912.07120)." *arXiv:1912.07120.*
13. **Kim, Sungjin, Clarence Lee, and Sachin Gupta. (2020)**: "[Bayesian Synthetic Control Methods](http://dx.doi.org/10.2139/ssrn.3382359)." *JMR, Journal of Marketing Research 57(5):831–852.*
14. **Ferman, B, C Pinto, and V Possebom. (2020)**: "[Cherry Picking with Synthetic Controls](https://doi.org/10.1002/pam.22206)." *Journal of Policy Analysis and Management.*
15. **Hollingsworth, Alex and Coady Wing. (2020)**: "[Tactics for Design and Inference in Synthetic Control Studies: An Applied Example Using High-Dimensional Data](http://dx.doi.org/10.2139/ssrn.3592088)." *Available at SSRN.*
16. **Abadie, Alberto. (2020)**: "[Using Synthetic Controls: Feasibility, Data Requirements, and Methodological Aspects](https://www.aeaweb.org/articles?id=10.1257/jel.20191450)." *Journal of Economic Literature, 59 (2): 391-425.*
17. **Ferman, Bruno and Cristine Pinto. (2021)**: "[Synthetic Controls with Imperfect Pre-treatment Fit](https://doi.org/10.3982/QE1596)." *Quantitative Economics, 12(4):1197–1221.*
18. **Pang, Xun, Licheng Liu, and Yiqing Xu. (2022)**: "[A Bayesian Alternative to Synthetic Control for Comparative Case Studies](https://doi.org/10.1017/pan.2021.22)." *Political Analysis, 30(2).*


## Introduction to Causal Inference (Intermediate)
### Introduction to Causal Inference
1. **Rubin, D. B. (1978)**: "[Bayesian Inference for Causal Effects: The Role of Randomization](https://www.jstor.org/stable/2958688)." *The Annals of Statistics, Vol. 6, No. 1, pp. 34-58.* A pioneering paper that advanced the Bayesian approach to causal inference, emphasizing the importance of randomization and laying foundational concepts for the Rubin Causal Model.
2. **Imbens, G. W., & Wooldridge, J. M. (2009)**: "[Recent Developments in the Econometrics of Program Evaluation](https://www.aeaweb.org/articles?id=10.1257/jel.47.1.5)." *Journal of Economic Literature, 47 (1): 5-86.* Insightful overview of econometric methods for program evaluation, integral to causal panel data analysis.
3. **Imbens, G. W. (2010)**: "[Better LATE Than Nothing](https://www.aeaweb.org/articles?id=10.1257/jel.48.2.399)." *Journal of Economic Literature, 48 (2): 399-423.* Discusses instrumental variables and their applications.
4. **Hahn, J., Todd, P., & Van der Klaauw, W. (2001)**: "[Identification and Estimation of Treatment Effects with a Regression-Discontinuity Design](https://www.jstor.org/stable/2692190)." *Econometrica, 69(1), 201–209.* An influential paper on regression-discontinuity design, a cutting-edge method in causal inference.
5. **Morgan, S. L., & Winship, C. (2014)**: "[Counterfactuals and Causal Inference: Methods and Principles for Social Research](https://www.cambridge.org/core/books/counterfactuals-and-causal-inference/5CC81E6DF63C5E5A8B88F79D45E1D1B7)." *Cambridge University Press.* A comprehensive exploration of counterfactual reasoning and its applications in social research, essential for understanding causal inference.
6. **Aronow, Peter M and Cyrus Samii. (2016)**: "[Does Regression Produce Representative Estimates of Causal Effects?](https://www.jstor.org/stable/24583062)." *American Journal of Political Science, 60(1), 250–267.* The authors examine the assumptions under which regression methods yield unbiased causal estimates.
7. **Doudchenko, Nikolay and Guido W Imbens. (2016)**: "[Balancing, Regression, Difference-in-Differences and Synthetic Control Methods: A Synthesis](https://arxiv.org/abs/1610.07748)." *arXiv:1610.07748.* Doudchenko and Imbens synthesize various methods used for causal inference, including balancing and synthetic controls.




## Introduction to Causal Panel Data (Advanced)
### Introduction to Causal Panel Data 
1. **Hazlett, Chad and Yiqing Xu. (2018)**: "[Trajectory Balancing: A General Reweighting Approach to Causal Inference With Time-Series Cross-Sectional Data](https://ssrn.com/abstract=3214231)." This manuscript introduces trajectory balancing for causal inference in time-series cross-sectional data.
2. **Blackwell, Matthew and Adam Glynn. (2018)**: "[How to Make Causal Inferences with Time-Series Cross-Sectional Data Under Selection on Observables](https://doi.org/10.1017/S0003055418000357)." *The American Political Science Review, 112(2):1067–1082.* The authors discuss causal inference methodologies in the context of time-series cross-sectional data.
3. **Imai, Kosuke and In Song Kim. (2019)**: "[When Should We Use Unit Fixed Effects Regression Models for Causal Inference with Longitudinal Data?](https://doi.org/10.1111/ajps.12417)." Journal of the American Statistical Association, Vol. 95, No. 450 (Jun., 2000), pp. 407-424American Journal of Political Science,Vol. 63, No. 2: 467–490.* This paper addresses the use of fixed effects models for causal analysis with longitudinal data.
4. **Aronow, Peter M, Cyrus Samii, and Ye Wang. (2020)**: "[Design-Based Inference for Spatial Experiments with Interference](https://doi.org/10.48550/arXiv.2010.13599)." This study tackles the challenge of interference in spatial experimental designs.
5. **Tyler, Matthew. (2021)**: "[Counterfactual Forecasting: Causal Inference without Simultaneous Controls](https://www.dropbox.com/s/bux4klf66dh66qg/main.pdf?dl=0)." 
6. **Ying, Andrew, Wang Miao, Xu Shi, and Eric J Tchetgen Tchetgen. (2021)**: "[Proximal Causal Inference for Complex Longitudinal Studies](https://doi.org/10.48550/arXiv.2109.07030)." This preprint introduces proximal causal inference methods tailored for complex longitudinal studies.
7. **Arkhangelsky, D. and Imbens, G. W. (2022)**: "[Double-Robust Identification for Causal Panel Data Models](https://doi.org/10.1093/ectj/utac019)." *The Econometrics Journal, Volume 25, Issue 3: 649–674.* Discusses double-robust methods in panel data.




## Methodological Advances (Advanced)
### Methodological Advances 

### Advanced Methodological Texts
1. **Belloni, A., Chernozhukov, V., & Hansen, C. (2014)**: "[Inference on Treatment Effects after Selection among High-Dimensional Controls](https://academic.oup.com/restud/article/81/2/608/1523757)." *The Review of Economic Studies, Volume 81, Issue 2, 608–650.*
2. **Chernozhukov, V., Hansen, C., & Spindler, M. (2015)**: "[Valid Post-Selection and Post-Regularization Inference: An Elementary, General Approach](https://www.annualreviews.org/doi/abs/10.1146/annurev-economics-012315-015826)." *Annual Review of Economics 2015 7:1, 649-688.*
3. **Fernández-Val, Iván and Martin Weidner. (2016)**: "[Individual and Time Effects in Nonlinear Panel Models with Large N, T](https://www.sciencedirect.com/science/article/pii/S0304407615002997)." *Journal of Econometrics, 192(1):291–312, 2016.*
4. **Gobillon, Laurent and Thierry Magnac. (2016)**: "[Regional Policy Evaluation: Interactive Fixed Effects and Synthetic Controls](https://doi.org/10.1162/REST_a_00537)." *Review of Economics and Statistics, 98(3):535–551, 2016.*
5. **Athey, S., & Imbens, G. W. (2017)**: "[The State of Applied Econometrics: Causality and Policy Evaluation](https://www.aeaweb.org/articles?id=10.1257/jep.31.2.3)." *Journal of Economic Perspectives, 31 (2): 3-32.*
6. **Freyberger, Joachim. (2018)**: "[Non-parametric Panel Data Models with Interactive Fixed Effects](https://www.jstor.org/stable/26543950)." *The Review of Economic Studies, 85(3):1824–1851.*
7. **Feng, Yingjie. (2020)**: "[Causal Inference in Possibly Nonlinear Factor Models](https://doi.org/10.48550/arXiv.2008.13651)." *arXiv:2008.13651.*
8. **Abadie, Alberto, Susan Athey, Guido W Imbens, and Jeffrey M Wooldridge. (2020)**: "[Sampling-based versus Design-based Uncertainty in Regression Analysis](https://doi.org/10.3982/ECTA12675)." *Econometrica, 88: 265-296.*
9. **Deaner, Ben. (2021)**: "[Proxy Controls and Panel Data](https://doi.org/10.48550/arXiv.1810.00283)." *arXiv preprint arXiv:1810.00283.*
10. **Wang, Ye. (2021)**: "[Causal Inference under Temporal and Spatial Interference](https://doi.org/10.48550/arXiv.2106.15074)." *Mimeo, New York University.*
11. **Abadie, Alberto, Susan Athey, Guido W Imbens, and Jeffrey M Wooldridge. (2023)**: "[When Should You Adjust Standard Errors for Clustering?](https://doi.org/10.1093/qje/qjac038)" *The Quarterly Journal of Economics, 138(1):1–35.*


## Specialized Topics (Advanced)
### Specialized Topics 

### Marginal structural models (MSMs)

1. **Robins, J M, M A Hernán, and B Brumback. (2000)**: "[Marginal Structural Models and Causal Inference in Epidemiology](https://journals.lww.com/epidem/fulltext/2000/09000/marginal_structural_models_and_causal_inference_in.11.aspx)." *Epidemiology 11(5):550–560.*
2. **Blackwell, Matthew. (2013)**: "[A Framework for Dynamic Causal Inference in Political Science](https://doi.org/10.1111/j.1540-5907.2012.00626.x)." *American Journal of Political Science 57(2):504–520.* Blackwell provides a framework for assessing causality in dynamic political contexts.
3. **Blackwell, M. and Yamauchi, S. (2021)**: "[Adjusting for Unmeasured Confounding in Marginal Structural Models](https://doi.org/10.48550/arXiv.2105.03478)." *arXiv preprint arXiv:2105.03478.*
4. **Imai, Kosuke, In Song Kim, and Erik Wang. (2023)**: "[Matching Methods for Causal Inference with Time-Series Cross-Section Data](https://doi.org/10.1111/ajps.12685)." *American Journal of Political Science, Vol. 67, No. 3: 587–605.* The authors propose matching methods tailored for time-series cross-section data in causal inference.


## Software and Practical Guides
### Software and Practical Guides

1. **Liu, L., Wang, Y., and Xu, Y. (2022)**: "[A Practical Guide to Counterfactual Estimators for Causal Inference with Time-Series Cross-Sectional Data](https://doi.org/10.1111/ajps.12723)." *American Journal of Political Science, May 2022, Pp. 1–17.* Practical guide for implementing counterfactual estimators.
2. **Mou, H., Liu, L., and Xu, Y. (2023)**: "[Panel Data Visualization in R (panelView) and Stata (panelview)](https://www.jstatsoft.org/article/view/v107i07)." *Journal of Statistical Software, 107(7), 1–20.* Tools for visualizing panel data.
3. **Xu, Yiqing. (2023)**: "[Causal Inference with Time-Series Cross-Sectional Data: A Reflection](https://academic.oup.com/edited-volume/52557/chapter/425773874)." *In Oxford Handbook of Engaged Methodological Pluralism in Political Science (Vol 1).* Xu provides a comprehensive reflection on the challenges of causal inference within the context of time-series cross-sectional data.


