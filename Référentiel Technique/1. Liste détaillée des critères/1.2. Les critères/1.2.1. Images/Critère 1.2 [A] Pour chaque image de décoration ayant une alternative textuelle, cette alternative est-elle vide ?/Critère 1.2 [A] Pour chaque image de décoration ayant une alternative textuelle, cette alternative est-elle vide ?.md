Principe=>Perceptible
Niveau=>A

*   Test 1.2.1 : Chaque [image de décoration](#image-de-dcoration) sans [légende](#lgende-dimage) (balise `img`) et ayant un attribut `alt` vérifie-t-elle ces conditions :
    *   le contenu de l'attribut alt est vide (`alt=""`)
    *   l'image de décoration ne possède pas d'attribut `title`
*   Test 1.2.2 : Chaque [zone non cliquable](#zone-non-cliquable) (balise `area` sans attribut `href`), non porteuse d'information et ayant un attribut `alt` vérifie-t-elle ces conditions ?
    *   le contenu de l'attribut `alt` est vide (`alt=""`)
    *   la zone cliquable ne possède pas d'attribut `title`
*   Test 1.2.3 : Pour chaque image objet sans [légende](#lgende-dimage) (balise `object` avec l'attribut `type="image/..."`) non porteuse d'information, l'alternative textuelle entre `<object>` et `</object>` est-elle vide ?
*   Test 1.2.4 : Chaque image vectorielle de décoration (balise `svg`) non porteuse d'information et possédant une alternative vérifie-t-elle ces conditions ?
    *   La balise `svg` possède un `role="img"`
    *   La balise `svg` ou l'un de ses enfants est dépourvue de role, propriété ou état ARIA visant à labelliser l'image vectorielle (`aria-label`, `aria-describedby`, `aria-labelledby` par exemple).
    *   Les balises `title` et `desc` sont absentes ou vides
    *   La balise `svg` ou l'un de ses enfants est dépourvue d'attribut `title`
*   Test 1.2.5 : Pour chaque image bitmap de décoration (balise `canvas`), le contenu entre `<canvas>` et `</canvas>` doit être dépourvu de contenus textuels, cette règle est-elle respectée ?

**Note technique :** [Consulter la note technique au sujet du role "présentation"](#critre-12-a)

**Correspondances WCAG 2.0**

Critère(s) de succès WCAG 2.0 : [1.1.1](http://www.w3.org/Translations/WCAG20-fr/#text-equiv-all) - [4.1.2](http://www.w3.org/Translations/WCAG20-fr/#ensure-compat-rsv)

Technique(s) suffisante(s) et/ou échec(s) WCAG 2.0 : [H67](http://www.w3.org/TR/WCAG-TECHS/H67.html) - [G196](http://www.w3.org/TR/WCAG-TECHS/G196.html) - [C9](http://www.w3.org/TR/WCAG-TECHS/C9.html) - [F39](http://www.w3.org/TR/WCAG-TECHS/F39.html) - [F38](http://www.w3.org/TR/WCAG-TECHS/F38.html) - [ARIA4](http://www.w3.org/TR/WCAG-TECHS/ARIA4.html) - [ARIA10](http://www.w3.org/TR/WCAG-TECHS/ARIA10.html)
