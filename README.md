## Objective:
To develop an accurate predictive model for crude oil prices using historical price data . The goal is to apply machine learning and deep learning techniques—such as LSTM, BiLSTM, CNN, and RNN—to forecast future crude oil prices, enabling better decision-making for stakeholders in the energy sector.

##  Conclusion

- **LSTM** model achieved the **highest accuracy** of **97.91%** with the **lowest MAE (0.0133)** and **RMSE (0.0196)**, making it the best performing model.
- **BiLSTM** closely followed with **97.45% accuracy**, effectively capturing bidirectional time dependencies.
-  **GRU** offered a good balance between performance and computational efficiency with **97.50% accuracy**.
-  **RNN** performed moderately with **96.17% accuracy**, but struggled with long-term dependencies.
-  **CNN** underperformed with only **80.34% accuracy**, indicating it's not well-suited for time-series forecasting in this context.
-  **Conclusion:** LSTM-based architectures are most effective for crude oil price prediction. BiLSTM and GRU are also strong alternatives.
-  **Future Scope:** Explore hybrid and transformer-based models for enhanced prediction accuracy.


