# Denoising Autoencoder for Missing Data Imputation
When to use Denoising Autoencoder as a method to impute missing values? 

In this project I will show you how to use Denoising Autoencoders to fill missing values. Moreover, I will compare the results of a classification model with different proportions of missing values when using Denoising Autoencoder and when using more classical techniques of imputation such as using the median (for continuous variables) or a new label indicating missing values (for categorical variables). What is more, I will perform this study in 2 different data sets (“Wine Quality” - https://archive.ics.uci.edu/dataset/186/wine+quality, and “Secondary Mushroom Dataset” - https://archive.ics.uci.edu/dataset/848/secondary+mushroom+dataset), and in 3 different situations. The first situation is when we have only continuous variables. The second, when we have only categorical variables. Lastly, when we have both continuous and categorical variables.

This git is separated in 2 folders and presentation.
-	The folder Mushroom contains the study when using only categorical variables and when using continuous and categorical variables.
-	The folder Wine contains the study when using only continuous variables.
-	The presentation contains some basic explanation about the datasets, shows how to code Denoising Autoencoders, and compare the results.

In each folder (“Mushroom” and “Wine”), you can find numbered Jupyter Notebook. The first notebook contains the exploratory data analysis. The notebooks with number 2 compare the performance metrics of models without missing values, with missing values but without Denoising Autoencoder, and with missing values and with Denoising Autoencoder. The notebooks with number 3 repeat the comparisons of notebook 2 when we have missing values, but this time using bootstrap.

In conclusion, using Denoising Autoencoders presented positive results with only categorical variables, but it did not improve the performance in the other cases. 
