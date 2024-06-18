# Module-11-Challenge
Part 1: Scrape Titles and Preview Text from Mars News
1. Open the Jupyter Notebook in the starter code folder and work in this code to scrape the Mars News website.
2. Visit the Mars news site using automated browsing. Inspect the page to identify the elements to scrape.
3. Create a Beautiful Soup object to extract text elements from the website.
4. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
   - Store each title-and-preview pair in a Python dictionary with two keys: title and preview.
   - Example:
     {'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm,"
      'preview': "For the first time in its eight years orbiting Mars, NASA's MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."}
   - Store all the dictionaries in a Python list.
   - Print the list in your notebook.

Part 2: Scrape and Analyze Mars Weather Data
1. Visit the Mars Temperature Data Site using automated browsing. Inspect the page to identify the elements to scrape. The URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.
2. Scrape the data and assemble it into a Pandas DataFrame.