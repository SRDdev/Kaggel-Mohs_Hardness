# Regression with a Mohs Hardness Dataset
## Kaggle Playground Series - Season 3, Episode 25

### Overview

Welcome to the 2023 Kaggle Playground Series! This competition, titled "Regression with a Mohs Hardness Dataset," is part of Season 3, Episode 25. We appreciate the active participation and contributions from the Kaggle community in this series.

#### Your Goal
Your task for this episode is to use regression techniques to predict the Mohs hardness of a mineral based on its properties. Best of luck!

- **Competition Status:** 497 teams currently competing.
- **Time Remaining:** 17 days.

### Evaluation

Submissions will be evaluated based on the Median Absolute Error (MedAE). The MedAE is calculated as the median of the absolute differences between the predicted values and the ground truth for each observation.

**MedAE Formula:**
\[ MedAE(y, \hat{y}) = median(|y_1 - \hat{y}_1|, ..., |y_n - \hat{y}_n|) \]

### Submission File Format

For each id row in the test set, you must predict the value for the target Hardness. Your submission file should have the following format:

```plaintext
id,Hardness
10407,4.647
10408,4.647
10409,4.647
... 
```

### Directories

Notebooks has all the latest experiments for this competition.