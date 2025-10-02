# Machine Learning Project - Drug Consumption Classification

## Dataset
- **Source**: Drug Consumption dataset (UCI repository / academic use)  
- **Shape**: 1885 rows × 32 columns  
- **Features**: Demographic (age, gender, education, country, ethnicity) + personality traits  
- **Target**: Drug consumption patterns (classification)

##  Goal
Predict patterns of drug consumption using demographic and personality-related features.  

##  Models Used
- Logistic Regression  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Random Forest  

## 📈 Results
| Model               | Accuracy | F1-score (0) | F1-score (1) | Macro Avg F1 |
|----------------------|----------|--------------|--------------|--------------|
| Logistic Regression | 0.804    | 0.83         | 0.76         | 0.80         |
| SVM                 | 0.793    | 0.82         | 0.75         | 0.79         |
| KNN                 | 0.759    | 0.80         | 0.70         | 0.75         |
| Random Forest       | 0.806    | 0.83         | 0.77         | 0.80         |

- **Best model**: Random Forest (highest overall performance, Accuracy = 0.806)  
- **Insight**: Logistic Regression also performed competitively, showing that linear models can work well on this dataset.  

##  Next Steps
- Hyperparameter tuning to further optimize Random Forest and SVM  
- Feature importance analysis to understand the impact of demographic/personality variables  
- Apply cross-validation for more robust evaluation  
- Experiment with ensemble methods (e.g., Gradient Boosting, XGBoost)  


