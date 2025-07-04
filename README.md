# R101_1

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/iutVilletaneuseDptInfo/R101_1/master)

Bases de la programmation

Ce dépôt contient les ressources pour le cours R101_1 du département de l'IUT de Villetaneuse. Ces ressources sont libres mais sous copy left.

## Initialisation du dépôt 

Il vous faut : 
1. Créer un dossier dans votre répertoire sauvegardé
2. Cloner le dépôt github qui contient tous les supports de cours/TD/TP.

Pour cela, ouvrez un terminal et copiez/collez les instructions suivantes :
```bash
mkdir ~/Bureau/Mes_Montages/$USER/R101_1
cd ~/Bureau/Mes_Montages/$USER/R101_1
git clone https://github.com/iutVilletaneuseDptInfo/R101_1.git .
```

## Mise-à-jour du dépôt en début de séance

À chaque début de séance, vous devez mettre à jour le dépôt et lancer le logiciel `jupyter notebook`. 

Pour cela, ouvrez un terminal et copier/coller les instructions suivantes :

```bash
cd ~/Bureau/Mes_Montages/$USER/R101_1
./updateDepot
jupyter-notebook
```



## Outils utilisés

La ressource R101 s'appuie sur les outils suivants : 
* un interpréteur python 
* le logiciel `jupyter-notebook`
* Plusieurs packages python

Ces logiciels sont déjà installés sur les machines de l'iut. Si vous souhaitez un environnement de dévoloppement chez vous, vous pouvez installer : 
* [`JupyterLab Desktop`](https://github.com/jupyterlab/jupyterlab-desktop#installation) : le logiciel `jupyterLab` est similaire au logiciel `jupyter-notebook` et la version `Desktop` installe également l'interpréteur python.

* Il est également possible d'installer différents packages optionnels pour améliorer le confort d'utilisation de `jupyterLab`. Ces packages s'installent en exécutant dans une cellule d'un notebook l'instruction suivante : 
  ```jupyter
  %pip install <package_name>
  ```
  Les packages optionnels sont : 
  * `matplotlib` : pour pouvoir afficher des courbes
  * `pytutor` : pour avoir accéder au site python tutor directement à partir d'un notebook
  * `ipyturtle3` : pour pouvoir faire les tp avec la tortue

## Contributeurs pour la réalisation de ces supports de cours :
* Hanane Azzag
* Frédérique Bassino
* Thierry Charnois
* Evaggelos Kritsikis
* Mathieu Lacroix
* Mustapha Lebbah
* Bouchaïb Lemaire
* Guillaume Santini
