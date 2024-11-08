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
### Scatter Plot (10/12)
I’ve created a proof of concept visualization of this data. It's a scatter plot and it shows the relationship between movie runtime and IMDB ratings. Each dot on the plot represents a movie, with its runtime on the x-axis and its rating on the y-axis. The colors of the dots are coded by genre, and users can filter the movies displayed by selecting a genre from the dropdown menu on the right. The legend, located beside the graph, lists all the available genres and their corresponding colors, allowing for an easy visual understanding of how genres relate to movie characteristics. This visualization helps identify patterns, such as whether certain genres tend to have longer runtimes or higher ratings, all while allowing interactive exploration through the genre filter.

![image](https://github.com/user-attachments/assets/9f82198b-d7f2-4da5-8b78-613e5cf15624)

Here is the link to the [visualization](https://vizhub.com/rkhan570/429e8e8914e1420590ba25713a5a95bc?mode=embed).

### World Map (10/17)
For this visualization, I initially intended to create a world map showing movie production by country based on the IMDB Top 1000 dataset. However, the IMDB dataset did not include a country column, which was essential for the map I envisioned. To overcome this limitation, I pivoted to using Netflix's title dataset, which contains a country column. This dataset allowed me to map the distribution of movies produced across different countries, represented using a color scale from grey (0 movies) to dark blue (100 movies). This map provides an interactive visualization of movie production worldwide, giving users insights into which countries have contributed the most Netflix titles.

![image](https://github.com/user-attachments/assets/ed1b0237-aa63-428f-9668-3071ed9384c3)

Here is the link to the [visualization](https://vizhub.com/rkhan570/2ac74cb664aa4253a8687beec3c46070?mode=embed).

### Bar Chart (10/17)
This visualization displays the number of movies released per decade, with data spanning from the 1920s to the 2010s. Each bar represents a decade, and hovering over a bar reveals a tooltip that provides information on the number of movies released during that decade and the title of the top-rated movie, making it easy to identify standout films across each era. This visualization offers a quick and interactive overview of movie release trends over time, highlighting both volume and popular titles by decade. 
![image](https://github.com/user-attachments/assets/ec1e5a72-5bb4-464a-a393-347a6d44b191)

Here is a link to the [visualization](https://vizhub.com/rkhan570/e580c750d66148a1bba59e3e17fb87af?mode=embed)

This bar chart illustrates the average IMDb rating across various movie genres, providing a clear comparative insight into genre preferences based on viewer ratings. Each bar represents a genre with its height reflecting the average IMDb rating of movies in that category. Additionally, hovering over a genre reveals a tooltip highlighting the top-rated movie within that genre, adding an interactive element that allows viewers to see information about that bar. 
![image](https://github.com/user-attachments/assets/bbfd0205-3221-442a-a035-7b15d5176aec)

Here is a link to the [visualization](https://vizhub.com/rkhan570/3e4ba018c8c1434baf03c6f56a945c0b?mode=embed)

### Bubble Chart (11/7)
This visualization displays the top 10 highest grossing movies in the dataset as a bubble chart. The size and the color of the bubble chart reflects whether the movie in question grossed high or low. Each bubble represents one of the 10 movies. When you hover over the bubbles, you can find out information about the movie such as its title, director's name, amount grossed, and its rating. This visualization helps to really contextualize the amount of money made by these movies and is a really quick tool to use when wanting to see information about the best selling movies.
![image](https://github.com/user-attachments/assets/b3270495-016a-426f-b073-567754e2d476)


Here is a link to the [visualization](https://vizhub.com/rkhan570/e8e436f75cd34cfc9b1f69c3cdd7a1ec?mode=embed)

## Milestones

Here is a tentative schedule for the project's progress:
* Week 1: Time series chart for movie ratings over time and bar chart for number of movies released per year.
* Week 2: scatter plot of ratings vs. runtime and bar chart for average rating per genre
* Week 3: bar chart of gross earnings per genre and bubble chart of movie ratings per director
* Week 4: bubble chart of gross earnings vs. ratings and bar chart of top 10 highest grossing movies
* Week 5: heatmap of certification trends overtime and stacked bar chart of meta score vs. IMDB ratings
* Week 6: Pie chart of genre distributions and fine tuning and adding advanced interactions
* Week 7: final polishing and presentations
