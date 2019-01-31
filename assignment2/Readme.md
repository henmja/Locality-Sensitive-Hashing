# Assignment 2

In this assignment you will be implementing your own decision trees. 

  * Build a **decision tree classifier** from the given training data set. Then, apply it on the test set and submit your predictions.
      - You need to build the decision tree classifier **from scratch**. (I.e., it is not allowed to use existing machine learning libraries or packages.)
      - You may use any programming language/environment of your choice, but you are required to submit the complete source code that produced your output.
      - The output (a single file with the predictions for each test instance) **must be generated automatically using the decision tree approach implemented by you**. Submitting predictions from any other source (Internet, another team, etc.) is considered cheating and will result in immediate disqualification (i.e., dismissal from the course).   
      - The autograder will automatically run your jupyter notebook to generate the predictions in a file called "submission.csv" and the autograder script will compute a score automatically. So you are not required to upload the submissions file but rather the code to generate the submissions file.
      - In order to pass this assignment, you need to reach a **Score of at least 80%** in autograder. This will be computed based on the Root Mean Square Error w.r.t to the test data.
      - A skeleton of a possible implementation in Python for an example dataset is made available in [this notebook](Decision_tree.ipynb).

* Dataset:
  - The dataset is taken from an ongoing [Kaggle competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
  - Optionally feel free to submit to the Kaggle competition
  - The dataset is for housing price prediction. Dataset description is found [here](data/data_description.txt)
    - The goal is predict the price of a house given its attributes
    - So it is a regression problem
    - Therefore your decision tree should be able to predict a value (housing price) rather than a class
    - Use appropriate splitting criterion and error function
  - The performance is evaluated using RMSE [Root Mean Square Error](https://en.wikipedia.org/wiki/Root-mean-square_deviation)
  - Training data set is [here]()
  - Test data is [here]()
