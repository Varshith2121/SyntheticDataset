Synthetic Data Factory Scalable and Domain-Agnostic Data Generation with Generative AI and Statistical Fidelity

📌 Overview
The Synthetic Data Factory is a robust, scalable framework designed to generate high-quality synthetic datasets across multiple domains including Healthcare, Finance, Retail, and the Stock Market. 
By leveraging Generative Adversarial Networks (GANs) like CTGAN and statistical models such as Gaussian Copulas, this project aims to produce privacy-preserving and utility-rich synthetic data that maintains the statistical characteristics of real data.

🎯 Features
✅ Domain-Agnostic Design: Plug-and-play architecture to support multiple domains.

🧠 Advanced Generative Models: Supports CTGAN, Gaussian Copulas, and other models.

📊 Statistical Fidelity Checks: Uses tests like the Kolmogorov–Smirnov test, correlation comparison, and distribution analysis.

📈 Data Utility Evaluation Module: Compares real and synthetic data by training ML models and evaluating metrics like accuracy, F1-score, and AUC-ROC.

🔐 Privacy-Aware Architecture: Optionally integrates Differential Privacy for secure synthetic data.

📦 Multi-source Ingestion: Accepts CSVs, databases, APIs, and external data portals (e.g., Kaggle, UCI).

📉 Real-time Streaming (Future Scope): Planned module for dynamic, real-time synthetic data generation.


🧬 Use Cases          
Medical research using synthetic patient records.

Financial simulations without exposing sensitive data.

Retail demand forecasting with anonymized customer behaviors.

Time-series model testing for trading algorithms.



🛠️ Technologies Used
Python 3.10+

CTGAN / SDV

Gaussian Copulas

Scikit-learn, XGBoost

Pandas, NumPy, Matplotlib, Seaborn

Kolmogorov–Smirnov Test, Jensen-Shannon Divergence

Streamlit (for visualization, optional)

FastAPI (optional backend support)




📈 Evaluation Metrics
Distribution Similarity (KS-Test, Wasserstein Distance)

Correlation Matrix Heatmaps

Classifier Performance (Accuracy, Precision, Recall, F1-score, AUC)

Confusion Matrix and ROC Curve visualizations



