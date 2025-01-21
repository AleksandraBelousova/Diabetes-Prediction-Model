### Core Features:
- Data pre-processing: Strategic imputation of zero values with column averages for pristine data continuity.
- Advanced modelling: Implementation of CatBoost 
- Hyperparameter tuning: RandomisedSearchCV to fine-tune model parameters.
- Performance Metrics: Evaluation with ROC-AUC scoring and comprehensive feature importance metrics.
### Technical Stack Requirements:
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- CatBoost
### Run the pipeline:
1. Data curation:
   - Impose null values with means for specified numeric attributes.
2. Dataset splitting:
   - Use `train_test_split` to generate stratified training and test datasets.
3. Algorithm deployment and optimisation:
   - Deploy CatBoost and refine with `RandomisedSearchCV`.
4. Model evaluation:
   - Visualise performance using ROC curves and carefully evaluate the importance of features.
5. Model selection:
   - Finalise the optimal model configuration based on the best ROC-AUC performance analysis.
### Contribution protocol:
Contributions are strongly encouraged. Please initiate a fork of the repo and submit a pull request with carefully documented improvements.
