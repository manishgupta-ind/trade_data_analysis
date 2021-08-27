# trade_data_analysis
Final optmial range of technical indicators for maximizing P&amp;L
**Objective:** I was given a dataset (570 rows × 6 columns) containing historical trade details such as entry price, exit price, p&l and some technical indicators like atr_perc, roc and rsi. Objective was to analyze dataset in python and  try to find best range of atr_perc , roc , rsi  so that the sum of P&L is maximized for the range of values for atr_perc , roc , rsi.

**Solution:**

**Indicator	Min. Value	  Max. Value**
RSI 		    58.02 		    89.72
ATR_perc	  0.274223035   0.427709112
ROC		      -77.72927145  2633.788326

Final P&L if we take entry only when given technical indicators were within above range: Rs. 65773

Time taken by program to process complete data and generate output: 2.03 seconds
