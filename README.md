# Ethical-Human-Resource-Management-EHRM-with-Ethical-AI-for-Decision-Making 🤝
Ethical AI in human resource management, addressing recruitment, performance evaluation, and promotion potential. With opt-out and Fairlearn mechanisms, it ensures ethical data handling and offers models for these HR processes.
 
## Technologies Used 🛠️

- **Python**: Primary programming language
- **Libraries:**
  - Pandas, NumPy: Data manipulation
  - Scikit-learn: Modeling and evaluation
  - Seaborn, Matplotlib: Data visualization
  - Fairlearn: For model fairness

## Methodology and Trained Models ⚙️

The project follows a rigorous methodology in multiple stages:

### Data Preprocessing

- Data augmentation: Added 2000 synthetic samples to improve representativeness.
- Feature engineering: Evaluation of promotion potential and job performance.

### Data Analysis

- Histograms: Evaluation of job performance and professional experience.
- Promotion Thresholds: Establishing criteria for promotion.

### Trained Models

The code includes classification and regression models:

#### Classification Model for "Call for Interview"

- **Algorithm:** Logistic Regression
- **Precision:** Classification results with confusion matrix and detailed report.

#### Classification Model for "Promotion Potential"

- **Algorithm:** Logistic Regression
- **Precision:** Accuracy assessment with confusion matrix and classification report.

#### Classification Model for "Recruitment Goal"

- **Algorithm:** Logistic Regression
- **Precision:** Performance metrics such as accuracy and confusion matrix.

#### Regression Model for "Job Performance"

- **Algorithm:** Random Forest
- **Precision:** Accuracy measures like mean squared error and coefficient of determination.

## Fairlearn for Model Fairness 🌐

Fairlearn techniques, like the **ThresholdOptimizer**, are used to mitigate biases in predictions. The project integrates Fairlearn metrics to evaluate and monitor model fairness.

## Code Execution

1. Ensure Python is installed.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Execute the code in the order of sections to visualize each step of the process.

---

This version highlights the technical aspects, methods used, model performances, and also integrates Fairlearn to ensure model fairness.