# Finding-Alpha-with-AI-v2

Improvements from [v1]:
1. Neural networks and tree models instead of just linear models
2. Also creating features from gold prices instead of just SPY ETF and bond prices.
3. Scoring function now accounts for shorting

In these series of jupyter notebooks, we will go over how to create simple AI models for strategies in the stock market. 

In the [first notebook], we evaluate and visualize different models to determine the correlation (aka similarity) between their outputs, in order to create diverse strategies that will perform well when combined into one model.

In the [second notebook], we compare the returns of different combinations of parameters related to data (specifically the N period interval and N period look back window) to determine the best performing combination of parameters related to data.

In the [third notebook], we evaluate different parameters of models (as opposed to data in the previous notebook), scoring them on average returns, in order to determine the best performing model parameters.

![image](https://github.com/replacementAI/Finding-Alpha-with-AI-v2/assets/55959390/0e18a23e-9fcf-4307-919b-d21e0499b527)
![image](https://github.com/replacementAI/Finding-Alpha-with-AI-v2/assets/55959390/b6165875-861d-4501-95bd-ab44f1becf52)
![image](https://github.com/replacementAI/Finding-Alpha-with-AI-v2/assets/55959390/66dcab54-1f00-49ad-9f98-72328627d5e0)
![image](https://github.com/replacementAI/Finding-Alpha-with-AI-v2/assets/55959390/617665a4-8aef-4ba7-8931-e4c30bc2044b)

[v1]: https://github.com/replacementAI/Finding-Alpha-with-AI
[first notebook]: https://github.com/replacementAI/Finding-Alpha-with-AI-v2/blob/main/Code/Step_1_Evaluating_Different_Models.ipynb
[second notebook]: https://github.com/replacementAI/Finding-Alpha-with-AI-v2/blob/main/Code/Step_2_Finding_Optimal_Interval_and_Lookback.ipynb
[third notebook]: https://github.com/replacementAI/Finding-Alpha-with-AI-v2/blob/main/Code/Step_3_Optimizing_Model_Parameters.ipynb
