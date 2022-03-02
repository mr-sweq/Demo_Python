Démo Python

Bienvenu dans cette démonstration de python!
Le but de cette démonstration est d'avoir une certaine façon de faire. La documentation sur Internet est souvent pour du Python pur, celle-ci, est plus axée sur la programmation avec des outils tel que VS Code et Anaconda.

## Prérequis
- Anaconda
- VS Code

Pour faciliter la gestion des paquets, il vaut mieux installer Anaconda plutôt que Python. En effet, lors de différents projets, il peut arriver que nous ayons besoin de paquets avec des versions spécifiques.

Vous pouvez le télécharger ici : https://www.anaconda.com/products/individual

VS Code est notre interface pour programmer. Vous pouvez le télécharger ici : https://code.visualstudio.com/download

## Installation et configuration
Une fois l'installation terminée, vous pouvez commencer à configurer Python. Pour ce faire, ouvrez un terminal d'anaconda.

Tapez la commande suivante :
```
conda create --name demo_python python=3.9
```
Si vous le souhaitez, vous pouvez utiliser un autre nom que `demo_python`.

Une fois que la commande est lancée, vous devrez accepter la demande d'installation des paquets.

Ensuite, il nous faut activer notre environnement virtuel pour être en mesure d'installer les paquets désirés :
```
conda activate demo_python
```
Maintenant, avant de nous lancer dans VS Code et d'ouvrir notre premier Notebook, il nous faut installer les dépendances :
```
pip install ipykernel
```

Maintenant, vous pouvez ouvrir VS Code.

## Démonstration
Pour poursuivre la démonstration, je vous invite à ouvrir le notebook `demonstration-python-base.ipynb` avec VS Code et de suivre les étapes indiquées.