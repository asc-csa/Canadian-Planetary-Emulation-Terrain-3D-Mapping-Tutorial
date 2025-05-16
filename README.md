<p align="center">
   <img src="AT-(Planetary-Analogue-Terrain).jpg" alt="Canadian Planetary Emulation Terrain Image" height=300> 
   <br> Crédit d'image | Image credit: <a href=https://www.asc-csa.gc.ca/eng/multimedia/search/image/8042>ASC-CSA</a>
</p>

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

<h2 align="center">
  <a href="#titre-du-projet">Français</a> |
  <a href="#project-title">English (follows)</a>
</h2>

<a id="titre-du-projet"></a>
# Cartographie 3D du terrain d’émulation planétaire canadienne -  Un tutoriel

> **Description brève :**
> Ce tutoriel guide les utilisateurs dans la création d’une carte 3D en Python à partir des données ouvertes du terrain d’émulation planétaire canadienne, en utilisant la bibliothèque open3d.

---

## À propos
Le tutoriel suivant a été créé pour aider les utilisateurs à utiliser les données ouvertes du terrain d’émulation planétaire canadienne pour créer une carte 3D en Python. Les scripts sont créés à l’aide de la bibliothèque open3d.  Les données se composent de 102 scans laser obtenus à l’aide d’un MobileRobots Pioneer P2AT modifié. Plus d’informations sur les données peuvent être trouvées via ce lien [ici](https://donnees-data.asc-csa.gc.ca/en/dataset/65376529-3z6l-6u7e-732sbzy824wa25).

## Démarrage rapide

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
   conda create -n map_env
   conda activate map_env
   ```
3. 📥 **Installer les dépendances**
   ```bash
   pip install -r requirements.txt
   ```
4. 🚀 **Lancer le tutoriel**
   ```bash
   jupyter notebook Canadian Planetary Emulation Terrain 3D Mapping Dataset Tutorial.ipynb
   ```
> **Remarque :** Si les graphiques ou cartes ne s’affichent pas, redémarrez Jupyter Notebook ou ajoutez `%matplotlib inline` dans la première cellule.

## Licence

Ce projet est  sous une licence MIT modifiée – voir le fichier [LICENSE](https://github.com/asc-csa/Canadian-Planetary-Emulation-Terrain-3D-Mapping-Tutorial/blob/main/LICENSE.txt) pour plus de détails.

---

<h2 align="center">
  <a href="#project-title">English </a> |
  <a href="#titre-du-projet">Français (précède)</a>
</h2>

<a id="project-title"></a>
# Canadian Planetary Emulation Terrain 3D Mapping -  A Tutorial 

> **Brief description:**
> This tutorial guides users in creating a 3D map in Python using open data from the Canadian planetary analogue terrain and the open3d library.


# About
The following tutorial has been created to help users use the open data of the Canadian Planetary Emulation terrain to create a 3D map in Python. The scripts are created using the open3d library. The data consists of of 102 laser scans obtained using a modified MobileRobots Pioneer P2AT. More information about the data can be found via this link [here](https://donnees-data.asc-csa.gc.ca/en/dataset/65376529-3z6l-6u7e-732sbzy824wa25).

## Quick Start

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
   conda create -n map_env 
   conda activate map_env
   ```
3. 📥 **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. 🚀 **Run the tutorial**
   ```bash
   jupyter notebook Canadian Planetary Emulation Terrain 3D Mapping Dataset Tutorial.ipynb
   ```
> **Note:** If plots or maps do not display, restart Jupyter Notebook or run `%matplotlib inline` in the first cell.

## License

This project is licensed under a modified MIT license - see the [LICENSE](https://github.com/asc-csa/Canadian-Planetary-Emulation-Terrain-3D-Mapping-Tutorial/blob/main/LICENSE.txt) file for details.

---
