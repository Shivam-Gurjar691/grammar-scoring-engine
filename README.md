# SHL Grammar Scoring Engine

## Project Summary
This project builds a grammar scoring engine using simulated transcriptions and grammar errors as features. It predicts a grammar score based on the number of grammatical mistakes.

## Approach
- Added mock transcriptions to training/test data.
- Used 'language_tool_python' (locally) to count grammar issues.
- Trained a RandomForestRegressor model.
- Evaluated using RMSE.
- Generated predictions for test data.

## Evaluation Metric
RMSE: ~1.16 on validation set.

## Dependencies
- pandas
- scikit-learn
- language_tool_python (used locally)

