# SIEM Log Data Analysis

## Project Description

This project focuses on the analysis of Security Information and Event Management (SIEM) log data to identify patterns, detect anomalies, and evaluate different threat detection techniques. SIEM systems are crucial in collecting and storing log data from various sources, including servers, network devices, applications, and endpoints. By applying correlation and analysis techniques, the project aims to identify security breaches and assist organizations in maintaining compliance with industry regulations (e.g., HIPAA, GDPR).

## Objectives

1. **Review the state of SIEM technology** and its role in security monitoring.
2. **Analyze SIEM log data** to identify patterns and anomalies.
3. **Evaluate the effectiveness of signature-based and machine learning-based detection techniques.**
4. **Compare the performance of different machine learning algorithms** using SIEM log data.
5. **Provide recommendations** for effective threat detection techniques.

## Tools Used

- **Splunk**: For log analysis and real-time monitoring.
- **IBM QRadar**: For data correlation and threat identification.
- **ArcSight**: For log data collection and advanced correlation.
- **LogRhythm**: For comprehensive threat detection and machine learning-based anomaly detection.
- **AlienVault**: For combining SIEM with other security capabilities.

## Implementation in Python

### 1. Data Collection and Preprocessing
- Libraries: `pandas`
- Tasks: Reading logs from various formats (CSV, JSON), cleaning, and preprocessing data.

### 2. Pattern and Anomaly Detection
- Libraries: `numpy`, `scipy`, `pandas`
- Tasks: Using statistical methods to identify outliers and implementing correlation techniques to find patterns.

### 3. Signature-Based Detection
- Libraries: `re`
- Tasks: Implementing rule-based detection using regular expressions or predefined conditions.

### 4. Machine Learning-Based Detection
- Libraries: `scikit-learn`, `tensorflow`, `keras`
- Tasks: Training machine learning models to identify anomalies and threats using algorithms like Logistic Regression, Decision Trees, Random Forests, SVM, and Neural Networks.

### 5. Evaluation and Comparison
- Libraries: `scikit-learn`
- Tasks: Evaluating models using metrics like accuracy, precision, recall, and F1 score; comparing different machine learning algorithms.

### 6. Visualization and Reporting
- Libraries: `matplotlib`, `seaborn`, `plotly`
- Tasks: Creating dashboards and reports for visualization.

## Dataset

The project includes a dataset in CSV format that consists of SIEM log data used for analysis. The dataset is located in the `data` directory.

## Jupyter Notebook

The implementation is provided in a Jupyter Notebook (`SIEM_Log_Analysis.ipynb`) which contains all the steps from data collection and preprocessing to model evaluation and visualization.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/MMZeeshanAI/SIEM-Log-Analysis.git
   ```
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook SIEM_Log_Analysis.ipynb
   ```

## Results and Recommendations

The final results include a comparison of different machine learning models and recommendations for effective threat detection techniques based on the analysis performed.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
