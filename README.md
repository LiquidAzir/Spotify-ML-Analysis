# Spotify Music Analysis 2023

## Overview
This project analyzes Spotify's most streamed songs to understand musical patterns, streaming success factors, and artist performance. Using Python with pandas, scikit-learn, and visualization libraries, we performed comprehensive data analysis and machine learning modeling.

## Analysis Components

### 1. Data Cleaning and Preprocessing
- Converted percentage values to decimal format
- Standardized column names
- Handled missing values in numeric and categorical columns
- Created derived features for enhanced analysis

### 2. Exploratory Data Analysis (EDA)
The EDA revealed several interesting patterns in musical characteristics:

#### Key Musical Feature Insights:
- **Danceability**: Most songs cluster between 60-80%, showing a preference for danceable tracks
- **Energy**: Similar to danceability, peaks at 70-80%, indicating high-energy songs dominate
- **Valence**: More evenly distributed, suggesting varied emotional content
- **Acousticness**: Right-skewed, meaning electronic/produced sounds are more common
- **Liveness and Speechiness**: Generally low (<20%), typical for studio recordings

### 3. Feature Engineering
Created new metrics to better understand success patterns:
- Playlist and charts presence metrics
- Streaming efficiency ratios
- Temporal features (release age, recency)
- Musical feature combinations (energy-dance ratio, valence-energy ratio)

### 4. Machine Learning Analysis
- Performed K-means clustering to identify song patterns
- Built a linear regression model to predict streaming success
- Analyzed feature importance for streaming predictions

## Key Findings

### Musical Characteristics
1. **Popular Song Patterns**
   - Most successful songs have high danceability (60-80%)
   - Energy levels typically peak at 70-80%
   - Valence (emotional tone) is evenly distributed
   - Studio recordings dominate over live recordings

### Success Factors
1. **Streaming Patterns**
   - Wide disparity between top streamed songs and average
   - Recent years show higher streaming numbers (likely due to platform growth)
   - Success isn't limited to any single musical style

2. **Temporal Trends**
   - More recent releases tend to have higher streaming numbers
   - Platform growth over time influences streaming counts
   - Recency bias in streaming behavior
   - Better optimization of songs for streaming platforms

### Artist Analysis
- Identified most consistent performing artists
- Analyzed relationship between playlist presence and streaming success
- Compared high-efficiency vs. high-volume streaming patterns

## Technical Implementation
- **Languages & Libraries**: Python, pandas, numpy, scikit-learn
- **Visualization**: matplotlib, seaborn
- **Machine Learning**: K-means clustering, Linear Regression

## Conclusions

### 1. Success Factors
- No single formula guarantees streaming success
- Musical features alone explain a small portion of streaming success
- Recent releases tend to perform better

### 2. Musical Patterns
- High energy and danceability are common in successful songs
- Production quality (studio recordings) matters
- Genre diversity suggests multiple paths to success

### 3. Platform Dynamics
- Playlist presence strongly correlates with success
- Recent songs benefit from platform growth
- Streaming optimization plays a crucial role

## Future Work
- Incorporate genre-specific analysis
- Add time series analysis for trending patterns
- Develop more sophisticated prediction models
- Include additional streaming platform data

## Requirements

python
pandas
numpy
matplotlib
seaborn
scikit-learn

## Getting Started
1. Clone this repository
2. Install requirements: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook analysis.ipynb`

## License
This project is licensed under the MIT License
