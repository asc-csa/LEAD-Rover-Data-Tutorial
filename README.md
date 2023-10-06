## LEAD Rover Data - A Tutorial (Le français suit)

### Background Information

In the time period between 2017-2019, The Canadian Space Agency (CSA) partnered with the European Space Agency (ESA) to conduct a series of field tests to replicate scenarios of a lunar sample return mission. This was to gain knowledge and hands-on experience to prepare for the next chapter of space exploration: sending human beings to more distant destinations like the Moon and Mars.

This mission simulation was conducted using the CSA'S Juno Rover: a rugged, all-terrain rover. These field tests were performed in three phases at two locations: a rock quarry and the CSA Analogue Terrain (also known as the Mars Yard) in Quebec. The rover was operated by teams based in Saint-Hubert (Quebec) and Germany to recreate the difficulty of long-distance communications.

This project was split as follows:

* **LEAD (HOPE)**: This focused on having trained operators carry out sample return missions. It took place over five days in October 2017 and four days in June 2019.
* **LEAD Rover Metrics Gathering Experiment (LRMGE)**: This part of the mission had six teams in June 2019 operate the rover along a pre-defined itinerary to gather metrics on rover driving performance.
* **LEAD Permanently Shadowed Region (PSR)**: Lastly, this part focused on rover driving tasks under dark lightning conditions emulating operations in a PSR. <br>

The dataset analyzed in this tutorial is from the **LEAD (PSR)** phase and took place in September 2019. It is in the form of a rosbag and provides imagery, LiDAR data, and the estimated pose of the rover.

You can read more about the mission here: <br>
**Juno Rover:** https://www.asc-csa.gc.ca/eng/multimedia/search/image/7824 <br>
**LEAD:** https://www.asc-csa.gc.ca/eng/rovers/mission-simulations/lunar-exploration-analogue-deployment.asp <br>
      https://www.hou.usra.edu/meetings/isairas2020fullpapers/pdf/5015.pdf <br>

### About
LEAD_Rover_Data_Tutorial.ipynb will guide the user on the steps to downloading and extracting the Rover data. Next, the tutorial will demonstrate how to open the data and save it as a CSV file, Point Cloud File or Image for further uses.
The last step involves creating a world map and plotting the rover's path and images taken on the path. 

*** 
### Quick Start


:exclamation: **Note:** If after the below steps you are unable to display the folium map, it may be required to run/re-start and/or install jupyter notebook into the same kernel that has the required packages.<br>

1. Setup a virtual environment or conda environment with the following version of python <br>
```
python = 3.8.8
```
2. Install requirements from the requirements.txt file by running the script (if using conda replace the below pip install with conda) <br>
```
pip install -r requirements.txt
```
3. Begin the tutorial found in the LEAD_Rover_Data_Tutorial.ipynb file. 

***
