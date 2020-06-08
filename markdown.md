## Code

Il y a plusieurs manières d'afficher du code en markdown.\
Si le code est inline, il suffit de l'insérer dans des backticks : `var example = true`\
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

Il est même possible d'avoir une mise en forme colorée du code. Pour ça il sufit de rajouter le nom de language utilisé sur la première ligne de backticks :

```javascript
if (isAwesome){
  return true
}
```

## Extras

GitHub gère de nombreux extras en markdown qui permettent référencer et créer des liens vers d'autres personnes. Pour envoyer un comentaire à une persone en particulier, il suffit d'ajouter le symbole @ juste devant son nom : Salut @Joe, j'adore ton t-shirt !\

Mais il faut admettre que les checklists sont vraiment cool :
- [x] Elément coché
- [ ] Elément non coché