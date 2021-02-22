# Machine-Learning-Replication-Project
During the summer I decided to replicate the results of a machine learning research paper.

### 2. Reproduced work on predicting the energy usage of a house based on Internet of Things (IoT) ###

 - The following project was to reproduce a research paper by Luis M. Candanedo, Véronique Feldheim, Dominique Deramaix. The research paper was titled 'Data driven prediction models of energy use of appliances in a low-energy house'. Within the project, graphs and table information alongside a linear regression model were reproduced and compared against eachother. The data provided are the training.csv and testing.csv files.

 - The first part of the project is data cleaning procedures, such as removing NaN values or unnecessary information. Alongside this, the two data sets training.csv and testing.csv were merged. In addition to this, two new columns were made with Python PANDAS called Hour and Date, which were to be used in later tasks within the project. Furthermore, some columns (WeekStatus) were changed from string to binary for model predicting.

 - Sequentially, the next part of the project is a reproduction of graphs from the research paper. The first visual reproduced was a line plot showing appliances energy consumption over time. The next plots were a histogram and a boxplot created with Seaborn, which were used to show the distribution of energy consumption, and to locate the median for the variable 'Appliances' respectively. Following this, a pair plot was generated to show scatterplots, histograms and correlations between variables within the data, allowing for relationships to be represented. The next plots were heatmaps; which showcase hourly energy consumption of appliances throughout the weeks to find trends throughout the week. The final graph within the project is an RFECV plot for the linear regression model to evaluate its skill and performance. Note that the final graph could only be achieved after setting up the linear regression model.

 - Another component of the project is the set up of the linear regression model. The model uses numeric and non-numeric data whilst also containing a test size of 0.25 and a random state of 142. The model uses all variables to predict energy consumption of appliances and evaluation metrics (RMSE, R^2 and MAE) and are used to assess the model's performance. In addition to this a RFECV is also conducted to find the optimal number of features and the best features.
 
 - A comparison between the research paper and portfolio is also done.
