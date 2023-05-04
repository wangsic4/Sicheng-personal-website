
![brooklyn bridge.png](https://s2.loli.net/2023/05/04/dZm6KRfsXtV1YGv.png)

Hello! My name is Sicheng Wang, a Master of Financial Engineering Student at Conerll Univeristy. My project and course work focuses on leveraging statistical tools and machine learning algorithms on Asset Pricing, Portfolio Construction, Credit and Market Risk Analysis. Prior to joining Cornell, I completed my undergraduate at the University of Toronto studying Statistics & Economics, and spent a summer exchanging to University of California, Berkeley, Haas School of Business. Outside of school, you'll find me traveling (18 Countries around the World and plan for more), doing long distance swimming (competitive swimmer for 7 years) and jogging.

## Proejcts

### $\dot$ Machine Learning Credit Risk Prediction (On going)
Constructed and trained Supervised Classification algorithms based on the Lending Club's Loan data from 2007 to 2018. PCA and feature engineering methods were performed to reduce redundant data and to select the most relevant features. K-fold cross-validation were applied for hyperparameter tunning. In sample prediction with different classification algorithms (ex. SVM, K-NN, and Random Forest) were performed to select the best model.   

### [Portfolio Construction via Fama-French 5 Factor Models](https://github.com/wangsic4/Sicheng-personal-website/blob/main/Fama-French%205%20Factor%20Estimation/Fama-French%20Five%20Factor%20Model.pdf)
Regression Model with 5 [Fama-French factors](https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html) is used to predict return and volatility of a bundle of stocks traded in NYSE. Constructed a portfolio consists the bundle of stocks via mean-variance analysis. The estimated stocks' returns and volatility from Fama-French Regression are used as the inputs for mean-variance analysis. Assessed Portfolio performance by comapring the back-testing results of the Fama-French estimated Portfolio to the traditional tangency Portfolio.

### [Minimum Variance Portfolio Constructio](https://github.com/wangsic4/Sicheng-personal-website/blob/main/Minimum%20Variance%20Portfolio%20Estimation/Minimum%20Variance%20Portfolio%20Construction.ipynb)
Estimated minimum-variance portfolio of 20 stocks via the least spuared method for 20 days holding period. The portfolio weighting was initial estimated by OLS regression. The OLS used the return difference of the 20th stock with the other 19 stocks as its 19 predictor $X_1....X_{19}$, and the estimated regression coefficient $\beta_1....\beta_{19}$ were the estimated weighting of the portfolio. To address the potential problem of overfitting, penalizing techniques such as Ridge and Lasso were added.


## Research

### [Macro Policy and Credit Risk Analysis of Irish Housing Market](https://github.com/wangsic4/Sicheng-personal-website/blob/main/Credit%20Risk%20Analysis%20of%20Irish%20Housing%20Market/Report.pdf)
Under the supervision of [Dr. Chris D'Souza](https://www.bankofcanada.ca/profile/chris-dsouza/) of Bank of Canada, an empirical study was conducted examing the post 2015 creit risk in Irish housing market and the macroprudential policies of Irish Central Bank. Macro-economic data and housing data (construction data, loan default data, etc) in Ireland from 2010 to 2020 were used as the predictors for the regression model. To address the potential simultaneity problem (where $X$ causes $Y$ but $Y$ can also potenitally cause $X$) using the Multiple Linear Regression model, a Simultanrous Equation model was used for the empirical analysis. Empirical findings suggests weak evidence in favor of the Irish Central Bank's policy in capping credit risk level post 2015.

### [Dollar Profit of Corporate Insider Trading](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2887628)
Supported the Research of [Professor Peter Cziraki](https://sites.google.com/site/petercziraki/) on corporate insider trading profit. Past research on insider trading suggests that there is a significant media coverage impact on insider trading activity. My main task was to collect and clean categorical data of degree of media coverage across the U.S. geographically and put the data in form of one hot encoding.
