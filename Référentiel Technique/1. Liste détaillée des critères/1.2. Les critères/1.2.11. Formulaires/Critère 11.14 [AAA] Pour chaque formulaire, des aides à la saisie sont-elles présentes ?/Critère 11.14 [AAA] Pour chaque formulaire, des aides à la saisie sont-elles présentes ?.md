Principe=>Perceptible
Principe=>Utilisable
Principe=>Compréhensible
Principe=>Robuste
Niveau=>AAA

*   Test 11.14.1 : Chaque formulaire vérifie-t-il une de ces conditions ?
    *   Il existe un lien vers une page d'aide
    *   Il existe des indications avant le formulaire
    *   Il existe des indications avant les champs de formulaire
    *   Il existe des indications dans l'étiquette (balise `label`, attribut `title`, propriété `aria-label`, passage de texte lié via la propriété `aria-labelledby`) du champ de formulaire
    *   Il existe des indications dans un passage de texte lié par la propriété ARIA `aria-describedby`
    *   Un assistant est disponible
*   Test 11.14.2 : Chaque indication qui utilise la propriété ARIA `aria-label` doit être accompagnée d'une indication visuelle équivalente explicite, cette règle est-elle respectée ?
*   Test 11.14.3 : Chaque indication qui utilise un passage de texte lié par la propriété ARIA `aria-describedby` vérifie-t-elle ces conditions ?
    *   Le passage de texte est identifié via un attribut `id`
    *   La valeur de l'attribut `id` est unique
    *   La valeur de la propriété ARIA `aria-describedby` est égale à la valeur de l'attribut `id`
*   Test 11.14.4 : Chaque champ de type texte vérifie-t-il, si nécessaire, l'une de ces conditions ?
    *   Un correcteur orthographique est disponible
    *   Des suggestions de saisie sont disponibles avant le champ du formulaire
    *   Des suggestions de saisie sont disponibles dans l'étiquette (balise `label`, attribut `title`, propriété `aria-label`, passage de texte lié via la propriété `aria-labelledby`) du champ de formulaire
    *   Des suggestions de saisie sont disponibles dans un passage de texte lié par la propriété ARIA `aria-describedby`
*   Test 11.14.5 : Chaque suggestion qui utilise la propriété ARIA `aria-label` doit être accompagnée d'une suggestion visuelle équivalente explicite, cette règle est-elle respectée ?
*   Test 11.14.6 : Chaque suggestion qui utilise un passage de texte lié par la propriété ARIA `aria-describedby` vérifie-t-elle ces conditions ?
    *   Le passage de texte est identifié via un attribut `id`
    *   La valeur de l'attribut `id` est unique
    *   La valeur de la propriété ARIA `aria-describedby` est égale à la valeur de l'attribut `id`

**Correspondances WCAG 2.0**

Critère(s) de succès WCAG 2.0 : [3.3.5](http://www.w3.org/Translations/WCAG20-fr/#minimize-error-context-help) - [3.3.2](http://www.w3.org/Translations/WCAG20-fr/#minimize-error-cues)

Technique(s) suffisante(s) et/ou échec(s) WCAG 2.0 : [G71](http://www.w3.org/TR/WCAG-TECHS/G71.html) - [G193](http://www.w3.org/TR/WCAG-TECHS/G193.html) - [G194](http://www.w3.org/TR/WCAG-TECHS/G194.html) - [G184](http://www.w3.org/TR/WCAG-TECHS/G184.html) - [G89](http://www.w3.org/TR/WCAG-TECHS/G89.html) - [ARIA1](http://www.w3.org/TR/WCAG-TECHS/ARIA1.html) - [ARIA6](http://www.w3.org/TR/WCAG-TECHS/ARIA6.html) - [ARIA9](http://www.w3.org/TR/WCAG-TECHS/ARIA9.html) - [ARIA16](http://www.w3.org/TR/WCAG-TECHS/ARIA16.html) - [F81](http://www.w3.org/TR/WCAG-TECHS/F81.html)
