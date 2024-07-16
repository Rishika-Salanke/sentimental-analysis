DATASET: the file "amazon reviews" contains the dataset used to perform sentimental analysis.
CODE: the file 'code' contains the python code.
in the code the dataset is read using pandas and then only ratings and reviews column is extracted and saved into review file(loading of data)
the dataset is then cleaned before training the model(data pre processing)
using textblob the polarity of the sentiment is extracted and based on the polarity the dataset is categorised into positive , negative and neutral
using this processed data the model is trained to predict the sentiment of a comment
then the report is displayed along with the plots of the result.
a function is defined based on the trained model to predict the sentiment, it accepts the user input and gives the output as to wheather the comments is positive , negative or neutral.
