
# Time2Vec Experimentation Summary

## Easiest way to inspect - Download html and open it in a browser


## Overview
This repository focuses on exploring and enhancing time series analysis through various embedding techniques, including the Time2Vec approach, and evaluating their impact on model performance.

## Plan
1. **Build EDA (Exploratory Data Analysis)** to thoroughly understand the dataset.
2. **Introduce methods to build embeddings for time series** data, adding valuable features for models.
3. **Explore the Time2Vec approach** as a novel method of time series representation.
4. **Consider alternatives to Time2Vec** for comparative analysis.
5. **Provide models for experimentation**:
    - v1: Model trained on original data.
    - v2: Model trained on data enriched with embeddings.
6. **Compare metrics** to assess the impact of embeddings on model performance.
7. **Implement an LSTM model** to further leverage the time series embeddings.
8. **Further compare metrics** post-LSTM implementation.

## 1. EDA for Data Familiarization
The EDA is designed to offer deep insights into the dataset, helping us understand underlying patterns, anomalies, and correlations. It's the first step in ensuring the robustness of subsequent analyses and model training.

## 2. Embedding Techniques for Time Series
Various techniques for embedding time series data are introduced, providing diverse ways to represent time-dependent features effectively.

## 3. Time2Vec Approach
We delve into the Time2Vec approach, evaluating its methodology and effectiveness in capturing temporal patterns in time series data.

## 4. Implementation of Time2Vec Model
The implementation details of the Time2Vec model are provided, illustrating how it transforms time series data into a more informative representation for predictive models.

## 5. Data Enrichment with Embeddings
We enrich our time series dataset with the generated embeddings, aiming to enhance the dataset's informational value and predictive power.

## 6 & 7. Model Training and Evaluation
Two model versions are trained and evaluated:
   - Linear regression on original data.
   - Linear regression on data enriched with embeddings.
The performance of both models is then compared using standard metrics.

## 8. LSTM Implementation
An LSTM model is implemented to utilize the embedded data effectively, harnessing its potential in capturing sequential dependencies in time series.

## 9. Extended Metrics Comparison
Post-LSTM, we again compare metrics to gauge the effectiveness of embeddings when used in conjunction with more complex models like LSTM.

## 10. Conclusion
The Time2Vec model, as it is right now, requires a lot of refinement.

Theoretically, its ability to capture the periodic aspects of data is advantageous, but practically, this involves a series of steps:

- Identifying appropriate periodic functions for creating representations.
- Determining the optimal dimensionality for embeddings.
- Undertaking substantial efforts in dimensionality reduction, which is currently lacking.
- Addressing the issue of rapidly increasing dimensionality in more complex models.

However, on a brighter note:

- There are possibilities with other modeling approaches.
- There still exists some space for experimentation.
