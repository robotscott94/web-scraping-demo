# web-scraping-demo

## Purpose
Demonstrate web scaping tools by pulling data and formatting it to be accessible to other users. Also, a brief analysis is done on the Mars weather data.

## Tools
Python's Splinter package was used to interact directly with websites instead of copying select HTML elements. The BeautifulSoup package was used to parse the HTML text and pull select elements from the webpages. Matplotlib and Pandas were used to manipulate and display the data.

## Results
In the first notebook, each story's title and preview and added to a dictionary that allows for easy access to the text. In the second notebook, graphs show how average temperature and pressure vary over the martian months. Also, dialy temperatures are plotted as a line graph to estimate the yearly cycle on Mars. Finally, the scaped data is saved as a csv.