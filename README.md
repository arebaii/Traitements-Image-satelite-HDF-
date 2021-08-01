
# 1 # INSTALLER LA LIBRAIRIE GDAL SUR PYTHON AVEC ANACONDA 
#Installations préalables:
Installer Anaconda (https://www.anaconda.com/products/individual)
IDE Python (exemple: Spyder, présent avec Anaconda)

1) Créer un nouvel environnement
-Ouvrir anaconda prompt, écrire:
conda create --name NOM

 2)Aller sur l'environnement créé, écrire:
conda activate NOM

3) Installer les librairies, écrire: 
conda install -c conda-forge gdal


# Tester l'instalation
 1)Tester avec python, toujours sur Anaconda Prompt, écrire:
python
from osgeo import gdal
exit()

(il est possible qu'il faille écrire deux fois la commande pour que ça fonctionne)

# Tester sur Spyder
-Il faut aller sur notre nouvel environnement créé: en bas à droite on clique sur modifier l'environnement de spyder
-une fenêtre préférences s'ouvre.
-on coche sur la seconde proposition et on colle le chemin du nouvel environnement
(il ressemble à /
C:\Users\NomUser\anaconda3\envs\NOM\python.exe
)
