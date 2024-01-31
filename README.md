![Movie popcorn on red background](redpopcorn.jpg)

# **Netflix Data Science Task**! 
`Your friend suspects that movies are getting shorter and they've found some initial evidence of this. Having peaked your interest, you will perform exploratory data analysis on the netflix_data.csv data to understand what may be contributing to movies getting shorter over time. `

You have been supplied with the dataset `netflix_data.csv` , along with the following table detailing the column names and descriptions:
## The data
### **netflix_data.csv**
| Column | Description |
|--------|-------------|
| `show_id` | The ID of the show |
| `type` | Type of show |
| `title` | Title of the show |
| `director` | Director of the show |
| `cast` | Cast of the show |
| `country` | Country of origin |
| `date_added` | Date added to Netflix |
| `release_year` | Year of Netflix release |
| `duration` | Duration of the show in minutes |
| `description` | Description of the show |
| `genre` | Show genre |

## Below is the breakdown of instructions.

### Load the CSV file
- `Load the CSV file and store as netflix_df.`

### Filter the netflix_df data 
- `Filter the data to remove TV shows and store as netflix_subset.`

### Filter the netflix_df data 
- `Filter the data to remove TV shows and store as netflix_subset.`

### Filter netflix_movies 
- `Filter netflix_movies to find the movies that are strictly shorter than 60 minutes, saving the resulting DataFrame as short_movies; inspect the result to find possible contributing factors.`

### Using a for loop and if/elif statements to iterate

- `Using a for loop and if/elif statements, iterate through the rows of netflix_movies and assign colors of your choice to four genre groups ("Children", "Documentaries", "Stand-Up", and "Other" for everything else). Save the results in a colors list.`

### Creation of scatter plots
- `Initialize a matplotlib figure object called fig and create a scatter plot for movie duration by release year using the colors list to color the points and using the labels "Release year" for the x-axis, "Duration (min)" for the y-axis, and the title "Movie Duration by Year of Release".`

### Sharing my observation
- `After inspecting the plot, answer the question "Are we certain that movies are getting shorter?" by assigning either "yes" or "no" to the variable answer.`


## Tool used 
`Python`

Python Library:
  - pandas
  - matplotlib


**Recommendation:** Feel free to play with the csv files and explore more. 
