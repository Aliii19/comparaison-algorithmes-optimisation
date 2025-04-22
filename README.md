# comparaison-algorithmes-optimisation
Analyse comparative des algorithmes d'optimisation

Ce projet propose une analyse comparative de trois algorithmes d'optimisation dans un contexte "boîte noire".

__Les algorithmes étudiés sont__ :

BFGS (Broyden-Fletcher-Goldfarb-Shanno) : Une méthode quasi-Newton efficace pour les fonctions lisses et convexes.

AMALGAM : Un algorithme hybride évolutionnaire combinant plusieurs stratégies, comme le Differential Evolution (DE) et le CMA-ES.

RandomSearch-5 : Un algorithme de référence basé sur une recherche aléatoire.

Les expériences utilisent des fonctions de référence issues de la suite BBOB (F1, F6, F10, F15, F20) en dimension 2. Les critères d’évaluation sont :

Temps d’exécution (mesuré en nombre d’évaluations de la fonction).

Qualité de la solution (écart à l’optimum connu).

Variabilité (évaluée par des exécutions multiples pour analyser la robustesse statistique).


__Liens vers les ressources__
Les scripts Python nécessaires pour exécuter les algorithmes d'optimisation et générer les graphiques sont disponibles 
dans le lien notebook Google Colab suivant : https://colab.research.google.com/drive/1S9JC9fN9v6vPph4qTYxparwESMNQG6zO?authuser=1#scrollTo=U71PYnHtMF1n&uniqifier=1



__Contenu du dépôt__

Le dépôt contient les éléments suivants :

Scripts_Colab.ipynb : Le notebook Jupyter contenant les scripts pour exécuter les algorithmes d'optimisation (BFGS, AMALGAM, RandomSearch-5) et générer les résultats graphiques.

rapport.pdf : Le rapport détaillant l’analyse comparative des algorithmes, avec des explications et les commentaires sur les résultats obtenus et la reproductibilité.

figures/ : Dossier contenant toutes les images des graphiques, illustrant les résultats des algorithmes et les fonctions de test. 

README.md : Ce fichier de description du projet.


__Installation et exécution __

Cloner le notebook Colab : Ouvrez le lien notebook Colab pour accéder aux scripts et aux données.

Exécuter l’expérience :

Lancez le notebook pour exécuter les algorithmes d'optimisation sur les fonctions de référence.

Générer les graphiques :

Le script dans le notebook génère des graphiques de performance pour chaque algorithme ,sauvegardés sous forme d’images dans le dossier figures/. 


Reproductibilité
Tous les scripts et résultats nécessaires à la reproduction de cette analyse sont disponibles dans le notebook Colab.
Ce dernier permet de garantir la reproductibilité des résultats et pour exécuter les codes, 
tester de nouvelles configurations ou analyser d'autres fonctions de test.
