Principe=>Perceptible
Niveau=>A

*   Test 1.10.1 : Chaque image légendée (balise `img` ou `input` avec l'attribut `type="image"` associée à une légende adjacente) vérifie-t-elle, si nécessaire, ces conditions ?
    *   L'image (balise `img`) et sa légende sont contenues dans une balise `figure`
    *   la balise `figure` possède un attribut `role="group"`
    *   Le contenu de l'attribut `alt` de l'image contient une référence à la légende adjacente
    *   L'attribut `title` de l'image s'il est présent, est strictement identique au contenu de l'attribut `alt`
*   Test 1.10.2 : Chaque image objet (balise `object` avec l'attribut `type="image/..."` associée à une légende adjacente) vérifie-t-elle, si nécessaire, ces conditions ?
    *   L'image (balise `object`) et sa légende sont contenues dans une balise `figure`
    *   la balise `figure` possède un attribut `role="group"`
*   Test 1.10.3 : Chaque image embarquée légendée (balise `embed` associée à une légende adjacente) vérifie-t-elle, si nécessaire, ces conditions ?
    *   L'image embarquée (balise `embed`) et sa légende sont contenues dans une balise `figure`
    *   la balise `figure` possède un attribut `role="group"`
    *   Le contenu de l'attribut `alt` de l'image contient une référence à la légende adjacente
    *   L'attribut `title` de l'image s'il est présent, est strictement identique au contenu de l'attribut `alt`
*   Test 1.10.4 : Chaque image vectorielle légendée (balise `svg` associée à une légende adjacente) vérifie-t-elle, si nécessaire, ces conditions ?
    *   L'image (balise `svg`) et sa légende sont contenues dans une balise `figure`
    *   la balise `figure` possède un `role="group"`
    *   Le contenu de la propriété `aria-label` ou de la balise `desc` de l'image vectorielle contient une référence à la légende adjacente
    *   L'attribut `title` de l'image vectorielle (balise `svg`) s'il est présent, est strictement identique au contenu de la propriété `aria-label` ou de la balise `desc` utilisé comme alternative.
*   Test 1.10.5 : Chaque image bitmap légendée (balise `canvas` associée à une légende adjacente) vérifie-t-elle, si nécessaire, ces conditions ?
    *   L'image (balise `canvas`) et sa légende sont contenues dans une balise `figure`
    *   la balise `figure` possède un attribut `role="group"`
    *   Le contenu entre `<canvas>` et `</canvas>` de l'image bitmap contient une référence à la légende adjacente

**Note technique :** [Consulter la note technique au sujet des légendes d'images](#critre-11-a0)
**Correspondances WCAG 2.0**

Critère(s) de succès WCAG 2.0 : [1.1.1](http://www.w3.org/Translations/WCAG20-fr/#text-equiv-all) - [4.1.2](http://www.w3.org/Translations/WCAG20-fr/#ensure-compat-rsv)

Technique(s) suffisante(s) et/ou échec(s) WCAG 2.0 : [G140](http://www.w3.org/TR/WCAG-TECHS/G140.html) - [ARIA4](http://www.w3.org/TR/WCAG-TECHS/ARIA4.html) - [ARIA6](http://www.w3.org/TR/WCAG-TECHS/ARIA6.html)
