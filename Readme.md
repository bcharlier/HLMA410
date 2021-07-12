# Matériel Pédagogique de HLMA410

Le cours comporte 2 parties:
  1. Géométrie: courbes paramétrées, normes, espace Euclidien
  2. Analyse: fonctions de plusieurs variables, intégration

Pendant 2 ans, il y a aussi eut une partie Probabilité discrète.

# Compilation des .tex

Les figures en pgfplot utilisent gnuplot pour générer les valeurs tracées. Il faut donc installer `gnuplot` sur la machine et utiliser la commande suivante pour compiler:

```bash
pdflatex --synctex=1 --shell-escape -interaction=nonstopmode $*
```
Les fichiers générés sont dans le sous-répertoire `output_latex`
