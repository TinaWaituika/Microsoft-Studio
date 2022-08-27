Microsoft Movie Studio Project
Authors: Christine Waituika
BUSINESS UNDERSTANDING

Link to Jupyter Notebook: http://localhost:8888/notebooks/student.ipynb 
Link to GitHub Repository: https://github.com/TinaWaituika/Microsoft-Studio.git 

1.1. UNDERSTANDING THE PROBLEM

This repo helps to explore relationships between runtime, budget, genre, TMDB average vote score, and ROI. The best movies for optimizing ROI are short, low budget horror/thriller movies. These tend to have lower reviews however.The best movies for optimizing vote score and total profit are long, high budget, Action/SciFi or Action/Adventure movies. These still have ROI much higher than average movie, but may require expensive IP. Short, high budget, Animation/Adventure/Comedy movies also do very well according to all three metrics (ROI, total profit, and vote score)

1.2. PROBLEM STATEMENT

Microsoft sees all the big companies creating original video content, and they want to get in on the fun. They have decided to create a new movie studio, but the problem is they don’t know anything about creating movies. They have hired you to help them better understand the movie industry. Your team is charged with exploring what type of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

Questions to consider:

Is movie making money?
 What type of movie is making more money? What's the genre, duration(how long), budget, studio, director and writer, actor. experience, etc.
Microsoft definitely has plenty of money to jump in on the big budget movies immediately, but without knowing the quality of their other investment opportunities and given they have an existing brand that is very valuable, I wanted to present a balanced approach that considers ROI, total profit, and also "quality". Why are these questions important from a business perspective? ROI is important to decide which movie making ventures make sense to fund vs. using the money in other Microsoft projects. Total profit is important in understanding the total amount of money that can be made making movies. Vote average may be important to Microsoft's brand, depending on how clearly the movie studio is associated with the parent company. Being associated with cheap or low quality things may damage Microsoft overall, even if the movies make them more money.

2. DATA UNDERSTANDING

2.1. DATA COLLECTION
The data was collected from the folder zippedData. In the folder zippedData in the associated GitHub repository are movie datasets from: Box Office Mojo, IMDB, Rotten Tomatoes and TheMovieDB.org.

3. DATA PREPARATION

3.1. SELECTING DATA

We’ll use tables movie_basics and movie_ratings of the IMDB database and bom.movie_gross.csv.gz   as they are all relevant to the study.

3.2. DATA CLEANING

This was done to ensure the Validity, Accuracy, Completeness, Consistency and Uniformity of the Data.

The first thing done was to rename the columns to make them uniform and readable. The columns were then checked to see if they were of the appropriate types / dtypes. After this, missing values in the datasets were checked for and were found to be none.  The data was also found to be consistent there being no duplicated data.

4. DATA ANALYSIS


5. CONCLUSION
While there are many other factors that we could consider in a future analysis we feel that the following 8 conclusions will result in a successful business venture as Microsoft enters the movie industry.
We recommend that Microsoft should focus their efforts on the top 6 most profitable movie genres: Adventure, Action, Comedy, Drama, Sci-Fi and Animation. A further recommendation to focus on Sci-Fi and Animation due to less competition and a higher opportunity to profit.
We recommend that Microsoft release the bulk of their movies, especially Animation, during the summer months. Adventure, Drama and Comedy movies would see similar success if released in November, but the recommendation remains to focus on summer.
We recommend that Microsoft take into consideration the rating of the movie based on the genre and target audience. If making animation movies, it is wise to stick to a G or PG rating, otherwise PG-13 is the sweetspot. In terms of runtime, there is little correlation in terms of overall profitability.
Microsoft should research Disney's best practices and try to build off the success of this well established studio.

6. RECOMMENDATION
Microsoft should look towards Disney based upon domestic gross per theater and win rate. This means that Microsoft should on average target for a movie to be in a maxium of 3818 theaters at its peak.

