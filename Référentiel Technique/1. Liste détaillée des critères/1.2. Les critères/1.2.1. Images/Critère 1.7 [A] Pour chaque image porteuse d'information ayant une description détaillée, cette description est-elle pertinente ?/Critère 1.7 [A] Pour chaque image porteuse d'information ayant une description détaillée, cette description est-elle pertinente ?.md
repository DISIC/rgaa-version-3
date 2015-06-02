Principe=>Perceptible
Niveau=>A

*   Test 1.7.1 : Chaque [image porteuse d'information](glossaire.htm#mimgInfo) (balise `img` ou `input` avec l'attribut `type="image"`) ayant une [description détaillée](#description-dtaille-image) vérifie-t-elle une de ces conditions ?
    *   La [description détaillée](#description-dtaille-image) via l'adresse référencée dans l'attribut `longdesc` est pertinente
    *   La [description détaillée](#description-dtaille-image) dans la page et signalée dans l'attribut `alt` est pertinente
    *   La [description détaillée](#description-dtaille-image) via un [lien adjacent](#lien) est pertinente
*   Test 1.7.2 : Chaque [image objet](glossaire.htm#mimgObj) (balise `object` avec l'attribut `type="image/..."`) ayant une [description détaillée](#description-dtaille-image) vérifie-t-elle une de ces conditions ?
    *   La [description détaillée](#description-dtaille-image) adjacente à l'image objet est pertinente
    *   La [description détaillée](#description-dtaille-image) via un [lien adjacent](#lien) est pertinente
*   Test 1.7.3 : Chaque image embarquée (balise `embed` avec l'attribut `type="image/..."`) ayant une [description détaillée](#description-dtaille-image) vérifie-t-elle une de ces conditions ?
    *   La [description détaillée](#description-dtaille-image) adjacente à l'image embarquée est pertinente
    *   La [description détaillée](#description-dtaille-image) via un [lien adjacent](#lien) est pertinente
*   Test 1.7.4 : Chaque image vectorielle (balise `svg`) ayant une [description détaillée](#description-dtaille-image) vérifie-t-elle une de ces conditions ?
    *   La [description détaillée](#description-dtaille-image) adjacente à l'image vectorielle est pertinente
    *   La [description détaillée](#description-dtaille-image) contenue dans la balise `desc` est pertinente
    *   La [description détaillée](#description-dtaille-image) via un [lien adjacent](#lien) est pertinente
*   Test 1.7.5: Pour chaque image vectorielle (balise `svg`) ayant une description détaillée implémentée via la balise `desc`, cette description détaillée est-elle [correctement restituée](#correctement-restitue-par-les-technologies-dassistance) par les technologies d'assistance ?
*   Test 1.7.6: Chaque image bitmap (balise `canvas`) ayant une description détaillée vérifie-t-elle une de ces conditions ?
    *   La description détaillée adjacente à l'image bitmap est pertinente
    *   La description détaillée contenue entre `<canvas>` et `</canvas>` est pertinente
    *   La description détaillée via un lien adjacent est pertinente
*   Test 1.7.7: Pour chaque image bitmap (balise `canvas`) ayant une description détaillée entre `<canvas>` et `</canvas>`, cette description détaillée est-elle [correctement restituée](#correctement-restitue-par-les-technologies-dassistance) par les technologies d'assistance ?

**Correspondances WCAG 2.0**

Critère(s) de succès WCAG 2.0 : [1.1.1](http://www.w3.org/Translations/WCAG20-fr/#text-equiv-all)

Technique(s) suffisante(s) et/ou échec(s) WCAG 2.0 : [G92](http://www.w3.org/TR/WCAG-TECHS/G92.html) - [F67](http://www.w3.org/TR/WCAG-TECHS/F67.html)
