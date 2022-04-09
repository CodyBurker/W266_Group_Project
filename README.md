# Data
## Raw Yelp Data 
*Used to train/test reference and base models*
### Train Set 1 (80,000 examples)
- `x_train_stage_1_sampled_yelp_data.csv`
- `y_train_stage_1_sampled_yelp_data.csv`
### Train Set 2 (80,000 examples)
- `x_train_stage_2_sampled_yelp_data.csv`
- `y_train_stage_2_sampled_yelp_data.csv`
### Test Set (20,000 examples)
- `x_test_sampled_yelp_data_NEW.csv`
- `y_test_sampled_yelp_data_NEW.csv`
## Processed Data (used to train/test ensemble models)
### BERT Predictions
- `BERT_Confidence_Predictions_80k_Stage_2.csv` (train with confidences)
- `BERT_X_Test_Confidence_Predictions.csv` (test with confidences)
- `BERT_Predictions_80k_stage_2_1_to_5.csv` (train without confidences)
- `BERT_X_Test_Predictions_1_to_5.csv` (test without confidences)
### CNN Predictions
- `CNN_Confidence_x_train_stage_2_sampled_yelp_data.csv` (train)
- `CNN_Confidence_x_test_sampled_yelp_data_NEW.csv` (test)
### T5 Predictions
- `t5_Predictions.csv` (train)
- `t5_Predictions_test20k.csv` (test)
# Notebooks
## Data Wrangling
- `yelp_data_sample_down_train_test_split_NEW.ipynb`
## Reference Models
- `NonNeuralReferenceModels.ipynb`
## Base Models
### BERT
- `BERT_final.ipynb`
- `CodyBert.ipynb`
### CNN
- `CNN-Balanced.ipynb`
- `CNN-word2vec.ipynb`
- `CNN_Confidence_Predictions.ipynb`
- `CNN_Predictions.ipynb` 
- `CodyCNNAnalysis.ipynb`
- `CodyCNNAnalysis2.ipynb`
### T5
- `t5_final.ipynb`
## Ensemble Models
- `CodyStack.ipynb`
- `Cody_Ensembles.ipynb`
- `Cody_Entropy.ipynb`
- `EnsembleDecisionTree.ipynb`
- `EnsembleLogisticRegression.ipynb`
- `ModelConfidenceAnalysis.ipynb`
- `ensembleModel_ruleBased.ipynb`
# Archive Folder
- *Older working files not needed in final report*
