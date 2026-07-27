Analyzing sales between the fourth week of March 2026 and the third week of June 2026, total sales peaked in the second and third weeks of April. Daily sales data was aggregated by week and visualized using a bar chart. Our objective is to forecast sales over the next four to eight weeks and, from that, deduce demand by product.

A seasonal decomposition of the time series would not be possible without at least two full cycles of data. Since the selected granularity is weekly, 104 weeks (i.e., 52 × 2) of data would be required. The mean weekly sales is around 22.98 million INR, while the standard deviation is nearly 9.65 million INR.

The forecast horizon depends on the lead time of the various products. To evaluate forecast accuracy, metrics such as forecast bias, root mean squared error (RMSE), and mean absolute error (MAE) will be used. We could use adjusted R² for feature selection.

The Augmented Dickey-Fuller (ADF) test on the sales data returned a p-value greater than 0.05, and the 5% critical value is more negative than the test statistic. Hence, we fail to reject the null hypothesis that the series is non-stationary. The time series will need to be made stationary, most likely through differencing.
