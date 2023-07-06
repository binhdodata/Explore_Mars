<!DOCTYPE html>
<html>


<h1>Mars Weather Data Analysis</h1>

<h2>Project Overview</h2>

<p>
    This project is aimed at leveraging the power of web scraping, data analysis, and visualization to gather and analyze news articles and weather data from Mars. The data is primarily sourced from the Mars News Site and the Mars Temperature Data Site.
</p>

<h2>Libraries Utilized</h2>

<p>
    Several Python libraries were utilized in this project, each serving a unique purpose:
</p>

<ol>
    <li><strong>Python</strong>: The fundamental programming language utilized throughout the project.</li>
    <li><strong>Pandas</strong>: This library provided tools for data manipulation and analysis, which were crucial in handling, analyzing, and exporting the scraped data.</li>
    <li><strong>BeautifulSoup</strong>: Used to parse HTML and XML documents, aiding in the extraction of relevant data from the Mars News and Mars Temperature Data Sites' HTML pages.</li>
    <li><strong>Splinter</strong>: This Python library facilitated automating browser actions, specifically visiting the Mars News and Mars Temperature Data Sites.</li>
    <li><strong>Matplotlib</strong>: A powerful plotting library utilized in creating static, animated, and interactive visualizations in Python, crucial in visualizing the analyzed data.</li>
</ol>

<h2>Deliverables</h2>

<p>
    The project is split into two key sections:
</p>

<h3>Part 1: Mars News Scraping</h3>

<ul>
    <li>Mars News website was visited using automated browsing, and HTML code was extracted with BeautifulSoup.</li>
    <li>Titles and preview text of news articles were then scraped and extracted.</li>
    <li>The scraped data was subsequently stored in a Python data structure - a list of dictionaries.</li>
    <li>The associated Python Notebook for this part is "part_1_mars_news.ipynb".</li>
</ul>

<h3>Part 2: Mars Weather Data Analysis</h3>

<ul>
    <li>Weather data was scraped from the Mars Temperature Data Site.</li>
    <li>Data from the HTML table was extracted and transformed into a Pandas DataFrame.</li>
    <li>The DataFrame features columns for id, terrestrial_date, sol, ls, month, min_temp, and pressure.</li>
    <li>Data was analyzed to answer key questions concerning Mars' climate and months.</li>
    <li>The associated Python Notebook for this part is "part_2_mars_weather.ipynb".</li>
</ul>

<h2>Source of Code</h2>

<p>
    All the code contained in this repository was exclusively authored by me.
</p>

</body>
</html>
