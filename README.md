# Data Visualization Project

## Data

The data I propose to visualize for my project contains detailed information about top-rated movies, including the title, release year, genre, IMDB rating, director, star cast, and gross earnings. This dataset allows us to explore various aspects of movie trends, performance, and audience preferences across different dimensions like runtime, votes, and revenue.

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

* How do IMDB ratings vary over time and by genre?
* Is there a relationship between runtime and IMDB rating?
* How does gross earnings relate to IMDB rating or the number of votes?
* Are certain directors associated with higher ratings or gross earnings?
* What are the trends in movie certifications (e.g., PG, R-rated) over the years?
  
## Sketches

### Line Chart
![image](https://github.com/user-attachments/assets/26ada15e-7058-4f75-844d-37409fd2c715)

This chart shows a time series of movie ratings over time. This is a line chart displaying how average ratings fluctuate by release year. Interactions for this chart include a filter where I can filter by genre. If I click on a specific line in the graph, it pops out a box that shows information about the movie. 

### Scatter Plot
![image](https://github.com/user-attachments/assets/3cb95b2f-002a-46e8-9694-72f5e53e011a)

This chart shows a scatter plot with the movie runtime on the x-axis and ratings on the y-axis. Each dot represents a movie, and genres are color-coded. Interactions include filtering by genre, with hover details showing the title and director. If you hover over the dots, you can see the movie name with its run time and rating information.

![image](https://github.com/user-attachments/assets/74b1715c-21a7-404b-b984-409db3c24891)

### Bubble Chart
![image](https://github.com/user-attachments/assets/ba22d872-3c31-4e1a-bab8-f9ea8fa45fe2)

This is a bubble chart where the size of each bubble represents the most highly rated movies. This chart can be filtered for directors and the chart will display data only for the chosen director. If you hover over the bubble, you can see the total ratings that the movie has received.

![image](https://github.com/user-attachments/assets/7d3f4b21-2797-4714-9c0e-f5606201b056)


## Prototypes

I’ve created a proof of concept visualization of this data. It's a scatter plot and it shows the relationship between movie runtime and IMDB ratings. Each dot on the plot represents a movie, with its runtime on the x-axis and its rating on the y-axis. The colors of the dots are coded by genre, and users can filter the movies displayed by selecting a genre from the dropdown menu on the right. The legend, located beside the graph, lists all the available genres and their corresponding colors, allowing for an easy visual understanding of how genres relate to movie characteristics. This visualization helps identify patterns, such as whether certain genres tend to have longer runtimes or higher ratings, all while allowing interactive exploration through the genre filter.

![image](https://github.com/user-attachments/assets/9f82198b-d7f2-4da5-8b78-613e5cf15624)

Here is the link to the [visualization](https://vizhub.com/rkhan570/429e8e8914e1420590ba25713a5a95bc?mode=embed).

## Milestones

Here is a tentative schedule for the project's progress:
* Week 1: Time series chart for movie ratings over time and bar chart for number of movies released per year.
* Week 2: scatter plot of ratings vs. runtime and bar chart for average rating per genre
* Week 3: bar chart of gross earnings per genre and bubble chart of movie ratings per director
* Week 4: bubble chart of gross earnings vs. ratings and bar chart of top 10 highest grossing movies
* Week 5: heatmap of certification trends overtime and stacked bar chart of meta score vs. IMDB ratings
* Week 6: Pie chart of genre distributions and fine tuning and adding advanced interactions
* Week 7: final polishing and presentations
