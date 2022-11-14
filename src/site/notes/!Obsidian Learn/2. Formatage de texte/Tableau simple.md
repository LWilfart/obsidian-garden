---
{"dg-publish":true,"permalink":"/obsidian-learn/2-formatage-de-texte/tableau-simple/"}
---

Tu peux créer des tables en assemblant des listes de mot.
Tu sépares les mots que tu veux en colonne par des  `-` et les mots que tu veux en lignes par des `|`.

```md
First Header | Second Header
------------ | ------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```

First Header | Second Header
------------ | ------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

---

là ils expliquent que les colonnes s'ordonnent elle même pour avoir la bonne taille.

```md
Tables can be justified with a colon | Another example with a long title
:----------------|-------------:
because of the `:` | these will be justified
```

Tables can be justified with a colon | Another example with a long title
:----------------|-------------:
because of the `:` | these will be justified

On peut évidemment mettre les liens dans les tables, cependant si tu utilise un `|` pour renommer ton lien, il faut utiliser `\`  avant le pipe, sinon ça marche pas.

```md
First Header | Second Header
------------ | ------------
[[!Obsidian Learn/5. Autres/Images\|Images]]	|  [[Callouts\|Callouts]]
```

First Header | Second Header
------------ | ------------
[[Images]]	|  [[!Obsidian Learn/2. Formatage de texte/Callout (Interpeller)\|Callouts]]

