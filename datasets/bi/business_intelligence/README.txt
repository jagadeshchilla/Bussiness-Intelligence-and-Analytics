
Business Intelligence & Customer Analytics Results
==============================================

Directory Structure:
------------------
/data/
    - customer_data.csv: Processed customer data
    - customer_features.csv: Features used for analysis

/segmentation/
    - customer_features.csv: Clustering features and results
    - cluster_analysis.csv: Detailed cluster analysis
    - pca_visualization.csv: PCA results for visualization

/high_value_customers/
    - high_value_metrics.csv: High-value customer thresholds and metrics
    - high_value_customers.csv: List of high-value customers
    - cluster_distribution.csv: Distribution across clusters

/churn_prediction/
    - customer_churn_data.csv: Churn prediction data
    - model_performance.csv: Model performance metrics

/models/
    - kmeans_model.pkl: Clustering model
    - random_forest_best.pkl: Best Random Forest model
    - xgboost_best.pkl: Best XGBoost model
    - feature_scaler.pkl: Feature scaler
    - label_encoders.pkl: Label encoders
    - model_parameters.json: Model parameters

/analysis/
    - feature_importance.csv: Feature importance analysis
    - summary_report.json: Comprehensive analysis summary

Usage for Power BI:
-----------------
1. Import CSV files from respective folders
2. Create relationships using common identifiers
3. Use the data to create:
   - Customer segmentation dashboards
   - High-value customer analysis
   - Churn prediction monitoring
   - Feature importance visualizations
