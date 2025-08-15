

<!-- Placeholder for tutorial image (required) -->
<p align="center">
   <img src="AT-(Planetary-Analogue-Terrain).jpg" alt="Canadian Planetary Emulation Terrain Image" height=300>
   <br> Crédit d'image | Image credit: <a href="https://www.asc-csa.gc.ca/eng/multimedia/search/image/8042">ASC-CSA</a>
</p>

<!-- Common badge header (required)
For changing the links, update the first four src=links and replace the section in the link of {{your-tutorial-name}} with the name of your tutorial seen in the url of the GitHub repository. -->
<p align="center">
    <a href="#stars">
        <img alt="Étoiles sur GitHub | GitHub Repo stars" src="https://img.shields.io/github/stars/asc-csa/Canadian-Planetary-Emulation-Terrain-3D-Mapping-Tutorial">
    </a>
    <a href="#watchers">
        <img alt="Spectateurs sur Github | GitHub watchers" src="https://img.shields.io/github/watchers/asc-csa/Canadian-Planetary-Emulation-Terrain-3D-Mapping-Tutorial">
    </a>
    <a href="https://github.com/asc-csa/Canadian-Planetary-Emulation-Terrain-3D-Mapping-Tutorial/commits/main">
        <img alt="Dernier commit sur GitHub | GitHub last commit" src="https://img.shields.io/github/last-commit/asc-csa/Canadian-Planetary-Emulation-Terrain-3D-Mapping-Tutorial">
    </a>
    <a href="https://github.com/asc-csa/Canadian-Planetary-Emulation-Terrain-3D-Mapping-Tutorial/graphs/contributors">
        <img alt="Contributeurs sur GitHub | GitHub contributors" src="https://img.shields.io/github/contributors/asc-csa/Canadian-Planetary-Emulation-Terrain-3D-Mapping-Tutorial">
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
# Cartographie 3D du terrain d'émulation planétaire canadienne - Tutoriel

<!-- A short summary phrase for the project (required)-->
> **Description brève :**
> Ce tutoriel aide les utilisateurs à utiliser les données ouvertes du terrain d'émulation planétaire canadienne pour créer une carte 3D en Python.


## À propos

<!-- Summary of the use of the tutorial (required)-->
**Cartographie 3D du terrain d'émulation planétaire canadienne - Tutoriel** est un tutoriel Jupyter Notebook qui guide les utilisateurs à travers l'utilisation des données ouvertes du terrain d'émulation planétaire canadienne pour créer une carte 3D en Python. Il couvre :

- Accès aux données ouvertes du terrain d'émulation planétaire
- Traitement des scans laser avec la bibliothèque open3d
- Création de cartes 3D interactives
- Analyse et visualisation des données de terrain

Les données se composent de 102 scans laser obtenus à l'aide d'un MobileRobots Pioneer P2AT modifié. Plus d'informations sur les données peuvent être trouvées via ce lien : https://donnees-data.asc-csa.gc.ca/en/dataset/65376529-3z6l-6u7e-732sbzy824wa25

*Ce tutoriel est fourni à des fins pédagogiques et expérimentales.*



<!-- Describe any requirements for the deployment (required) -->
## Prérequis

- Python 3.8 ou plus récent
- Jupyter Notebook ou Jupyter Lab
- Connexion Internet (pour le téléchargement des données)
- Bibliothèque open3d pour le traitement 3D



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
   git clone https://github.com/asc-csa/Canadian-Planetary-Emulation-Terrain-3D-Mapping-Tutorial.git
   cd Canadian-Planetary-Emulation-Terrain-3D-Mapping-Tutorial
   ```
2. 🐍 **Créer un environnement**
   ```bash
   # Avec virtualenv
   python -m venv env
   source env/bin/activate

   # Ou avec conda
   conda create -n terrain_env python=3.8
   conda activate terrain_env
   ```
3. 📥 **Installer les dépendances**
   ```bash
   pip install -r requirements.txt
   ```
4. 🚀 **Lancer le tutoriel**
   ```bash
   jupyter notebook terrain_mapping_tutorial.ipynb
   ```

> **Remarque :** Assurez-vous que la bibliothèque open3d est correctement installée pour le traitement 3D.



<!-- It can be helpflul to describe the different tools users will learn from your tutorial (optional) -->
## Fonctionnalités

- **Accès aux données :** Télécharger et prétraiter les données de scans laser du terrain d'émulation planétaire
- **Traitement 3D :** Utiliser la bibliothèque open3d pour manipuler les nuages de points
- **Cartographie :** Créer des cartes 3D interactives du terrain
- **Visualisation :** Analyser et visualiser les données de terrain en temps réel



<!-- The standard license required for ASC-CSA tutorials (required) -->
## Licence

Ce projet est sous une licence MIT modifiée – voir le fichier [LICENSE](https://github.com/asc-csa/Canadian-Planetary-Emulation-Terrain-3D-Mapping-Tutorial/blob/main/LICENSE.txt) pour plus de détails.


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
# Canadian Planetary Emulation Terrain 3D Mapping Tutorial

<!-- A short summary phrase for the project (required)-->
> **Brief description:**
> This tutorial helps users use the open data of the Canadian Planetary Emulation terrain to create a 3D map in Python.


<!-- Summary of the use of the tutorial (required)-->
## About

**Canadian Planetary Emulation Terrain 3D Mapping Tutorial** is a Jupyter Notebook tutorial that guides users through using the open data of the Canadian Planetary Emulation terrain to create a 3D map in Python. It covers:

- Accessing open data from the Canadian Planetary Emulation terrain
- Processing laser scans using the open3d library
- Creating interactive 3D maps
- Analyzing and visualizing terrain data

The data consists of 102 laser scans obtained using a modified MobileRobots Pioneer P2AT. More information about the data can be found via this link: https://donnees-data.asc-csa.gc.ca/en/dataset/65376529-3z6l-6u7e-732sbzy824wa25

*This tutorial is provided for educational and experimental purposes.*



<!-- Describe any requirements for the deployment (required) -->
## Prerequisites

- Python 3.8 or newer
- Jupyter Notebook or Jupyter Lab
- Internet connection (for data download)
- Open3d library for 3D processing



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
   git clone https://github.com/asc-csa/Canadian-Planetary-Emulation-Terrain-3D-Mapping-Tutorial.git
   cd Canadian-Planetary-Emulation-Terrain-3D-Mapping-Tutorial
   ```
2. 🐍 **Create environment**
   ```bash
   # Using virtualenv
   python -m venv env
   source env/bin/activate

   # Or using conda
   conda create -n terrain_env python=3.8
   conda activate terrain_env
   ```
3. 📥 **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. 🚀 **Run the tutorial**
   ```bash
   jupyter notebook terrain_mapping_tutorial.ipynb
   ```

> **Note:** Ensure that the open3d library is properly installed for 3D processing.



<!-- It can be helpflul to describe the different tools users will learn from your tutorial (optional) -->
## Features

- **Data Access:** Download and preprocess laser scan data from the Canadian Planetary Emulation terrain
- **3D Processing:** Use the open3d library to manipulate point clouds
- **Mapping:** Create interactive 3D maps of the terrain
- **Visualization:** Analyze and visualize terrain data in real-time



<!-- The standard license required for ASC-CSA tutorials (required) -->
## License

This project is licensed under a modified MIT license - see the [LICENSE](https://github.com/asc-csa/Canadian-Planetary-Emulation-Terrain-3D-Mapping-Tutorial/blob/main/LICENSE.txt) file for details.
