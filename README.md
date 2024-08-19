# LLM_competition_mathematics_problem_solver
LLM Zoomcamp 2024 Competition. Solve high school mathematical problems with LLMs


From: https://www.kaggle.com/competitions/llm-zoomcamp-2024-competition/overview

## Overview
Welcome to the LLM Zoomcamp 2024 Competition! In this competition, participants need to solve high school mathematics problems with LLMs.

The problems originate from ЕГЭ, a high school mathematics exam in Russia.

Each problem has been translated to English using GPT-4, and additionally we provide the original Russian texts for reference.

The goal of the competition is to solve these problems with or without LLMs. Solving the problems by hand is not permitted.

## Description
Participants are tasked with developing models capable of accurately solving mathematical problems presented in both English and Russian.

The primary goal is to predict the correct answer for each problem in the test set.

The data is provided by @dremovd. Thank you for the dataset!

## Evaluation
Submissions are evaluated on the accuracy of the predicted answers. Accuracy is defined as the proportion of correct predictions out of the total number of problems in the test set. The higher the accuracy, the better your model performs.

### Submission Guidelines
The file must be a CSV file.
The file should contain exactly two columns: problem_id and answer.
Each problem_id should match the IDs provided in the test set.
Each answer should be the predicted solution to the corresponding problem.
Ensure that there are no missing or extra rows, as this will result in a submission error.
### Evaluation Metric
The primary evaluation metric for this competition is accuracy, calculated as:

Accuracy = Number of Correct Predictions / Total Number of Problems

Your submission will be compared to the ground truth answers provided in the test set. The submission with the highest accuracy will be considered the winner.

### Example Submission
Here is an example of how your submission file should look:

problem_id,answer
11919,11
8513,12
7887,44
5272,13
8295,31
3219,15
7235,51
3688,12
6116,128
...
Make sure to validate your submission file format and contents before uploading to avoid any errors. Good luck!

### Citation
ololo. (2024). LLM Zoomcamp 2024 Competition. Kaggle. https://kaggle.com/competitions/llm-zoomcamp-2024-competition


