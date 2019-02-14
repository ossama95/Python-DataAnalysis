# Parkinson-Speech-Dataset-with-Multiple-Types-of-Sound-Recordings
Devoir à la maison : __Python for data-science__   
Date de rendu : *15 février 2019*  
Par _Ossama Ougzin_



## 1) Informations sur le jeu de données : [Dataset et description](https://archive.ics.uci.edu/ml/datasets/Avila)

### i) Introduction

L'ensemble de données d'Avila a été extrait de 800 images de la "Bible d'Avila", une copie latine géante de l'ensemble de la Bible produite au XIIe siècle entre l'Italie et l'Espagne.
L'analyse paléographique du manuscrit a mis en évidence la présence de 12 copistes. Les pages écrites par chaque copiste ne sont pas également nombreuses.
Chaque modèle contient 10 entités et correspond à un groupe de 4 lignes consécutives

* La tâche de prédiction consiste à associer chaque motif à l’un des 12 copistes (A, B, C, D, E, F, G, H, I, W, X, Y).
* Les données ont été normalisées à l’aide de la méthode de normalisation Z et divisées en deux ensembles de données: un ensemble d’apprentissage contenant 10430 échantillons et un ensemble d’essais contenant les 10437 échantillons.

Distribution de classe (Dataset pour le training)
A: 4286
B: 5
C: 103
D: 352
E: 1095
F: 1961
G: 446
H: 519
I: 831
W: 44
X: 522
Y: 266

DESCRIPTION DES ATTRIBUTS : 

* Nom d'identité
* Distance intercolumnaire F1
* F2 marge supérieure
* F3 marge inférieure
* Exploitation F4
* Numéro de ligne F5
* Ratio modulaire F6
* Espacement interlinéaire F7
* Poids F8
* Nombre de pointe F9
* Rapport modulaire F10 / espacement interlinéaire
* Classe: A, B, C, D, E, F, G, H, I, W, X, Y


C. De Stefano, M. Maniaci, F. Fontanella, A. Scotto di Freca,
Reliable writer identification in medieval manuscripts through page layout features: The "Avila" Bible case, Engineering Applications of Artificial Intelligence, Volume 72, 2018, pp. 99-110.

-----------------  

### 3) L'application

Pour répondre à la problématique, j'ai crée un script python qui automatise toute la procédure de modélisation de la base de données :  

1. Lancer [Jupiter](https://jupyter.org/install)  
2. Ouvrir un nouveau fichier script  
3. Copier la commande `git clone ` et lancer l'execution   
5. Ouvrez le script `Projet_Python_DataAnalysis.ipynb`  

-----------------    
