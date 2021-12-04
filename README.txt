Hello there!

DESCRIPTION:
This is a group project created by Team The Underdogs for Georgia Tech class CX 4242. The goal of our team was to create a real estate data visualization that allows users to investigate trends historical and forecasted data. Our team trained a machine learning model, ARIMA, that forecasts prices into future years based on the historical trends in our dataset.
The visualization is a web-based chloropleth map that allows users to quickly see which states are the most and least expensive in a given year. Users may input the parameters year and number of bedrooms to change the chloropleth map.

INSTALLATION:

Once the CX4242-Housing directory is on your machine, you will need to run a http server in the directory to view the web tool. Luckily, if you have Python installed, it is easy to run a server in the command-line. Simply navigate to the root directory of the project in the command line and then enter the command "python -m http.server". The server will start running and you may go to 0.0.0.0:8000 in your web browser of choice (we recommend Chrome since we are using D3). You should see now the contents of our project directory in your browser. To open the web visualization tool navigate to the Visualization directory and then click chloropleth.html. The tool should open in a new tab and you will see our final product!

EXECUTION:
The user may select the year and number of bedrooms that they are interested in. The default when the tool is opened is 1 bedroom in the year 2010. When the user hovers their mouse over any state, a tooltip should appear displaying the state name, median rental price, and median property price for that year and number of bedrooms. There also should appear two line charts below the map when the mouse hovers over a state showing the time-series data for these two variables including our model's predictions for future months. The user may select a future year from the dropdown to see a forecasted chloropleth map. We suggest that the user should choose several different combinations of year and number of bedrooms to start getting a feel for the data and how the web tool works. The most expensive states according to the user's parameters are always shown in dark green while the least expensive states are showin in light green. When there is no data that state will appear gray.  
