# Google Play Store Apps Analysis and Insights

This project analyzes the Google Play Store Apps dataset from Kaggle to derive insights, analyze user sentiments, and recommend app replacements. The analysis is divided into three main parts:

## Overview

### Part 1: Exploration
- Clean and explore the dataset.
- Visualize key metrics (e.g., categories, ratings, reviews).
- Derive initial insights.

### Part 2: Sentiment Analysis
- Analyze the distribution of sentiments in user reviews.
- Compare results from an LLM-based model and a specialized sentiment analysis model.

### Part 3: Insights and Recommendations
- Extract user opinions by combining app and review data.
- Generate a synthetic dataset of users and their installed apps.
- Recommend app replacements for poorly rated apps.

## Results
* The result for the recommendation are stored in the `recommendations_results.txt` file.

## Installation and Setup

### Step 1: Install Requirements
1. Ensure you have Python installed (preferably Python 3.7 or higher).
2. Install the required packages using pip:
    ```sh
    pip3 install -r requirements.txt
    ```

### Step 2: Set Up Environment Variables
1. Create a `.env` file in the root directory of your project.
2. Add the `OPEN_API_KEY` to environment variables to the `.env` file like:
    ```env
    OPENAI_API_KEY=your_openai_api_key
    ```

### Step 3: Run the Jupyter Notebook
1. Launch Jupyter Notebook:
    ```sh
    jupyter notebook
    ```
2. Open the `google_play_store.ipynb` file and run the cells to perform the analysis.