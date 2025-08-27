# Lotto Data Analysis & Prediction

## Overview

This project performs **data cleaning, preprocessing, exploratory data analysis (EDA)** on a lotto dataset. The dataset contains historical draw results including winning numbers, jackpot amounts, winners, and game types.

## Features

* **Data Cleaning & Preprocessing**

  * Removed irrelevant columns (`no_draw`, `no_draw_reason`, `created_at`, `updated_at`).
  * Converted `draw_date` to datetime and extracted `year`, `month`, `day`, and `weekday`.
  * Split and counted winning numbers (`num_count`).

* **Exploratory Data Analysis (EDA)**

  * Distribution of games.
  * Jackpot winners distribution.
  * Jackpot trends over time (years).

## Requirements

* Python 3.8+
* Libraries:

  * pandas
  * numpy
  * matplotlib
  * seaborn
  * scikit-learn

Install requirements:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Place your dataset file `lotto_games.csv` in the project folder.
2. Run the Jupyter Notebook locally:

```bash
conda activate
jupyter notebook
```

3. Choose the ```bash lotto.ipynb```

## Output

* EDA visualizations:

  * Game distribution.
  * Winners distribution.
  * Jackpot trends over time (years).

## Future Improvements

* Encodes categorical features (`game type`, `weekday`).
* Uses **Linear Regression** to predict `jackpot_amount_in_php`.
* Add **classification model** to predict whether there will be winners or not.
