Principe=>Perceptible
Niveau=>A

*   Test 1.6.1 : Chaque [image porteuse d'information](#image-porteuse-dinformation) (balise `img`) qui nécessite une [description détaillée](#description-dtaille-image), vérifie-t-elle une de ces conditions ?
    *   Il existe un attribut `longdesc` qui donne l'adresse (`url`) d'une page contenant la [description détaillée](#description-dtaille-image)
    *   Il existe un attribut `alt` contenant la référence à une description détaillée adjacente à l'image
    *   Il existe un lien adjacent (via une `url` ou une `ancre`) permettant d'accéder au contenu de la description détaillée
*   Test 1.6.2 : Chaque image objet porteuse d'information (balise `object` avec l'attribut `type="image/..."`), qui nécessite une [description détaillée](#description-dtaille-image), vérifie-t-elle une de ces conditions ?
    *   Il existe un lien adjacent (via une `url` ou une `ancre`) permettant d'accéder au contenu de la [description détaillée](#description-dtaille-image)
    *   Il existe une [description détaillée](#description-dtaille-image) clairement identifiable adjacente à l'image objet
*   Test 1.6.3 : Chaque image embarquée porteuse d'information (balise `embed`), qui nécessite une [description détaillée](#description-dtaille-image), vérifie-t-elle une de ces conditions ?
    *   Il existe un lien adjacent (via une `url` ou une `ancre`) permettant d'accéder au contenu de la [description détaillée](#description-dtaille-image)
    *   Il existe une [description détaillée](#description-dtaille-image) clairement identifiable adjacente à l'image embarquée
*   Test 1.6.4 : Chaque bouton de formulaire de type image (balise `input` avec l'attribut `type="image"`), qui nécessite une [description détaillée](#description-dtaille-image), vérifie-t-il une de ces conditions ?
    *   Il existe un attribut `alt` contenant la référence à une description détaillée adjacente à l'image
    *   Il existe un [lien adjacent](#lien-adjacent) (via une `url` ou une `ancre`) permettant d'accéder au contenu de la [description détaillée](#description-dtaille-image)
*   Test 1.6.5 : Chaque image vectorielle (balise `svg`) qui nécessite une [description détaillée](#description-dtaille-image) vérifie-t-elle une de ces conditions ?
    *   Il existe une propriété `aria-label` contenant une référence à une description détaillée adjacente à l'image vectorielle
    *   Il existe une balise `desc` contenant une référence à une [description détaillée](#description-dtaille-image) adjacente à l'image vectorielle
    *   Il existe une balise `desc` contenant la [description détaillée](#description-dtaille-image)
    *   Il existe un lien adjacent (via une balise `url` ou une `ancre`) permettant d'accéder au contenu de la [description détaillée](#description-dtaille-image)
*   Test 1.6.6: Pour chaque image vectorielle (balise `svg`) qui implémente une référence à une [description détaillée](#description-dtaille-image) adjacente via une propriété `aria-label` ou une balise `desc`, cette référence est-elle [correctement restituée](#correctement-restitue-par-les-technologies-dassistance) par les technologies d'assistance ?
*   Test 1.6.7: Chaque image bitmap (balise `canvas`) qui nécessite une [description détaillée](#description-dtaille-image) vérifie-t-elle une de ces conditions ?
    *   Il existe un passage de texte entre `<canvas>` et `</canvas>` contenant une référence à une [description détaillée](#description-dtaille-image) adjacente à l'image bitmap
    *   Il existe un contenu textuel entre `<canvas>` et `</canvas>` faisant office de [description détaillée](#description-dtaille-image).
    *   Il existe un lien adjacent (via une `url` ou une `ancre`) permettant d'accéder au contenu de la [description détaillée](#description-dtaille-image)
*   Test 1.6.8: Pour chaque image bitmap (balise `canvas`) qui implémente une référence à une [description détaillée](#description-dtaille-image) adjacente, cette référence est-elle [correctement restituée](#correctement-restitue-par-les-technologies-dassistance) par les technologies d'assistance ?

**Note technique :** [Consulter la note technique au sujet des images vectorielle et de l'utilisation de la propriété `aria-describedby`](#critre-16-a)

**Correspondances WCAG 2.0**

Critère(s) de succès WCAG 2.0 : [1.1.1](http://www.w3.org/Translations/WCAG20-fr/#text-equiv-all)
Technique(s) suffisante(s) et/ou échec(s) WCAG 2.0 : [G92](http://www.w3.org/TR/WCAG-TECHS/G92.html) - [G74](http://www.w3.org/TR/WCAG-TECHS/G74.html) - [G73](http://www.w3.org/TR/WCAG-TECHS/G73.html) - [H45](http://www.w3.org/TR/WCAG-TECHS/H45.html) - [ARIA6](http://www.w3.org/TR/WCAG-TECHS/ARIA6.html)
