
<img src="JUNO_Rover.jpg" width=90% />
Image source / Source de l’image: https://www.asc-csa.gc.ca/eng/multimedia/search/image/7818/
<br>
<br>
<p align="center">
    <a href="#stars">
        <img alt="Étoiles sur GitHub | GitHub Repo stars" src="https://img.shields.io/github/stars/asc-csa/LEAD-Rover-Data-Tutorial">
    </a>
    <a href="#watchers">
        <img alt="Spectateurs sur Github | GitHub watchers" src="https://img.shields.io/github/watchers/asc-csa/LEAD-Rover-Data-Tutorial">
    </a>
    <a href="https://github.com/asc-csa/LEAD-Rover-Data-Tutorial/commits/main">
        <img alt="Dernier commit sur GitHub | GitHub last commit" src="https://img.shields.io/github/last-commit/asc-csa/LEAD-Rover-Data-Tutorial">
    </a>
    <a href="https://github.com/asc-csa/LEAD-Rover-Data-Tutorial/graphs/contributors">
        <img alt="Contributeurs sur GitHub | GitHub contributors" src="https://img.shields.io/github/contributors/asc-csa/LEAD-Rover-Data-Tutorial">
    </a>
    <a href="https://twitter.com/intent/follow?screen_name=csa_asc">
        <img alt="Suivre sur Twitter | Twitter Follow" src="https://img.shields.io/twitter/follow/csa_asc?style=social">
    </a>
</p>

* [Français](https://github.com/asc-csa/LEAD-Rover-Data-Tutorial#donn%C3%A9es-de-rover-provenant-de-ros-english-follows) <br>
* [English](https://github.com/asc-csa/LEAD-Rover-Data-Tutorial#rover-data-from-ros-le-fran%C3%A7ais-pr%C3%A9c%C3%A8de)
  
## Données de Rover provenant de ROS (English follows)
Ce cours aborde les bases de l'extraction et de l'analyse de données sous forme de ROSBAGS en Python. <br>

### Informations Générales
Entre 2017 et 2019, l'Agence Spatiale Canadienne (ASC) s'est associée à l'Agence Spatiale Européenne (ASE) pour mener une série d'essais sur le terrain afin de reproduire les scénarios d'une mission de retour d'échantillons lunaires. Il s'agissait d'acquérir des connaissances et une expérience pratique pour préparer le prochain chapitre de l'exploration spatiale : envoyer des êtres humains vers des destinations plus lointaines comme la Lune et Mars. <br>

Le jeu de données analysé dans ce tutoriel provient de **Déploiement d'analogues d'exploration lunaire : Région ombragée en permanence** et a eu lieu en septembre 2019. Il se présente sous la forme d'un rosbag et fournit des images, des données LiDAR et la pose estimée du rover.

Pour en savoir plus sur la mission, cliquez ici: <br>
**Rover Juno:** https://www.asc-csa.gc.ca/eng/multimedia/search/image/7824 <br>
**Déploiement d'analogues d'exploration lunaire:** <br> https://www.asc-csa.gc.ca/eng/rovers/mission-simulations/lunar-exploration-analogue-deployment.asp <br>
https://www.hou.usra.edu/meetings/isairas2020fullpapers/pdf/5015.pdf <br>
*** 
### Démarrage Rapide


:exclamation: **Remarque:** Si, après avoir suivi les étapes ci-dessous, vous ne parvenez pas à afficher la carte du folium, il peut être nécessaire d'exécuter/redémarrer *Jupyter Notebook*.<br>

1. Installez un environnement virtuel ou un environnement conda avec la version suivante de python <br>
```
python = 3.8.8
```
2. Installez les exigences à partir du fichier requirements.txt en exécutant le script (si vous utilisez conda, remplacez le script pip install ci-dessous par conda) <br>
```
pip install -r requirements.txt
```
3. Commencez le tutoriel qui se trouve dans le fichier LEAD_Rover_Data_Tutorial.ipynb. 

***
### Navigation et fichiers

 - [LEAD_Rover_Data_Tutorial.ipynb](LEAD_Rover_Data_Tutorial.ipynb) guidera l'utilisateur dans les étapes de téléchargement et d'extraction des données Rover Juno à partir d'une réplique de mission de retour d'échantillon lunaire. Ensuite, le didacticiel montrera comment ouvrir les données, les visualiser et les enregistrer sous forme de fichier CSV, de nuage de points ou d'image en vue d'utilisations ultérieures.
 
 - [ROSBAG_Cheat_Sheet_Python.ipynb](ROSBAG_Cheat_Sheet_Python.ipynb) contient une feuille de contrôle comprenant des astuces que j'ai trouvées utiles pour manipuler les données ROS en utilisant uniquement Python.

***

## Rover Data from ROS (Le français précède)
This repository dives into the basics of extracting and analyzing data in the form of ROSBAGS in Python. <br>

### Background Information 
In the time period between 2017-2019, The Canadian Space Agency (CSA) partnered with the European Space Agency (ESA) to conduct a series of field tests to replicate scenarios of a lunar sample return mission. This was to gain knowledge and hands-on experience to prepare for the next chapter of space exploration: sending human beings to more distant destinations like the Moon and Mars. <br>

The dataset analyzed in this tutorial is from the **Lunar Exploration Analogue Deployment: Permanently Shadowed Region (LEAD: PSR)** phase and took place in September 2019. It is in the form of a rosbag and provides imagery, LiDAR data, and the estimated pose of the rover.

You can read more about the mission here: <br>
**Juno Rover:** https://www.asc-csa.gc.ca/eng/multimedia/search/image/7824 <br>
**LEAD:** https://www.asc-csa.gc.ca/eng/rovers/mission-simulations/lunar-exploration-analogue-deployment.asp <br>
      https://www.hou.usra.edu/meetings/isairas2020fullpapers/pdf/5015.pdf <br> 

*** 
### Quick Start


:exclamation: **Note:** If after the below steps you are unable to display the map, it may be required to run/re-start jupyter notebook.<br>

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

### Navigation and files

 - [LEAD_Rover_Data_Tutorial.ipynb](LEAD_Rover_Data_Tutorial.ipynb) guides the user on the steps to downloading and extracting Juno Rover data from a lunar sample return mission replicate. Next, the tutorial will demonstrate how to open the data, visualize and save it as a CSV file, Point Cloud File or Image for further uses. The last step involves creating a world map and plotting the rover's path and images taken on the path. 
 
 - [ROSBAG_Cheat_Sheet_Python.ipynb](ROSBAG_Cheat_Sheet_Python.ipynb) contains a cheatsheet including tips I found useful when manipulating ROS data using only Python.

***
