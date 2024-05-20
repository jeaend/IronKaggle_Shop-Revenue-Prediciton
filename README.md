# IronKaggle - Shop Revenue Prediction Competition 

## Overview
The objective of this project is to predict the revenue of shops. The dataset contains information about various factors that might influence shop revenue, such as the number of customers, whether the shop was open, promotions, holidays, etc.

## Installation
This project requires Python and the following libraries:
- pandas
- scikit-learn

## Usage
To use the project:
1. Clone this repository.
2. Navigate to the project directory.
3. Run the ironKaggle.ipynb.

## Data
The dataset consists of the following columns:
- `shop_ID`: Shop's unique identifier.
- `day_of_the_week`: Encoded from 0 to 6.
- `date`: Day, month, and year of the data point.
- `number_of_customers`: Quantity of customers that showed up that day.
- `open`: Binary variable equal to 0 if the shop was closed that day and 1 if the shop was open.
- `promotion`: Binary variable equal to 0 if the shop had no promotions that day and 1 if it did.
- `state_holiday`: Encoded as 0, a, b, c indicating if there was a state holiday at all (0 if not), and otherwise, the number indicates which state holiday it was.
- `school_holiday`: Binary variable equal to 0 if there was a school holiday that day and 1 if not.

## Analysis
We conducted the following analysis and experimentation:
- Hypothesis Testing: Investigated relationships between variables and their impact on shop revenue.
- Feature Engineering: Created new features to improve model performance.
- Model Selection: Experimented with linear regression, decision tree regression, and random forest regression models.

## Results
Based on our analysis and experimentation, we selected the RandomForestRegressor as the final model.

**Competition Results:**
🏆🏆🏆 Our team participated in a Kaggle competition using the provided dataset. We successfully developed a model that achieved the lowest RSMA (Root Mean Squared Error) among all participants, leading us to win the competition. 🏆🏆🏆

## Future Work
Future work could include refining the model further, exploring additional features, and optimizing hyperparameters to improve prediction accuracy.

## Contributors
- [Siwar Hakim](https://github.com/siwarhakim) - fellow Data Analyst Student
- [Nuria Torres](https://github.com/NURIAT83) - fellow Data Analyst Student
