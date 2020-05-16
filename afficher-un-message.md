# Comment afficher un message en Common Lisp ?

En Common Lisp, les chaînes de caractères sont notées entre guillemets (`"`).

Exemple :
```lisp
"Chaîne de caractères"
```

Il existe deux moyens simples d'afficher un message en Common Lisp :
* [print](#afficher-un-message-avec-print)
* [format](#afficher-un-message-avec-format)

## Afficher un message avec print

La commande suivante affiche une chaîne de caractères :
```lisp
(print "Message")
```

* `print` est le nom de la fonction. Elle permet d'afficher un objet.
* `"Message"` est une chaîne de caractères.

## Afficher un message avec format

La commande suivante affiche une chaîne de caractères :
```lisp
(format t "Message~%")
```

* `format` est le nom de la fonction. Elle permet d'afficher une chaîne de caractères formatée.
* `t` signifie que le message doit s'afficher dans la console standard. Il est également possible de spécifier d'autres cibles où le message doit être enregistré hormis la console standard, comme par exemple un fichier.
* `"Message~%"` est une chaîne de caractères.
* Le `~%` dans la chaîne de caractères passée en paramètre de la fonction `format` affichera un saut à la ligne. Puisqu'il s'agit d'un effet sur l'affichage du texte, la chaîne de caractères est dite "formatée".
