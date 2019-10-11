# Classification-Tweet-data
## Created By Andreas Mulyarahardja
<br><br>
We are trying to build classification model to predict if user's tweet classified as Positive (1) or negative (0). We are suing tweets data which we get from using pyspark to access server. This repositories is pure educational.

<br><br>
In this repositories, we want to classify from twitter tweets, if people has positive sentiment or negative. In general, our work process is :
<br><br>

**Work Process :**

1. Importing necessary modules and packages
2. Data preprocessing, which itself divided by :
    - Data Explaratory Analysis
    - Removing Null values
    - Removing stopwords
    - Word lemmatization
    - Data Visualization (using **Target** column)
    - exporting data to csv (which is df3.csv)
3. Data sampling
4. Data Split to train and test
5. count vectorizer (to change text data to numeric using weight)
6. Modelling
7. Conclusion

<br>
<br>
Part 1-2 will be in Data Preprocessing files, and part 3-7 in Data Modelling. 
<br><br>

**Notes**

<br>
We split python files because when we model our data, it takes to long and sometimes, a loop happens and we have to restart the jupyter notebook kernel. And so, we split our python file to make it easier and faster when there are error in our modelling process
