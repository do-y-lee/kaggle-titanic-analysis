# Kaggle Titanic Survival Predictions

> Predicting passenger survival using existing and engineered features, and understanding feature importance.

---

## Motivation

On April 15, 1912, the RMS Titanic sank traveling across the Altantic Ocean from Southampton, England, to New York City. In this Kaggle exercise, I'll be using the Titanic passenger dataset to determine what features highly correlate to passenger survival. The binary classification model approach is very relevant in the real world. Using algorithms like logistic regression we can isolate important features to determine success or failure. Using Kaggle Titanic dataset, I'll be answering these questions and building a binary classification model to predict survival.

* How many passenger classes did Titanic have and what was the median age in each class?
* Were there more families or single passengers on the Titanic?
* What is the one characteristic among the passengers that determined highest probability of survival?


## Requirements

* Python 3.7.4
* pandas 1.2.3
* numpy 1.19.5
* matplotlib 3.2.0
* seaborn 0.11.1
* sklearn 0.24.2


## Data Directory

* `titanic_data/data-train.csv`: Transformed train dataset
* `titanic_data/data-test.csv`: Transformed test dataset
* `titanic_data/train.csv`: Original train dataset from Kaggle
* `titanic_data/test.csv`: Original test dataset from Kaggle


## Files 

- Exploratory Analysis & Feature Engineering: Conducted in Postgres SQL
	- [create_base_titanic_tables.sql](https://gist.github.com/do-y-lee/bc578f62e81ea34094e6ec5c9680d076#file-create_base_titanic_tables-sql)
	- [titanic_survival_by_feature_high_level.sql](https://gist.github.com/do-y-lee/3651d07c7948ca6d8fbc722f1e113fce#file-titanic_survival_by_feature_high_level-sql)
	- [titanic_train_test_missing_vals.sql](https://gist.github.com/do-y-lee/cf8e348017778ffd02b5ec6dc82d11f5#file-titanic_train_test_missing_vals-sql)
	- [titanic_overall_survival.sql](https://gist.github.com/do-y-lee/c1a8ef35d9c177f9a11e2b34a763a047#file-titanic_overall_survival-sql)
	- [titanic_sex_age_survival.sql](https://gist.github.com/do-y-lee/1db7686153f52086033d25b5a9efa78b#file-titanic_sex_age_survival-sql)
	- [titanic_survival_fare_per_passenger.sql](https://gist.github.com/do-y-lee/fa713cf76e696d4e9673b351e96139e8#file-titanic_survival_fare_per_passenger-sql)
	- [titanic_survival_title.sql](https://gist.github.com/do-y-lee/10803438c336a3ae16bcaeaeead7a713#file-titanic_survival_title-sql)
	- [titanic_is_woman_child.sql](https://gist.github.com/do-y-lee/06490fff41a1465a271d036ece23854f#file-titanic_is_woman_child-sql)
	- [titanic_cabin_level_embarked.sql](https://gist.github.com/do-y-lee/7b318760c3a12b7d297be66e2a3ae229#file-titanic_cabin_level_embarked-sql)
	- [titanic_one_family_mixed_group_alone.sql](https://gist.github.com/do-y-lee/42bb24f4e451bad627abbb7afa98dd8c#file-titanic_one_family_mixed_group_alone-sql)
	- [titanic_family_size_by_class.sql](https://gist.github.com/do-y-lee/0d08537be53ab4d1dd1e9254a623a659#file-titanic_family_size_by_class-sql)
	- [titanic_train_test_raw_v2.sql](https://gist.github.com/do-y-lee/f59524aa2df23b5efcce645b3abef281#file-titanic_train_test_raw_v2-sql)
	- [titanic_estimate_cabin_level_logic.sql](https://gist.github.com/do-y-lee/eca45e1b0437e1f11b093b0dd10d741f#file-titanic_estimate_cabin_level_logic-sql)
	- [titanic_train_test_raw_v3.sql](https://gist.github.com/do-y-lee/dce29c3dfc8148094fca477877a1aaff#file-titanic_train_test_raw_v3-sql)
	- [titanic_train_test_wcg_v0.sql](https://gist.github.com/do-y-lee/b31f4872ba93eeb0dccc3f151cdc2232#file-titanic_train_test_wcg_v0-sql)
	- [titanic_train_test_ml_features_v0.sql](https://gist.github.com/do-y-lee/e810a18ba3120438adec86489af73abb#file-titanic_train_test_ml_features_v0-sql)

- Modeling & Visualization: Conducted in Python with Jupyter notebook 
	- [Titanic_Modeling_Analysis.ipynb](https://github.com/do-y-lee/kaggle-titanic-analysis/blob/main/Titanic_Modeling_Analysis.ipynb)


## Project Technical Blogs on Medium:

- [Kaggle Titanic Competition in SQL by Do Lee](https://towardsdatascience.com/kaggle-titanic-competition-in-sql-78ae3cd551ce)
- [Kaggle Titanic Competition: Model Building & Tuning in Python by Do Lee](https://towardsdatascience.com/kaggle-titanic-competition-model-building-tuning-in-python-12f4f74436b5)


## Results

* Please check out the following [blog post](https://dolee.medium.com/surviving-the-rms-titanic-a-brief-59e8a7b80d02) on [Medium](https://medium.com/).


## Acknowledgements/References

- [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)

