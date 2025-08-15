<!-- Placeholder for tutorial image (required) -->
<p align="center">
   <img src="https://www.asc-csa.gc.ca/images/recherche//hi-res/7298e672-f22d-4b6e-8829-b3beb9d7c80b.jpg" alt="JUNO Rover" height=300>
   <br> Crédit d'image | Image credit: <a href="https://www.asc-csa.gc.ca/eng/multimedia/search/image/7818/">ASC-CSA</a>
</p>

<!-- Common badge header (required)
For changing the links, update the first four src=links and replace the section in the link of {{your-tutorial-name}} with the name of your tutorial seen in the url of the GitHub repository. -->
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

<!-- This should not need to be updated unless you change the "id" section of the title section (required) -->

---

<h3 align="center">
  <a href="#titre-du-projet">Français</a> |
  <a href="#project-title">English (follows)</a>
</h3>

---

<!-- ============ FRANÇAIS ============
An engaging title for the project (required)-->
<a id="titre-du-projet"></a>
# Données de Rover LEAD - Tutoriel

<!-- A short summary phrase for the project (required)-->
> **Description brève :**
> Ce tutoriel aborde les bases de l'extraction et de l'analyse de données sous forme de ROSBAGS en Python.

## À propos

<!-- Summary of the use of the tutorial (required)-->
**Données de Rover LEAD - Tutoriel** est un tutoriel Jupyter Notebook qui guide les utilisateurs à travers l'extraction et l'analyse de données sous forme de ROSBAGS en Python. Il couvre :

- Téléchargement et extraction des données Rover Juno
- Ouverture et visualisation des données
- Sauvegarde sous forme de fichier CSV, de nuage de points ou d'image
- Création d'une carte mondiale et traçage du parcours du rover

Entre 2017 et 2019, l'Agence Spatiale Canadienne (ASC) s'est associée à l'Agence Spatiale Européenne (ASE) pour mener une série d'essais sur le terrain afin de reproduire les scénarios d'une mission de retour d'échantillons lunaires. Le jeu de données analysé dans ce tutoriel provient de **Déploiement d'analogues d'exploration lunaire : Région ombragée en permanence** et a eu lieu en septembre 2019.

*Ce tutoriel est fourni à des fins pédagogiques et expérimentales.*



<!-- Describe any requirements for the deployment (required) -->
## Prérequis

- Python 3.8.8
- Jupyter Notebook ou Jupyter Lab
- Connexion Internet (pour le téléchargement des données)
- Bibliothèques Python pour ROS et analyse de données



## Démarrage rapide
<!-- The process for setting up your tutorial. Use one of the following:
pip freeze > requirements.txt

The method above will likely require some level of cleaning to create a good requirements.txt. Alternatively, you can try pip-chill to help create a better cleaner requirements.txt.

pip install pip-chill
pip-chill --no-chill -v > requirements.txt

Or if you prefer to specify a conda environment:
conda env export --no-builds | grep -v "^prefix: " > environment.yml
 (required) -->
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
   jupyter notebook LEAD_Rover_Data_Tutorial.ipynb
   ```

> **Remarque :** Si après avoir suivi les étapes ci-dessous, vous ne parvenez pas à afficher la carte du folium, il peut être nécessaire d'exécuter/redémarrer Jupyter Notebook.



<!-- This can be useful if your tutorial contains several associated scripts or supporting functions (optional) -->
## Navigation et fichiers

- **[LEAD_Rover_Data_Tutorial.ipynb](LEAD_Rover_Data_Tutorial.ipynb)** - Tutoriel principal qui guide l'utilisateur dans les étapes de téléchargement et d'extraction des données Rover Juno à partir d'une réplique de mission de retour d'échantillon lunaire. Montre comment ouvrir les données, les visualiser et les enregistrer sous différents formats.

- **[ROSBAG_Cheat_Sheet_Python.ipynb](ROSBAG_Cheat_Sheet_Python.ipynb)** - Feuille de contrôle comprenant des astuces utiles pour manipuler les données ROS en utilisant uniquement Python.

Pour en savoir plus sur la mission :
- **Rover Juno :** https://www.asc-csa.gc.ca/eng/multimedia/search/image/7824
- **Déploiement d'analogues d'exploration lunaire :** https://www.asc-csa.gc.ca/eng/rovers/mission-simulations/lunar-exploration-analogue-deployment.asp
- **Documentation scientifique :** https://www.hou.usra.edu/meetings/isairas2020fullpapers/pdf/5015.pdf



<!-- The standard license required for ASC-CSA tutorials (required) -->
## Licence

Ce projet est sous une licence MIT modifiée – voir le fichier [LICENSE](https://github.com/asc-csa/LEAD-Rover-Data-Tutorial/blob/main/LICENSE.txt) pour plus de détails.


<!-- This should not need to be updated unless you change the "id" section of the title section (required) -->

---

<h3 align="center">
  <a href="#project-title">English </a> |
  <a href="#titre-du-projet">Français (précède)</a>
</h3>

---

<!-- ============ English ============
An engaging title for the project (required)-->
<a id="project-title"></a>
# LEAD Rover Data Tutorial

<!-- A short summary phrase for the project (required)-->
> **Brief description:**
> This tutorial dives into the basics of extracting and analyzing data in the form of ROSBAGS in Python.


<!-- Summary of the use of the tutorial (required)-->
## About

**LEAD Rover Data Tutorial** is a Jupyter Notebook tutorial that guides users through extracting and analyzing data in the form of ROSBAGS in Python. It covers:

- Downloading and extracting Juno Rover data
- Opening and visualizing the data
- Saving as CSV file, Point Cloud File or Image
- Creating a world map and plotting the rover's path

Between 2017-2019, The Canadian Space Agency (CSA) partnered with the European Space Agency (ESA) to conduct a series of field tests to replicate scenarios of a lunar sample return mission. The dataset analyzed in this tutorial is from the **Lunar Exploration Analogue Deployment: Permanently Shadowed Region (LEAD: PSR)** phase and took place in September 2019.

*This tutorial is provided for educational and experimental purposes.*



<!-- Describe any requirements for the deployment (required) -->
## Prerequisites

- Python 3.8.8
- Jupyter Notebook or Jupyter Lab
- Internet connection (for data download)
- Python libraries for ROS and data analysis



## Quick Start
<!-- The process for setting up your tutorial. Use one of the following:
pip freeze > requirements.txt

The method above will likely require some level of cleaning to create a good requirements.txt. Alternatively, you can try pip-chill to help create a better cleaner requirements.txt.

pip install pip-chill
pip-chill --no-chill -v > requirements.txt

Or if you prefer to specify a conda environment:
conda env export --no-builds | grep -v "^prefix: " > environment.yml
 (required) -->

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

> **Note:** If after the below steps you are unable to display the map, it may be required to run/re-start jupyter notebook.



<!-- This can be useful if your tutorial contains several associated scripts or supporting functions (optional) -->
## Navigation and Files

- **[LEAD_Rover_Data_Tutorial.ipynb](LEAD_Rover_Data_Tutorial.ipynb)** - Main tutorial that guides the user on the steps to downloading and extracting Juno Rover data from a lunar sample return mission replicate. Demonstrates how to open the data, visualize and save it as different file formats. The last step involves creating a world map and plotting the rover's path and images taken on the path.

- **[ROSBAG_Cheat_Sheet_Python.ipynb](ROSBAG_Cheat_Sheet_Python.ipynb)** - Contains a cheatsheet including tips found useful when manipulating ROS data using only Python.

You can read more about the mission here:
- **Juno Rover:** https://www.asc-csa.gc.ca/eng/multimedia/search/image/7824
- **LEAD:** https://www.asc-csa.gc.ca/eng/rovers/mission-simulations/lunar-exploration-analogue-deployment.asp
- **Scientific documentation:** https://www.hou.usra.edu/meetings/isairas2020fullpapers/pdf/5015.pdf



<!-- The standard license required for ASC-CSA tutorials (required) -->
## License

This project is licensed under a modified MIT license - see the [LICENSE](https://github.com/asc-csa/LEAD-Rover-Data-Tutorial/blob/main/LICENSE.txt) file for details.
