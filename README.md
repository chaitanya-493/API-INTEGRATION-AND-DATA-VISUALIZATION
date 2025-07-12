# API-INTEGRATION-AND-DATA-VISUALIZATION
*COMPANY* : CODTECH IT SOLUTIONS
*NAME* : KOLUSU CHAITANYA VARMA
*INTERN ID* : CT08DF1081
*DOMAIN* : PYTHON PROGRAMMING
*DURATION* : 8 WEEKS
*MENTOR* : NEELA SANTHOSH

**DESCRIPTION:
In this project, I created a simple yet effective weather forecasting visualization tool using Python. The main goal was to fetch and display the temperature forecast of a particular city, which I chose as Vijayawada, using the OpenWeatherMap API. The task was entirely implemented in PyCharm.

The program starts by sending a request to the OpenWeatherMap API, which provides weather forecast data for various cities worldwide. After signing up on their platform, I received a free API key, which is necessary to access the weather data. In the code, I built a request URL using the city name, the API key, and added a parameter to receive the temperature in Celsius (units=metric). I used the requests library to fetch the data in JSON format.

Once the data was retrieved, I focused on extracting two main pieces of information: the forecast date and time (dt_txt) and the temperature at that time. These values were stored in two lists and later used to create a visual graph. To handle and format the date-time strings, I used the datetime module. For the visualization part, I used the matplotlib and seaborn libraries.

The final output was a line graph showing how the temperature would change over the next five days in Vijayawada. I added markers on the data points to make them clear, rotated the date labels on the x-axis for better readability, and customized the size and style of the graph using seaborn's dark grid theme. The result was a neat and informative temperature forecast plot.

Applications of the Project
This task has several real-life applications. It can serve as a basic weather dashboard for individuals who want to quickly check the temperature trends of any city. For travelers, farmers, delivery services, and even event organizers, knowing how the temperature will change can be very useful in planning their day or week. It can also be integrated into larger weather-based applications, alert systems, or smart home displays to provide live temperature updates.

**OUTPUT:
<img width="1200" height="600" alt="Image" src="https://github.com/user-attachments/assets/df270c0f-8c6f-4a91-89bb-628ecd57e574" />




