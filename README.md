# IS424 Data Mining and Analytics Project  
## Project Overview
Electricity consumption predictor that predicts electrcity consumption (kWh) for the specified month based on weather, region, and dwelling type inputs. Prediction models include 8 Deep Neural Nets, 7 Regression models, 3 Ensemble models and 1 K-Nearest Neighbors model
## Datasets - (found in "python notebooks") <br/>
### Singapore Energy Statistics
* Gathered by the Energy Market Authority of Singapore
* Variables used from Sheet T3.5 - Average Monthly Household Elecrtricity Consumption by Planning Area & Dwelling Type
### Singapore weather dataset
* Historical climate data gathered by the Meteorological Service of Singapore
* Data scraped using a script
* Variables used [grouped by location]:
  * Daily rainfall
  * Highest 120m rainfall
  * Temperature (Mean, Maximum, Minimum)
  * Wind speed (Mean, Maximum)
## Running the application
Install the dependencies with the command below.
```bash
pip install -r requirements.txt
```
Finally, run the program with the command below.
```bash
python app.py 
