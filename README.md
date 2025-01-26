# Sampling

## Made By
Prarthana Samal (Roll Number 102383015)

## Description
This project aims to evaluate the effectiveness of different sampling techniques and machine learning models for fraud detection in an imbalanced dataset of credit card transactions. Due to the highly imbalanced nature of the dataset, several sampling methods are explored to address the class imbalance, followed by the training and evaluation of various machine learning models.
Various sampling techniques used include:
1. **Simple Random Sampling**: Involves the random selection of samples from the entire population.
2. **Systematic Sampling**: Selects samples at regular intervals after a random starting point.
3. **Cluster Sampling**: Randomly selects entire clusters from the population.
4. **Stratified Sampling**: Divides the population into subgroups based on specific criteria for sampling.
5. **Bootstrap Sampling**: Resamples with replacement to generate multiple samples from the original dataset.


## Results Summary
| **Sampling Technique**  | **Random Forest** | **Logistic Regression** | **SVM**    | **Decision Trees** | **AdaBoost** |
|--------------------------|-------------------|--------------------------|------------|--------------------|--------------|
| Simple Random Sampling   | 98.70%           | 88.31%                  | 75.32%     | 93.51%             | 93.51%       |
| Systematic Sampling      | 99.33%           | 92.62%                  | 71.81%     | 97.99%             | 96.64%       |
| Cluster Sampling         | 98.94%           | 92.55%                  | 76.60%     | 98.94%             | 98.94%       |
| Stratified Sampling      | 100.00%          | 90.30%                  | 62.69%     | 91.79%             | 98.51%       |
| Bootstrap Sampling       | 100.00%          | 92.50%                  | 67.50%     | 95.00%             | 95.00%       |

### Key Insights:
1. Random Forest consistently delivers the highest accuracy across all sampling techniques.
2. AdaBoost demonstrates stable performance, with accuracy values ranging between 93.51% (Simple Random Sampling) and 98.51% (Stratified Sampling).
3. Stratified Sampling and Bootstrap Sampling yield the highest accuracies for most models. This suggests that these techniques may better capture the underlying data distribution compared to others, particularly for Random Forest and Decision Trees.



