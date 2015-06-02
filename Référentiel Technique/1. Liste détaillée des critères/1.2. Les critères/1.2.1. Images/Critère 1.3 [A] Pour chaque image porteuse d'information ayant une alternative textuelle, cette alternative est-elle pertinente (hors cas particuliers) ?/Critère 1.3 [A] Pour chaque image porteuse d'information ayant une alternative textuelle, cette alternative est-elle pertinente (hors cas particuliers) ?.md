Principe=>Perceptible
Niveau=>A

*   Test 1.3.1 : Chaque [image porteuse d'information](#image-porteuse-dinformation) (balise `img`) ayant un attribut `alt` vérifie-t-elle ces conditions (hors [cas particuliers](#critre-13)) ?
    *   Le contenu de l'attribut `alt` est pertinent
    *   S'il est présent, le contenu de l'attribut `title` est identique au contenu de l'attribut `alt`
*   Test 1.3.2 : Chaque [zone](#zone-dune-image-ractive) (balise area) d'une [image réactive](#image-ractive), porteuse d'information et ayant un attribut `alt`, vérifie-t-elle ces conditions (hors [cas particuliers](#critre-13)) ?
    *   Le contenu de l'attribut `alt` est pertinent
    *   S'il est présent, le contenu de l'attribut `title` est identique au contenu de l'attribut `alt`
*   Test 1.3.3 : Pour chaque bouton associé à une image (balise `input` avec l'attribut `type="image"`) ayant un attribut `alt`, le contenu de cet attribut est-il pertinent (hors [cas particuliers](#critre-13)) ?
*   Test 1.3.4 : Chaque image objet (balise `object` avec l'attribut `type="image/..."`) porteuse d'information vérifie-t-elle une de ces conditions(hors [cas particuliers](#critre-13)) ?
    *   L'image objet est immédiatement suivie d'un lien adjacent permettant d'afficher une page ou un passage de texte contenant une alternative pertinente.
    *   Un mécanisme permet à l'utilisateur de remplacer l'image objet par un texte alternatif pertinent
    *   Un mécanisme permet à l'utilisateur de remplacer l'image objet par une image possédant une alternative pertinente.
*   Test 1.3.5 : Chaque image embarquée (balise `embed` avec l'attribut `type="image/..."`) porteuse d'information vérifie-t-elle une de ces conditions (hors [cas particuliers](#critre-13)) ?
    *   L'image embarquée est immédiatement suivie d'un lien adjacent permettant d'afficher une page ou un passage de texte contenant une alternative pertinente.
    *   Un mécanisme permet à l'utilisateur de remplacer l'image embarquée par un texte alternatif pertinent
    *   Un mécanisme permet à l'utilisateur de remplacer l'image embarquée par une image possédant une alternative pertinente.
*   Test 1.3.6 : Chaque image vectorielle porteuse d'information (balise `svg`) et possédant une alternative vérifie-t-elle une de ces conditions (hors [cas particuliers](#critre-13)) ?
    *   La balise `svg` possède un `role="img"`
    *   La balise `svg` possède une propriété `aria-label` dont le contenu est pertinent et identique à l'attribut `title` s'il est présent
    *   La balise `svg` possède une balise `desc` dont le contenu est pertinent et identique à l'attribut `title` de la balise `svg` s'il est présent
    *   Un lien adjacent permet d'accéder à une alternative dont le contenu est pertinent et identique à l'attribut `title` de la balise `svg` s'il est présent
*   Test 1.3.7 : Pour chaque image vectorielle porteuse d'information (balise `svg`) et possédant une alternative, cette alternative est-elle [correctement restituée](#correctement-restitue-par-les-technologies-dassistance) par les technologies d'assistance ?
*   Test 1.3.8 : Pour chaque image bitmap porteuse d'information (balise `canvas`) et possédant une alternative (contenu entre `<canvas>` et `</canvas>`), cette alternative est-elle [correctement restituée](#correctement-restitue-par-les-technologies-dassistance) par les technologies d'assistance ?
*   Test 1.3.9 : Pour chaque image bitmap porteuse d'information (balise `canvas`) et possédant une alternative (contenu entre `<canvas>` et `</canvas>`), cette alternative est-elle pertinente ?
*   Test 1.3.10 : Pour chaque image porteuse d'information et ayant une alternative textuelle, l'alternative textuelle est-elle [courte et concise](#alternative-courte-et-concise) (hors [cas particuliers](#critre-13)) ?

**Note technique :**[Consulter la note technique au sujet de l'attribut title et des des images vectorielles](#critre-13-a)

**Note technique :** [Consulter la note technique au sujet des images vectorielles](#critre-11-a)

**Correspondances WCAG 2.0**

Critère(s) de succès WCAG 2.0 : [1.1.1](http://www.w3.org/Translations/WCAG20-fr/#text-equiv-all) - [4.1.2](http://www.w3.org/Translations/WCAG20-fr/#ensure-compat-rsv)

Technique(s) suffisante(s) et/ou échec(s) WCAG 2.0 : [G94](http://www.w3.org/TR/WCAG-TECHS/G94.html) - [G95](http://www.w3.org/TR/WCAG-TECHS/G95.html) - [F30](http://www.w3.org/TR/WCAG-TECHS/F30.html) - [F71](http://www.w3.org/TR/WCAG-TECHS/F71.html) - [G196](http://www.w3.org/TR/WCAG-TECHS/G196.html) - [ARIA4](http://www.w3.org/TR/WCAG-TECHS/ARIA4.html)
