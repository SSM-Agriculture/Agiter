
## Qu’est-ce que *git-who* ?

**git-who** est un petit utilitaire en ligne de commande qui permet d’identifier facilement les auteurs de parties précises de votre dépôt Git.  
Son objectif : **simplifier et rendre plus lisible** la recherche d’auteurs, en combinant la puissance de `git log` et `git blame` avec une présentation claire.

Avec git-who, vous pouvez par exemple :  
- retrouver rapidement l’auteur d’une fonction, d’un bloc ou d’une ligne,  
- afficher un résumé des contributeurs sur un fichier,  
- visualiser la répartition des contributions.

## Installation

Voir avec Pierre pour une future installation sur Cerise (propre pour tous les utilisateurs) ?

TO DO

## Exemples d’utilisation

Avec le projet :

![](Agiter_1/assets/projet_exemple.png)

Avec git-who on peut avoir une vue d'ensemble des contributeurs d'un dépôt :  

![](Agiter_1/assets/exemple_1.png)

On peut aussi utiliser l'option -l pour lister les principaux contributeurs classés par nombre de lignes qu'ils ont ajoutées ou supprimées :  

![](Agiter_1/assets/exemple_2.png)

On peut utiliser une autre commande hist pour avoir une idée de la façon dont le meilleur contributeur a changé au fil du temps :  

![](Agiter_1/assets/exemple_3.png)

En utilisant le flag --since, on peut voir qui a contribué au projet depuis une certaine date (ici le 1er avril 2025) :  

![](Agiter_1/assets/exemple_4.png)

Enfin, git-who permet également de voir qui a contribué pour la dernière fois à chacun des fichiers du projet :  

![](Agiter_1/assets/exemple_5.png)