# Franchises 

UCD Data Science in Practice (COMP30780)

by Joshua Harris and Adam Brennan

The goal of this project is to analyse franchises across different media and discover how well they perform as more content is released, paying particular attention to the frequency and regularity of the content, and how well they handle negative ratings and flops. We also examine the Marvel and DC franchises to see how they perform against eachother across both industries. 

The notebooks are organised in run order and can be roughly organised as follows:
Data Collection:
-   100_IMDB_Datasets.ipynb - Downloads zip files from IMDB, containing all individual movie and game information and converts them to dataframes. 
-   101_GiantBomb.ipynb - Scrapes lists of game franchises, games associated with those franchises and game metadata from Giantbomb and converts them to dataframes. 
-   102_Wikipedia.ipynb - Scrapes lists of movie franchises and movies associated with those franchises from Wikipedia and converts them to dataframes. 

Data Cleaning:
-   103_IMDB_Wiki_Matching.ipynb - Matches any movies found on Wikipedia to movies in our IMDB dataframe by title and year. 
-   104_IMDB_Giantbomb_Matching.ipynb - Matches any games found on Giantbomb to games in our IMDB dataframe by title and year, then performs fuzzymatching to determine the best matches for the remainder.
-   105_Initial_Analysis.ipynb - Creates dataframes that we will use for our analysis and performs initial examinations on the characteristics of our data.

Data Analysis:
-   106_RQ1.ipynb - Examines the relation of frequency and regularity of a franchises release schedule, and the subsequent rating and vote count.
-   107_RQ2.ipynb - Examines the effects of negative ratings and flops on a franchise. 
-   108_CaseStudy.ipynb - Examines how the Marvel and DC franchises perform across movies and games. 


