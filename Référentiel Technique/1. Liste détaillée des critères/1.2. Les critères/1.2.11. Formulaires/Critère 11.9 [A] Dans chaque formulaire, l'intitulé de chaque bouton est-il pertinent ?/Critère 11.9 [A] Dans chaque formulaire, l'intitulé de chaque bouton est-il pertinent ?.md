Principe=>Perceptible
Principe=>Utilisable
Principe=>Compréhensible
Principe=>Robuste
Niveau=>A

*   Test 11.9.1 : Dans chaque formulaire, l'intitulé de chaque [bouton](#bouton-formulaire) vérifie-t-il une de ces conditions ?
    *   Le contenu de l'attribut value des boutons de formulaire de type `submit`, `reset` ou `button` est pertinent
    *   Le contenu de la balise `<button>` est pertinent
    *   Le contenu de l'attribut `title` est pertinent
    *   Le contenu de la propriété ARIA `aria-label` est pertinent
*   Test 11.9.2 : Dans chaque formulaire, l'intitulé de chaque [bouton](#bouton-formulaire) implémenté via une propriété ARIA `aria-labelledby` vérifie-t-il ces conditions ?
    *   Le passage de texte servant d'intitulé possède un attribut `Id`
    *   La valeur de l'attribut `id` est unique
    *   La valeur de la propriété ARIA `aria-labelledby` est égale à la valeur de l'attribut `id` du passage de texte
    *   Le passage de texte est pertinent

**Correspondances WCAG 2.0**

Critère(s) de succès WCAG 2.0 : [4.1.2](http://www.w3.org/Translations/WCAG20-fr/#ensure-compat-rsv)

Technique(s) suffisante(s) et/ou échec(s) WCAG 2.0 : [H36](http://www.w3.org/TR/WCAG-TECHS/H36.html) - [H91](http://www.w3.org/TR/WCAG-TECHS/H91.html) - [ARIA6](http://www.w3.org/TR/WCAG-TECHS/ARIA6.html) - [ARIA9](http://www.w3.org/TR/WCAG-TECHS/ARIA9.html) - [ARIA16](http://www.w3.org/TR/WCAG-TECHS/ARIA16.html) - [ARIA14](http://www.w3.org/TR/WCAG-TECHS/ARIA14.html)
