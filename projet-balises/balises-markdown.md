# SOMMAIRE 

-[faire un titre](#faire-un-titre)

-[insérer une image](#insérer-une-image)

[faire une liste](#faire-une-liste)

[styliser notre texte](#styliser-notre-texte)

[insérer du code](#insérer-du-code)

[citations](#citations)

[création de tableau](#création-de-tableau)

[rediriger sur la page](#rediriger-sur-la-page)

  
 ## faire un titre  
                           
Pour faire un titre en markdown on utilise le "#" exemple pour un titre niveau 1 on utilisera un seul "#" 

pour faire un titre de niveau 2 on utilisera 2 "#" .

etc

EXEMPLE :

# titre de niveau 1
## titre de niveau 2 
### titre de niveau 3  
#### titre de niveau 4
##### titre de niveau 5
###### titre de niveau 6 


 ## insérer une image

pour insérer une image en markdown on procède comme ceci 

![Texte alternatif de l'image](chemin/vers/l'image)

EXEMPLE : 

![logo de markdown en noir et blanc](images/logo-markdown.png)



## faire une liste

En markdown on peut faire deux listes différentes 

- les listes ordonnées
- les listes non-ordonnées


Pour faire une liste ordonnées on procède  comme ceci :

on met le numéro de la liste suivi d'un "."  

EXEMPLE : 

1. banane
2. pomme
3. poire

Pour faire les listes non ordonnées on procède comme ceci :

on met un "-" (tiret du 6) pour créer un élément de la liste

EXEMPLE : 

- Élément 1
- Élément 2
- Élément 3

on peut tout à fait créer des sous-listes en ajoutant un espace ou une tabulation 

EXEMPLE: 

- Élément 1
  - Sous-élément 1
  - Sous-élément 2
- Élément 2
  - Sous-élément 3
  - Sous-élément 4



## styliser notre texte

En markdown on peut aussi styliser notre texte.


- En gras
- En italique
- En souligné

### EN GRAS

pour mettre un texte en gras on utilise "**" ou "____" 

EXEMPLE :

**texte en gras**

__texte en gras__

pour mettre un texte en italique on utilise on utilise "*" ou "_"

EXEMPLE :

*texte en italique*

_texte en italique_


pour souligner un texte on utilise "__"

EXEMPLE :


__Texte souligné__



# Insérer du code 

pour insérer du code on utilise les '''

EXEMPLE :

```python
print("Hello, world!")
```


aprés les ''' on peut spécifier le language du code affiché , dans cet exemple on spécifie le language PYTHON




## citations

pour faire une citations en markdown on utilise ">"

> N'importe quel idiot peut écrire du code qu'un ordinateur peut comprendre. Les bons programmeurs écrivent du code que les humains peuvent comprendre. Martin Fowler




## création de tableau

pour créer un tableau on procède comme ceci :

- on utilise les "|" pour délimiter les colonnes 
- on utilise les "-" pour délimiter les en-têtes et les lignes de séparation

exemple de tableau basique 


   '''| En-tête 1 | En-tête 2 | En-tête 3 |

      | --------- | --------- | --------- |

      | Cellule 1 | Cellule 2 | Cellule 3 |

      | Cellule 4 | Cellule 5 | Cellule 6 |
      '''

   

   donne 



   | En-tête 1 | En-tête 2 | En-tête 3 |
   | --------- | --------- | --------- |
   | Cellule 1 | Cellule 2 | Cellule 3 |
   | Cellule 4 | Cellule 5 | Cellule 6 |



on peut aussi décider d'aligner le texte d'une cellule en utilisant ":"

exemple :

    '''| Aligné à gauche | Centré | Aligné à droite |
       | :-------------- | :----: | -------------: |

       | Cellule 1       |   Cellule 2   |       Cellule 3    |

       | Cellule 4       |   Cellule 5   |       Cellule 6    |
    '''

donne 

| Aligné à gauche | Centré | Aligné à droite |
| :-------------- | :----: | -------------: |
| Cellule 1       |   Cellule 2   |       Cellule 3    |
| Cellule 4       |   Cellule 5   |       Cellule 6    |    




## rediriger sur la page

pour un gain de temps on peut rediriger le lecteur directement sur un autre endroit de la page

on utilise la syntaxe suivante

    '''[aller à faire un titre](#faire-un-titre)

    '''
avec entre crochets l'action à réaliser , et entre parenthèses le nom du titre auquel on veut se rendre en remplacant les espaces par des

[sommaire](#sommaire)
