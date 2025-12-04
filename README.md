# Résumé des Méthodes JavaScript (1 à 20)

Ce dépôt contient un résumé détaillé des principales méthodes JavaScript utilisées pour manipuler les tableaux, les strings et les objets. Chaque méthode est décrite avec son rôle, ses arguments et sa valeur de retour.

---

## 1. filter()
**Définition :** Crée un nouveau tableau contenant seulement les éléments qui passent une condition.  
**Arguments :** callback(element, index, array)  
**Retour :** Nouveau tableau filtré  

## 2. find()
**Définition :** Cherche et retourne le premier élément qui satisfait une condition donnée.  
**Arguments :** callback(element, index, array)  
**Retour :** Élément trouvé ou undefined  

## 3. findIndex()
**Définition :** Retourne l’index du premier élément qui satisfait une condition.  
**Arguments :** callback(element, index, array)  
**Retour :** Index ou -1  

## 4. indexOf()
**Définition :** Cherche la position d’une valeur dans un tableau ou une string.  
**Arguments :** valeur, indexDeDépart (optionnel)  
**Retour :** Index ou -1  

## 5. sort()
**Définition :** Trie les éléments d’un tableau selon un ordre spécifique.  
**Arguments :** Fonction de comparaison (optionnelle)  
**Retour :** Tableau trié (modifié)  

## 6. reduce()
**Définition :** Transforme un tableau en une valeur unique en cumulant ses éléments.  
**Arguments :** callback(accumulateur, element, index, array), valeurInitiale  
**Retour :** Valeur finale  

## 7. map()
**Définition :** Applique une fonction à chaque élément et retourne un nouveau tableau.  
**Arguments :** callback(element, index, array)  
**Retour :** Tableau transformé  

## 8. includes()
**Définition :** Vérifie si un tableau ou une string contient une valeur spécifique.  
**Arguments :** valeur, indexDeDépart (optionnel)  
**Retour :** true / false  

## 9. forEach() / for…in / for…of
**Définition :** Permettent de parcourir les éléments d’un tableau ou les clés/valeurs d’un objet.  
**Arguments :** callback(element, index, array) pour forEach  
**Retour :** forEach → undefined, for…in / for…of → boucle  

## 10. push()
**Définition :** Ajoute un ou plusieurs éléments à la fin d’un tableau.  
**Arguments :** Éléments à ajouter  
**Retour :** Nouvelle longueur  

## 11. pop()
**Définition :** Supprime le dernier élément d’un tableau et le retourne.  
**Arguments :** Aucun  
**Retour :** Élément retiré  

## 12. shift()
**Définition :** Supprime le premier élément d’un tableau et le retourne.  
**Arguments :** Aucun  
**Retour :** Élément retiré  

## 13. unshift()
**Définition :** Ajoute un ou plusieurs éléments au début d’un tableau.  
**Arguments :** Éléments à ajouter  
**Retour :** Nouvelle longueur  

## 14. slice()
**Définition :** Retourne une copie d’une portion du tableau ou d’une string sans modifier l’original.  
**Arguments :** Début, fin (optionnel)  
**Retour :** Nouveau tableau / string  

## 15. split()
**Définition :** Découpe une string en tableau de sous-chaînes selon un séparateur.  
**Arguments :** Séparateur, limite (optionnel)  
**Retour :** Tableau  

## 16. join()
**Définition :** Transforme un tableau en string en assemblant les éléments avec un séparateur.  
**Arguments :** Séparateur (optionnel)  
**Retour :** String  

## 17. some()
**Définition :** Vérifie si au moins un élément du tableau satisfait une condition.  
**Arguments :** callback(element, index, array)  
**Retour :** true / false  

## 18. every()
**Définition :** Vérifie si tous les éléments du tableau satisfont une condition.  
**Arguments :** callback(element, index, array)  
**Retour :** true / false  

## 19. splice()
**Définition :** Modifie un tableau en ajoutant, supprimant ou remplaçant des éléments.  
**Arguments :** indexDépart, nbASupprimer, élémentsAAjouter (optionnel)  
**Retour :** Tableau des éléments supprimés  

## 20. Set
**Définition :** Structure qui contient des valeurs uniques, sans doublons.  
**Arguments :** Valeurs initiales (optionnel)  
**Méthodes principales :** add(value), delete(value), has(value)  
**Retour :** Objet Set  

---

*Ce README est conçu pour fournir un guide rapide et clair des méthodes JavaScript les plus utilisées pour travailler avec les tableaux, les chaînes et les objets.*
