# Monte-Carlo-Simulation
Group assignment applying advanced econometric techniques in EViews/Stata: Koyck distributed-lag models, simultaneous-equation identification (Order Condition), 2SLS estimation of a beef-market system, and nonlinear least-squares via the Marquardt algorithm. Includes full derivations, regression output, and economic interpretation.
Full README Description
Overview
This project was completed as part of Applied Econometric Modeling (AEM702S) at the Namibian University of Science and Technology. It demonstrates the practical application of three core econometric frameworks to real/simulated economic data:

Distributed Lag & Koyck Transformation — Modelling the delayed and persistent effects of annual rainfall on agricultural output using 150 observations.

Simultaneous Equations & Identification — Estimating a structural demand-and-supply model of the Namibian beef market (50 annual observations, 1975–2024), including Order Condition identification, reduced-form derivation, and 2SLS estimation.

Nonlinear Regression — Detailed treatment of the Marquardt algorithm for estimating an exponential production function, including the Jacobian, damping parameter, and convergence criteria.

What the Project Covers
Question 1 — Koyck Distributed Lag Model

Economic rationale for distributed lags (soil moisture, groundwater, pasture, livestock, investment effects)

Derivation and estimation of the Koyck transformation

Estimated decay rate (λ = 0.6827), long-run multiplier (0.1563), mean lag (2.15 years), and median lag (1.82 years)

Question 3 — Simultaneous Equations (Namibian Beef Market)

Explanation of endogeneity and simultaneity bias

Order Condition identification (demand overidentified; supply exactly identified)

Derivation of reduced-form price and quantity equations

2SLS estimation of structural demand and supply equations with full coefficient interpretation

Question 4 — Nonlinear Regression (Marquardt Method)

Distinction between intrinsically linear and intrinsically nonlinear models

Log-linearisation of the exponential model and its limitations

Full mathematical formulation of the Marquardt algorithm (Jacobian, damping, update rule, stopping criteria)

Advantages, limitations, and a proposed Namibian agricultural application

Tools & Software
EViews / Stata (regression output, 2SLS, nonlinear least squares)

LaTeX / Word (mathematical derivations and report formatting)

APA 7th edition referencing

Key Results
Model	Key Estimate
Koyck decay parameter (λ)	0.6827
Long-run multiplier	0.1563
Mean lag	2.15 years
Median lag	1.82 years
Demand price elasticity (2SLS)	−0.5843
Supply price elasticity (2SLS)	+0.4936
Skills Learned / Demonstrated
Econometric & Statistical Skills
Distributed-lag modelling — specifying, transforming, and interpreting finite/infinite lag structures

Koyck transformation — deriving the estimable form and recovering structural parameters

Lag-weight analysis — computing decay rates, long-run multipliers, mean and median lags

Simultaneous-equation modelling — specifying structural demand and supply systems

Identification theory — applying the Order Condition (and understanding the Rank Condition) to classify equations as under-, exactly, or over-identified

Reduced-form derivation — solving the structural system for endogenous variables in terms of exogenous variables

Instrumental Variables / 2SLS — selecting valid instruments and estimating structural parameters consistently

Nonlinear least squares — formulating the objective function, Jacobian, and Gauss-Newton/Marquardt updates

Numerical optimisation — understanding damping parameters, convergence criteria, and local vs. global minima

Data & Software Skills
Time-series data manipulation (constructing lagged variables, handling lost observations)

Running and interpreting regression output (R², adjusted R², F-statistics, t-tests, p-values)

Estimating 2SLS and nonlinear models in econometric software

Presenting results in publication-quality tables and equations

Analytical & Communication Skills
Translating econometric output into economic interpretation (not just reporting coefficients)

Distinguishing structural vs. reduced-form parameters and avoiding misinterpretation

Writing rigorous mathematical derivations with clear notation

Critical evaluation of model assumptions and limitations

Structuring a professional report to academic (APA) standards

Collaborative group work and division of technical tasks

Theoretical Understanding
Endogeneity and why OLS fails in simultaneous systems

The relationship between model transformation and error-term structure

When linearisation is valid and when it changes the estimation target

Trade-offs between algorithm stability (damping) and convergence speed

