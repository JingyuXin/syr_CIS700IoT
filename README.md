# syr_CIS700IoT

DataSplit_BBMAS.ipynb is used to process gait data from BBMAS [1] dataset.

m2one_prediction.ipynb can generate synthetic data and then train a many-to-one CNN-LSTM model to distinguish between pure data and synthetic data whose length is 2min with 100 Hz sampling rate (3 x 12000).

m2m_prediction.ipynb train a many-to-many CNN-LSTM model.

[1] Belman, Amith K., et al. "Insights from BB-MAS--A Large Dataset for Typing, Gait and Swipes of the Same Person on Desktop, Tablet and Phone." arXiv (2019): arXiv-1912.
