Principe=>Perceptible
Niveau=>A

*   Test 5.7.1 : Chaque en-tête (balise `th`) s'appliquant à la totalité de la ligne ou de la colonne possède-t-il un attribut `id` unique ou un attribut `scope` ?
*   Test 5.7.2 : Chaque en-tête (balise `th`) s'appliquant à la totalité de la ligne ou de la colonne et possédant un attribut `scope` vérifie-t-il une de ces conditions ?
    *   L'en-tête possède un attribut `scope` avec la valeur `"row"` pour les en-têtes de ligne
    *   L'en-tête possède un attribut `scope` avec la valeur `"col"` pour les en-têtes de colonne
*   Test 5.7.3 : Chaque en-tête (balise `th`) ne s'appliquant pas à la totalité de la ligne ou de la colonne vérifie-t-il ces conditions ?
    *   L'en-tête ne possède pas d'attribut `scope`
    *   L'en-tête possède un attribut `id` unique
*   Test 5.7.4 : Chaque cellule (balise `td` ou `th`) associée à un ou plusieurs en-têtes possédant un attribut `id` vérifie-t-elle ces conditions ?
    *   La cellule possède un attribut `headers`
    *   L'attribut `headers` possède la liste des valeurs des en-têtes associés à la cellule.

**Correspondances WCAG 2.0**

Critère(s) de succès WCAG 2.0 : [1.3.1](http://www.w3.org/Translations/WCAG20-fr/#content-structure-separation-programmatic)

Technique(s) suffisante(s) et/ou échec(s) WCAG 2.0 : [H63](http://www.w3.org/TR/WCAG-TECHS/H63.html) - [H43](http://www.w3.org/TR/WCAG-TECHS/H43.html) - [F90](http://www.w3.org/TR/2014/NOTE-WCAG20-TECHS-20140916/F90.html)
