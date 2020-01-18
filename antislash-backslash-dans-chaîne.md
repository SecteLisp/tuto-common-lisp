# Comment mettre un antislash/backslash (\\) dans une chaîne de caractères en Common Lisp ?

En Common Lisp, une chaîne de caractères est notée entre guillemets (`"`).

Exemple :
```lisp
"Ma chaîne de caractères"
```

Pour mettre un antislash/backslash (`\`) dans une chaîne de cracatères, c'est-à-dire "échapper" l'antislash/backslash, il faut mettre un autre antislash/backslash `\` devant.

Exemple :
```lisp
"Mon antislash/backslash: \\."
```

Important: il ne faut pas confondre l'antislash/backslash (`\`) avec le slash (`/`). Le slash ne nécessite pas d'échappement.
