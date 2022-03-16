# Démo Python

Bienvenu dans cette démonstration de python!
Le but de cette démonstration est d'avoir une certaine façon de faire pour travailler avec des algorithmes d'apprentissage automatique (Machine Learning). La documentation sur Internet est souvent pour des questions précises. Il manque souvent un pourquoi il faut faire ceci plutôt que celà. Ceci assume que les gens doivent avoir une connaissance à priori.

La première portion est pour apprendre le python avec des outils pour les analystes en Python. Généralement, l'apprentissage de Python est fait pour du Python pur, celle-ci, est plus axée sur la programmation avec des outils tel que VS Code, Anaconda et des Jupyter Notebook. Sachez qu'il s'agit d'une façon de faire, il existe d'autre manière de faire. Elles ont leurs avantages et inconvénient.

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

## Démonstration \#1
Pour poursuivre la démonstration, je vous invite à ouvrir le notebook `01 Introduction Python/demonstration-python-base.ipynb` avec VS Code et de suivre les étapes indiquées.

Le corrigé est disponible sous le même répertoire. Je vous invite fortement de faire des essais par vous même, oui c'est plus long, mais ceci vous restera plus facilement en mémoire que de simplement lire le solutionnaire.

## Démonstration \#2
Maintenant que nous avons une base en python, il est temps de poursuivre avec la manipulation des données avec Numpy et Pandas. je vous invite à ouvrir le notebook `02 Initiation ensemble de données/Initiation-ensemble-donnees.ipynb` avec VS Code et de suivre les étapes indiquées.

## Démonstration \#3
Enfin! Le vif du sujet! L'apprentissage machine! Je vous invite à ouvrir `03 Initiation apprentissage machine/Initiation-ML-Classique.ipynb` avec VS Code et de suivre les étapes indiquées.

## Démonstration \#4
Nous avons vu comment exécuté UN modèle d'apprentissage. Ceci peut être assez fastidieux... Avec cette démonstration, nous allons voir comment une des multiples technique peut nous aider à générer des modèles en rafale! Je vous invite à ouvrir `04 Initiation AutoML/Pycaret.ipynb` avec VS Code et de suivre les étapes indiquées. Amusez vous bien!

# Conclusion
Voilà! C'est terminé! J'espère que vous avez appris quelque chose. Si vous souhaitez en savoir plus, je vous invite à fouiller le site de Scikit-Learn, de rechercher les autoML, de regarder le site de Kaggle et même de pratiquer avec les diverses compétitions. Surtout, tenez-vous au courant, lisez et gardez la piqure!