# *challenge-6-042723*
---
**Repository for challenge 6 for FinTech BootCamp**
---
## Proptech

![Image used from original FinTech challenge files](/Starter_Code/Images/6-4-challenge-image.png)
The purpose of this challenge was to create visuals using hvplot, analyze the data from the visuals generated and provide a recommendation based on the data on where Proptech can use the strategy of buying property and immediately renting the property. 

## Technologies

This project leverages python 3.7 specifically and assumes that jupyter lab has been installed.  in the root directory. In additon, you would need to have the following modules installed:
* pandas
* hvplot

## Resources
* Data provided by Columbia FinTech program.

## Contributions 

Historical data and challenge questions provided by Columbia FinTech progam.
Analysis, code, and conclusions completed by Sean Senhouse

## Installation Guide
### To review challenge 6:

* First initialze the dev environment and the Jupyter lab by typing the following at the command prompt:  

```python
str("conda activate dev")
str("jupyter lab")
```
* Open the Jupter Notebook titled: **san_francisco_housing.ipynb** 

* Run all of the code

## Usage
The code imports the data from csv files. The code then generates the following charts: 

Figure 1 Shows the summary of the growth of housing units in the market in San Francisco from 2010 - 2016
![Number of housing units in San Francisco](/Starter_Code/Images/output-housing-units-plot.png)

Figure 2 Shows the summary of the average price per square foot and the average rental income for units within the market. 
![Average price per square foot and the rental income](/Starter_Code/Images/output-sales-prices-plot.png)

FIgure 3 Shows the geographic summary of the data
![Avg prices per square foot and rental income geographic map](/Starter_Code/Images/output-geoview-plot.png)

## Final Recomendations
The one click-by-and-rent strategy can work for specific neighborhoods, where the price per square foot is decreasing or flat, while the number of housing units continues to rise and the overall gross rent continues to increase. Examples of where this strategy can work are in the neighborhood of Anza Vista and Vistacoin Valley, where their price per square foot is decreasing, or flat while gross rents have increased. Other neighborhoods to avoid would be South Beach or Mission Bay, where prices per square foot have remained flat, but gross rent has increased minimally. In addition, these locations have not shown the same increases in housing units