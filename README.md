Football Pass Receiver Prediction

This project implements a high-performance machine learning system designed to predict the intended target of a football pass based on player position snapshots.
🚀 Key Features

    Learning-to-Rank (LTR) Framework: Utilizes lambdarank and ndcg objectives to evaluate 22 candidates per snapshot simultaneously.

    Advanced Geometric Engineering: Models passing lanes and interception risks using a custom Vertex-Focus Ellipse logic.

    Hybrid Ensemble: Combines the geometric precision of LightGBM with the statistical robustness of XGBoost.

    Optimized Calibration: Implements Temperature Scaling to minimize Brier Score and ensure accurate probability distribution.

📊 Results

    Top-1 Accuracy: ~42.15%

    Validation Strategy: Strict chronological split (90/10) to prevent data leakage.

    Hyperparameter Tuning: Fully optimized via systematic Grid Search.