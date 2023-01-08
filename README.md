# IBM Data Science Python Project for Data Science
## Analyzing Historical Stock/Revenue Data
### Project Overview
For this project, I  assumed the role of a Data Scientist / Data Analyst working for a new startup investment firm that helps customers invest their money in stocks. My job is to extract financial data like historical share prices and quarterly revenue reportings from various sources using Python libraries and web scraping on popular stocks. After collecting this data I will visualize it in a dashboard to identify patterns or trends. The stocks we will work with are Tesla, Amazon, AMD, and GameStop.

### Extracting Stock Data Using a Python Library
I will use a Python library to obtain financial data. I will extract historical stock data using yfinance library. 

### Extracting Stock Data Using Web Scraping
I will use web scraping to obtain financial data. I will extract historical stock data from a web page using the python beautiful soup web scraping library.

### Dashboard Analytics Displayed
- A dashboard often provides a view of key performance indicators in a clear way. Analyzing a data set and extracting key performance indicators will be practiced. Prompts will be used to support learning in accessing and displaying data in dashboards. Learning how to display key performance indicators on a dashboard will be included in this assignment. We will be using Plotly in this course for data visualization and is not a requirement to take this course.
- Plotly plots are not supported on GitHub, so I have inserted the images here:
    - **Plot Tesla Stock Graph**
```make_graph(tesla_data, tesla_revenue, 'Tesla')```
![Plot Tesla Stock Graph](/img/tesla.png)
    - **Plot GameStop Stock Graph** ```make_graph(gme_data, gme_revenue, 'GameStop')```
![Plot GameStop Stock Graph](/img/gamestop.png)

