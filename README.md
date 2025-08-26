# Applied-Data-Science-SpaceX-Launch
Using Data Science to predict SpaceX landing success and rocket reusability. A jupyter notebooks project

- Data collection using API and webscraping of wikipedia
    - Using BeautifulSoup and Request libraries to scrape data from tables on the spacex launch wikipedia page
- Data wrangling
    - get number of launches at each launch site
    - get number of each type of orbitals
    - get number of different type of landing outcomes
    - create new column called class in order to classify if landing outcome was success (1) or failure (0)
- EDA
    - Use sqlalchemy and slqlite3 to query table of launch data for useful data such as max payload, which rockets carried max payloads, number of successful/failed landings and which type of landing, etc.
- Interactive visual dashboard - SpaceX Dashboard
    - Use dash library to create a dashboard dropdown to choose the launchsite. Visualized with a pie chart and scatter plot for the different launch sites and the successful outcomes
    ![alt text](https://github.com/jdowling23/Applied-Data-Science-SpaceX-Launch/blob/main/SpaceX-Dashboard/Dahsboard-screenshot.png "Dashboard screenshot")
- Predictive analysis to determine the succesful launches
    - Use the Supervised learning SVM, classification tree and Logistic regression models
    - determine which models perform best using score
- Presentation
    - Powerpoint presentation walking through all the steps of the project including visualization representations of findings and summary 
