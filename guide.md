# Predicting 2024 U.S. Corn Yield  
**Take-Home Project Instructions**

---

## Objective

Build a model to **predict the 2024 U.S. national corn yield (bu/acre)** using historical USDA yield data and provided weather data. Your final output should include:

- A **point prediction** and **uncertainty estimate** for 2024.
- An evaluation of model performance on past years.
- Clear documentation of assumptions, logic, process, and key findings.

You are free to choose modeling techniques, evaluation methods, and feature design. Focus on **clarity, reproducibility, and insight**.

---

## Project Outline

### 1. Data Acquisition

- Download **historical corn yield data** at county, state, and national level from USDA quick stats.
- Load **daily county-level weather data** provided with the project, *wx_hist_df.parquet*.

### 2. Data Sanity Check

- Validate yield and weather data.
- Handle missing values, check for unit consistency, and verify dimensions.

### 3. Exploratory Data Analysis

- Explore yield trends over time and space.
- Examine relationships between weather patterns and yield outcomes.

### 4. Feature Engineering

- Derive relevant features from the raw weather data.
- Consider time windows, aggregations, and stress indicators.
- Justify your feature design choices.

### 5. Model Development & Evaluation

- Train one or more models to predict national yield.
- Evaluate performance using recent years as holdout.
- Include performance metrics and interpretability (if applicable).

### 6. Predict 2024 Yield

- Create input variables.
- Make a national yield prediction with uncertainty estimates.
- Describe assumptions behind missing/future data handling.

### 7. Reporting

- Summarize your modeling process, prediction, and findings.
- Include a brief discussion of limitations and potential improvements.

---

## Deliverables

- One clean, self-contained Jupyter notebook (`corn_yield_2024.ipynb`)
- Your notebook should:
  - Run top-to-bottom without error
  - Include markdown comments explaining key steps
  - Present your final 2024 prediction and model performance clearly

Optionally include:
- `requirements.txt` for dependencies
- `README.md` with brief setup or notes

---

## Evaluation Criteria

We will evaluate your submission based on:

- Clarity and structure of your approach
- Data understanding and problem framing
- Creativity in feature engineering and modeling
- Soundness of validation
- Communication of results and reasoning

Good luck, and enjoy the project!
