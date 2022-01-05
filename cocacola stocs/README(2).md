
# Cocacola stocks

In this project I tryed to predict mean stock price of Cocacola dataset.


## Features of dataset 
- Date 
- Open: Opening price of the day
- Close: Closeing price of the day
- High: Highest price of the day
- Low: Lowest price of the day
- Adj Close: The adjusted closing price amends a stock's closing price to reflect that stock's value after accounting for any corporate actions
- Volume: Volume is the amount of an asset or security that changes hands over some period of time, often over the course of a day
## Walkthrough
Here I explaine my notebook file

**step 1**: Loading data and extracting some information from it about attributes


**step 2**:Preprocessing:

- I did not need  more data than before 2010 so I removed them
- Finding missing values using a heatmap
- Finding correlation of attributes
- replacing non-numeric values with numeric ones ( *some of them were not binary so I reme)

**step 3**:some data analysis

**step 4**:Applying Linear Regression with a usual train test split and evaluating

**step 5**:Applying knn with a usual train test split and evaluating



      
## Results(*without optimization*)

- Linear Regression
![](https://gcdn.pbrd.co/images/oL7tfIvGk8WQ.jpg?o=1)

- KNN
![](https://gcdn.pbrd.co/images/MIJIE5tQJOhD.jpg?o=1)

## Some conclusion

So because we have linear data it is the best choise for us to use linear Regression but I used the Knn to see the result and 
as you see the knn broke the relation between datas and made them non-linear.


## Feedback

If you have any feedback, please reach out to us at Mahyarfardinfar@gmail.com

