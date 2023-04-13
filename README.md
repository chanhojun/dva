# Budget Collector

We partnered with Budget Collector to work on a project whose goal is to determine whether there is any correlation between the color choices of an art piece, the region the art piece was painted and the period it was painted. 


## Description
Budget Collector is a  Data Science company that is dedicated to turning art enthusiasts into art collectors through their mobile app.We partnered with them in order to determine whether there is any correlation between the color choices of an art piece, the region the art piece was painted and the period it was painted. 

To accomplish the project objectives, we extracted dominant colors of an image using image processing techniques. Afterwards we used statistical and machine learning methods and time series visualization to establish correlation. The successful accomplishment of the project objectives will be beneficial to artists, art enthusiasts and art collectors in different aspects.


## Getting Started

### Dependencies

Below are the python libraries required. Some are in the python standard library, however some will need to be installed.
* pyairtable 
* Pandas
* PIL
* requests
* sklearn.cluster 
* numpy
* matplotlib.pyplot
* cv2

One csv file are also required for the code to run successfully and to get the required results. The csv file contains the pallete we created to derive color names and color shades.
* The file is Colors_with_shades.csv. Ensure that the file is resident on the same folder as the notebook


### Installing

* if any of the above libraries are not already existing, then use pip to install the library. An example is shown below

pip install pyairtable

### Executing program

* Run each cell block by itself and wait until the execution of each cell has completed successfully.
* Execute the cell blocks sequentially as the later cells are dependent on the earlier cells.
* Once the last cell has been executed, the csv file used to create the interactive medium will be downloaded and saved in the folder containing the code. The name of the file is data_with_color_names_ranked.csv


## Authors

Contributors names

* Lilian Chepng'eno  
* Hojun Chan
* Joao Pedro Martins Morand 

## Acknowledgments

* https://towardsdatascience.com/extracting-colours-from-an-image-using-k-means-clustering-9616348712be
* https://htmlcolorcodes.com/colors/
* https://stackoverflow.com/questions/9694165/convert-rgb-color-to-english-color-name-like-green-with-python
* https://stackoverflow.com/questions/50331463/convert-rgba-to-rgb-in-python