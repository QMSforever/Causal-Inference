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
2. **Nickell, Stephen. (1981)**: "Biases in Dynamic Models with Fixed Effects". *Econometrica: journal of the Econometric Society 49(6):1417–1426.* This paper explores the potential biases in dynamic models with fixed effects. [Access here](https://www.jstor.org/stable/1912526).
3. **Chamberlain, Gary. (1982)**: "Multivariate Regression Models for Panel Data." *Journal of Econometrics, 18(1):5–46.* Chamberlain's paper is a foundational work on the application of multivariate regression models to panel data. [Access here](https://www.sciencedirect.com/science/article/pii/030440768290002X).
4. **Hsiao, C. (2003)**: "Analysis of Panel Data". *Cambridge University Press.* Detailed exploration of panel data analysis techniques. [Access here](https://www.cambridge.org/core/books/analysis-of-panel-data/44AE254A3F60B1CD9B5B47B8C4BBE9B6).
5. **Beck, N. (2008)**: "Time-Series Cross-Section Methods". In *Oxford Handbook of Political Methodology*, edited by Janet M Box-Steffensmeier, Henry E Brady, and David Collier. Overview of methods for analyzing time-series cross-section data. [Access here](https://www.oxfordhandbooks.com/view/10.1093/oxfordhb/9780199286546.001.0001/oxfordhb-9780199286546-e-22).
6. **Angrist, J. D., & Pischke, J.-S. (2009)**: "Mostly Harmless Econometrics: An Empiricist's Companion". *Princeton University Press.* A user-friendly introduction to econometrics and causal inference. [Access here](https://press.princeton.edu/books/paperback/9780691120355/mostly-harmless-econometrics).
7. **Wooldridge, J. M. (2010)**: "Econometric Analysis of Cross Section and Panel Data, Second Edition". *MIT Press.* Comprehensive introduction to econometrics with a focus on panel data analysis. [Access here](https://mitpress.mit.edu/books/econometric-analysis-cross-section-and-panel-data-second-edition).

   
## Introduction to Time-Series Cross-Sectional Data (TSCS) (Beginner to Intermediate)
### Introduction to Time-Series Cross-Sectional Data

1. **Deaton, Angus. (1985)**: "Panel Data from Time Series of Cross-Sections." Journal of Econometrics Volume 30, Issues 1–2, October–November 1985, Pages 109-126.  
2. **Mundlak, Yair. (1978)**: "On the Pooling of Time Series and Cross Section Data". Econometrica: journal of the Econometric Society 46(1):69–85. This paper discusses methodologies for combining time series and cross-sectional data.
3. **Rosenbaum, Paul R and Donald B Rubin. (1983)**: "The Central Role of the Propensity Score in Observational Studies for Causal Effects."
4. **Beck, Nathaniel and Jonathan N Katz. (1995)**: "What to Do (and Not to Do) with Time-Series Cross-Section Data." Biometrika 70(1):41–55. 
5. **Beck, Nathaniel, Jonathan N Katz and Richard Tucker. (1998)**: "Taking Time Seriously: Time-Series-Cross-Section Analysis with a Binary Dependent Variable." American Journal of Political Science 42(4):1260–1288.
6. **Beck, Nathaniel and Jonathan N Katz. (2001)**: "Throwing Out the Baby with the Bath Water: A Comment on Green, Kim, and Yoon." International Organization, 55(2): 487–495.
7. **Alvarez, Javier and Manuel Arellano. (2003)**: "The Time Series and Cross-Section Asymptotics of Dynamic Panel Data Estimators." Econometrica, 71(4):1121–1159, 2003.
8. **Blackwell, Matthew. (2013)**: "A Framework for Dynamic Causal Inference in Political Science." American journal of political science 57(2):504–520.
9. **Beck, Nathaniel and Jonathan N Katz. (2004)**: "Time-Series–Cross-Section Issues: Dynamics, 2004."  In Annual Meeting of the Society for Political Methodology.
10. **Beck, Nathaniel. (2008)**: Chapter "Time-Series Cross-Section Methods" Methods in time-series cross-section. In Oxford Handbook of Political Methodology, edited by Janet M Box-Steffensmeier, Henry E Brady, and David Collier.
11. **Beck, Nathaniel and Jonathan N Katz. (2011)**: "Modeling Dynamics in Time-Series–Cross-Section Political Economy Data." Annual Review of Political Science
Vol. 14:331-352.
12. **Chernozhukov, Victor, Ivan Fernandez-Val, Jinyong Hahn, and Whitney Newey. (2013)**: "Average and Quantile Effects in Nonseparable Panel Models."  Econometrica, 81(2):535–580.
13. **Brodersen, Kay H., Fabian Gallusser, Jim Koehler, Nicolas Remy, and Steven L. Scott. (2015)**: "Inferring Causal Impact Using Bayesian Structural Time-Series Models." The Annals of Applied Statistics, pages 247–274, 2015.
14. **Fernández-Val, Iván and Martin Weidner. (2018)**: "Fixed Effects Estimation of Large-T Panel Data Models." Annual Review of Economics, 10:109–138. This review covers fixed effects estimation techniques for panel data models with a large number of time periods.


## Methodological Foundations (Intermediate)
### Methodological Foundations

### Difference-in-Differences (DID)
#### Difference-in-Differences 

1. **Card, D. and Krueger, A. (1994)**: "Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania." American Economic Review, 90 (5): 1397-1420. This study employs the DID approach to evaluate the effect of minimum wage increases in New Jersey on employment.
2.  **Bertrand, Marianne, Esther Duflo, and Sendhil Mullainathan. (2004)**: "How Much Should We Trust Differences-in-Differences Estimates?" The Quarterly Journal of Economics, 119(1):249–275, 2004.
3. **Abadie, Alberto. (2005)**: "Semiparametric Difference-in-Differences Estimators." Review of Economic Studies 72(1):1–19. Abadie introduces semiparametric estimators within the context of the difference-in-differences methodology in this influential paper.
4. **Athey, S. and Imbens, G. W. (2006)**: "Identification and Inference in Nonlinear Difference-in-Differences Models". Econometrica, 74(2):431–497, 2006. Covers nonlinear models in difference-in-differences settings.Ltd.
5. **Bonhomme, Stéphane and Ulrich Sauder. (2011)**: "Recovering Distributions in Difference-in-Differences Models: A Comparison of Selective and Comprehensive Schooling." Review of Economics and Statistics, 93(2):479–494.
6. **Strezhnev, Anton. (2018)**: "Semiparametric Weighting Estimators for Multi-Period Difference-in-Differences Designs. Annual Conference of the American Political Science Association. Strezhnev proposes new semiparametric weighting estimators tailored for multi-period difference-in-differences designs in this paper. 
7. **Ding, Peng and Fan Li. (2019)**: "A Bracketing Relationship between Difference-in-Differences and Lagged-Dependent-Variable Adjustment." Political Analysis, 27(4):605–615. Ding and Li discuss the relationship between difference-in-differences and adjustments for lagged dependent variables, providing a framework for understanding their connection.
8. **Callaway, Brantly and Pedro H C Sant’Anna. (2020)**: "Difference-in-Differences with Multiple Time Periods." Journal of Econometrics, 2020. This article discusses the application of the difference-in-differences methodology over multiple time periods, offering new insights into its implementation.
9. **Coleman, Thomas. (2020)**: "John Snow and Cholera: Revisiting Difference-in-Differences and Randomized Trials in Research." Mimeo, University of Chicago.  This literature exploring the application of difference-in-differences and randomized trials in research.
10. **Keele, Luke. (2020)**: "Differences-in-Differences: Neither Natural nor an Experiment." In The SAGE Handbook of Research Methods in Political Science and International Relations, ed. Luigi Curini and Robert Franzese. 
11. **Sant’Anna, Pedro HC and Jun Zhao. (2020)**: "Doubly Robust Difference-in-Differences Estimators." Journal of Econometrics, 219(1):101–122. This paper focuses on developing doubly robust estimators to improve the reliability of difference-in-differences analysis.
12. **Arkhangelsky, Dmitry, Susan Athey, David A Hirshberg, Guido W Imbens, and Stefan Wager. (2021)**: "Synthetic Difference-in-Differences." American Economic Review, 111(12):4088–4118, 2021. 
13. **Callaway, Brantly, Andrew Goodman-Bacon, and Pedro HC Sant’Anna. (2021)**: "Difference-in-Differences with a Continuous Treatment." arXiv preprint arXiv:2107.02637. This preprint extends the difference-in-differences framework to settings with continuous treatments.
14. **Goodman-Bacon, Andrew. (2021)**: "Difference-in-Differences with Variation in Treatment Timing." Journal of Econometrics, 225(2):254–277. Goodman-Bacon analyzes the difference-in-differences methodology in settings where treatment timing varies across observations.
15. **Wooldridge, Jeffrey M. (2021)**: "Two-Way Fixed Effects, the Two-Way Mundlak Regression, and Difference-in-Differences Estimators." Mimeo. This paper explores two-way fixed effects and Mundlak regression in the context of difference-in-differences estimators.
16. **Chen, Yehu, Roman Garnett, Jacob M Montgomery, and Annamaria Prati. (2021)**: "Difference in Differences with Parallel-ish Trends via Joint Gaussian Processes."
17. **Athey, Susan and Guido Imbens. (2022)**: "Design-based Analysis in Difference-in-Differences Settings with Staggered Adoption." Journal of Econometrics Volume 226, Issue 1, Pages 62-79. Athey and Imbens present a design-based analytical approach tailored for difference-in-differences studies with staggered adoption timelines, enhancing the robustness of causal estimates.
18. **Egami, Naoki and Soichiro Yamauchi. (2023)**: "Using Multiple Pre-treatment Periods to Improve Difference-in-Differences and Staggered Adoption Designs." Political Analysis. Cambridge University Press, 31(2), pp. 195–212. This paper advocates for the use of multiple pre-treatment periods to enhance the design and interpretation of difference-in-differences studies.





### Twoway Fixed Effects (TWFE)
#### Twoway Fixed Effects

1. **Chamberlain, Gary. (1982)**: "Multivariate Regression Models for Panel Data." Journal of Econometrics 18(1):5–46.  Chamberlain presents multivariate regression models tailored for panel data analysis.
2. **Nickell, Stephen. (1981)**: "Biases in Dynamic Models with Fixed Effects." Econometrica, Vol. 49, No. 6, 1417–1426.
3. **Bai, Jushan. (2009)**: "Panel Data Models with Interactive Fixed Effects." Econometrica, Vol. 77, No. 4, 1229-1279.
4. **Vogelsang, Timothy J. (2012)**: "Heteroskedasticity, Autocorrelation, and Spatial Correlation Robust Inference in Linear Panel Models with Fixed-Effects." Journal of Econometrics, 166(2):303–319. Vogelsang explores robust inference techniques for linear panel models in the presence of heteroskedasticity, autocorrelation, and spatial correlation.
5. **Gobillon, Laurent and Thierry Magnac. (2016)**: "Regional Policy Evaluation: Interactive Fixed Effects and Synthetic Controls." Review of Economics and Statistics, 98(3):535–551.
6. **de Chaisemartin, Clément and Xavier D’Haultfœuille. (2017**): "Fuzzy Differences-in-Differences." The Review of Economic Studies, 85(2):999–1028.
7. **Arkhangelsky, Dmitry and Guido Imbens. (2018)**: "The Role of the Propensity Score in Fixed Effect Models." Technical report, National Bureau of Economic Research. This report by Arkhangelsky and Imbens discusses the integration of propensity score methods within fixed effect models to improve causal inference in observational studies.
8. **Sun, Liyang and Sarah Abraham. (2018)**: "Estimating Dynamic Treatment Effects in Event Studies with Heterogeneous Treatment Effects." Journal of Econometrics
Volume 225, Issue 2, 175-199
9. **Imai, Kosuke and In Song Kim. (2019)**: "When Should We Use Unit Fixed Effects Regression Models for Causal Inference with Longitudinal Data?" American Journal of Political Science, 63(2):467–490.
10. **de Chaisemartin, Clément and Xavier D’Haultfœuille. (2020)**: "Two-way Fixed Effects Estimators with Heterogeneous Treatment Effects." The American Economic Review, 110(9):2964–2996.
11. **Hazlett, Chad and Leonard Wainstein. (2020)**: "Understanding, Choosing, and Unifying Multi-level and Fixed Effect Approaches." Political Analysis. Cambridge University Press, 30(1), pp. 46–65.
12. **Sant’Anna, Pedro HC and Jun Zhao. (2020)**: "Doubly Robust Difference-in-Differences Estimators." Journal of Econometrics, 219(1):101–122.
13. **De Chaisemartin, Clément and Xavier d’Haultfœuille. (2020)**: "Two-way Fixed Effects Estimators with Heterogeneous Treatment Effects." American Economic Review, 110(9):2964–2996. 
14. **Callaway, Brantly and Sonia Karami. (2021)**: "Treatment Effects in Interactive Fixed Effects Models." Mimeo, University of Georgia.
15. **Arkhangelsky, Dmitry, Guido W Imbens, Lihua Lei, and Xiaoman Luo. (2021)**: "Double-Robust Two-Way-Fixed-Effects Regression For Panel Data." arXiv:2107.13737. 
16. **Wooldridge, Jeffrey M. (2021)**: "Two-Way Fixed Effects, the Two-Way Mundlak Regression, and Difference-in-Differences Estimators." Mimeo. This paper explores two-way fixed effects and Mundlak regression in the context of difference-in-differences estimators.
17. **De Chaisemartin, Clément and Xavier D’haultfœuille. (2022)**: "Two-way Fixed Effects and Differences-in-Differences with Heterogeneous Treatment Effects: A Survey." The Econometrics Journal, Volume 26, Issue 3, 1-30.


### The Synthetic Control Method (SCM)
#### The Synthetic Control Method

1. **Abadie, A and J Gardeazabal. (2003)**: "The Economic Costs of Conflict: A Case Study of the Basque Country." The American Economic Review, 93(1):113–132. In this study, Abadie and Gardeazabal introduce the Synthetic Control Method (SCM) in assessing the economic impact of conflict, particularly in the Basque Country.
2. **Abadie, Alberto, Alexis Diamond, and Jens Hainmueller. (2010)**: "Synthetic Control Methods for Comparative Case Studies: Estimating the Effect of California’s Tobacco Control Program." Journal of the American Statistical Association 105(490):493–505.
3. **Abadie, Alberto, Alexis Diamond, and Jens Hainmueller. (2015)**: "Comparative Politics and the Synthetic Control Method." American Journal of Political Science 59(2):495–510.
4. **Doudchenko, Nikolay and Guido W Imbens. (2016)**: "Balancing, Regression, Difference-In-Differences and Synthetic Control Methods: A Synthesis." arXiv:1610.07748.
5. **Gobillon, Laurent and Thierry Magnac. (2016)**: "Regional Policy Evaluation: Interactive Fixed Effects and Synthetic Controls." Review of Economics and Statistics, 98(3):535–551.
6. **Hahn, Jinyong and Ruoyao Shi. (2017)**: "Synthetic Control and Inference." Econometrics, 5(4):52.
7. **Robbins, Michael W., Jessica Saunders, and Beau Kilmer. (2017)**: "A Framework for Synthetic Control Methods With High-Dimensional, Micro-Level Data: Evaluating a Neighborhood-Specific Crime Intervention." Journal of the American Statistical Association, 112(517):109–126.
8.  **Xu, Yiqing. (2017)**: "Generalized Synthetic Control Method: Causal Inference with Interactive Fixed Effects Models." Political Analysis, 25(1):57–76.
9.  **Chernozhukov, Victor, Kaspar Wuthrich, and Yinchu Zhu. (2017)**: "An Exact and Robust Conformal Inference Method for Counterfactual and Synthetic Controls." arXiv:1712.09089. 
10.  **Firpo, Sergio and Vitor Possebom. (2018)**: "Synthetic Control Method: Inference, Sensitivity Analysis, and Confidence Sets." Journal of Causal Inference, 6(2).
11.  **Ben-Michael, Eli, Avi Feller, and Jesse Rothstein. (2018)**: "The Augmented Synthetic Control Method."
12.  **Amjad, Muhammad, Devavrat Shah, and Dennis Shen. (2018)**: "Robust Synthetic Control." The Journal of Machine Learning Research, 19(1):802–852.
13.  **Cattaneo, Matias D., Yingjie Feng, and Rocio Titiunik. (2019)**: "Prediction Intervals for Synthetic Control Methods."	arXiv:1912.07120. 
14.  **Kim, Sungjin, Clarence Lee, and Sachin Gupta. (2020)**: "Bayesian Synthetic Control Methods." JMR, Journal of marketing research 57(5):831–852.
15.  **Ferman, B, C Pinto, and V Possebom. (2020)**: "Cherry Picking with Synthetic Controls." Journal of Policy Analysis and Management.
16.  **Hollingsworth, Alex and Coady Wing. (2020)**: "Tactics for Design and Inference in Synthetic Control Studies: An Applied Example Using High-Dimensional Data." Available at SSRN: https://ssrn.com/abstract=3592088
17.  **Abaide, Alberto. (2020)**: "Using Synthetic Controls: Feasibility, Data Requirements, and Methodological Aspects." Journal of Economic Literature, 59 (2): 391-425.
18.  **Ferman, Bruno and Cristine Pinto. (2021)**: "Synthetic Controls with Imperfect Pre-treatment Fit." Quantitative Economics, 12(4):1197–1221.  
19.  **Pang, Xun, Licheng Liu, and Yiqing Xu. (2022)**: "A Bayesian Alternative to Synthetic Control for Comparative Case Studies." Political Analysis, 30(2).

## Introduction to Causal Inference (Intermediate)
### Introduction to Causal Inference
1. **Rubin, D. B. (1978)**: "Bayesian Inference for Causal Effects: The Role of Randomization". The Annals of Statistics, Vol. 6, No. 1：34-58. A pioneering paper that advanced the Bayesian approach to causal inference, emphasizing the importance of randomization and laying foundational concepts for the Rubin Causal Model.
2. **Imbens, G. W., & Wooldridge, J. M. (2009)**: "Recent Developments in the Econometrics of Program Evaluation". Journal of Economic Literature, 47 (1): 5-86. Insightful overview of econometric methods for program evaluation, integral to causal panel data analysis.
3. **Imbens, G. W. (2010)**: "Better LATE Than Nothing". Journal of Economic Literature, 48 (2): 399-423. Discusses instrumental variables and their applications.
4. **Hahn, J., Todd, P., & Van der Klaauw, W. (2001)**: "Identification and Estimation of Treatment Effects with a Regression-Discontinuity Design". Econometrica, 69(1), 201–209. An influential paper on regression-discontinuity design, a cutting-edge method in causal inference.
5. **Morgan, S. L., & Winship, C. (2014)**: "Counterfactuals and Causal Inference: Methods and Principles for Social Research". Cambridge: Cambridge University Press. A comprehensive exploration of counterfactual reasoning and its applications in social research, essential for understanding causal inference.
6. **Aronow, Peter M and Cyrus Samii. (2016)**: "Does Regression Produce Representative Estimates of Causal Effects?" American Journal of Political Science, 60(1), 250–267. The authors examine the assumptions under which regression methods yield unbiased causal estimates.
7. **Doudchenko, Nikolay and Guido W Imbens. (2016)**: "Balancing, Regression, Difference-in-Differences and Synthetic Control Methods: A Synthesis." Technical report, National Bureau of Economic Research. Doudchenko and Imbens synthesize various methods used for causal inference, including balancing and synthetic controls



## Introduction to Causal Panel Data (Advanced)
### Introduction to Causal Panel Data 
1. **Hazlett, Chad and Yiqing Xu. (2018)**: "Trajectory Balancing: A General Reweighting Approach to Causal Inference With Time-Series Cross-Sectional Data." Available at SSRN: https://ssrn.com/abstract=3214231. This manuscript introduces trajectory balancing for causal inference in time-series cross-sectional data.
2. **Blackwell, Matthew and Adam Glynn. (2018)**: "How to Make Causal Inferences with Time-Series Cross-Sectional Data Under Selection on Observables." The American Political Science Review, 112(2):1067–1082. The authors discuss causal inference methodologies in the context of time-series cross-sectional data.
3. **Imai, Kosuke and In Song Kim. (2019)**: "When Should We Use Unit Fixed Effects Regression Models for Causal Inference with Longitudinal Data?"  This paper addresses the use of fixed effects models for causal analysis with longitudinal data.
4. **Aronow, Peter M, Cyrus Samii, and Ye Wang. (2020)**: "Design-Based Inference for Spatial Experiments with Interference." This study tackles the challenge of interference in spatial experimental designs.
5. **Tyler, Matthew. (2021)**: "Counterfactual Forecasting: Causal Inference without Simultaneous Controls."
6. **Ying, Andrew, Wang Miao, Xu Shi, and Eric J Tchetgen Tchetgen. (2021)**: "Proximal Causal Inference for Complex Longitudinal Studies." This preprint introduces proximal causal inference methods tailored for complex longitudinal studies.
7. **Arkhangelsky, D. and Imbens, G. W. (2022)**: "Double-Robust Identification for Causal Panel Data Models". The Econometrics Journal, Volume 25, Issue 3: 649–674. Discusses double-robust methods in panel data.



## Methodological Advances (Advanced)
### Methodological Advances 

### Advanced Methodological Texts
1. **Athey, S., & Imbens, G. W. (2017)**: "The State of Applied Econometrics: Causality and Policy Evaluation". Journal of Economic Perspectives, 31 (2): 3-32.  
2. **Chernozhukov, V., Hansen, C., & Spindler, M. (2015)**: "Valid Post-Selection and Post-Regularization Inference: An Elementary, General Approach". Annual Review of Economics 2015 7:1, 649-688. For readers interested in post-selection inference, crucial for understanding model selection in causal analysis.
3. **Belloni, A., Chernozhukov, V., & Hansen, C. (2014)**: "Inference on Treatment Effects after Selection among High-Dimensional Controls". The Review of Economic Studies, Volume 81, Issue 2: 608–650. This paper provides practical guidance on dealing with high-dimensional controls in causal inference.
4. **Fernández-Val, Iván and Martin Weidner. (2016)**: "Individual and Time Effects in Nonlinear Panel Models with Large N, T." Journal of Econometrics, 192(1):291–312, 2016. The authors examine the estimation of individual and time effects in nonlinear panel models with large dimensions.
5. **Gobillon, Laurent and Thierry Magnac. (2016)**: "Regional Policy Evaluation: Interactive Fixed Effects and Synthetic Controls." Review of Economics and Statistics, 98(3):535–551, 2016. Gobillon and Magnac evaluate regional policies using interactive fixed effects models and synthetic controls.
6. **Freyberger, Joachim. (2018)**: "Non-parametric Panel Data Models with Interactive Fixed Effects." The Review of Economic Studies, 85(3):1824–1851. Freyberger discusses non-parametric panel data models and their application in econometric analysis.
7. **Feng, Yingjie. (2020)**: "Causal Inference in Possibly Nonlinear Factor Models." arXiv:2008.13651. Feng explores causal inference within potentially nonlinear factor models, expanding the toolbox for dealing with complex data structures.
8. **Abadie, Alberto, Susan Athey, Guido W Imbens, and Jeffrey M Wooldridge. (2020)**: "Sampling-based versus Design-based Uncertainty in Regression Analysis." Econometrica, 88: 265-296. The authors discuss the differences between sampling-based and design-based approaches to uncertainty in regression analysis, providing guidance on when each approach is appropriate.
9. **Deaner, Ben. (2021)**: "Proxy Controls and Panel Data." arXiv preprint arXiv:1810.00283. This paper addresses the integration of proxy controls in panel data models for causal analysis.
10. **Tyler, Matthew. (2021)**: "Counterfactual Forecasting: Causal Inference without Simultaneous Controls." Mimeo, Stanford University.  Tyler's manuscript addresses the methodology of causal inference forecasting without the need for simultaneous control variables. 
11. **Wang, Ye. (2021)**: "Causal Inference under Temporal and Spatial Interference." Mimeo, New York University.  Wang's work delves into the complexities of causal inference when dealing with interference across both time and space.
12. **Abadie, Alberto, Susan Athey, Guido W Imbens, and Jeffrey M Wooldridge. (2023)**: "When Should You Adjust Standard Errors for Clustering?" The Quarterly Journal of Economics, 138(1):1–35. This article addresses the crucial question of when to adjust standard errors for clustering in statistical analysis, offering best practices for researchers.

## Specialized Topics (Advanced)
### Specialized Topics 

### Marginal structural models (MSMs)
1. **Robins, J M, M A Hernán, and B Brumback. (2000)**: "Marginal Structural Models and Causal Inference in Epidemiology." Epidemiology 11(5):550–560.
2. **Blackwell, Matthew. (2013)**: "A Framework for Dynamic Causal Inference in Political Science." American journal of political science 57(2):504–520. Blackwell provides a framework for assessing causality in dynamic political contexts.
3. **Blackwell, M. and Yamauchi, S. (2021)**: "Adjusting for Unmeasured Confounding in Marginal Structural Models".arXiv preprint, arXiv:2105.03478
4. **Imai, Kosuke, In Song Kim, and Erik Wang. (2023)**: "Matching Methods for Causal Inference with Time-Series Cross-Section Data." The authors propose matching methods tailored for time-series cross-section data in causal inference. American Journal of Political Science, Vol. 67, No. 3: 587–605.


## Software and Practical Guides
### Software and Practical Guides
1. **Liu, L., Wang, Y., and Xu, Y. (2022)**: "A Practical Guide to Counterfactual Estimators for Causal Inference with Time-Series Cross-Sectional Data". American Journal of Political Science, May 2022, Pp. 1–17. Practical guide for implementing counterfactual estimators.
2. **Mou, H., Liu, L., and Xu, Y. (2023)**: "Panel Data Visualization in R (panelView) and Stata (panelview)". Journal of Statistical Software, 107(7), 1–20. Tools for visualizing panel data.
3. **Xu, Yiqing. (2023)**: "Causal Inference with Time-Series Cross-Sectional Data: A Reflection." In Oxford Handbook of Engaged Methodological Pluralism in Political Science (Vol 1).  Xu provides a comprehensive reflection on the challenges of causal inference within the context of time-series cross-sectional data.




