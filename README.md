
A Project by Team Colab


INTRODUCTION

Crimes against women is a popular human right violation in the world, this is why there are a lot of laws and policies to protect women's gender.  Violence against women refers to physical and sexual violence committed against women, common violence against women in India are acts such as domestic abuse, sexual assault, and murder.

Team colab was given the dataset of crimes against women in India, this data contained information on the different crimes committed against women in different states from 2001-2014.



OBJECTIVE

The objective of the project is to analyze and draw insight from the dataset.

The team used python libraries such as Pandas and NumPy to analyze the data, Matplotlib and Seaborn to build the visualizations needed.



DATASET DESCRIPTION

The dataset was downloaded from Kaggle[1]. It consists of 10677 rows and 11 columns. The columns include:Year, Rape, Kidnapping and Abduction, Dowry Deaths, Assault on women with intent to outrage her modesty, insult to modesty of women, Cruelty by Husband or his relatives, and importation of girls. Fig 1 shows a statistical description of the numerical columns in the dataset.



  Fig 1. Dataset Description



METHODOLOGY

Data Wrangling/Cleaning
This involved handling irrelevant/missing data and any features that weren’t necessary for the analysis. There were no missing values in the dataset. The columns were renamed for easy identification and analysis. There were 72 duplicates on the states column due to different naming conventions which had to be cleaned, white spaces were removed and duplicates were removed.


Exploratory Data Analysis (EDA) and Visualization
Bar charts were used to represent the total crime rate by year while line charts and pie charts were used to represent the different crime rates in respect to one another in the different states.

Based on the dataset,the crime rates steadily increased each year and Fig 2 shows this information. With 2014 having the highest number of crimes.Importation of Girls was the most erratic. Cruelty by Husband and his Relatives had the highest rate of crime in India from 2001-2014, while the lowest was Importation of Girls. The state with the highest crime is Uttar Pradesh while the state with the lowest crime is Lakshadweep.




Fig 2: Crime rate by year


The total number of crimes steadily increased from 2001 to 2014 with a value of  265,000 in 2001 to a value of 652,000 in 2014. Of the women living in India, 7.5% live in West Bengal where 5.05% of the total reported crime against women occurs. Andhra Pradesh is home to 7.3% of India's female population and accounts for 5.41% of the total reported crimes against women.


Out of the various crimes committed against women from 2001 to 2014, cruelty by husband or his relatives constituted about 41.98% which is the highest, followed by assault on women with intent to outrage her modesty with 22.78%, then kidnapping and abduction with 14.02% as shown in fig 3 below.



Fig 3. Distribution of crimes 2001 to 2014




Fig 4: Crime Rate based on State




CONCLUSION

From the above analysis, we can see that crime against women in India from 2001-2014 was progressing rapidly with Cruelty by Husbands contributing to most of the crime. This may be because in India the societal norms favours the masculinity of men. Men believe they are superior, and women should endure violence to keep the home together.

The variations of crime presented in this report are only a few of the many insights that can be obtained from the data. The methods can also be applied on other types of data.


RECOMMENDATION

More women rights groups should be created to protect women and give them a place of refuge when they need it, especially for married women.
There should be people who enforce “The Protection of Women from Domestic Violence Act (PWDVA) 2005”.
Reachout programs should be carried out in various states and cities to educate and enlighten Indian women on their rights.


REFERENCE 

The dataset was downloaded from Kaggle: https://www.kaggle.com/datasets/greeshmagirish/crime-against-women-20012014-india?resource=download 
Kapila, Pallavi. (2020). Crimes against Women: An Overview of Indian scenario.
