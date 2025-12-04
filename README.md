# Résumé des Méthodes JavaScript

Ce dépôt contient un résumé détaillé des principales méthodes JavaScript utilisées pour manipuler les tableaux, les strings et les objets. Chaque méthode est décrite avec son rôle, ses arguments et sa valeur de retour.

---

## filter()
**Définition :** Crée un nouveau tableau contenant seulement les éléments qui passent une condition.  
**Arguments :** callback(element, index, array)  
**Retour :** Nouveau tableau filtré  
```javascript
const words = ["sun", "planet", "sky", "galaxy"];
const longWords = words.filter(w => w.length > 4);
// ["planet", "galaxy"]
```

## find()
**Définition :** Cherche et retourne le premier élément qui satisfait une condition donnée.  
**Arguments :** callback(element, index, array)  
**Retour :** Élément trouvé ou undefined  
```javascript
const temps = [12, 8, 3, -2, -5];
const firstNegative = temps.find(t => t < 0);
// -2
```

## findIndex()
**Définition :** Retourne l’index du premier élément qui satisfait une condition.  
**Arguments :** callback(element, index, array)  
**Retour :** Index ou -1  
```javascript
const nums = [2, 4, 6, 7, 8];
const posOdd = nums.findIndex(n => n % 2 !== 0);
// 3
```

## indexOf()
**Définition :** Cherche la position d’une valeur dans un tableau ou une string.  
**Arguments :** valeur, indexDeDépart (optionnel)  
**Retour :** Index ou -1  
```javascript
const colors = ["red", "green", "blue"];
colors.indexOf("blue");
// 2
```

## sort()
**Définition :** Trie les éléments d’un tableau selon un ordre spécifique.  
**Arguments :** Fonction de comparaison (optionnelle)  
**Retour :** Tableau trié (modifié)  
```javascript
const names = ["Sami", "Adnane", "Rayhane"];
names.sort();
// ["Adnane", "Rayhane", "Sami"]
```

## reduce()
**Définition :** Transforme un tableau en une valeur unique en cumulant ses éléments.  
**Arguments :** callback(accumulateur, element, index, array), valeurInitiale  
**Retour :** Valeur finale  
```javascript
const nums = [2, 3, 4];
const result = nums.reduce((a, b) => a * b, 1);
// 24
```

## map()
**Définition :** Applique une fonction à chaque élément et retourne un nouveau tableau.  
**Arguments :** callback(element, index, array)  
**Retour :** Tableau transformé  
```javascript
const words = ["hello", "world"];
const newWords = words.map(w => w + "!");
// ["hello!", "world!"]
```

## includes()
**Définition :** Vérifie si un tableau ou une string contient une valeur spécifique.  
**Arguments :** valeur, indexDeDépart (optionnel)  
**Retour :** true / false  
```javascript
const langs = ["arabic", "french", "spanish"];
langs.includes("french");
// true
```

## forEach() / for…in / for…of
**Définition :** Permettent de parcourir les éléments d’un tableau ou les clés/valeurs d’un objet.  
**Arguments :** callback(element, index, array) pour forEach  
**Retour :** forEach → undefined, for…in / for…of → boucle 
```javascript
["Paris", "Tokyo", "Dubai"].forEach(city => console.log(city));
```
```javascript
const car = {brand: "BMW", year: 2020};
for (let key in car) console.log(key);
// brand, year
```
```javascript
for (let char of "Adnane") console.log(char);
```

## push()
**Définition :** Ajoute un ou plusieurs éléments à la fin d’un tableau.  
**Arguments :** Éléments à ajouter  
**Retour :** Nouvelle longueur  
```javascript
const tasks = ["Study"];
tasks.push("Run");
// ["Study", "Run"]
```

## pop()
**Définition :** Supprime le dernier élément d’un tableau et le retourne.  
**Arguments :** Aucun  
**Retour :** Élément retiré  
```javascript
const notifications = ["msg1", "msg2", "msg3"];
notifications.pop();
// ["msg1", "msg2"]
```

## shift()
**Définition :** Supprime le premier élément d’un tableau et le retourne.  
**Arguments :** Aucun  
**Retour :** Élément retiré  
```javascript
const queue = ["client1", "client2", "client3"];
queue.shift();
// ["client2", "client3"]
```

## unshift()
**Définition :** Ajoute un ou plusieurs éléments au début d’un tableau.  
**Arguments :** Éléments à ajouter  
**Retour :** Nouvelle longueur  
```javascript
const clients = ["client2", "client3"];
clients.unshift("client1");
// ["client1", "client2", "client3"]
```

## slice()
**Définition :** Retourne une copie d’une portion du tableau ou d’une string sans modifier l’original.  
**Arguments :** Début, fin (optionnel)  
**Retour :** Nouveau tableau / string  
```javascript
const messages = ["m1", "m2", "m3", "m4"];
messages.slice(0, 3);
// ["m1", "m2", "m3"]
```

## split()
**Définition :** Découpe une string en tableau de sous-chaînes selon un séparateur.  
**Arguments :** Séparateur, limite (optionnel)  
**Retour :** Tableau  
```javascript
"Bloody Bry".split(" ");
// ["Bloody", "Bry"]
```

## join()
**Définition :** Transforme un tableau en string en assemblant les éléments avec un séparateur.  
**Arguments :** Séparateur (optionnel)  
**Retour :** String  
```javascript
["2025", "12", "03"].join("-");
// "2025-12-03"
```

## some()
**Définition :** Vérifie si au moins un élément du tableau satisfait une condition.  
**Arguments :** callback(element, index, array)  
**Retour :** true / false  
```javascript
const grades = [12, 10, 9, 17];
grades.some(g => g > 15);
// true
```

## every()
**Définition :** Vérifie si tous les éléments du tableau satisfont une condition.  
**Arguments :** callback(element, index, array)  
**Retour :** true / false  
```javascript
const words = ["hello", "world", "nice"];
words.every(w => w === w.toLowerCase());
// true
```

## splice()
**Définition :** Modifie un tableau en ajoutant, supprimant ou remplaçant des éléments.  
**Arguments :** indexDépart, nbASupprimer, élémentsAAjouter (optionnel)  
**Retour :** Tableau des éléments supprimés
```javascript
const arr = ["a", "c", "d"];
arr.splice(1, 0, "b");
// ["a", "b", "c", "d"]
```

## Set
**Définition :** Structure qui contient des valeurs uniques, sans doublons.  
**Arguments :** Valeurs initiales (optionnel)  
**Méthodes principales :** add(value), delete(value), has(value)  
**Retour :** Objet Set  
```javascript
const numbers = new Set([1, 2, 2, 3]);
numbers.add(4);
// Set {1, 2, 3, 4}
```
