# Comment savoir si un objet est un symbole en Common Lisp ?

Il faut utiliser la fonction `symbolp`.

Exemples :
```lisp
(symbolp 'ok)
(symbolp "cette chaîne est-elle un symbole ?")
```
