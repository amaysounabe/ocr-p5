<h1 style="text-align: center; font-size: 35px;">Segmentation de clients</h1>

## Description
Taille du jeu de données : **8,1 Mo** <br>
Le jeu de données se trouve dans le dossier `data/`

## Procédure
- Exploration des données
- Segmentation (KMeans, DBScan, Hierarchical Clustering)
- Maintenance de l'algorithme


## Dossiers & fichiers
- **graphiques** &rarr; Dossier contenant les graphiques enregistrés au cours de l'analyse.
- **data** &rarr; Dossier contenant les données ainsi que les dataframes enregistrés au format .csv au cours du projet.
- **notebook_eda.ipynb** &rarr; Notebook comportant l'analyse exploratoire des données.
- **notebook_segmentation.ipynb** &rarr; Notebook comportant les essais de segmentation.
- **notebook_maintenance.ipynb** &rarr; Notebook comportant la fonction de maintenance du modèle de segmentation.
- **presentation_slides.pdf** &rarr; Fichier pdf des slides de présentation de l'analyse exploratoire utilisées à lors de la soutenance du projet.
- **requirements.txt** &rarr; Fichier texte contenant la liste des bibliothèques utilisées

## Installation
Pour une utilisation en local :

```bash
git clone https://github.com/amaysounabe/ocr-p5.git
cd ocr-p5
pip install -r requirements.txt
```