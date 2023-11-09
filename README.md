# Causal-Panel-Data-Reading-List
This is a Causal Panel Data reading list 

* [ Foundational Texts](#foundational-texts)
* [ Introduction to Causal Inference](#introduction_to_causal_inference)
* [ Methodological Foundations (Intermediate)](#methodological_foundations_(Intermediate))
    * [Difference-in-Differences (DID)](#difference_in_differences_(DID))
    * [Twoway Fixed Effects (TWFE)](#twoway_fixed_effects_(TWFE))
    * [The Synthetic Control Method (SCM)](#the_synthetic_control_method_(SCM))
* [ Methodological Advances](#methodological_advances)
* [ Applications and Case Studies](#applications-and-case-studies)
* [ Specialized Topics](#specialized-topics)
* [ Software and Practical Guides](#software-and-practical-guides)

## Foundational Texts 
### Foundational Texts (Beginner)
1. **Ashenfelter, O. (1978)**: "Estimating the Effect of Training Programs on Earnings." Ashenfelter's paper is recognized for its early use of the Difference in Differences (DID) approach to estimate the impact of job training programs on earnings.
2. **Nickell, Stephen. (1981)**: "Biases in Dynamic Models with Fixed Effects". This paper explores the potential biases in dynamic models with fixed effects.
3. **Wooldridge, Jeffrey M. (2001)**: Econometric Analysis of Cross Section and Panel Data. This text offers an in-depth exploration of methods applied to cross-sectional and panel data.
4. **Abadie, A and J Gardeazabal. (2003)**: "The Economic Costs of Conflict: A Case Study of the Basque Country." The American Economic Review, 93(1):113–132.
5. **Hsiao, C. (2003)**: "Analysis of Panel Data". Detailed exploration of panel data analysis techniques.
6. **Beck, N. (2008)**: "Time-Series Cross-Section Methods". Overview of methods for analyzing time-series cross-section data.
7. **Beck, Nathaniel. (2008)**: Chapter "Time-Series Cross-Section Methods" Methods in time-series cross-section.
8. **Angrist, J. D., & Pischke, J.-S. (2009)**: "Mostly Harmless Econometrics: An Empiricist's Companion". A user-friendly introduction to econometrics and causal inference.
9. **Wooldridge, J. M. (2010)**: "Econometric Analysis of Cross Section and Panel Data, Second Edition". Comprehensive introduction to econometrics with a focus on panel data analysis.
   
### Introduction to Causal Inference (Beginner)
1. **Rubin, D. B. (1978)**: "Bayesian Inference for Causal Effects: The Role of Randomization". A pioneering paper that advanced the Bayesian approach to causal inference, emphasizing the importance of randomization and laying foundational concepts for the Rubin Causal Model.
6. **Imbens, G. W., & Wooldridge, J. M. (2009)**: "Recent Developments in the Econometrics of Program Evaluation". Insightful overview of econometric methods for program evaluation, integral to causal panel data analysis.
7. **Imbens, G. W. (2010)**: "Better LATE Than Nothing". Discusses instrumental variables and their applications.
8. **Hahn, J., Todd, P., & Van der Klaauw, W. (2001)**: "Identification and Estimation of Treatment Effects with a Regression-Discontinuity Design". An influential paper on regression-discontinuity design, a cutting-edge method in causal inference.
9. **Morgan, S. L., & Winship, C. (2014)**: "Counterfactuals and Causal Inference: Methods and Principles for Social Research". A comprehensive exploration of counterfactual reasoning and its applications in social research, essential for understanding causal inference.



## Methodological Foundations (Intermediate)

### Difference-in-Differences (DID)
1. **Card, D. and Krueger, A. (1994)**: "Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania." This study employs the DID approach to evaluate the effect of minimum wage increases in New Jersey on employment.
2.  **Athey, S. and Imbens, G. W. (2006)**: "Identification and Inference in Nonlinear Difference-in-Differences Models". Covers nonlinear models in difference-in-differences settings.
**Abadie, Alberto. (2005)**: "Semiparametric Difference-in-Differences Estimators." Review of Economic Studies, 72(1):1–19. Abadie introduces semiparametric estimators within the context of the difference-in-differences methodology in this influential paper.
**Strezhnev, Anton. (2018)**: "Semiparametric Weighting Estimators for Multi-Period Difference-in-Differences Designs. Strezhnev proposes new semiparametric weighting estimators tailored for multi-period difference-in-differences designs in this paper.
**Ding, Peng and Fan Li. (2019)**: "A Bracketing Relationship between Difference-in-Differences and Lagged-Dependent-Variable Adjustment." Ding and Li discuss the relationship between difference-in-differences and adjustments for lagged dependent variables, providing a framework for understanding their connection.
**Callaway, Brantly and Pedro H C Sant’Anna. (2020)**: "Difference-in-Differences with Multiple Time Periods." This article discusses the application of the difference-in-differences methodology over multiple time periods, offering new insights into its implementation.
14. **Coleman, Thomas. (2020)**: "John Snow and Cholera: Revisiting Difference-in-Differences and Randomized Trials in Research."  This literature exploring the application of difference-in-differences and randomized trials in research.
**Sant’Anna, Pedro HC and Jun Zhao. (2020)**: "Doubly Robust Difference-in-Differences Estimators." This paper focuses on developing doubly robust estimators to improve the reliability of difference-in-differences analysis.
**Egami, Naoki and Soichiro Yamauchi. (2021)**: "Using Multiple Pre-treatment Periods to Improve Difference-in-Differences and Staggered Adoption Designs." This paper advocates for the use of multiple pre-treatment periods to enhance the design and interpretation of difference-in-differences studies.
**Callaway, Brantly, Andrew Goodman-Bacon, and Pedro H C Sant’Anna. (2021)**: "Difference-in-Differences with a Continuous Treatment." This work extends the difference-in-differences approach to scenarios with a continuous treatment variable.
**Wooldridge, Jeffrey M. (2021)**: "Two-Way Fixed Effects, the Two-Way Mundlak Regression, and Difference-in-Differences Estimators." This paper explores two-way fixed effects and Mundlak regression in the context of difference-in-differences estimators.


### Twoway Fixed Effects (TWFE)
**Mundlak, Yair. (1978)**: "On the Pooling of Time Series and Cross Section Data". This paper discusses methodologies for combining time series and cross-sectional data.
**Chamberlain, Gary. (1982)**: "Multivariate Regression Models for Panel Data."  Chamberlain presents multivariate regression models tailored for panel data analysis.
**Nickell, Stephen. (1981)**: "Biases in Dynamic Models with Fixed Effects." 
**Bai, Jushan. (2009)**: "Panel Data Models with Interactive Fixed Effects." 
**Gobillon, Laurent and Thierry Magnac. (2016)**: "Regional Policy Evaluation: Interactive Fixed Effects and Synthetic Controls." 
**de Chaisemartin, Clément and Xavier D’Haultfœuille. (2017**): "Fuzzy Differences-in-Differences." 
**Sun, Liyang and Sarah Abraham. (2018)**: "Estimating Dynamic Treatment Effects in Event Studies with Heterogeneous Treatment Effects."
**Imai, Kosuke and In Song Kim. (2019)**: "When Should We Use Unit Fixed Effects Regression Models for Causal Inference with Longitudinal Data?" 
**de Chaisemartin, Clément and Xavier D’Haultfœuille. (2020)**: "Two-way Fixed Effects Estimators with Heterogeneous Treatment Effects." 
**Hazlett, Chad and Leonard Wainstein. (2020)**: "Understanding, Choosing, and Unifying Multi-level and Fixed Effect Approaches."
**Sant’Anna, Pedro HC and Jun Zhao. (2020)**: "Doubly Robust Difference-in-Differences Estimators."
**Callaway, Brantly and Sonia Karami. (2021)**: "Treatment Effects in Interactive Fixed Effects Models." 
**Wooldridge, Jeffrey M. (2021)**: "Two-Way Fixed Effects, the Two-Way Mundlak Regression, and Difference-in-Differences Estimators."
**Arkhangelsky, Dmitry, Guido W Imbens, Lihua Lei, and Xiaoman Luo. (2021)**: "Double-Robust Two-Way-Fixed-Effects Regression For Panel Data."
**Blackwell, Matthew and Soichiro Yamauchi. (2021)**: "Adjusting for Unmeasured Confounding in Marginal Structural Models with Propensity-Score Fixed Effects."
**Wooldridge, Jeffrey M. (2021)**: "Two-Way Fixed Effects, the Two-Way Mundlak Regression, and Difference-in-Differences Estimators." This paper explores two-way fixed effects and Mundlak regression in the context of difference-in-differences estimators.
**Chiu, Albert, Xingchen Lan, Ziyi Liu, and Yiqing Xu. (2023)**: "What To Do (and Not to Do) with Causal Panel Analysis: Parallel Trends, Heterogeneous Treatment Effects, and Diagnostics."

### The Synthetic Control Method (SCM)

**Abadie, Alberto, Alexis Diamond, and Jens Hainmueller. (2010)**: "Synthetic Control Methods for Comparative Case Studies: Estimating the Effect of California’s Tobacco Control Program." Journal of the American Statistical Association, 105(490):493–505.
**Abadie, Alberto, Alexis Diamond, and Jens Hainmueller. (2015)**: "Comparative Politics and the Synthetic Control Method." American Journal of Political Science, 59(2):495–510.
**Doudchenko, Nikolay and Guido W Imbens. (2016)**: "Balancing, Regression, Difference-In-Differences and Synthetic Control Methods: A Synthesis."
**Gobillon, Laurent and Thierry Magnac. (2016)**: "Regional Policy Evaluation: Interactive Fixed Effects and Synthetic Controls." Review of Economics and Statistics, 98(3):535–551.
**Hahn, Jinyong and Ruoyao Shi. (2017)**: "Synthetic Control and Inference." Econometrics, 5(4):52.
**Robbins, Michael W., Jessica Saunders, and Beau Kilmer. (2017)**: "A Framework for Synthetic Control Methods With High-Dimensional, Micro-Level Data: Evaluating a Neighborhood-Specific Crime Intervention." Journal of the American Statistical Association, 112(517):109–126.
**Xu, Yiqing. (2017)**: "Generalized Synthetic Control Method: Causal Inference with Interactive Fixed Effects Models." Political Analysis, 25(1):57–76.
**Chernozhukov, Victor, Kaspar Wuthrich, and Yinchu Zhu. (2017)**: "An Exact and Robust Conformal Inference Method for Counterfactual and Synthetic Controls."
**Firpo, Sergio and Vitor Possebom. (2018)**: "Synthetic Control Method: Inference, Sensitivity Analysis, and Confidence Sets." Journal of Causal Inference, 6(2).
**Ben-Michael, Eli, Avi Feller, and Jesse Rothstein. (2018)**: "The Augmented Synthetic Control Method."
**Cattaneo, Matias D., Yingjie Feng, and Rocio Titiunik. (2019)**: "Prediction Intervals for Synthetic Control Methods."
**Kim, Sungjin, Clarence Lee, and Sachin Gupta. (2020)**: "Bayesian Synthetic Control Methods." JMR, Journal of Marketing Research, 57(5):831–852.
**Ferman, B, C Pinto, and V Possebom. (2020)**: "Cherry Picking with Synthetic Controls." Journal of Policy Analysis and Management.
**Hollingsworth, Alex and Coady Wing. (2020)**: "Tactics for Design and Inference in Synthetic Control Studies: An Applied Example Using High-Dimensional Data."
**Abaide, Alberto. (2020)**: "Using Synthetic Controls: Feasibility, Data Requirements, and Methodological Aspects." Journal of Economic Literature.
**Pang, Xun, Licheng Liu, and Yiqing Xu. (2022)**: "A Bayesian Alternative to Synthetic Control for Comparative Case Studies." Political Analysis, 30(2).

## Methodological Advances
### Advanced Methodological Texts
8. **Abadie, A., Diamond, A., & Hainmueller, J. (2010)**: "Synthetic Control Methods for Comparative Case Studies: Estimating the Effect of California's Tobacco Control Program". A seminal paper on synthetic control methods, essential for advanced understanding of causal panel data analysis.
9. **Arellano, M., & Bond, S. (1991)**: "Some Tests of Specification for Panel Data: Monte Carlo Evidence and an Application to Employment Equations". This paper is fundamental for understanding dynamic panel data models.
10. **Arkhangelsky, D. and Imbens, G. W. (2019)**: "Double-Robust Identification for Causal Panel Data Models". Discusses double-robust methods in panel data.
11. **Xu, Y. (2017)**: "Generalized Synthetic Control Method". Expands on synthetic control methods for interactive fixed effects models.
12. **Bai, J. (2009)**: "Panel Data Models with Interactive Fixed Effects". Presents models for panel data with interactive effects.

## Specialized Topics
### Specialized Topics
14. **Athey, S., & Imbens, G. W. (2017)**: "The State of Applied Econometrics: Causality and Policy Evaluation". A paper that discusses modern approaches in applied econometrics, specifically causality and policy evaluation.
15. **Chernozhukov, V., Hansen, C., & Spindler, M. (2015)**: "Valid Post-Selection and Post-Regularization Inference: An Elementary, General Approach". For readers interested in post-selection inference, crucial for understanding model selection in causal analysis.

## Applications and Case Studies
### Practical Application
16. **Belloni, A., Chernozhukov, V., & Hansen, C. (2014)**: "Inference on Treatment Effects after Selection among High-Dimensional Controls". This paper provides practical guidance on dealing with high-dimensional controls in causal inference.
17. **Xu, Y. (2017)**: "Generalized Synthetic Control Method: Causal Inference with Interactive Fixed Effects Models". A practical guide to the generalized synthetic control method, useful for applied researchers.

## Software and Practical Guides
### Software and Practical Guides
18. **Mou, H., Liu, L., and Xu, Y. (2023)**: "Panel Data Visualization in R (panelView) and Stata (panelview)". Tools for visualizing panel data.
19. **Blackwell, M. and Yamauchi, S. (2021)**: "Adjusting for Unmeasured Confounding in Marginal Structural Models". Guide to dealing with confounding in models.
20. **Liu, L., Wang, Y., and Xu, Y. (2022)**: "A Practical Guide to Counterfactual Estimators for Causal Inference with Time-Series Cross-Sectional Data". Practical advice for implementing counterfactual estimators.


