# Assignment3
# Plot the following distribuions: 
# PART-1
  >> Analyse and explore the data (size, datatype, count, describe, etc) - comment below, the count, is the result of df.printSchema() all StringType?
  >> Check for missing values in each column and apply imputation pyspark - comment below the column you found null values, % of nume values, if none type none
# PART-2
1.Distribution of Age and its relationship with the target variable (heart attack chance).
2.Bar plot for Sex distribution and its impact on the likelihood of a heart attack.
3.Count plot for exercise-induced angina (exang) and its correlation with heart attack chances.
4.Resting blood pressure (trtbps) to understand its distribution and potential impact on heart attack chances.
# PART-3
1.Scale the 'thalach' column to a common range.
2.Change the oldpeak column to round to nearest decimal
3.Assume following formula predicts if a patient gets heart attack, create a column and find ther percentage of people with risk greater than 60%:
	Risk_Score = (0.3 * Age) + (0.2 * trtbps) + (0.25 * chol) + (0.15 * ca)
4.Sclare thalch  column to 0-1 using an estimator.
