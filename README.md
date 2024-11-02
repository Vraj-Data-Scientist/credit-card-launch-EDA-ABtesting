# Bank Credit Card Launch: EDA and A/B Testing

This project involves analyzing bank customer data to identify the optimal group for launching a new credit card. The analysis includes performing Exploratory Data Analysis (EDA) to uncover target customer segments, followed by A/B testing to evaluate the new credit card’s performance compared to an existing one.

## Table of Contents
- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [A/B Testing](#a-b-testing)
- [Results](#results)
- [How to Use](#how-to-use)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)

## Project Overview

The goal of this project is to provide a data-driven strategy for the new credit card launch by:
1. Conducting **Exploratory Data Analysis (EDA)** to understand customer characteristics and segment them effectively.
2. Using **A/B testing** to measure the new card’s impact on selected metrics in comparison to the existing card.

## Project Structure

- **`Bank_Credit_Card_Launch_EDA.ipynb`** - Notebook with EDA to explore customer segments.
- **`bank_credit_card_ABtesting.ipynb`** - Notebook for A/B testing to compare new and old card performance.
- **`analysis.png`** - Visual summary of key analysis results.
- **`README.md`** - Project overview and guide.

## Exploratory Data Analysis (EDA)

In the EDA, we:
- **Cleaned and processed** the data by removing duplicates, handling missing values, and engineering relevant features.
- Conducted **descriptive statistics** to summarize key data characteristics.
- Created **visualizations** to identify potential customer segments based on spending habits, demographics, and engagement with the existing credit card.

## A/B Testing

### Objective
To determine if the new credit card performs better than the old one, we conducted A/B testing, comparing metrics between a control group (old card users) and a test group (new card users).

### Hypothesis
- **Null Hypothesis (H₀):** No significant difference in performance metrics (e.g., spending, engagement) between the old and new cards.
- **Alternative Hypothesis (H₁):** The new card shows significant improvement over the old card.

### Methodology
A/B testing was used to directly compare the outcomes between control and test groups, focusing on the significance of differences in selected metrics.

## Results

Results indicate that the **new credit card improves [specific metric, e.g., customer engagement]** within the targeted demographic group, suggesting a favorable response. Detailed results and visualizations can be found in `analysis.png` and the A/B testing notebook.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Vraj-Data-Scientist/credit-card-launch-EDA-ABtesting.git
   ```

## Technologies Used

- **Python**: Data processing and analysis
- **Pandas, NumPy**: Data manipulation
- **Matplotlib, Seaborn**: Data visualization
- **A/B Testing**: For performance comparison between groups

## Contributing

We welcome contributions from the community! If you'd like to improve the model or add new features, feel free to fork this repository and submit a pull request.

## Dataset Citation
This project uses a dataset provided by Codebasics as part of the Codebasics Data Science Bootcamp. The dataset is not included in this repository due to usage restrictions.

### Citation
Note: Users interested in obtaining the dataset should contact Codebasics directly through their website to gain access. This citation is for reference purposes only.



