# Causal-Panel-Data-Reading-List
This is a Causal Panel Data Reading List 

* [ Foundational Texts](#foundational-texts)
* [ Introduction to Causal Inference](#introduction_to_causal_inference)
* [Introduction to Time-Series Cross-Sectional Data (TSCS)](introduction_to_time_series_cross_sectional_data (TSCS))
* [ Methodological Foundations (Intermediate)](#methodological_foundations_(Intermediate))
    * [Difference-in-Differences (DID)](#difference_in_differences_(DID))
    * [Twoway Fixed Effects (TWFE)](#twoway_fixed_effects_(TWFE))
    * [The Synthetic Control Method (SCM)](#the_synthetic_control_method_(SCM))
* [ Methodological Advances](#methodological_advances)
* [Introduction to Causal Panel Data](#introduction_to_causal_panel_data)
* [ Specialized Topics](#specialized-topics)
    * [Marginal structural models (MSMs)](marginal_structural_models_(MSMs))
* [ Software and Practical Guides](#software-and-practical-guides)

## Foundational Texts (Beginner)
### Foundational Texts 
1. **Ashenfelter, O. (1978)**: "Estimating the Effect of Training Programs on Earnings." Ashenfelter's paper is recognized for its early use of the Difference in Differences (DID) approach to estimate the impact of job training programs on earnings.
2. **Nickell, Stephen. (1981)**: "Biases in Dynamic Models with Fixed Effects". This paper explores the potential biases in dynamic models with fixed effects.
3. **Wooldridge, Jeffrey M. (2001)**: Econometric Analysis of Cross Section and Panel Data. This text offers an in-depth exploration of methods applied to cross-sectional and panel data.
4. **Abadie, A and J Gardeazabal. (2003)**: "The Economic Costs of Conflict: A Case Study of the Basque Country." The American Economic Review, 93(1):113–132.
5. **Hsiao, C. (2003)**: "Analysis of Panel Data". Detailed exploration of panel data analysis techniques.
6. **Beck, N. (2008)**: "Time-Series Cross-Section Methods". Overview of methods for analyzing time-series cross-section data.
8. **Angrist, J. D., & Pischke, J.-S. (2009)**: "Mostly Harmless Econometrics: An Empiricist's Companion". A user-friendly introduction to econometrics and causal inference.
9. **Wooldridge, J. M. (2010)**: "Econometric Analysis of Cross Section and Panel Data, Second Edition". Comprehensive introduction to econometrics with a focus on panel data analysis.
   
## Introduction to Causal Inference 
1. **Rubin, D. B. (1978)**: "Bayesian Inference for Causal Effects: The Role of Randomization". A pioneering paper that advanced the Bayesian approach to causal inference, emphasizing the importance of randomization and laying foundational concepts for the Rubin Causal Model.
6. **Imbens, G. W., & Wooldridge, J. M. (2009)**: "Recent Developments in the Econometrics of Program Evaluation". Insightful overview of econometric methods for program evaluation, integral to causal panel data analysis.
7. **Imbens, G. W. (2010)**: "Better LATE Than Nothing". Discusses instrumental variables and their applications.
8. **Hahn, J., Todd, P., & Van der Klaauw, W. (2001)**: "Identification and Estimation of Treatment Effects with a Regression-Discontinuity Design". An influential paper on regression-discontinuity design, a cutting-edge method in causal inference.
9. **Morgan, S. L., & Winship, C. (2014)**: "Counterfactuals and Causal Inference: Methods and Principles for Social Research". A comprehensive exploration of counterfactual reasoning and its applications in social research, essential for understanding causal inference.

Aronow, Peter M and Cyrus Samii. (2016): "Does Regression Produce Representative Estimates of Causal Effects?" American Journal of Political Science, 60(1):250–267. The authors examine the assumptions under which regression methods yield unbiased causal estimates.
Chernozhukov, Victor, Kaspar Wuthrich, and Yinchu Zhu. (2017): "An Exact and Robust Conformal Inference Method for Counterfactual and Synthetic Controls." Chernozhukov et al. present a robust method for counterfactual prediction and policy analysis.


## Introduction to Time-Series Cross-Sectional Data (TSCS) (Beginner to Intermediate)
1. **Mundlak, Yair. (1978)**: "On the Pooling of Time Series and Cross Section Data". This paper discusses methodologies for combining time series and cross-sectional data.
2. **Rosenbaum, Paul R and Donald B Rubin. (1983)**: "The Central Role of the Propensity Score in Observational Studies for Causal Effects."
1. **Beck, Nathaniel and Jonathan N Katz. (1995)**: "What to Do (and Not to Do) with Time-Series Cross-Section Data." 
2. **Beck, Nathaniel, Jonathan N Katz and Richard Tucker. (1998)**: "Taking Time Seriously: Time-Series-Cross-Section Analysis with a Binary Dependent Variable." 
4. **Beck, Nathaniel and Jonathan N Katz. (2001)**: "Throwing Out the Baby with the Bath Water: A Comment on Green, Kim, and Yoon." 
5. **Blackwell, Matthew. (2013)**: "A Framework for Dynamic Causal Inference in Political Science." 
6. **Beck, Nathaniel and Jonathan N Katz. (2004)**: "Time-Series–Cross-Section Issues: Dynamics, 2004." 
7. **Beck, Nathaniel. (2008)**: Chapter "Time-Series Cross-Section Methods" Methods in time-series cross-section.
8. **Beck, Nathaniel and Jonathan N Katz. (2011)**: "Modeling Dynamics in Time-Series–Cross-Section Political Economy Data." 


## Methodological Foundations (Intermediate)

### Difference-in-Differences (DID)
1. **Card, D. and Krueger, A. (1994)**: "Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania." This study employs the DID approach to evaluate the effect of minimum wage increases in New Jersey on employment.
2.  **Athey, S. and Imbens, G. W. (2006)**: "Identification and Inference in Nonlinear Difference-in-Differences Models". Covers nonlinear models in difference-in-differences settings.Ltd.
3. **Abadie, Alberto. (2005)**: "Semiparametric Difference-in-Differences Estimators."  Abadie introduces semiparametric estimators within the context of the difference-in-differences methodology in this influential paper.
4. **Strezhnev, Anton. (2018)**: "Semiparametric Weighting Estimators for Multi-Period Difference-in-Differences Designs. Strezhnev proposes new semiparametric weighting estimators tailored for multi-period difference-in-differences designs in this paper.
5. **Ding, Peng and Fan Li. (2019)**: "A Bracketing Relationship between Difference-in-Differences and Lagged-Dependent-Variable Adjustment." Ding and Li discuss the relationship between difference-in-differences and adjustments for lagged dependent variables, providing a framework for understanding their connection.
6. **Callaway, Brantly and Pedro H C Sant’Anna. (2020)**: "Difference-in-Differences with Multiple Time Periods." This article discusses the application of the difference-in-differences methodology over multiple time periods, offering new insights into its implementation.
7. **Coleman, Thomas. (2020)**: "John Snow and Cholera: Revisiting Difference-in-Differences and Randomized Trials in Research."  This literature exploring the application of difference-in-differences and randomized trials in research.
8. **Keele, Luke. (2020)**: "Differences-in-Differences: Neither Natural nor an Experiment." 
9. **Sant’Anna, Pedro HC and Jun Zhao. (2020)**: "Doubly Robust Difference-in-Differences Estimators." This paper focuses on developing doubly robust estimators to improve the reliability of difference-in-differences analysis.
10. **Egami, Naoki and Soichiro Yamauchi. (2021)**: "Using Multiple Pre-treatment Periods to Improve Difference-in-Differences and Staggered Adoption Designs." This paper advocates for the use of multiple pre-treatment periods to enhance the design and interpretation of difference-in-differences studies.
11. **Callaway, Brantly, Andrew Goodman-Bacon, and Pedro H C Sant’Anna. (2021)**: "Difference-in-Differences with a Continuous Treatment." This work extends the difference-in-differences approach to scenarios with a continuous treatment variable.
12. **Wooldridge, Jeffrey M. (2021)**: "Two-Way Fixed Effects, the Two-Way Mundlak Regression, and Difference-in-Differences Estimators." This paper explores two-way fixed effects and Mundlak regression in the context of difference-in-differences estimators.


### Twoway Fixed Effects (TWFE)
2. **Chamberlain, Gary. (1982)**: "Multivariate Regression Models for Panel Data."  Chamberlain presents multivariate regression models tailored for panel data analysis.
3. **Nickell, Stephen. (1981)**: "Biases in Dynamic Models with Fixed Effects."
4. **Bai, Jushan. (2009)**: "Panel Data Models with Interactive Fixed Effects."
5. **Gobillon, Laurent and Thierry Magnac. (2016)**: "Regional Policy Evaluation: Interactive Fixed Effects and Synthetic Controls."
6. **de Chaisemartin, Clément and Xavier D’Haultfœuille. (2017**): "Fuzzy Differences-in-Differences."
7. **Sun, Liyang and Sarah Abraham. (2018)**: "Estimating Dynamic Treatment Effects in Event Studies with Heterogeneous Treatment Effects."
8. **Imai, Kosuke and In Song Kim. (2019)**: "When Should We Use Unit Fixed Effects Regression Models for Causal Inference with Longitudinal Data?"
9. **de Chaisemartin, Clément and Xavier D’Haultfœuille. (2020)**: "Two-way Fixed Effects Estimators with Heterogeneous Treatment Effects."
10. **Hazlett, Chad and Leonard Wainstein. (2020)**: "Understanding, Choosing, and Unifying Multi-level and Fixed Effect Approaches."
11. **Sant’Anna, Pedro HC and Jun Zhao. (2020)**: "Doubly Robust Difference-in-Differences Estimators."
12. **Callaway, Brantly and Sonia Karami. (2021)**: "Treatment Effects in Interactive Fixed Effects Models."
13. **Wooldridge, Jeffrey M. (2021)**: "Two-Way Fixed Effects, the Two-Way Mundlak Regression, and Difference-in-Differences Estimators."
14. **Arkhangelsky, Dmitry, Guido W Imbens, Lihua Lei, and Xiaoman Luo. (2021)**: "Double-Robust Two-Way-Fixed-Effects Regression For Panel Data."
16. **Wooldridge, Jeffrey M. (2021)**: "Two-Way Fixed Effects, the Two-Way Mundlak Regression, and Difference-in-Differences Estimators." This paper explores two-way fixed effects and Mundlak regression in the context of difference-in-differences estimators.


### The Synthetic Control Method (SCM)

1. **Abadie, Alberto, Alexis Diamond, and Jens Hainmueller. (2010)**: "Synthetic Control Methods for Comparative Case Studies: Estimating the Effect of California’s Tobacco Control Program." 
**Abadie, Alberto, Alexis Diamond, and Jens Hainmueller. (2015)**: "Comparative Politics and the Synthetic Control Method." 
**Doudchenko, Nikolay and Guido W Imbens. (2016)**: "Balancing, Regression, Difference-In-Differences and Synthetic Control Methods: A Synthesis."
**Gobillon, Laurent and Thierry Magnac. (2016)**: "Regional Policy Evaluation: Interactive Fixed Effects and Synthetic Controls." 
**Hahn, Jinyong and Ruoyao Shi. (2017)**: "Synthetic Control and Inference." Econometrics, 5(4):52.
**Robbins, Michael W., Jessica Saunders, and Beau Kilmer. (2017)**: "A Framework for Synthetic Control Methods With High-Dimensional, Micro-Level Data: Evaluating a Neighborhood-Specific Crime Intervention." 
**Xu, Yiqing. (2017)**: "Generalized Synthetic Control Method: Causal Inference with Interactive Fixed Effects Models." 
**Chernozhukov, Victor, Kaspar Wuthrich, and Yinchu Zhu. (2017)**: "An Exact and Robust Conformal Inference Method for Counterfactual and Synthetic Controls."
**Firpo, Sergio and Vitor Possebom. (2018)**: "Synthetic Control Method: Inference, Sensitivity Analysis, and Confidence Sets." 
**Ben-Michael, Eli, Avi Feller, and Jesse Rothstein. (2018)**: "The Augmented Synthetic Control Method."
**Cattaneo, Matias D., Yingjie Feng, and Rocio Titiunik. (2019)**: "Prediction Intervals for Synthetic Control Methods."
**Kim, Sungjin, Clarence Lee, and Sachin Gupta. (2020)**: "Bayesian Synthetic Control Methods." 
**Ferman, B, C Pinto, and V Possebom. (2020)**: "Cherry Picking with Synthetic Controls." 
**Hollingsworth, Alex and Coady Wing. (2020)**: "Tactics for Design and Inference in Synthetic Control Studies: An Applied Example Using High-Dimensional Data."
**Abaide, Alberto. (2020)**: "Using Synthetic Controls: Feasibility, Data Requirements, and Methodological Aspects." 
**Pang, Xun, Licheng Liu, and Yiqing Xu. (2022)**: "A Bayesian Alternative to Synthetic Control for Comparative Case Studies."


## Introduction to Causal Panel Data (Advanced)
1. **Hazlett, Chad and Yiqing Xu. (2018)**: "Trajectory Balancing: A General Reweighting Approach to Causal Inference With Time-Series Cross-Sectional Data." This manuscript introduces trajectory balancing for causal inference in time-series cross-sectional data.
2. **Blackwell, Matthew and Adam Glynn. (2018)**: "How to Make Causal Inferences with Time-Series Cross-Sectional Data Under Selection on Observables." The authors discuss causal inference methodologies in the context of time-series cross-sectional data.
4. **Arkhangelsky, D. and Imbens, G. W. (2019)**: "Double-Robust Identification for Causal Panel Data Models". Discusses double-robust methods in panel data.
5. **Imai, Kosuke and In Song Kim. (2019)**: "When Should We Use Unit Fixed Effects Regression Models for Causal Inference with Longitudinal Data?"  This paper addresses the use of fixed effects models for causal analysis with longitudinal data.
7. **Aronow, Peter M, Cyrus Samii, and Ye Wang. (2020)**: "Design-Based Inference for Spatial Experiments with Interference." This study tackles the challenge of interference in spatial experimental designs.
8. **Imai, Kosuke, In Song Kim, and Erik Wang. (2021)**: "Matching Methods for Causal Inference with Time-Series Cross-Section Data." The authors propose matching methods tailored for time-series cross-section data in causal inference.



## Methodological Advances (Advanced)
### Advanced Methodological Texts
1. **Athey, S., & Imbens, G. W. (2017)**: "The State of Applied Econometrics: Causality and Policy Evaluation". 
2. **Chernozhukov, V., Hansen, C., & Spindler, M. (2015)**: "Valid Post-Selection and Post-Regularization Inference: An Elementary, General Approach". For readers interested in post-selection inference, crucial for understanding model selection in causal analysis.
3. **Belloni, A., Chernozhukov, V., & Hansen, C. (2014)**: "Inference on Treatment Effects after Selection among High-Dimensional Controls". This paper provides practical guidance on dealing with high-dimensional controls in causal inference.
4. **Feng, Yingjie. (2020)**: "Causal Inference in Possibly Nonlinear Factor Models." Feng explores causal inference within potentially nonlinear factor models, expanding the toolbox for dealing with complex data structures.
5. **Tyler, Matthew. (2021)**: "Counterfactual Forecasting: Causal Inference without Simultaneous Controls."  Tyler's manuscript addresses the methodology of causal inference forecasting without the need for simultaneous control variables.
6.**Wang, Ye. (2021)**: "Causal Inference under Temporal and Spatial Interference."  Wang's work delves into the complexities of causal inference when dealing with interference across both time and space.


## Specialized Topics (Advanced)
### Marginal structural models (MSMs)
1. **Robins, J M, M A Hernán, and B Brumback. (2000)**: "Marginal Structural Models and Causal Inference in Epidemiology."
2. **Blackwell, Matthew. (2013)**: "A Framework for Dynamic Causal Inference in Political Science." Blackwell provides a framework for assessing causality in dynamic political contexts.
3. **Blackwell, M. and Yamauchi, S. (2021)**: "Adjusting for Unmeasured Confounding in Marginal Structural Models". 
4. **Blackwell, Matthew and Soichiro Yamauchi. (2021)**: "Adjusting for Unmeasured Confounding in Marginal Structural Models with Propensity-Score Fixed Effects."



## Software and Practical Guides
### Software and Practical Guides
18. **Mou, H., Liu, L., and Xu, Y. (2023)**: "Panel Data Visualization in R (panelView) and Stata (panelview)". Tools for visualizing panel data.

20. **Liu, L., Wang, Y., and Xu, Y. (2022)**: "A Practical Guide to Counterfactual Estimators for Causal Inference with Time-Series Cross-Sectional Data". Practical advice for implementing counterfactual estimators.
17. **Xu, Y. (2017)**: "Generalized Synthetic Control Method: Causal Inference with Interactive Fixed Effects Models". A practical guide to the generalized synthetic control method, useful for applied researchers.

