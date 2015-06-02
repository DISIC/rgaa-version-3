Principe=>Perceptible
Principe=>Utilisable
Principe=>Compréhensible
Principe=>Robuste
Niveau=>A

*   Test 11.1.1 : Chaque [champ de formulaire](#champ-de-saisie-de-formulaire) vérifie-t-il une de ces conditions ?
    *   Le champ de formulaire possède un attribut `title`
    *   Une [étiquette](#tiquette-de-champs-de-formulaire) (balise `label`) est associée au champ de formulaire
    *   Le [champ de formulaire](#champ-de-saisie-de-formulaire) possède une propriété `aria-label`
    *   Le [champ de formulaire](#champ-de-saisie-de-formulaire) possède une propriété `aria-labelledby` référençant un passage de texte identifié
*   Test 11.1.2 : Chaque [champ de formulaire](#champ-de-saisie-de-formulaire), associé à une [étiquette](#tiquette-de-champs-de-formulaire) (balise `label`), vérifie-t-il ces conditions ?
    *   Le [champ de formulaire](#champ-de-saisie-de-formulaire) possède un attribut `id`
    *   La valeur de l'attribut `id` est unique
    *   La balise `label` possède un attribut `for`
    *   La valeur de l'attribut `for` est égale à la valeur de l'attribut `id` du [champ de formulaire](#champ-de-saisie-de-formulaire) associé
*   Test 11.1.3 : Chaque [champ de formulaire](#champ-de-saisie-de-formulaire) associé à une [étiquette](#tiquette-de-champs-de-formulaire) via la propriété ARIA `aria-labelledby`, vérifie-t-il ces conditions ?
    *   l'[étiquette](#tiquette-de-champs-de-formulaire) possède un attribut `id`
    *   La valeur de l'attribut `id` est unique
    *   La valeur de la propriété ARIA `aria-labelledby` est égale à la valeur de l'attribut `id` de l'[étiquette](#tiquette-de-champs-de-formulaire)

**Correspondances WCAG 2.0**

Critère(s) de succès WCAG 2.0 : [1.3.1](http://www.w3.org/Translations/WCAG20-fr/#content-structure-separation-programmatic) - [2.4.6](http://www.w3.org/Translations/WCAG20-fr/#navigation-mechanisms-descriptive) - [3.3.2](http://www.w3.org/Translations/WCAG20-fr/#minimize-error-cues) - [4.1.2](http://www.w3.org/Translations/WCAG20-fr/#ensure-compat-rsv)

Technique(s) suffisante(s) et/ou échec(s) WCAG 2.0 : [H44](http://www.w3.org/TR/WCAG-TECHS/H44.html) - [H65](http://www.w3.org/TR/WCAG-TECHS/H65.html) - [G82](http://www.w3.org/TR/WCAG-TECHS/G82.html) - [G131](http://www.w3.org/TR/WCAG-TECHS/G131.html) - [ARIA6](http://www.w3.org/TR/WCAG-TECHS/ARIA6.html) - [ARIA9](http://www.w3.org/TR/WCAG-TECHS/ARIA9.html) - [ARIA16](http://www.w3.org/TR/WCAG-TECHS/ARIA16.html) - [ARIA14](http://www.w3.org/TR/WCAG-TECHS/ARIA14.html) - [F17](http://www.w3.org/TR/WCAG-TECHS/F17.html) - [F82](http://www.w3.org/TR/WCAG-TECHS/F82.html) - [F86](http://www.w3.org/TR/WCAG-TECHS/F86.html) - [F68](http://www.w3.org/TR/2014/NOTE-WCAG20-TECHS-20140916/F68.html)
