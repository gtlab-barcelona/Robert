# Analysis of Kaliningrad insect data

Robert Wright <br>
robat.wright@gmail.com <br>
[Botanical Institute of Barcelona (IBB)](https://www.ibb.csic.es/en/)

## Code structure 

The data analysis is divided into two main parts/files:

- *import_raw_data.py*: This script imports the data from the excel file and does some pre-processing. 
  It displays the complete time series of an individual species (per trap). Lastly, the formatted data
  is stored as a pickle-object for further analysis.
- *further_analysis.ipynb*: This piece of code visualizes various aspects of the dataset, e.g., 
  first and last day of sight per year and a comparison between v. atalanta & v. cardui. Further information
  can be found in the notebook itself — it's sort of commented.
- *vals.py* & *funcs.py*: These files contain variables and functions that are used frequently
  throughout the analysis. By separating them from the main code, they don't have to be defined 
  multiple times.
