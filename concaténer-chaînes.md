# Comment concaténer des chaînes de caractères en Common Lisp ?

\[Note] "Concaténer" signifie "mettre bout à bout".

Pour concaténer des chaînes de caractères en Common Lisp, il suffit d'utiliser la fonction `concatenate` avec le symbole `string`.

Par exemple, pour concaténer `"abc"`, `"def"`, et `"ghi"` :
```lisp
(concatenate 'string "abc" "def" "ghi")
```
