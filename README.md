# Jupyter Notebooks for "Ensemble Methods for Machine Learning"

This repository contains companion material: data, Python code and Jupyter notebooks for [Ensemble Methods for Machine Learning (Manning Publications)](https://www.manning.com/books/ensemble-methods-for-machine-learning). The code and notebooks are released under the [MIT license](https://github.com/gkunapuli/ensemble-methods-notebooks/blob/master/LICENSE).

These notebooks primarily use Python 3.7, scikit-learn 0.22 and matplotlib 3.2.1, though other packages such as pandas, seaborn and Keras make guest appearances as well.

This book is a work in progress and expected to be released some time in Fall 2022.

## List of notebooks

* Chapter 1. Ensemble Methods: Hype or Halleujah?
    * [1.3. Fit vs. Complexity in Machine-Learning Models](https://nbviewer.jupyter.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch1.3-fit-vs-complexity.ipynb?flush_cache=true)
    * [1.4. A Simple Model Averaging Ensemble](https://nbviewer.jupyter.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch1.4-model-averaging-example.ipynb?flush_cache=True)
    
* Chapter 2. Homogeneous Parallel Ensembles: Bagging and Random Forests
   * [2.2, 2.3. Bagging and Random Forest](https://nbviewer.jupyter.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch2.2and2.3-bagging-and-random-forest.ipynb?flush_cache=True)
   * [2.5. Case Study: Breast Cancer Diagnosis](https://nbviewer.jupyter.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch2.5-case-study-breast-cancer-diagnosis.ipynb?flush_cache=True)

* Chapter 3: Heterogeneous Parallel Ensembles: Combining Strong Learners
   * [3.1 Base Estimators for Heterogeneous Ensembles](https://nbviewer.jupyter.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch3.1-base-estimators-for-heterogeneous-ensembles.ipynb?flush_cache=True)
   * [3.2 Combining Predictions by Weighting](https://nbviewer.jupyter.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch3.2-combining-predictions-by-weighting.ipynb?flush_cache=True)
   * [3.3 Combining Predictions by Meta-Learning](https://nbviewer.jupyter.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch3.3-combining-predictions-by-meta-learning.ipynb?flush_cache=True)
   * [3.4 Case Study: Sentiment Analysis](https://nbviewer.jupyter.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch3.4-case-study-sentiment-analysis.ipynb?flush_cache=True)


* Chapter 4: Sequential Ensembles: Boosting
   * [4.1, 4.2 AdaBoost: Adaptive Boosting](https://nbviewer.jupyter.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch4.1and4.2-sequential-ensembles-and-Adaboost.ipynb?flush_cache=True)
   * [4.3 AdaBoost in Practice](https://nbviewer.jupyter.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch4.3-AdaBoost-in-practice.ipynb?flush_cache=True)
   * [4.4 Case Study: Handwritten Digit Classification](https://nbviewer.jupyter.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch4.4-case-study-handwritten-digit-classification.ipynb?flush_cache=True)
   * [4.5 LogitBoost: Boosting with the Logistic Loss](https://nbviewer.jupyter.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch4.5-LogitBoost-boosting-with-the-logistic-loss.ipynb?flush_cache=True)

* Chapter 5: Sequential Ensembles: Gradient Boosting
   * [5.1 Gradient Descent for Minimization](https://nbviewer.jupyter.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch5.1-gradient-descent-for-minimization.ipynb?flush_cache=True)
   * [5.2 Gradient Boosting: Gradient Descent + Boosting](https://nbviewer.jupyter.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch5.2-gradient-boosting.ipynb?flush_cache=True)
   * [5.3, 5.4 LightGBM in Practice](https://nbviewer.jupyter.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch5.3and5.4-practical-boosting-with-lightgbm.ipynb?flush_cache=True)
   * [5.5 Case Study: Document Retrieval](https://nbviewer.jupyter.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch5.5-case-study-document-retrieval.ipynb?flush_cache=True)

* Chapter 6: Sequential Ensembles: Newton Boosting
   * [6.1 Newton's Method for Minimization](https://nbviewer.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch6.1-newtons-method-for-minimization.ipynb?flush_cache=True)
   * [6.2 Newton Boosting: Newton's Method + Boosting](https://nbviewer.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch6.2-newton-boosting.ipynb?flush_cache=True)
   * [6.3, 6.4 XGBoost in Practice](https://nbviewer.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch6.3and6.4-practical-boosting-with-XGBoost.ipynb?flush_cache=True)
   * [6.5 Case Study: Document Retrieval](https://nbviewer.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch6.5-case-study-document-retrieval.ipynb?flush_cache=True)

* Chapter 7: Learning with Continuous and Count Labels
	* [7.1 A Brief Review of Regression](https://nbviewer.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch7.1-regression.ipynb?flush_cache=True)
    * [7.2, 7.3 Parallel and Sequential Ensembles for Regression](https://nbviewer.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch7.2-and7.3-parallel-and-sequential-ensembles-for-regression.ipynb?flush_cache=True)
	* [7.4 Case Study: Demand Forecasting](https://nbviewer.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch7.4-case-study-demand-prediction.ipynb?flush_cache=True)

* Chapter 8: Learning with Categorical Features
	* [8.1, 8.2	Encoding and Training with Categorical Features with category_encoders & CatBoost](https://nbviewer.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch8.1and8.2-encoding-categorical-features_with_category_encoders_and_CatBoost.ipynb?flush_cache=True)
    * [8.3 Case Study: Income Prediction](https://nbviewer.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch8.3-case-study-income-prediction.ipynb?flush_cache=True)
	* [8.4 Encoding High-Cardinality String Features](https://nbviewer.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch8.4-high-cardinality-categories.ipynb?flush_cache=True)

* Chapter 9: Explaining Your Ensembles
	* [9.1 What is Interpretability? Black-Box vs. Glass-Box Models](https://nbviewer.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch9.1-glassbox-vs-blackbox-models.ipynb?flush_cache=True)
	* [9.2 Case Study: Data-driven Marketing](https://nbviewer.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch9.2-case-study-data-driven-marketing.ipynb?flush_cache=True)
	* [9.3 Black-Box Methods for Global Explainability](https://nbviewer.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch9.3-black-box-methods-for-global-explainability.ipynb?flush_cache=True)
	* [9.4, 9.5 Black-Box Methods for Local Explainability, Glass-Box Ensembles](https://nbviewer.org/github/gkunapuli/ensemble-methods-notebooks/blob/master/Ch9.4and9.5-black-box-methods-for-local-explainability-and-glass-box-methods.ipynb?flush_cache=True)
