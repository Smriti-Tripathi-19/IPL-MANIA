# IPL-MANIA
This repository consists of all the code that was written to make the Shiny App - "IPL MANIA"
## 🚀 About the Project
The project has 4 main components :
- Data Visualisation through **Graphs** - You can see year-wise graphs and can even compare the performances of two teams in some graphs.
- Data Visualisation through **Maps** - You can see the nationality of a player be it a batsmen or bowler. You can also look at the country-wise distribution of IPL-2023 players.
- **IPL Auction Simulation** for 22 Players - You and your friends can form teams and compete with each other through an Auction of Players. Let's see who wins!
- A **Searchable Summary** section - You can search the information about all the players from the year 2013-2023 who have played in IPL.

## 🛠 Libraries Required
- rvest
- shiny
- shinythemes
- leaflet
- maps
- dplyr
- ggplot2
- tidyverse
- packcircles
  
## Running the Shiny App
Steps to run the App :
- STEP 1 - Download "Data Sets" folder onto your local machines.
- STEP 2 - Set the working directory for the "App.R" file as the directory in which this "Data Sets" folder is present.
- STEP 3 - Run the App and see the **MAGIC**.

## DATASET STRUCTURE FOR BATTERS
![Screenshot (486)](https://github.com/dootika/class-project-group-11-1/assets/82405359/ac339f15-9baf-4868-9c86-3c5d3a9ac2ad)

## DATASET STRUCTURE FOR BOWLERS
![Screenshot (487)](https://github.com/dootika/class-project-group-11-1/assets/82405359/4210b22b-6dac-455f-a466-4f4d942bae8c)

## Running Tests
To run the app, type the following command on the console -
```bash
  shinyApp(ui,server)
```

## Acknowledgements
 - [How to write a Good Read.me](https://www.youtube.com/watch?v=Rtpu2cWz7W8&ab_channel=CodeWithHarry)
 - [Getting started with Leaflet](https://www.youtube.com/watch?v=IQfsHnUYrFo&ab_channel=GeoProgramming)
