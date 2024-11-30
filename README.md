# Mastering Hyperparameter Tuning: Classification Example  

This repository showcases the process of mastering hyperparameter tuning through a **classification problem**. The project explores manual tuning techniques alongside automated methods to optimize model performance, focusing on key hyperparameters such as layers, neurons, learning rates, and optimizers.  

## Table of Contents  
- Overview  
- Dataset  
- Key Features  
- Project Structure  
- Installation  
- Usage  
- Evaluation Metrics  
- Contributing  
- License  

## Overview  
This project is a continuation of the journey to master hyperparameter tuning. It involves building, optimizing, and evaluating classification models by exploring:  
- **Manual Tuning**: Layer-by-layer analysis to identify optimal configurations based on performance and computation time.  
- **Automated Tuning**: Leveraging tools like `RandomSearchCV` and `keras_tuner` for efficient hyperparameter exploration.  

## Dataset  
The dataset used for this project can be found [here](https://www.kaggle.com/datasets/gauravduttakiit/smoker-status-prediction-using-biosignals).  

## Key Features  
1. **Manual Tuning**  
   - Adjusted layers, neurons, learning rates, optimizers, activations, initializers, regularization, and dropout techniques.  
2. **Automated Tuning**  
   - Utilized `keras_tuner` for RandomSearch and BayesianOptimization to fine-tune hyperparameters such as `batch_size`, `model__activation`, and `model__neurons`.  
3. **Evaluation Metrics**  
   - Binary cross-entropy  
   - Accuracy  
   - Customized F1 Score  
   - ROC, AUC, and Confusion Matrix  

## Project Structure   
- [ClassificationEx_SmokingPrediction_ANN.ipynb](./ClassificationEx_SmokingPrediction_ANN.ipynb)   
- [LICENSE](./LICENSE)  
- [README.md](./README.md)  

### Data Preprocessing  
- Data Loading: Dataset imported for analysis.  
- Splitting: Train-test split for validation.  
- Scaling: Applied transformations for better model performance.  

### Installation  
- Clone this repository:  
```bash  
git clone https://github.com/ahmedomer13218/HyperParameter-Tuning_classification-example.git  

cd HyperParameter-Tuning_classification-example  
```
### Usage
- run the notebook

### Contributing
We welcome contributions! If you'd like to contribute, please fork the repository and submit a pull request.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### 
This repository demonstrates the journey from manual hyperparameter tuning to automated optimization, showcasing practical applications of tuning techniques for Classification models. 🎯
