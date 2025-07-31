
![brooklyn bridge.png](https://s2.loli.net/2023/05/04/dZm6KRfsXtV1YGv.png)

Hello! My name is Sicheng Wang, a gradute from the  Master of Financial Engineering program from the Cornell Univeristy. My project and course work focuses on leveraging statistical tools and machine learning algorithms on Asset Pricing, Portfolio Construction, Credit and Market Risk Analysis. Prior to joining Cornell, I completed my undergraduate at the University of Toronto studying Statistics & Economics, and spent a summer exchanging to Haas School of Business at UC Berkeley. Outside of school, you'll find me traveling (24 Countries around the World and plan for more), doing long distance swimming (competitive swimmer for 7 years), playing tennis, and jogging.

## <ins>Proejcts</ins>
### [*CNN-LSTM Pairs Trading Strategy for Cryptocurrency Markets*](https://github.com/wangsic4/Crypto-Pairs-Trading-Based-on-CNN-LSTM-Deep-Learning/tree/main)
Pairs trading strategy between BTC and ETH is implemented based on Deep Learning forecasting (CNN+LSTM). The strategy is based on the research paper "An Advanced CNN-LSTM Model for Cryptocurrency Forecasting" by Livieris et al. (2021) and extends their Multiple-Input Cryptocurrency Deep Learning (MICDL) model for practical trading applications.

### [*Election Arbitrage During the 2024 U.S. Presidential Election*](https://github.com/wangsic4/Sicheng-personal-website/blob/main/2024%20Election%20Arbitrage/2024%20Election%20Arbitrage.pdf)
In this study, we examine the arbitrage opportunities presented by the 2024 U.S. Presidential Election through the construction of a pair of systematic asymmetric
portfolios designed to outperform market benchmarks (e.g., the S&P 500) in the event of either candidate’s victory. The systematic approach to constructing the
asymmetric portfolios involves three key steps: 

     1. Conducting qualitative analysis of election policies to create thematic baskets.
     2. Identifying key event windows in the election cycle based on betting odds volatility.
     3. implementing dynamic floor and cap filters to select assets based on their average returns during these event windows. 
     
The asymmetric nature of the portfolios arises from the dynamic filtering mechanism, which requires assets to exceed a performance threshold during positive events while ensuring returns remain above a specified floor during negative events. Two asymmetric portfolios were constructed—one for each presidential candidate. Post-election results demonstrate that the combined performance of the asymmetric
portfolios significantly outperformed the benchmark, indicating the presence of election-driven arbitrage opportunities.


### [*VIX Volatility Index One Day Spike Forecast*](https://github.com/wangsic4/Sicheng-personal-website/blob/main/VIX%20Index%20One%20Day%20Spike%20Forecast/Wang.Sicheng.VIX_Final_Report%20copy.pdf)
Forecasting the largest single day spike in VIX index in August 2024 via the Heterogeneous Autoregressive model(HAR Model). The HAR model utilize lagged Daily, Weekly, and Monthly Volatility as predictors, first proposed by Coris(2009). To improve upon the naive OLS estimation method, the Alternative estimation methods such as Realized GARCH error term and Weighted Least Square were implemented to
the original model to improve model robustness and forecasting results.

### [*Deep Learning Stock Return Prediction & Mean-Variance Forecasting Portfolio*](https://github.com/wangsic4/Sicheng-personal-website/blob/main/Stock%20Return%20Prediction%20and%20Portfolio%20Construction%20via%20Deep%20Learning/MVF%20Report.pdf)
Utilized Forecasting techniques such as ARIMA, Machine Learning techniques such as Random Forest, and Deep Learning Alogrithms such as LSTM and CNN-LSTM for short-term stock returns prediction of the 50 top market cap equities in S&P500. The predicted return is then used as input for the Mean-Variance optimization to arrived at a Forecasting/Predictive Portfolio. Our results suggests that Markowitz Portfolios using ARIMA and CNN-LSTM forecasted returns achieves significant abnormal return compare to the tradtional Markowitz and S&P500 Index.

### [*Machine Learning Credit Risk Prediction*](https://github.com/wangsic4/Sicheng-personal-website/blob/main/Machine%20Learning%20Credit%20Default%20Prediction/Machine%20Learning%20for%20Credit%20Default%20Prediction%20Report.pdf) 
Constructed and trained Supervised Classification algorithms based on the Lending Club's Loan data from 2007 to 2018. PCA and feature engineering methods were performed to reduce redundant data and to select the most relevant features. K-fold cross-validation were applied for hyperparameter tunning. In sample prediction with different classification algorithms (ex. SVM, K-NN, and Random Forest) were performed to select the best model.   

### [*Portfolio Construction via Fama-French 5 Factor Models*](https://github.com/wangsic4/Sicheng-personal-website/blob/main/Fama-French%205%20Factor%20Estimation/Fama-French%20Five%20Factor%20Model.pdf)
Regression Model with 5 [Fama-French factors](https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html) is used to predict return and volatility of a bundle of stocks traded in NYSE. Constructed a portfolio consists the bundle of stocks via mean-variance analysis. The estimated stocks' returns and volatility from Fama-French Regression are used as the inputs for mean-variance analysis. Assessed Portfolio performance by comapring the back-testing results of the Fama-French estimated Portfolio to the traditional tangency Portfolio.

### [*Minimum Variance Portfolio Constructio*](https://github.com/wangsic4/Sicheng-personal-website/blob/main/Minimum%20Variance%20Portfolio%20Estimation/Minimum%20Variance%20Portfolio%20Construction.ipynb)
Estimated minimum-variance portfolio of 20 stocks via the least spuared method for 20 days holding period. The portfolio weighting was initial estimated by OLS regression. The OLS used the return difference of the 20th stock with the other 19 stocks as its 19 predictor X_1....X_{19}, and the estimated regression coefficient \beta_1....\beta_{19} were the estimated weighting of the portfolio. To address the potential problem of overfitting, penalizing techniques such as Ridge and Lasso were added.


## <ins>Research</ins>

### [*Macro Policy and Credit Risk Analysis of Irish Housing Market*](https://github.com/wangsic4/Sicheng-personal-website/blob/main/Credit%20Risk%20Analysis%20of%20Irish%20Housing%20Market/Report.pdf)
Under the supervision of [Dr. Chris D'Souza](https://www.bankofcanada.ca/profile/chris-dsouza/) of Bank of Canada, an empirical study was conducted examing the post 2015 creit risk in Irish housing market and the macroprudential policies of Irish Central Bank. Macro-economic data and housing data (construction data, loan default data, etc) in Ireland from 2010 to 2020 were used as the predictors for the regression model. To address the potential simultaneity problem (where X causes Y but Y can also potenitally cause X) using the Multiple Linear Regression model, a Simultaneous Equation model was used for the empirical analysis. Empirical findings suggests weak evidence in favor of the Irish Central Bank's policy in capping credit risk level post 2015.

### [*Dollar Profit of Corporate Insider Trading*](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2887628)
Supported the Research of [Professor Peter Cziraki](https://sites.google.com/site/petercziraki/) on corporate insider trading profit. Past research on insider trading suggests that there is a significant media coverage impact on insider trading activity. My main task was to collect and clean categorical data of geographic media coverage across the U.S. and put the data in form of one hot encoding.
