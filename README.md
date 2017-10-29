# Machine Learning Engineer Nanodegree
# Model Evaluation and Validation
# Project: Predicting Boston Housing Prices

## Output
### Data Exploration
Statistics for Boston housing dataset:

-   Minimum price: $105,000.00
-   Maximum price: $1,024,800.00
-   Mean price: $454,342.94
-   Median price $438,900.00<br/>
-   Standard deviation of prices: $165,171.13
-   Model has a coefficient of determination, R^2, of 0.923.

### Learning Curves
![alt text](https://raw.githubusercontent.com/nagappankv/mlnd-project2-bostonhousing/master/learning_curves.png)

### Complexity Curves
![alt text](https://raw.githubusercontent.com/nagappankv/mlnd-project2-bostonhousing/master/complexity_curves.png)

### Max depth = 5

### Sensitivity
-   Trial 1: $391,183.33
-   Trial 2: $419,700.00
-   Trial 3: $415,800.00
-   Trial 4: $420,622.22
-   Trial 5: $418,377.27
-   Trial 6: $411,931.58
-   Trial 7: $399,663.16
-   Trial 8: $407,232.00
-   Trial 9: $351,577.61
-   Trial 10: $413,700.00

Range in prices: $69,044.61


### Install

This project requires **Python 2.7**(if you complete this project in Python 3.x, you will have to update the code in various places including all relevant print statements) and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer.

### Code

Template code is provided in the `boston_housing.ipynb` notebook file. You will also be required to use the included `visuals.py` Python file and the `housing.csv` dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. Note that the code included in `visuals.py` is meant to be used out-of-the-box and not intended for students to manipulate. If you are interested in how the visualizations are created in the notebook, please feel free to explore this Python file.

### Run

In a terminal or command window, navigate to the top-level project directory `boston_housing/` (that contains this README) and run one of the following commands:

```bash
ipython notebook boston_housing.ipynb
```  
or
```bash
jupyter notebook boston_housing.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town

**Target Variable**
4. `MEDV`: median value of owner-occupied homes