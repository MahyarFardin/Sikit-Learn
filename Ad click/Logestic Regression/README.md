
# Ad click project with Logestic Regression

In this project I tried to predict whether some one with some given information
will click on an advertisement on the internet or not.



## why did I use Logestic Regression
Well, the answere is easy; it is for binary and catagorized attributes. Also I used it to 
somehow compare it with Random Forest and Decision tree ( *which is done in anothe folder in this repository* ) their accuracy rate.


## Features of dataset 
- Daily Time Spent on Site: daily Time Spent on Site by users
- Age: age of the users
- Area Income: income of the users
- Daily Internet Usage
- Ad Topic Line: the text written on the add's title
- City: City of the users
- Male: whether they are male or not
- Country: Country of the users
- Timestamp: time of the day they clicked on the Ad
- Clicked on Ad: whether or not they clicked on the add

## Walkthrough
Here I explaine my notebook file

**step 1**: Loading data and extracting some information from it about attributes


**step 2**:Preprocessing:

- Finding missing values using a heatmap
- Finding correlation of attributes
- Removeing non-numeric values ( *in another project I will replcae them with numeric values to see that whether it will increase the accuracy or not* )
**step 3**:Applying logestic regression with a usual train test split

      
## Results

![App Screenshot](https://gcdn.pbrd.co/images/POxNtOnyyLgh.jpg?o=1)


## Optimizations

As i said I have not done any Optimizations on this project and I have got a 90 percent accuracy which is good but I assume that if I replace non-numeric values with numeric ones the accuracy rate may increas

*ps: I will do this in another repository and add the link to the end of this README file*


## Feedback

If you have any feedback, please reach out to us at Mahyarfardinfar@gmail.com


## Data
("https://drive.google.com/drive/folders/1Gv0jtk73SVfXBEhjV4sX9WU_hP_w5vA3")