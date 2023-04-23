# LokSabha2019

## The Indian Lok Sabha elections of 2019 witnessed an intense political battle between various political parties and their candidates. While the candidates were vying for the voters' support, it is imperative to assess the possibility of any criminal charges against them. The data for criminal cases registered against Lok Sabha MPs, who contested in the 2019 elections, has been extracted from myneta.info, a website that provides detailed information about candidates' assets, liabilities, and criminal records. The analysis of this data can be crucial in understanding the relationship between criminal charges and electoral outcomes. In this context, predicting criminal cases against the MPs contested in the 2019 Lok Sabha elections can provide valuable insights into the nature of Indian politics and the role of criminal charges in shaping electoral outcomes.

## The code provided is a Python script that scrapes data from an election website and stores it in a SQLite database. The script imports various libraries such as requests, re, sqlite3, BeautifulSoup, pandas, and numpy. The function clean_text() is defined which takes a text string as input and removes newline characters and extra spaces from both the left and right ends of the string. It also replaces a special character and removes any Unicode escape characters from the string. If the string contains a currency denominator, it removes the currency denomination and converts the remaining string into an integer. If the string is "Nil," the function converts it to an empty string. If the string contains only digits, the function converts it to an integer.

## The code then fetches data from a specific URL using the requests library and parses the data using BeautifulSoup. It extracts data from a table in the HTML using soup.find_all(), find_parent(), and find_all() methods and stores the table data in a list. It also extracts data from another table using regular expressions (re) and stores it in another list. It then establishes a connection to an SQLite database and creates two tables (candidates and winners) using SQL queries. It inserts data into these tables using the executemany() method of the cursor object and saves the changes to the database using the commit() method. 

## Pandas, NumPy, and Matplotlib libraries were used for performing fundamental data cleaning and analysis. The resulting word cloud displays the parties that had a higher number of candidates contesting in the 2019 Lok Sabha Elections.

## The results show that the predictive models produced impressive accuracies.

## The first method used is logistic regression, which produced a training accuracy of 81.05%. Logistic regression is a popular method used in predictive modeling, and it aims to find the best fit line that separates two classes. The model's accuracy indicates that logistic regression is an effective method for predicting criminal cases of Lok Sabha candidates.

## The second method used is K Neighbors, which produced a training accuracy of 81.71%. K Neighbors is a non-parametric method that works by finding the K nearest points to a given data point and classifying the data point based on the majority class of its neighbors. The model's high accuracy indicates that K Neighbors is a reliable method for predicting criminal cases of Lok Sabha candidates.

## The third method used is SVC Linear, which produced a training accuracy of 81.06%. SVC Linear is a method that finds the best separating line or hyperplane between two classes. The model's accuracy indicates that SVC Linear is an effective method for predicting criminal cases of Lok Sabha candidates.

## The fourth method used is SVC rbf, which produced a training accuracy of 81.2%. SVC rbf is a method that uses a radial basis function to separate two classes. The model's high accuracy indicates that SVC rbf is a reliable method for predicting criminal cases of Lok Sabha candidates.

## The fifth method used is Gaussian NB, which produced a training accuracy of 80.8%. Gaussian NB is a method that assumes the features are normally distributed and uses Bayes' theorem to classify data points. The model's accuracy indicates that Gaussian NB is an effective method for predicting criminal cases of Lok Sabha candidates.

## The sixth method used is Decision Tree, which produced a training accuracy of 99.5%. Decision trees are a popular method used in predictive modeling, and they work by recursively splitting the data based on the features' values to create a tree-like structure. The high accuracy of the model indicates that Decision Tree is a reliable method for predicting criminal cases of Lok Sabha candidates.

## The seventh method used is Random Forest, which produced a training accuracy of 96.4%. Random Forest is an ensemble method that combines multiple decision trees to produce a more accurate model. The model's high accuracy indicates that Random Forest is a reliable method for predicting criminal cases of Lok Sabha candidates.

## In conclusion, the impressive accuracies of the predictive models using different methods demonstrate that machine learning is a powerful tool in predicting criminal cases of Lok Sabha candidates. The methods used in this study have shown that machine learning algorithms can be used to improve the accuracy and efficiency of predicting criminal cases of Lok Sabha candidates in future elections.

