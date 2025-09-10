
# Adult Income Classification (Python)

Supervised classification on the **Adult (Census Income)** dataset to predict whether income ≥ $50K.  
This project compares classifiers built with two different algorithms (**K-Nearest Neighbors** and **Random Forest**) in terms of performance, interpretability, and fairness.  
The analysis includes exploratory data analysis (EDA), preprocessing, model training, evaluation, and a discussion of ethical and social considerations.  

## Repository Structure
```
adult-income-classification/
├── notebooks/
│   └── classification.ipynb     # Jupyter Notebook with full code and outputs
├── data/
│   └── adult.csv                # Dataset
├── report.pdf                   # Detailed report with methodology, results, and discussion
├── LICENSE
└── README.md
```

## Dataset

The project uses the **Adult (Census Income)** dataset from the UCI Machine Learning Repository, licensed **CC BY 4.0**.  
- UCI page: https://archive.ics.uci.edu/dataset/2/adult  
- Original reference:  
  Becker, B. & Kohavi, R. (1996). *Adult* [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5XW20  


## What’s Inside
- **Exploratory Data Analysis (EDA)**: distributions, correlations, and demographic insights.  
- **Preprocessing**: handling missing values, encoding categorical variables, feature scaling.  
- **Classification models**:  
  - K-Nearest Neighbors (KNN)  
  - Random Forest  
- **Evaluation**: accuracy, precision, recall, F1, confusion matrix.  
- **Comparison**: performance trade-offs between KNN and Random Forest.  
- **Ethics & bias**: reflections on fairness and societal impact of income prediction models.  

## How to Use
### Option 1: Quick View  
Open `notebooks/classification.ipynb` directly in GitHub to view code and outputs.  

### Option 2: Run Locally  
1. Clone the repository:  
   ```bash
   git clone https://github.com/JoseWongg/adult-income-classification.git
   cd adult-income-classification
   ```
2. Open the notebook:  
   ```bash
   jupyter notebook notebooks/classification.ipynb
   ```

## Authorship & Contact
Developed by **Jose Wong**  
j.wong@mail.com  
https://www.linkedin.com/in/jose-wongg  
https://github.com/JoseWongg  

## License
MIT — see the [LICENSE](LICENSE) file for details.
