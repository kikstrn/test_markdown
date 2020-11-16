# Tuto Markdown

Le Markdown est un langage de balisage (comme le HTML). Sa structure est très légère.

## Les titres

avec #vous pouvez indiquer des titres de différents niveaux (comme h1, h2 etc en HTML)

    # Titre de niveau 1
    ## Titre de niveau 2
    etc

    ## Les listes

    On peut faire des listes de plusieurs niveaux:

 ##   Liste de course:

 - tomates
    - 3 normales
    - une barquette de tomate cerise
- mozzarella
- parmesan
 - huile d'olive

        - tomates
            - 3 normales
            - une barquette de tomate cerise
        - mozzarella
        - parmesan
        - huile d'olive

 ## Les liens

 Pour créer un lien on utilise les crochets [] pour y mettre notre texte et les parenthèses pour indiquer le lien vers lequel il redirige:

 [lien vers github](https://github.com)

    [lien vers github](https://github.com)

 ## Les images

 On peut rajouter des images !

 ![alt text](url de l'image)

 ## Les tableaux

| En-tête de colone 1 | En-tête de colone 2 |
|---------------------|---------------------|
| element colonne de ligne 1 | element colonne de ligne 1|
| element colonne de ligne 2 | element colonne de ligne 2|
| element colonne de ligne 3 | element colonne de ligne 3|
| element colonne de ligne 4 | element colonne de ligne 4|
| element colonne de ligne 5 | element colonne de ligne 5|

        | En-tête de colone 1 | En-tête de colone 2 |
        |---------------------|---------------------|
        | element colonne de ligne 1 | element colonne de ligne 1|
        | element colonne de ligne 2 | element colonne de ligne 2|
        | element colonne de ligne 3 | element colonne de ligne 3|
        | element colonne de ligne 4 | element colonne de ligne 4|
        | element colonne de ligne 5 | element colonne de ligne 5|

##Les éléments de texte

On peut mettre des éléments de texte en *italique*

    On peut mettre des éléments de texte en *italique*

Ou en **gras**

    Ou en **gras**

    Il est possible d'insérer des lignes de code entre 3 backticks (``) ou avec des tabulations

```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Morpion</title>

    <link rel="stylesheet" href="./css/style.css">
</head>
```

Le markdown n'interprète pas le retour à la ligne comme les autres langages:

On peut faire  
des  
retours  
à la ligne  
avec 2 espaces
