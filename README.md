# Mapping Political Parties Ideological Positions

## Overview
This study proposes a machine learning approach to classify European political parties’ position on the ideological spectrum based on The Manifesto Project and the Chapel Hill Expert Survey (CHES).
- Model Input - text document representing a political party manifesto (translated in english) for each election year.
- Target - match each combination of election year-political party with their corresponding ideological score.
- Methodology - reduce text spasticity through preprocessing, apply TD-IDF vectorization, proceed with
feature selection (weighting), and compute several models.
- Approach - evaluate the best results between predicting exact score (continuous variable) against classifying into 3 groups (left, center, right).
