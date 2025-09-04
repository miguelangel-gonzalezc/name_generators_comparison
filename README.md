# Collecting a large number of alters in egocentric network research: A comparative analysis of three approaches
This is the official repository that includes the clean data required to reproduce the results presented in the article with DOI: [https://doi.org/10.1016/j.socnet.2025.07.004](https://doi.org/10.1016/j.socnet.2025.07.004)

All the data is contained in .csv files. There are three types of files: 
- {NG}\_ego\_df.csv
- {NG}\_{i}\_alters_df.csv
- {NG}\_{i}\_edgelist.csv

{NG} refers to the treatment group (name generator), which can be FCh (Free Choice), M20 (Minimum 20) or F30 (Fixed 30). 

{i} refers to the respondent's ID. 

- The files {NG}\_ego\_df.csv contain all the information about the respondents in each name generator: Gender, Age, Residency and Survey Time (in seconds)
- The files {NG}\_{i}\_alters_df.csv contain all the information about the alters named by respondent i in each name generator: Gender, Age, Residency, Emotional Proximity with the respondent and Context in which the respondent and the alter met. 
- The files {NG}\_{i}\_edgelist.csv contain the edgelists of the ego network reported by the respondent i in each name generator. It has two columns with the IDs of the two alters involved in a link, and a third column specifying if the respondent considers that there is a link, stating Yes, Maybe or No. 


