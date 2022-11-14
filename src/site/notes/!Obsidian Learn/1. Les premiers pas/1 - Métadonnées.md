---
{"dg-publish":true,"permalink":"/obsidian-learn/1-les-premiers-pas/1-metadonnees/"}
---


**SUPER IMPORTANT CA PERMET DE TRIER**

Il y a 2 façons d'écrire des métadonnées:
- En YAML
- Dans le corps de la page

### 1. YAML

Pour cela il faut mettre `---` au tout début d'un document. 
Dedans on peut y mettre tout ce qu'on veut pour aider à trier
Il y a l'exemple en début de page. (Il est repliable)
>[!CAUTION] 
>Attention il faut laisser un espace après ':' sinon ça foire
### 2. Corps de la page

On l'écrira comme suit
```
## Metadata
type:: #blublu
status:: #bloblo
source::
cost::
topics::
```
Ce qui donne: 
## Metadata
type:: `#blublu`
status:: `#bloblo` 
source::
cost::
topics::

Pareil que pour YAML laisser un espace après `::`.
