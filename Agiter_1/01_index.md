
## Qu’est-ce que *git-who* ?

**git-who** est un petit utilitaire en ligne de commande qui permet d’identifier facilement les auteurs de parties précises de votre dépôt Git.  
Son objectif : **simplifier et rendre plus lisible** la recherche d’auteurs, en combinant la puissance de `git log` et `git blame` avec une présentation claire.

Avec git-who, vous pouvez par exemple :  
- retrouver rapidement l’auteur d’une fonction, d’un bloc ou d’une ligne,  
- afficher un résumé des contributeurs sur un fichier,  
- visualiser la répartition des contributions.

---

## Comment ça marche ?

L’installation est simple, puisqu’il s’agit d’un outil écrit en Go et distribué sous forme d’exécutable.  
Une fois installé, il suffit d’appeler la commande :

```bash
git who chemin/vers/fichier

