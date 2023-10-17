# Augmented Dickey-Fuller (ADF) Test:
- The ADF test is a statistical test used to determine whether a given time series is stationary or non-stationary. A stationary time series is one whose statistical properties, such as mean and variance, remain constant over time. In contrast, a non-stationary time series exhibits trends or seasonality and has statistical properties that change over time.
The ADF test is based on the following autoregressive (AR) model:
# Δyt​=α+βyt−1​+γΔyt−1​+δ1​Δyt−2​+…+δp​Δyt−p​+ϵt​
- Where:
 -   • yt​ is the time series at time t.
   -  • Δyt​ is the differenced time series at time t, which represents the change between consecutive observations.
  -   • α is a constant.
  -   • β measures the impact of the lagged value yt−1​ on the current change Δyt​.
  -   • γ accounts for any remaining autocorrelation in the differenced series.
  -   • δ1​,δ2​,…,δp​ are coefficients of lagged differences.
  -   • ϵt​ is a white noise error term.
## Interpretation of the ADF Test:
-  The null hypothesis (H0​) of the ADF test is that the time series has a unit root, making it non-stationary. The alternative hypothesis (H1​) is that the time series is stationary.
  -   • If the test statistic (ADF statistic) is less than the critical values (determined by significance level and sample size), we reject the null hypothesis (H0​) and conclude that the time series is stationary.
-     • If the test statistic is greater than the critical values, we fail to reject the null hypothesis and conclude that the time series is non-stationary.
# Random Walk Model:
- The random walk is a specific type of non-stationary time series. It can be represented as:
- yt​=yt−1​+ϵt​
- Where:
-     • yt​ is the value of the time series at time t.
-     • yt−1​ is the value at the previous time step.
 -    • ϵt​ is a white noise error term.
- In the random walk model, each new value (yt​) is equal to the previous value plus a random shock (ϵt​). This randomness makes the random walk non-stationary because the mean and variance of the series change over time.
