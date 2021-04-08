
# Does Size, in this case height, matter for an NFL Quarterback?
Code Louisville - January 2021 Data Science with Python 

(1) The Jupter Notebook file, "Football.ipynb", is the main file for this project.
(2) CSV files used for the dataframes of this project are located in the "supp" folder. Player measureables was taken from https://newsday.sportsdirectinc.com/football/nfl-players.aspx?page=/data/nfl/players/A_players.html   & player stats was taken from https://www.pro-football-reference.com/

## Running the code/project
### Requirements:
Python 3.7 or newer
conda 4.9.2

### Installation
Clone or Download project located https://github.com/timbosan/Python2.git

#### Using Visual Studio Code
1) Install the Python Extension for VS Code more detailed instructions can be found here https://code.visualstudio.com/docs/python/python-tutorial
2) Select and activate conda environment by using the Python: Select Interpreter command from the Command Palette. Detail instructions located here https://code.visualstudio.com/docs/python/environments
3) Choose Football.ipynb project file from cloned or downloaded repo and run all cells.  


#### Jupyter Notebook system
1) This project can be ran using the Jupyter Notebook system. It is recommended to download Anaconda (https://www.anaconda.com/distribution/) to access Jupyter Notebooks
2) Create a virtual environment in Anaconda Navigator, instuctions here, https://docs.anaconda.com/anaconda/navigator/tutorials/manage-environments/
3) Install pandas, numpy, matplotlib, seaborn, and scipy packages
4) Click Launch button from Anaconda Navigator under Jupyter Tab
5) Choose Football.ipynb project file from cloned or downloaded repo and run all cells. 


## Research question: 
We can assume that larger quarterbacks both in height and weight are more durable and able to see over the tall offensive linemen in front of them. However it has been shown that shorter quarterbacks such as Drew Brees & Russel Wilson have found long success as starting NFL quarterbacks. Looking at data from the last 3 NFL seasons can we determine that positive passing metrics are the same for short and tall quarterbacks?
### Null Hypothesis: Touchdowns thrown of tall and short quarterbacks are the same
### Alternate Hypothesis: Touchdowns thrown of tall and short quarterbacks are the same

## Conclusion:
T-Test returned a P value of 0.7761015 or a value greater than any alpha. Meaning we would fail to reject the null, so in this case Touchdowns thrown of tall and short NFL quarterbacks are the same. 
This test is very limited to expand one could take data from over a larger range of years. Also one could argue that TDs thrown is not the only metric determine a successful QB so looking at other metrics like completion percentage or games won could be done in the future. 
