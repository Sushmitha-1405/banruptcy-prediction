Financial Risk Analysis & Bankruptcy Prediction Using Genetic Algorithms

A hybrid Machine Learning model that predicts corporate bankruptcy by combining Neural Networks (NN) with Genetic Algorithms (GA) for hyperparameter optimization. Built as a Major Project at GRIET, Hyderabad (2025–2026).


-> Problem Statement

Corporate bankruptcy — especially among Small and Medium Enterprises (SMEs) — can cause widespread economic damage including unemployment, supply chain disruptions, and loss of investor confidence. Traditional prediction methods like ratio analysis fail to capture complex, nonlinear financial patterns and struggle with imbalanced datasets where bankrupt cases are rare.
This project addresses that gap with an adaptive, intelligent hybrid model.


-> Proposed Solution

A GA-optimized Neural Network that:
Learns complex, nonlinear relationships among financial indicators
Uses Genetic Algorithms to automatically find the best hyperparameters (learning rate, neurons, batch size)
Handles imbalanced datasets effectively
Provides probability-based predictions for financial risk assessment


-> System Architecture

Raw Financial Data
       ↓
Data Preprocessing (cleaning, normalization, train-test split)
       ↓
Neural Network Model (baseline training)
       ↓
Genetic Algorithm Optimization (selection → crossover → mutation)
       ↓
Optimized Neural Network
       ↓
Bankruptcy Predictions + Performance Metrics

-> Modules

ModuleDescriptionData PreprocessingHandles missing values, normalizes features, addresses class imbalanceFeature EngineeringSelects 63 relevant financial attributes and structures them into input vectorsNeural Network ModelFeedforward NN with ReLU & softmax activations, trained using backpropagationGenetic Algorithm OptimizerEvolves optimal hyperparameters via fitness evaluation, selection, crossover & mutationPrediction & EvaluationClassifies firms as bankrupt/non-bankrupt, outputs probability scores and metrics


-> Tech Stack

CategoryToolsLanguagePython 3.10+Deep LearningTensorFlow / Keras 2.15.0Data ProcessingNumPy 1.25.2, pandasVisualizationMatplotlib 3.7.1ML UtilitiesScikit-learnIDEVS Code / PyCharm


->Key Features

✅ Hybrid GA–NN model for superior prediction accuracy
✅ Handles imbalanced financial datasets
✅ Automatic hyperparameter tuning via evolutionary optimization
✅ Evaluated on accuracy, precision, recall, and F1-score
✅ Scalable across industries (agriculture, retail, construction, manufacturing)
✅ Probability-based output for risk interpretation


-> Results

The GA-optimized model outperformed the baseline neural network across all metrics:
MetricBaseline NNGA-Optimized NNAccuracyBaselineImproved ✅PrecisionBaselineImproved ✅RecallBaselineImproved ✅F1-ScoreBaselineImproved ✅
The model successfully identified financially distressed firms even in the presence of class imbalance, demonstrating robustness for real-world use.


-> Future Scope

Integration of real-time financial data streams
Addition of non-financial indicators (social media sentiment, macroeconomic factors)
Industry-specific model variants (retail, manufacturing, technology)
Explainable AI (SHAP / LIME) for transparent predictions
Cloud deployment via AWS / Azure for scalability
