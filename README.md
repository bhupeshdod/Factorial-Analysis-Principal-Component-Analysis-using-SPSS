# Factorial-Analysis-Principal-Component-Analysis-using-SPSS

## Overview
This repository contains the statistical analysis of Nordstrom's brand imagery perception using IBM SPSS software. The primary objective of this analysis is to understand the impact of brand imagery factors and brand commitment on the likelihood of customer recommendation.

## Objective
To determine whether Nordstrom should focus more on brand imagery factors or on brand commitment and likelihood to purchase to increase the likelihood of recommendation.

## Data Description
The analysis uses a dataset that includes responses to various survey questions related to Nordstrom's brand imagery (Q15_3), brand commitment (Q11_3), likelihood to purchase (Q12_3), and likelihood of recommendation (Q13_3).

## Methodology
1. ### Data Preparation
- Handle missing values and adjust the scale to Interval for the variable of interest, Brand Imagery (Q15_3).

2. ### Factor Analysis
- Perform KMO and Bartlett’s test for assessing the suitability of factor analysis.<br>
- Use Principal Component Analysis for extraction with eigenvalues > 1.<br>
- Apply Varimax rotation method and Regression method for factor scores calculation.

3. ### Multiple Linear Regression
Analyze the relationship between brand commitment, likelihood to purchase, brand imagery factors, and the likelihood of recommendation.

## Analysis Results
Identified three key factors from brand imagery perception statements.<br>
Conducted multiple linear regression indicating a significant relationship between the independent variables and the likelihood of recommendation.

## Key Findings
The regression model explained 49.5% of the variance in the likelihood of recommendation.<br>
Prioritization of factors for Nordstrom’s strategy should be in the order: Brand Imagery Factor 1, Factor 2, Factor 3, and Brand Commitment.

## Equation
**Nordstrom’s Likelihood of Recommendation = 8.883 - 0.354 * Nordstrom Commitment + 0.706 * Factor 1 + 0.588 * Factor 2 + 0.585 * Factor 3**
