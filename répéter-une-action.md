# Comment répéter une action en Common Lisp ?

Il faut utiliser la macro `dotimes`.

Exemple:
```lisp
(dotimes (i 3)
  (format t "coucou !~%"))
```
Affiche "coucou !" 3 fois.
