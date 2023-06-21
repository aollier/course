---
jupytext:
  cell_metadata_filter: all, -hidden, -heading_collapsed, -run_control, -trusted
  notebook_metadata_filter: all, -jupytext.text_representation.jupytext_version, -jupytext.text_representation.format_version,
    -language_info.version, -language_info.codemirror_mode.version, -language_info.codemirror_mode,
    -language_info.file_extension, -language_info.mimetype, -toc
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
language_info:
  name: python
  pygments_lexer: ipython3
notebookname: Les boucles `for`
---

<div class="licence">
<span>Licence CC BY-NC-ND</span>
<span>Thierry Parmentelat &amp; Arnaud Legout</span>
<span><img src="media/both-logos-small-alpha.png" /></span>
</div>

+++

# Les boucles `for`

+++

******

+++

## Exercice - niveau intermédiaire

+++

### Produit scalaire

On veut écrire une fonction qui retourne le produit scalaire de deux vecteurs. Pour ceci on va matérialiser les deux vecteurs en entrée par deux listes que l'on suppose de même taille.

On rappelle que le produit de X et Y vaut $\sum_{i} X_i * Y_i$.

On posera que le produit scalaire de deux listes vides vaut `0`.

+++

Naturellement puisque le sujet de la séquence est les expressions génératrices, on vous demande d'utiliser ce trait pour résoudre cet exercice.

**NOTE** remarquez bien qu'on a dit **expression** génératrice et pas nécessairement **fonction génératrice**.

```{code-cell} ipython3
# un petit exemple
from corrections.exo_produit_scalaire import exo_produit_scalaire
exo_produit_scalaire.example()
```

Vous devez donc écrire :

```{code-cell} ipython3
def produit_scalaire(X, Y): 
    """retourne le produit scalaire de deux listes de même taille"""
    "<votre_code>"
```

```{code-cell} ipython3
# pour vérifier votre code
exo_produit_scalaire.correction(produit_scalaire)
```
