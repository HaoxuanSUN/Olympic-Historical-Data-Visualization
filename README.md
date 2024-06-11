### Overview
This project presents a visualization system designed to help users explore how each nation performed in the Olympics from 1896 to 2014. Utilizing a geomap, line chart, and bar chart, users can locate countries of interest, observe trends in medal counts, and compare achievements of male and female athletes.

### Goals & Tasks
The primary goal is to create a visual hierarchy that allows users to explore a nation's Olympic performance, with a focus on medal counts and gender comparisons. The system supports interaction between views, ensuring a cohesive and informative user experience.

### Data
- **Dataset**: The project uses the "Olympic Sports and Medals, 1896-2014" dataset, which includes around 37,000 records of Olympic athletes who won medals. The dataset was aggregated to focus on visualizable attributes and ensure efficient performance.
- **Source**: The data is provided by the IOC Research and Reference Service and published by the Guardian's Datablog.

### Libraries and Technologies
- **HTML/CSS/JavaScript**: The foundational technologies used for building the interactive webpage.
- **React**: Used for rendering the static UI of the webpage and managing the overall structure of the application.
- **D3.js**: Utilized for managing the dynamic and interactive parts of the application, particularly for data visualization components such as the geomap, line chart, and bar chart.
- **CSV Data Handling**: Techniques for efficiently processing and aggregating large datasets to ensure smooth performance and interaction.

### Key Features
- **Geographical Visualization**: The geomap enables users to see the total number of medals won by each country, with a tooltip showing detailed information when hovering over a country.
- **Trend Analysis**: The line chart displays the historical trend of gold, silver, and bronze medals won by a selected country, providing a clear view of performance over time.
- **Gender Comparison**: The bar chart compares the number of medals won by male and female athletes, highlighting the progression of female athletes in the Olympics.

### Visualization
- **Geo-map**: Displays countries colored by the total number of medals won. Tooltips provide additional details, and selecting a country updates all views.
- **Line Chart**: Shows trends of gold, silver, and bronze medals over the years. Hovering over points highlights related data and provides detailed information.
- **Grouped Bar Chart**: Compares medals won by male and female athletes. Hovering highlights the bars and displays detailed information.

### Interaction
- **UI Widgets**: Includes sliders for selecting the Olympic season (summer or winter) and the time period, as well as a drop-down menu for country selection. All views update dynamically based on user input.

### Responsibilities
- Developed an interactive webpage using HTML, CSS, and JavaScript to visualize historical Olympic data (37k entries).
- Rendered the static UI of the webpage and managed the overall structure using the React library.
- Managed the dynamic and interactive parts of the project, handling specific data visualization components using the D3 library.
- Conducted a presentation and demonstration of the project as the team leader.

### Demo Video
For use instructions, please refer to the demo video provided in the GitHub repository.

### Running the Project
To run the project, follow these steps:
1. Navigate to the project directory.
2. Open a command line interface.
3. Run the command `npm start`.