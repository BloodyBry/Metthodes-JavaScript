# Résumé des Méthodes JavaScript

Ce dépôt contient un résumé détaillé des principales méthodes JavaScript utilisées pour manipuler les tableaux, les strings et les objets. Chaque méthode est décrite avec son rôle, ses arguments et sa valeur de retour.

---

## filter()
**Définition :** Crée un nouveau tableau contenant seulement les éléments qui passent une condition.  
**Arguments :** callback(element, index, array)  
**Retour :** Nouveau tableau filtré  

## find()
**Définition :** Cherche et retourne le premier élément qui satisfait une condition donnée.  
**Arguments :** callback(element, index, array)  
**Retour :** Élément trouvé ou undefined  

## findIndex()
**Définition :** Retourne l’index du premier élément qui satisfait une condition.  
**Arguments :** callback(element, index, array)  
**Retour :** Index ou -1  

## indexOf()
**Définition :** Cherche la position d’une valeur dans un tableau ou une string.  
**Arguments :** valeur, indexDeDépart (optionnel)  
**Retour :** Index ou -1  

## sort()
**Définition :** Trie les éléments d’un tableau selon un ordre spécifique.  
**Arguments :** Fonction de comparaison (optionnelle)  
**Retour :** Tableau trié (modifié)  

## reduce()
**Définition :** Transforme un tableau en une valeur unique en cumulant ses éléments.  
**Arguments :** callback(accumulateur, element, index, array), valeurInitiale  
**Retour :** Valeur finale  

## map()
**Définition :** Applique une fonction à chaque élément et retourne un nouveau tableau.  
**Arguments :** callback(element, index, array)  
**Retour :** Tableau transformé  

## includes()
**Définition :** Vérifie si un tableau ou une string contient une valeur spécifique.  
**Arguments :** valeur, indexDeDépart (optionnel)  
**Retour :** true / false  

## forEach() / for…in / for…of
**Définition :** Permettent de parcourir les éléments d’un tableau ou les clés/valeurs d’un objet.  
**Arguments :** callback(element, index, array) pour forEach  
**Retour :** forEach → undefined, for…in / for…of → boucle  

## push()
**Définition :** Ajoute un ou plusieurs éléments à la fin d’un tableau.  
**Arguments :** Éléments à ajouter  
**Retour :** Nouvelle longueur  

## pop()
**Définition :** Supprime le dernier élément d’un tableau et le retourne.  
**Arguments :** Aucun  
**Retour :** Élément retiré  

## shift()
**Définition :** Supprime le premier élément d’un tableau et le retourne.  
**Arguments :** Aucun  
**Retour :** Élément retiré  

## unshift()
**Définition :** Ajoute un ou plusieurs éléments au début d’un tableau.  
**Arguments :** Éléments à ajouter  
**Retour :** Nouvelle longueur  

## slice()
**Définition :** Retourne une copie d’une portion du tableau ou d’une string sans modifier l’original.  
**Arguments :** Début, fin (optionnel)  
**Retour :** Nouveau tableau / string  

## split()
**Définition :** Découpe une string en tableau de sous-chaînes selon un séparateur.  
**Arguments :** Séparateur, limite (optionnel)  
**Retour :** Tableau  

## join()
**Définition :** Transforme un tableau en string en assemblant les éléments avec un séparateur.  
**Arguments :** Séparateur (optionnel)  
**Retour :** String  

## some()
**Définition :** Vérifie si au moins un élément du tableau satisfait une condition.  
**Arguments :** callback(element, index, array)  
**Retour :** true / false  

## every()
**Définition :** Vérifie si tous les éléments du tableau satisfont une condition.  
**Arguments :** callback(element, index, array)  
**Retour :** true / false  

## splice()
**Définition :** Modifie un tableau en ajoutant, supprimant ou remplaçant des éléments.  
**Arguments :** indexDépart, nbASupprimer, élémentsAAjouter (optionnel)  
**Retour :** Tableau des éléments supprimés  

## Set
**Définition :** Structure qui contient des valeurs uniques, sans doublons.  
**Arguments :** Valeurs initiales (optionnel)  
**Méthodes principales :** add(value), delete(value), has(value)  
**Retour :** Objet Set  

