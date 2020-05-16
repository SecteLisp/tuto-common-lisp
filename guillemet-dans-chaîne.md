# Comment mettre une guillemet (") dans une chaîne de caractères en Common Lisp ?

En Common Lisp, une chaîne de caractères est notée entre guillemets (`"`).

Exemple :
```lisp
"Ma chaîne de caractères"
```

Pour mettre une guillemet dans une chaîne de caractères, c'est-à-dire "échapper" la guillemet, il faut mettre un `\` devant.

Exemple :
```lisp
"Ma guillemet: \"."
```

Important: il ne faut pas confondre la guillemet (`"`) avec l'apostrophe (`'`) ou l'accent grave (`` ` ``). L'apostrophe et l'accent grave ne nécessitent pas d'échappement.
