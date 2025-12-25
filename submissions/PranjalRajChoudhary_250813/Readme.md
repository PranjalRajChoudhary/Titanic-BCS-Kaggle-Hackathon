Titanic Submission - Pranjal Raj Choudhary

## Stats
- **Kaggle Leaderboard Rank:** 14,707/15992
- **Public Score (Accuracy):** 0.74641
- **Other Evaluation Metrics:** 
Class 0 (Did not survive) Precision, Recall and f1 score -> 82%, 85%, 84%
Class 1 (Did survive) Precision, Recall and f1 score -> 75%, 71%, 73%


## Approach

- **Model Used:** LogisticRegression
- **Data Handling:** Used median values grouped by Pclass and Sex to fill in missing Age values.
Removed Cabin, Parch and SipSp features because they seemed irrelevant to me


## Key Learnings

- This didn't perform that well, we should use new model such as Decision Trees or maybe engineer new features.
