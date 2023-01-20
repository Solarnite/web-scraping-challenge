# web-scraping-challenge
 
# Background
For this assignment we are to use our knowlege of web-scraping to help answer some questions based on some Mars data. Through identifying HTML elements on a website and finding thier respective id's and class attributes, that information was extracted and parsed with the use of two automated browing tools, Splinter and Beautiful Soup.

# Part 1: Scrape Titles and Preview Text from Mars News
Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup).

The titles and preview text of the news articles were scraped and extracted into a list of dictionaries.

# Part 2: Scrape and Analyze Mars Weather Data

The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types.

The following questions were answered:

1. How many months exist on Mars? 
2. How many Martian days' worth of data are there? 
3. Which month, on average, has the lowest temperature? The highest?
4. Which month, on average, has the lowest atmospheric pressure? The highest?
5. How many terrestrial days exist in a Martian year?

# Results

1. There are 12 months on Mars based on the data given
2. There are 1867 days worth of data
3. The 3rd month was the coldest with a temp of -83.31°C and the 8th month was the hottest with a temp of -68.38°C
4. The 6th month had the lowest pressure of 745.1 Pa and the 9th month had the highest pressure of 913.3 Pa
5. The distance from peak to peak on the graph is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.
