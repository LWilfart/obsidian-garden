---
{"dg-publish":true,"permalink":"/obsidian-learn/2-formatage-de-texte/callout-interpeller/"}
---

**Utilise la synthaxe suivante pour créer un callout:** `> [!INFO]`.
```markdown
> [!INFO]
> Here's a callout block.
> It supports **markdown** and [[Internal link|wikilinks]].
```

**Résultats:**
> [!INFO]
> Here's a callout block.
> It supports **markdown** and [[!Obsidian Learn/1. Les premiers pas/4 - Liens internes\|wikilinks]].

### Types

Par défaut il y a 12 types de callout (différentes couleurs et icones).
Pour les utiliser il suffit de remplacer `INFO`  par un autre mot.

- note
- abstract, summary, tldr
- info, todo
- tip, hint, important
- success, check, done
- question, help, faq
- warning, caution, attention
- failure, fail, missing
- danger, error
- bug
- example
- quote, cite

On peut également en créer soi-même. mais pas besoin de s'encombrer la tête pour le moment.

### Titre

Le titre du callout peut être modifier comme suit:

```markdown
> [!TIP] Callouts can have custom titles
```

> [!TIP] Callouts can have custom titles

### Folding (replier)

On peut rentre un callout plié par défaut (dépliable) en ajoutant le signe `-` après les [].

```markdown
> [!FAQ]- Are callouts foldable?
> Yes! In a foldable callout, the contents are hidden until it is expanded.
```

**Résultats:**

> [!FAQ]- Are callouts foldable?
> Yes! In a foldable callout, the contents are hidden until it is expanded
