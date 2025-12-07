Poker Hand Analysis

This project analyzes poker hand histories to explore player behavior, bet sizing tendencies, and aggression dynamics across different hand types and game streets. The analysis includes both large-scale simulated hand data and 83 hands from professional World Series of Poker (WSOP) events to compare population-level and expert-level trends.

Project Overview

Conducted exploratory data analysis (EDA) on player actions, bet sizing, and aggression rates.

Quantified first-in aggression percentages (bet/raise share) and checked frequencies by position and hand type.

Investigated turn bet sizing distributions and the relationship between hand categories and pot commitment levels.

Analyzed WSOP hands to derive player-level aggression indices and identify stylistic differences among professionals.

Machine Learning Additions

For Sprint 3, the project introduced a full modeling pipeline to predict whether a player will take an aggressive action (bet or raise) on a given street. This included feature engineering, one-hot encoding of hand types and positions, and building a logistic regression baseline model. The model was evaluated using accuracy, precision, recall, F1 score, ROC-AUC, and coefficient interpretation to understand which features most strongly influenced aggression.
The goal of this addition was not just prediction, but using model outputs to deepen the behavioral insights found in the EDA phase.
📁 Poker-Hand-Analysis
├── data/                # Raw and cleaned datasets (hand histories, WSOP sample)
├── DataAnalysis.ipynb/           # Jupyter notebooks for EDA, modeling, and visualization
├── MachineLearningAnalysis.ipynb/ #jupyter notebooks for ML 
├── figures/             # Exported plots and summary tables
├── report/              # Sprint 2 project report (PDF + DOCX)
└── README.md            # Project summary

Key Visualizations

Turn Check % and Aggression % by Hand Type and Position

Turn Bet Size Distribution (% of Pot)

WSOP Player Aggression Index

Tools Used

Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebooks for analysis and documentation

GitHub for version control and collaboration

Author

Ogtay Orujov
University of Maryland – Social Data Science (Psychology Track)

GitHub Repository: https://github.com/ogtay/Poker-Hand-Analysis
