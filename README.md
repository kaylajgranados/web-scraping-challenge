# web-scraping-challenge

*Web Scraping Challenge*

This new assignment consists of two technical products. You will submit the following deliverables:

Deliverable 1: Scrape titles and preview text from Mars news articles. Optionally export the data into a JSON file or a MongoDB database.

Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.



_Deliverable 1: Scrape Titles and Preview Text from Mars News_ 

Deliverable 1 Instructions
Create a new Jupyter notebook named mars_data_challenge_part_1.ipynb.

Scrape the Mars NewsLinks to an external site. website by using Splinter and Beautiful Soup. Specifically, scrape the title and preview text, or summary text, of each article on the landing page.

If you’d like a hint on identifying which elements to scrape, that’s totally okay. If not, that’s great too. You can always revisit this later if you change your mind.

Store all the dictionaries in a Python list.

Print the list in your notebook.



_Deliverable 2: Scrape and Analyze Mars Weather Data_ 

Deliverable 2 Instructions
Create a Jupyter notebook named mars_data_challenge_part_2.ipynb. Import the relevant dependencies for web scraping, Pandas, and Matplotlib.

With your automated browser, visit the Mars Temperature DataLinks to an external site. site. Note that the URL is https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html.

Scrape the data in the HTML table. To do so, choose one of two ways. The first, simpler way is to use Pandas's read_html method. The second, slightly more challenging way is to manually scrape the data by using Splinter and Beautiful Soup. We highly encourage you to choose the latter to reinforce your scraping skills.

If you’d like a hint on manually scraping the data, that’s totally okay. If not, that’s great too. You can always revisit this later if you change your mind.

Answer the following question: How many months exist on Mars?

Answer the following question: How many Martian (and not Earth) days worth of data exist in the scraped dataset?

Answer the following question: What are the coldest and the warmest months on Mars (at the location of Curiosity)? Get the answer by averaging the minimum daily temperature of all the months. Plot the results as a bar chart.

Answer the following question: Which months have the lowest and the highest atmospheric pressure on Mars? Get the answer by averaging the daily atmospheric pressure of all the months. Plot the results as a bar chart.

Answer the following question: About how many terrestrial (Earth) days exist in a Martian year? That is, in the time that Mars circles the Sun once, how many days elapse on Earth? Visually estimate the result by plotting the daily minimum temperature.

Export the DataFrame to a CSV file.

