# Kiva Crowdfunding Analysis 
# Applying machine learning to Understand Kiva Microlending aiming to alleviate poverty

# What's Here
Kiva is an international non-profit that hosts a crowdfunding platform that connects prospective borrowers with lenders to receive interest-free capital for loans of up to USD10,000 (or loans with interest above USD10,000). Kaggle, a platform that is home to machine learning open source data sets and competitions, hosted a "Data Science for Good" competition to generate some targeted machine learning models to predict information about loans and borrowers (https://www.kaggle.com/kiva/data-science-for-good-kiva-crowdfunding/data).

I decided to determine if I could predict the amount of a kiva loan based on certain information about the borrower and loan (e.g., poverty level, gender, etc.). To answer this question, I used the kiva data provided from the Kaggle competition and collection some external data on poverty (United Nations Development Programme Human Development Index data) and on presence of armed conflicts in the location of the borrower (Armed Conflict Location and Event Database project data).

I applied several different machine learning models (decision tree, random forest, linear regression) to the data in my analysis while trying to predict loan amounts below. Please enjoy reading it and let me know if you have any questions. There is still a lot to be done to tighten up these models, but this is my starting point as I continue to optimize my approach.

Have fun!

-Carole

# Data Sources

I used information from 3 different data sets:
Kaggle-Kiva data from https://www.kaggle.com/kiva/data-science-for-good-kiva-crowdfunding/data
ACLED data from https://www.acleddata.com/data/
UNDP data from http://hdr.undp.org/en/content/human-development-index-hdi
