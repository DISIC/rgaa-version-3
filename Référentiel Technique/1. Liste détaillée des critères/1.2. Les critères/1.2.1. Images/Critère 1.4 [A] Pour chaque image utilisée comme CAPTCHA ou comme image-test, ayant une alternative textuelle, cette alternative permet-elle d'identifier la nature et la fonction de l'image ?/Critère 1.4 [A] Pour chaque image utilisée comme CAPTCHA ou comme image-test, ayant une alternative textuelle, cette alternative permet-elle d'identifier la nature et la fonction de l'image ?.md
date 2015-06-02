Principe=>Perceptible
Niveau=>A

*   Test 1.4.1 : Chaque image (balise `img`) utilisée comme [CAPTCHA](#captcha) ou comme [image-test](#imagetest), ayant un attribut `alt`, vérifie-t-elle ces conditions ?
    *   le contenu de l'attribut `alt` permet d'identifier la nature et la fonction de l'image
    *   s'il est présent, le contenu de l'attribut `title` est identique au contenu de l'attribut `alt`
*   Test 1.4.2 : Chaque [zone](#zone-dune-image-ractive) (balise `area`) d'une [image réactive](#image-ractive), utilisée comme [CAPTCHA](#captcha) ou comme [image-test](#imagetest), et ayant un attribut `alt` vérifie-t-elle ces conditions ?
    *   le contenu de l'attribut `alt` permet d'identifier la nature et la fonction de la zone
    *   s'il est présent, le contenu de l'attribut `title` est identique au contenu de l'attribut `alt`
*   Test 1.4.3 : Chaque bouton associé à une image (balise `input` avec l'attribut `type="image"`) utilisée comme [CAPTCHA](#captcha) ou comme [image-test](#imagetest), ayant un attribut `alt` vérifie-t-il ces conditions ?
    *   le contenu de l'attribut `alt` permet d'identifier la nature et la fonction du bouton
    *   s'il est présent, le contenu de l'attribut `title` est identique au contenu de l'attribut `alt`
*   Test 1.4.4 : Pour chaque [image objet](#image-objet) (balise `object` avec l'attribut `type="image/..."`) utilisée comme [CAPTCHA](#captcha) ou comme [image-test](#imagetest), et ayant une [alternative textuelle](#alternative-textuelle-image), l'[alternative textuelle](#alternative-textuelle-image) permet-elle d'identifier la nature et la fonction de l'image ?
*   Test 1.4.5 : Pour chaque image embarquée (balise `embed` avec l'attribut `type="image/..."`) utilisée comme [CAPTCHA](#captcha) ou comme [image-test](#imagetest), et ayant une [alternative textuelle](#alternative-textuelle-image), l'[alternative textuelle](#alternative-textuelle-image) permet-elle d'identifier la nature et la fonction de l'image ?
*   Test 1.4.6 : Chaque image vectorielle (balise `svg`) utilisée comme [CAPTCHA](#captcha) ou comme [image-test](#imagetest) et ayant une [alternative textuelle](#alternative-textuelle-image) via la propriété `aria-label` ou la balise `desc` vérifie-t-elle ces conditions ?
    *   l'alternative textuelle implémentée via la propriété `aria-label` permet d'identifier la nature et la fonction de l'image et est identique à l'attribut `title` s'il est présent
    *   l'alternative textuelle implémentée via la balise `desc` permet d'identifier la nature et la fonction de l'image et est identique à l'attribut `title` de la balise `svg` s'il est présent
*   Test 1.4.7 : Pour chaque image vectorielle (balise `svg`) utilisée comme [CAPTCHA](#captcha) ou comme image-test et ayant une alternative textuelle , l'alternative textuelle est-elle [correctement restituée](#correctement-restitue-par-les-technologies-dassistance) par les technologies d'assistance ?
*   Test 1.4.8 : Pour chaque image bitmap (balise `canvas`) utilisée comme [CAPTCHA](#captcha) ou comme image-test et ayant une alternative textuelle, l'alternative textuelle permet-elle d'identifier la nature et la fonction de l'image ?
*   Test 1.4.9 : Pour chaque image bitmap (balise `canvas`) utilisée comme [CAPTCHA](#captcha) ou comme image-test et ayant une alternative textuelle , l'alternative textuelle est-elle [correctement restituée](#correctement-restitue-par-les-technologies-dassistance) par les technologies d'assistance ?

**Correspondances WCAG 2.0**

Critère(s) de succès WCAG 2.0 : [1.1.1](http://www.w3.org/Translations/WCAG20-fr/#text-equiv-all)

Technique(s) suffisante(s) et/ou échec(s) WCAG 2.0 : [G143](http://www.w3.org/TR/WCAG-TECHS/G143.html) - [G100](http://www.w3.org/TR/WCAG-TECHS/G100.html)
