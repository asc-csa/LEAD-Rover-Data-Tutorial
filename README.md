<p align="center">
   <img src="JUNO_Rover.jpg" alt="image-text" height=300> 
   <br> Crédit d'image | Image credit: <a href= https://www.asc-csa.gc.ca/eng/multimedia/search/image/7818/>ASC-CSA</a>
</p>

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

<h2 align="center">
  <a href="#titre-du-projet">Français</a> |
  <a href="#project-title">English (follows)</a>
</h2>

<a id="titre-du-projet"></a>
# Données de Rover provenant de ROS 

> **Description brève :**
> Ce cours aborde les bases de l'extraction et de l'analyse de données sous forme de ROSBAGS en Python.

---

## À propos
Entre 2017 et 2019, l'Agence Spatiale Canadienne (ASC) s'est associée à l'Agence Spatiale Européenne (ASE) pour mener une série d'essais sur le terrain afin de reproduire les scénarios d'une mission de retour d'échantillons lunaires. Il s'agissait d'acquérir des connaissances et une expérience pratique pour préparer le prochain chapitre de l'exploration spatiale : envoyer des êtres humains vers des destinations plus lointaines comme la Lune et Mars. <br>

Le jeu de données analysé dans ce tutoriel provient de **Déploiement d'analogues d'exploration lunaire : Région ombragée en permanence** et a eu lieu en septembre 2019. Il se présente sous la forme d'un rosbag et fournit des images, des données LiDAR et la pose estimée du rover.

Pour en savoir plus sur la mission, cliquez ici: <br>
**Rover Juno:** https://www.asc-csa.gc.ca/eng/multimedia/search/image/7824 <br>
**Déploiement d'analogues d'exploration lunaire:** <br> https://www.asc-csa.gc.ca/eng/rovers/mission-simulations/lunar-exploration-analogue-deployment.asp <br>
https://www.hou.usra.edu/meetings/isairas2020fullpapers/pdf/5015.pdf <br>

## Démarrage rapide

1. 📦 **Cloner le dépôt**
   ```bash
   git clone https://github.com/asc-csa/LEAD-Rover-Data-Tutorial.git
   cd LEAD-Rover-Data-Tutorial
   ```
2. 🐍 **Créer un environnement**
   ```bash
   # Avec virtualenv
   python -m venv env
   source env/bin/activate

   # Ou avec conda
   conda create -n lead_env python=3.8.8
   conda activate lead_env
   ```
3. 📥 **Installer les dépendances**
   ```bash
   pip install -r requirements.txt
   ```
4. 🚀 **Lancer le tutoriel**
   ```bash
   jupyter notebook LEAD_Rover_Data_Tutorial..ipynb
   ```

> **Remarque :** Si les graphiques ou cartes ne s’affichent pas, redémarrez Jupyter Notebook ou ajoutez `%matplotlib inline` dans la première cellule.

## Fonctionnalités

 - [LEAD_Rover_Data_Tutorial.ipynb](LEAD_Rover_Data_Tutorial.ipynb) guidera l'utilisateur dans les étapes de téléchargement et d'extraction des données Rover Juno à partir d'une réplique de mission de retour d'échantillon lunaire. Ensuite, le didacticiel montrera comment ouvrir les données, les visualiser et les enregistrer sous forme de fichier CSV, de nuage de points ou d'image en vue d'utilisations ultérieures.
 
 - [ROSBAG_Cheat_Sheet_Python.ipynb](ROSBAG_Cheat_Sheet_Python.ipynb) contient une feuille de contrôle comprenant des astuces que j'ai trouvées utiles pour manipuler les données ROS en utilisant uniquement Python.

## Licence

Ce projet est  sous une licence MIT modifiée – voir le fichier [LICENSE](https://github.com/asc-csa/LEAD-Rover-Data-Tutorial/blob/main/LICENSE.txt) pour plus de détails.

---

<h2 align="center">
  <a href="#project-title">English </a> |
  <a href="#titre-du-projet">Français (précède)</a>
</h2>

<a id="project-title"></a>
# Rover Data from ROS

> **Brief description:**
> This repository dives into the basics of extracting and analyzing data in the form of ROSBAGS in Python.

## About
In the time period between 2017-2019, The Canadian Space Agency (CSA) partnered with the European Space Agency (ESA) to conduct a series of field tests to replicate scenarios of a lunar sample return mission. This was to gain knowledge and hands-on experience to prepare for the next chapter of space exploration: sending human beings to more distant destinations like the Moon and Mars. <br>

The dataset analyzed in this tutorial is from the **Lunar Exploration Analogue Deployment: Permanently Shadowed Region (LEAD: PSR)** phase and took place in September 2019. It is in the form of a rosbag and provides imagery, LiDAR data, and the estimated pose of the rover.

You can read more about the mission here: <br>
**Juno Rover:** https://www.asc-csa.gc.ca/eng/multimedia/search/image/7824 <br>
**LEAD:** https://www.asc-csa.gc.ca/eng/rovers/mission-simulations/lunar-exploration-analogue-deployment.asp <br>
      https://www.hou.usra.edu/meetings/isairas2020fullpapers/pdf/5015.pdf <br> 

## Quick Start

1. 📦 **Clone the repo**
   ```bash
   git clone https://github.com/asc-csa/LEAD-Rover-Data-Tutorial.git
   cd LEAD-Rover-Data-Tutorial
   ```
2. 🐍 **Create environment**
   ```bash
   # Using virtualenv
   python -m venv env
   source env/bin/activate

   # Or using conda
   conda create -n lead_env python=3.8.8
   conda activate lead_env
   ```
3. 📥 **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. 🚀 **Run the tutorial**
   ```bash
   jupyter notebook LEAD_Rover_Data_Tutorial.ipynb
   ```

> **Note:** If plots or maps do not display, restart Jupyter Notebook or run `%matplotlib inline` in the first cell.

## Functionality

 - [LEAD_Rover_Data_Tutorial.ipynb](LEAD_Rover_Data_Tutorial.ipynb) guides the user on the steps to downloading and extracting Juno Rover data from a lunar sample return mission replicate. Next, the tutorial will demonstrate how to open the data, visualize and save it as a CSV file, Point Cloud File or Image for further uses. The last step involves creating a world map and plotting the rover's path and images taken on the path. 
 
 - [ROSBAG_Cheat_Sheet_Python.ipynb](ROSBAG_Cheat_Sheet_Python.ipynb) contains a cheatsheet including tips I found useful when manipulating ROS data using only Python.

## License

This project is licensed under a modified MIT license - see the [LICENSE](https://github.com/asc-csa/LEAD-Rover-Data-Tutorial/blob/main/LICENSE.txt) file for details.

---
