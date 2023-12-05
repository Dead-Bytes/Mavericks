Here we have used dataset from https://www.kaggle.com/datasets/shree1992/housedata.
We have taken only 200 data points and sliced columns to make it simple.
We have also uploaded the dataset in data.csv

Descriptions are provided below

Notebook by Shourya Aswal : First I imported the data and created a pandas dataframe. Then I used seaborn library to find correlating between the features of the   
                            dataset. Then I used sklearn's linear regression ML model. I useda regression model because the targed was continous data and not descrete. Then I used matplotlib library to plot the regression graph between 'price' and 'area'. I used the linregress method from scipy library to get the slope and intercept of the regression graph. (GIT :https://github.com/ShouryaAswal )

Notebook by Aditya Bhatt : Modules used : 
                                        1) csv
                                        2) matplotlib.pyplot
                                        3) scipy
                            I used csv.reader() store data from the data.csv file in the form of a list of records. Then asked the user to input what field do they want to plot against price. I then used matplotlib.pyplot.plot() to plot the field with price (blue dots), and used scipy.stats.linregress() to find the slope, intercept, r value, p value & standard deviation of the data.Next, I used matplotlib.pyplot.plot() to plot a line with the calculated slope and intercept. Finally asked user for a value for the inputted field, to predict the price using the line plotted. ( GIT : https://github.com/adityabhatt205)

Notebook by Nishant : i have imported the libraries mathplotlib.pyplot, scipy, csv, then defined a rms function to calculate rms of no. of bedrooms and area of                             house. Then i have extracted the specific values of these columns and also the "price" column and used linregress function from scipy to perform linear regression, then plotting the data points and regression line,also defining a "predict" function, next, i  printed the accuracy of the model and then using the inputs provided by the user as parameter of the "predict" function to find the projected value of the house. (GIT : https://github.com/iampruh887)

Notebook by Pranita Mahajan : The program is basically to understand and perform linear regression on the given dataset. We import csv library in python to have an 
                              access to the csv file( comma separated file). The header row can be removed using next(cursor name) function. The data extracted from the csv file has string as the initial datatype so we need to convert it to float first to perform linear regression. Now we make separate lists for the given columns. With the help of matplotlib.pyplot library and scipy library we can plot the graph and predict certain values of the graph like slope , intercept and accuracy(r**2) respectively.Usually the price is taken as the y axis and accordingly we change the values x axis would represent and the maximum accuracy that can be achieved is 47.  (GIT :  https://github.com/pranita1305)
