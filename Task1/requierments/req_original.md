Individual: Web scraping & basic data analysis

Find a city that starts with the same letter as your first name on https://www.timeanddate.com/weather/. Only use cities that have both weather and climate tables available.

Retrieve the data from the summary table „Forecast for the next 48 hours“. (Weather symbols can be ignored.) Output a table that summarizes this information. (Edit to clarify: "summarize" might be misleading here, the table should contain the information you scraped.)
Example Vienna
Visualize the predicted development of temperature, wind, and humidity for the next 24 hours (retrieve the data from „Detailed Hourly Forecast - Next 24 hours“). Date & times should be formatted nicely.
Example Vienna
Retrieve the monthly annual weather averages from „Climate (Averages) - Annual Weather Averages“. Tip: It might be easier to use the climate table object (id: climateTable) than the graph to retrieve the information.

Example Vienna
Get the following summary statistics:

annual minimum, maximum, and mean temperature
annual mean precipitation
Output a table and a plot for the monthly values (Edit to clarify: of the variables you analyzed in the point above).

For each of the above tasks, take screenshots of the website data you used and include them in your report.

Guidelines for the report:

use RMarkdown
include a table of contents (structure the report in an appropriate way)
briefly summarize the functions used
display all important code snippets in the .pdf
document your findings
all table columns should be readable in the report, you might find the kable and kableExtra packages useful: Reference
another useful family of functions for working with regular expressions is grep
Submit both the .rmd and .pdf file via TUWEL.