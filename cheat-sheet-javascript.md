 La différence entre var, let et const réside dans leur portée (scope) et leur capacité à être réassignées.
 var a une portée de fonction, 
 let a une portée de bloc et peut être réassignée, 
 tandis que const a une portée de bloc et ne peut pas être réassignée après son initialisation.
# tableau Javascript

### declaration de variable

let banane ;

###

banane = 'c'est bon';

### creer un tableau 

tableau = [];

push() : Cette fonction permet d'ajouter un ou plusieurs éléments à la fin d'un tableau.

var fruits = ['pomme', 'banane', 'orange'];
fruits.push('kiwi');
console.log(fruits); // ['pomme', 'banane', 'orange', 'kiwi']

-----------------------------------------------------------------------------------

Modification de tableau :

    push() : Ajoute un ou plusieurs éléments à la fin du tableau et renvoie la nouvelle taille du tableau.
    pop() : Supprime le dernier élément du tableau et le renvoie.
    shift() : Supprime le premier élément du tableau et le renvoie.
    unshift() : Ajoute un ou plusieurs éléments au début du tableau et renvoie la nouvelle taille du tableau.
    splice() : Modifie le contenu d'un tableau en ajoutant, supprimant ou remplaçant des éléments.

Accès aux éléments :

    concat() : Fusionne deux tableaux ou plus pour créer un nouveau tableau.
    slice() : Renvoie une copie superficielle d'une portion d'un tableau dans un nouveau tableau.
    indexOf() : Renvoie le premier index de l'élément spécifié dans le tableau, -1 s'il n'est pas trouvé.
    lastIndexOf() : Renvoie le dernier index de l'élément spécifié dans le tableau, -1 s'il n'est pas trouvé.


Itération sur le tableau :

    forEach() : Exécute une fonction donnée une fois pour chaque élément du tableau.
    map() : Crée un nouveau tableau contenant les résultats d'appeler une fonction fournie sur chaque élément du tableau.
    filter() : Crée un nouveau tableau contenant tous les éléments du tableau d'origine qui passent un test spécifié.
    reduce() : Applique une fonction à un accumulateur et à chaque élément du tableau (de gauche à droite) pour réduire le tableau à une seule valeur.
    find() : Renvoie la première valeur d'élément du tableau qui satisfait une fonction de test fournie.
    some() : Vérifie si au moins un élément du tableau satisfait une condition donnée.
    every() : Vérifie si tous les éléments du tableau satisfont une condition donnée.



Manipulation et transformation du tableau :

    sort() : Trie les éléments d'un tableau dans l'ordre approprié.
    reverse() : Inverse l'ordre des éléments dans un tableau.
    join() : Joint tous les éléments d'un tableau dans une chaîne de caractères.
    toString() : Renvoie une chaîne de caractères représentant le tableau.
    includes() : Détermine si un tableau contient une valeur spécifique.
    isArray() : Vérifie si un objet est un tableau.!!