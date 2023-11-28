# Computational-Tools-For-Data-Science-Group46
What performance statistic makes a football player “good”?

In this GitHub repository, you will find:
- The data used in our study in the folder "football_data", where inside the folder you will find .csv files for the 7 top leagues in European Football
- The contributions of each group member to the project in the file Group_Members_Contributions_Project.txt
- The Jupyter Notebook Project_Comp_Tools_DS_Group46.ipynb where all our data cleaning, preprocessing and algorithm implementation takes place
- Our project report "Computational_Tools_for_Data_Science_Project_Report_Group_46.pdf"

## What is our project about?
The aim of this project is to have a more precise and accurate evaluator of a football player’s skill value. By using various data science and machine learning methods, we aim to identify the performance metric of football players we should look at first when evaluating their strictly technical and physical skills. 

This project could then further be used as a technical supplement to the strategic and business-related decision-making process of player recruiters. Our results could also be relevant for football clubs to objectively analyze and optimize their team’s and/or player’s success potential, by enhancing their decision-making processes about future investments in current and/or new players.

## How is our project organized?
Throughout the Jupyter Notebook, you will notice a first very important data cleaning and preprocessing part, followed by an analysis by clustering to highlight the specificities amongst features with regards to the player's position, i.e. goalkeeper, midfielder, forward, and defender, and lastly you will find a more thorough study per player position using clustering and regression methods to investigate which performance metric of players has the highest positive impact on their ranking.

## How to use the code and replicate the analysis
To use the Jupyter Notebook, first download the folder with the data, i.e. "football_data", on your drive and change the cell in the jupyter notebook with the appropriate path:

from google.colab import drive
drive.mount('/content/drive')
path = "drive/MyDrive/football_data/"

You can also clone this repository to simplify this path. We have commented out the previous lines of code that we used in our project so that the path is simpler:

\# from google.colab import drive
\# drive.mount('/content/drive')
\# path = "drive/MyDrive/Comp_Tools_Data_Science/football_data/"
path = "football_data/"

A last option you have if you want to have the most recent data is to go directly on the website Footystats: https://footystats.org , where we found our data. You can then download the top 7 leagues in Europe and, after checking that all the leagues have the same amount of features, add a "league" feature with the associated number and merge all 7 datasets into a single one. This is further explained in the report, and can be seen in the Jupyter Notebook as well.

Once the data is downloaded and connected to the Jupyter Notebook accordingly, you can run each cell in one go and the results and plots will appear automatically as seen in the report. Throughout the Jupyter Notebook, there will be titles and short explanations to guide you through the project and aligns with the report.