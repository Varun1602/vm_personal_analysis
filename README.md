Varun's Algo flow - Dynamic Rolling and Selection (Long only)


01-03-2025: 1. P_Value compare suggests that model is overfitting to noise in the data, results are good for Absolute Drawdown when we compare it with Model Accuracy on OOS.
            2. P_Value are derived from MCPT of the time series of any stock, preserving trend and blocks of trading days.. meaning block permutations to preserve reality. 
            3. Consider a Model trained on time set T, call it M_{T}.. objective of Cross_Validation is to derive a distribution of Performance Metrics using M_{T} on time set K, where K != T. 
