# ML_Classification
In this project, we trained three models (Artificial Neural Network, K-Nearest Neighbors and XGBoost) to predict whether event logs were malicious or not, based on generated features. The data was gathered by simulating two types of attacks and gathering and labelling these logs.
# Results
**ANN**
![image](https://user-images.githubusercontent.com/35642063/212908065-58c00d1c-d744-476a-8c48-d4afd07d589f.png)

**KNN**

![image](https://user-images.githubusercontent.com/35642063/212908152-4f8d581f-f8bf-4086-9fa9-04423b332903.png)

**XGBoost**

![image](https://user-images.githubusercontent.com/35642063/212908417-8c84d82e-2839-45eb-9684-c5084a354ac1.png)


The results of the model evaluations showed that all three models achieved very high F1 scores, with values greater than 0.99. This suggests that the models were able to accurately identify both malicious and non-malicious event logs.

Despite the high performance of these models, there are some limitations and issues to consider. One potential problem with the data is that it may have been generated using simulated attacks, which may not fully reflect the complexity and diversity of real-world attacks. Additionally, the high performance of the models may be due to overfitting, as the data was generated and labeled by the same team. Therefore, it would be essential to test these models on real-world data, as well as additional unseen data, to ensure their robustness.

Another limitation is that the features used in this study were generated based on the simulated attacks and may not be generalizable to real-world attacks. It's important to note that the feature selection process could have an impact on the performance of the models and further research may be needed to identify the most informative and relevant features for this task.

In conclusion, the models trained in this study achieved very high F1 scores on the simulated data. However, further testing on real-world data is needed to confirm the robustness and generalizability of these models. Additionally, the feature selection process should be further investigated to ensure that the most informative and relevant features are being used.
