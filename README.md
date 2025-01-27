# Topsis - Multi-Criteria Decision Analysis

## Overview

The Topsis (Technique for Order of Preference by Similarity to Ideal Solution) method is a powerful decision-making tool used in multi-criteria decision analysis (MCDA). This Python package simplifies the implementation of Topsis, helping users rank and evaluate alternatives based on multiple criteria, with the flexibility to assign weights and impacts to each criterion.

## Features

Analyze alternatives effectively based on specified criteria.
Allows assigning weights to prioritize criteria and impacts to define if a criterion is beneficial or non-beneficial.
Computes rankings and scores for alternatives to identify the best choice.
Suitable for use in diverse fields like business, engineering, project management, and more.
Input Requirements

The package requires data in tabular format, with alternatives as rows and criteria as columns. Each criterion should have corresponding weights and impacts provided by the user.

## Weights: Define the relative importance of each criterion.
Impacts: Specify whether a criterion is beneficial (+) or non-beneficial (-).
How It Works

## Normalization: All criteria are normalized to ensure comparability.
Weighted Normalization: Normalized values are multiplied by their corresponding weights.
Identify Ideal Solutions: Determine the ideal (best) and anti-ideal (worst) solutions for each criterion.
Distance Calculation: Calculate the distance of each alternative from the ideal and anti-ideal solutions.
Ranking: Compute scores for each alternative based on their proximity to the ideal solution and rank them accordingly.
Applications

## Evaluating alternatives for decision-making problems.
Product comparisons in business (e.g., laptops, smartphones, etc.).
Project prioritization and resource allocation.
Selecting the best option among competing alternatives in various domains.
Output

## The output includes:

### Scores: Quantitative scores for each alternative, indicating its performance relative to others.
Rankings: Alternatives ranked from best to worst based on their scores.
Why Use This Package?

This package provides a simple and efficient way to implement the Topsis method without requiring advanced programming knowledge. It is designed to handle decision-making problems involving multiple conflicting criteria, making it a versatile tool for users in any domain.

## License

This package is open-source and available under the MIT License, allowing users to freely use, modify, and distribute it.
