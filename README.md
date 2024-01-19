# ML-HousePricePredictor

## Description
The goal of this project is to compare Linear Regression, KNN, Random Forest Tree, and Gradient Boosting algorithms using the scikit-learn library on the House Price dataset.

## Implementation

Before using the dataset in algorithms, we need to make slight adjustments to enhance the algorithm's performance.

  1) Shuffle dataset.
  
  2) Make one-hot value from column 'ocean_proximity'.
  
  3) Put 'median_house_value' column (target) as last column.
  
  4) Drop rows with missing data

Now our dataset is ready to run through all algorithms.

## Results

|   | Score  | MSE |
| :------------ |:---------------:| -----:|
| Linear Regression     | 0.646 | 68593.056 |
| K nearest neighbors      | 0.783        |   53759.099 |
| Random forest tree | 0.858        |    43468.472 |
| Gradient Boosting  | 0.832       |    47274.822 |

## Author

- [@BrankoTrifkovic](https://www.linkedin.com/in/branko-trifkovic/)
