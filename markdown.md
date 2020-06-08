# Code
Il y a plusieurs manières d'afficher du code en markdown.
C'est le code est inline, il suffit de de l'insérer dans des backticks : `var example = true`
Pour les block de code plus longs, il suffit de les décaler de 4 espaces :

    if (isAwesome){
      return true
    }

GitHub permet aussi d'afficher des blocks de code sans devoir les décaler :

```
if (isAwesome){
  return true
}
```

Il est même possible d'avoir une mise en forme du code. Pour ça il sufit de rajouter le nom de language utilisé :

```javascript
if (isAwesome){
  return true
}
```