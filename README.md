# UFC_Fights_Predictor
all notebooks are still work-in-progress

### 1. scrapping every UFC fighter statistics from http://ufcstats.com/ to "ufc_fighters_stats.csv"
- [x] Notebook: [Fighters_stats_scrape.ipynb](https://github.com/sagi778/UFC_Fights_Predictor/blob/main/notebooks/Fighters_stats_scrape.ipynb)
- Output file: [ufc_fighters_stats.csv](https://github.com/sagi778/UFC_Fights_Predictor/blob/main/data/ufc_fighters_stats.csv)

### 2. scrapping every UFC fight statistics from http://ufcstats.com/ to "ufc_fights_stats.csv"
- [x] Notebook: [Fights_stats_scrape.ipynb](https://github.com/sagi778/UFC_Fights_Predictor/blob/main/notebooks/Fights_stats_scrape.ipynb)
- Output data file: [ufc_fights_stats.csv](https://github.com/sagi778/UFC_Fights_Predictor/blob/main/data/ufc_fights_stats.csv)

### 3. Data Pre-Processing & Exploratory Data Analysis:
- [x] Units conversion (height, reach & weight to cm).
- [x] Replacing Null values. 
- [x] Convert fighter's record to win%
- [x] Featuring win & lose fighting streak. 
- [x] Merge [ufc_fighters_stats.csv](https://github.com/sagi778/UFC_Fights_Predictor/blob/main/data/ufc_fighters_stats.csv) & [ufc_fights_stats.csv](https://github.com/sagi778/UFC_Fights_Predictor/blob/main/data/ufc_fights_stats.csv).
- Output data file: [ufc_data.csv](https://github.com/sagi778/UFC_Fights_Predictor/blob/main/data/ufc_data.csv)

### 4. Feature Engineering
- [x] 

### 5. Training Models, Tuning & evaluating 
- [x] Fight statistics prediction model: [stats_model_training.ipynb](https://github.com/sagi778/UFC_Fights_Predictor/blob/main/notebooks/stats_model_training.ipynb)
- [x] Result prediction model: [result_model_training.ipynb](https://github.com/sagi778/UFC_Fights_Predictor/blob/main/notebooks/result_model_training.ipynb)
- [x] Method(=Decision/Submission/Knockout) prediction model: [method_model_training.ipynb](https://github.com/sagi778/UFC_Fights_Predictor/blob/main/notebooks/method_model_training.ipynb)

- **Training Random Forest model**: Optimizing model for best accuracy with minimum number of estimators
![rf_model](https://github.com/sagi778/UFC_Fights_Predictor/blob/main/pic/rf_model_opt.png)

- Final fight outcome testing & evaluating:
  **85% - 88% accurate predictions**:
  ![confusion_matrix](https://github.com/sagi778/UFC_Fights_Predictor/blob/main/pic/test_score_confusion_matrix.png)
