## Les niveaux de titres

En Markdown on peut utiliser jusqu'à 6 niveaux de titres avec des `#`:

`# Titre` sera un titre de niveau 1.

`## Titre` sera un titre de niveau 2.

`### Titre` sera un titre de niveau 3.

Etc. jusque `###### Titre` qui sera un titre de niveau 6.

## Le formatage de texte

Le markdown permet de formater du texte avec une syntaxe simple.

### Italique

Pour mettre du texte en italique il y a deux méthodes:

- `*`exemple`*` donne *exemple*.
- `_`exemple`_` donne _exemple_.

### Gras

La manière de mettre le texte en gras est similaire à l'italique mais on double les symboles:

- `**`exemple`**` donne **exemple**.
- `__`exemple`__` donne __exemple__.

### Barré

Pour ~~barrer~~ un mot ou une phrase, il suffit de l'encapsuler comme ceci `~~exemple~~`.

## Les listes

Le Markdown nous permet de faire des listes, ordonnées ou non, avec la possibilité de les imbriquer.

### Liste à puce

Pour réaliser une liste à puce, on peut utiliser des `*` ou des `-`.

Pour faire une liste imbriquée il suffit de laisser un espace devant la ligne souhaitée.
```
- Par
- exemple
    - comme
    - ceci
- !
```
Donne:

- Par
- exemple
    - comme
    - ceci
- !

### Liste ordonnée

Pour la liste ordonnée, c'est la meme syntaxe que pour la liste à puce sauf qu'on remplace les symboles par `1.`.
```
1. Par
1. exemple
    1. comme
    1. ceci
1. !
```
Donne:

1. Par
1. exemple
    1. comme
    1. ceci
1. !

## Code

Il y a plusieurs manières d'afficher du code en markdown.  
Si le code est inline, il suffit de l'insérer dans des backticks : `var example = true`  
Pour les blocks de code plus longs, il suffit de les décaler de 4 espaces :

    if (isAwesome){
      return true
    }

GitHub permet aussi d'afficher des blocks de code sans devoir les décaler, en insérant une ligne avec 3 backticks avant et après :

```
if (isAwesome){
  return true
}
```

Il est même possible d'avoir une coloration syntaxique du code. Pour ça il sufit de rajouter le nom de language utilisé sur la première ligne, juste après les 3 backticks :

```javascript
if (isAwesome){
  return true
}
```

## Extras

### Liens

GitHub gère de nombreux extras en markdown qui permettent de référencer et créer des liens vers d'autres personnes. Pour envoyer un comentaire à une personne en particulier, il suffit d'ajouter le symbole `@` juste devant son nom : Salut @fwauters, j'adore ton t-shirt !  

### Checklists

Il faut reconnaître que les checklists sont vraiment cool :
- [x] Elément coché
- [ ] Elément non coché

### Emojis

Pour afficher des emojis, il suffit d'écrire la référence de celui qu'on veut utiliser, encadrée par le symbole `:`   
Voici quelques exemples :

Code      | Emoji
--------- | ---------
`:smile:` | :smile:
`:wink:`  | :wink:
`:joy:`   | :joy:
`:yum:`   | :yum:
`:hugs:`  | :hugs:
`:mask:`  | :mask:

## Insertion d’une image statique

Les images s'insèrent en mettant un point d'exclamation `!` devant les premiers crochets. Le texte entre crochets `[``]` est le texte alternatif de l'image suivi du lien de l'image entre parenthèse `(``)` exemple :

> `![Zozor](lien/url)`

## Insertion d’une image animée

C'est pareil que pour insérer une image statique avec une seul différence, le lien de l'image doit finir en `.gif` exemple:

> `![Chat](lien/url)`

## Citations

Si vous souhaitez citer quelqu'un, utilisez le caractère `>` avant la ligne et ce pour chaque ligne de texte à citer.  Exemple :

> `> Ceci est un texte cité.`

## Les tables

Pour la création des tableaux, utiliser **-** pout les lignes horisontales, et un tuyau **|** pour les lignes verticales (*raccourci clavier:ALT 124*)

### Les étapes a suivre pour obtenir le tableau ci-bas

1. Ecrivez en-tête.
2. Placez un tuyau.
3. Ecrivez votre deuxième en-tête.
4. Sautez la ligne.
5. Divisez par les tirets.  
6. Sautez la ligne.
7. Ecrivez le contenu de votre texte1.
8. Placez un tuyau.  
9. Contenu de votre texte2.  
10. Saut a la ligne.
11. Contenu de texte3.  
12. Placez un tuyeau.  
13. contenu texte4.  

*(Pensez a bien alligner vos tuyaux ensemble)*

En-tête           |    En-tête2
------------------|---------------
Contenu texte1    |Contenu texte2
Contenu texte3    |Contenu texte4

## Liens automatiques

Les URL seront automatiquement convertis en lien cliquable.

*Ex:*

(https://twitter.com/explore)

## Mentions

Pour mentionner une personne, précéder son nom d'utilisateur de `@`.

*Ex:*

Salut @88aleksandra88
