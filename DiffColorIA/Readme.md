 DiffColorIA
===========

DiffColorIA est une application d'intelligence artificielle qui permet de déterminer la couleur dominante dans une image. L'application utilise TensorFlow pour entraîner un modèle de réseau de neurones capable de classer les images en fonction de leur couleur dominante.

Fonctionnalités
-------------

* Chargement et prétraitement des images
* Entraînement d'un modèle de réseau de neurones avec TensorFlow
* Évaluation de la couleur dominante dans une image

Installation
------------

Pour installer DiffColorIA, vous devez avoir Python 3.x installé sur votre ordinateur. Vous pouvez ensuite utiliser pip pour installer les dépendances nécessaires :

```
pip install matplotlib numpy numpy pandas tensorflow pillow Pillow
```

Une fois les dépendances installées, vous pouvez exécuter le fichier `main.ipynb` dans un environnement Jupyter Notebook.

Utilisation
-----------

Pour utiliser DiffColorIA, suivez les étapes suivantes :

1. Chargez une image en utilisant la fonction `load_and_preprocess_image()`.
2. Évaluez l'image en utilisant la fonction `predict()` du modèle entraîné.
3. La couleur dominante dans l'image sera affichée dans la sortie.

Remarques
-------

* Le modèle entraîné dans DiffColorIA est capable de classer les images en fonction de neuf couleurs différentes : rouge, vert, bleu, jaune.
* Pour de meilleurs résultats, assurez-vous que l'image que vous chargez est bien éclairée et que la couleur dominante est clairement visible.
* DiffColorIA est fourni à titre indicatif uniquement et ne doit pas être utilisé dans des applications critiques où une précision de couleur élevée est nécessaire.