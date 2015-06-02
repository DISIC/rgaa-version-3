Principe=>Perceptible
Principe=>Utilisable
Principe=>Compréhensible
Principe=>Robuste
Niveau=>A

*   Test 11.10.1 : Pour chaque formulaire, les indications de champs obligatoires vérifient-ils une de ces conditions ?
    *   L'indication de champ obligatoire est donnée par un passage de texte avant le champ de formulaire
    *   L'indication de champ obligatoire est donnée via un attribut `required`
    *   L'indication de champ obligatoire est donnée via la propriété ARIA `aria-required`
    *   L'indication de champ obligatoire est donnée dans l'étiquette (balise attribut `label`, attribut `title`, propriété `aria-label`, passage de texte lié via la propriété `aria-labelledby`) du champ de formulaire
    *   L'indication de champ obligatoire est donnée par un passage de texte lié par la propriété ARIA `aria-describedby`
*   Test 11.10.2 : Chaque indication de champ obligatoire qui utilise les propriétés ARIA `aria-label`, `aria-required` ou l'attribut `required` doit être accompagnée d'une indication visuelle explicite dans l'étiquette (balise `label`) ou dans un passage de texte lié au champ par la propriété ARIA `aria-describedby` ou `aria-labelledby`, cette règle est-elle respectée ?
*   Test 11.10.3 : Chaque indication de champ obligatoire qui utilise un passage de texte lié par la propriété ARIA `aria-describedby` ou `aria-labelledby` vérifie-t-elle ces conditions ?
    *   Le passage de texte est identifié via un attribut `id`
    *   La valeur de l'attribut `id` est unique
    *   La valeur de la propriété ARIA `aria-describedby` ou `aria-labelledby` est égale à la valeur de l'attribut `id`
*   Test 11.10.4 : Pour chaque formulaire, les erreurs de saisie vérifient-elles une de ces conditions ?
    *   L'erreur de saisie est indiquée dans l'étiquette (balise `label`, attribut `title`, propriété ARIA `aria-label`, passage de texte lié via la propriété ARIA `aria-labelledby`) du champ de formulaire
    *   L'erreur de saisie est indiquée par un passage de texte avant le champ de formulaire
    *   Le champ de formulaire possède un `type` qui produit de manière automatique un message d'erreur de saisie
    *   L'erreur de saisie est indiquée par un passage de texte lié par la propriété ARIA `aria-describedby`
    *   L’erreur de saisie est indiquée via la propriété ARIA `aria-invalid`
*   Test 11.10.5 : Chaque indication d’erreur de saisie réalisée grâce à la propriété ARIA `aria-label` ou `aria-invalid` doit être accompagnée d'une indication visuelle explicite dans l’étiquette (balise `label`) ou dans un passage de texte lié au champ par la propriété ARIA `aria-describedby` ou `aria-labelledby`, cette règle est-elle respectée ?
*   Test 11.10.6 : Chaque erreur de saisie qui utilise un passage de texte lié par la propriété ARIA `aria-describedby` ou `aria-labelledby` vérifie-t-elle ces conditions ?
    *   Le passage de texte est identifié via un attribut `id`
    *   La valeur de l'attribut `id` est unique
    *   La valeur de la propriété ARIA `aria-describedby` ou `aria-labelledby` est égale à la valeur de l'attribut `id`
*   Test 11.10.7 : Pour chaque formulaire, chaque champ obligatoire vérifie-t-il une de ces conditions ?
    *   Le type de donnée et/ou de format est indiqué, si nécessaire, dans l'étiquette (balise `label`, attribut `title`, propriété ARIA `aria-label`, texte lié via la propriété ARIA `aria-labelledby`) du champ
    *   Le type de donnée et/ou de format est indiqué, si nécessaire, par un passage de texte avant le champ de formulaire
    *   Le type de donnée et/ou de format est indiqué, si nécessaire, par un texte lié par la propriété ARIA `aria-describedby`
*   Test 11.10.8 : Chaque indication du type de donnée et/ou de format réalisée grâce à la propriété ARIA `aria-label` doit être accompagnée d'une indication visuelle explicite dans l’étiquette (balise `label`) ou dans un passage de texte lié au champ par la propriété ARIA `aria-describedby` ou `aria-labelledby`, cette règle est-elle respectée ?
*   Test 11.10.9 : Chaque indication de type de donnée et/ou de format qui utilise un passage de texte lié par la propriété ARIA `aria-describedby` ou ARIA `aria-labelledby` vérifie-t-elle ces conditions ?
    *   Le passage de texte est identifié via un attribut `id`
    *   La valeur de l'attribut `id` est unique
    *   La valeur de la propriété ARIA `aria-describedby` ou ARIA `aria-labelledby` est égale à la valeur de l'attribut `id`

**Correspondances WCAG 2.0**

Critère(s) de succès WCAG 2.0 : [3.3.1](http://www.w3.org/Translations/WCAG20-fr/#minimize-error-identified) - [3.3.2](http://www.w3.org/Translations/WCAG20-fr/#minimize-error-cues)

Technique(s) suffisante(s) et/ou échec(s) WCAG 2.0 : [G83](http://www.w3.org/TR/WCAG-TECHS/G83.html) - [G84](http://www.w3.org/TR/WCAG-TECHS/G84.html) - [G85](http://www.w3.org/TR/WCAG-TECHS/G85.html) - [G89](http://www.w3.org/TR/WCAG-TECHS/G89.html) - [G184](http://www.w3.org/TR/WCAG-TECHS/G184.html) - [H44](http://www.w3.org/TR/WCAG-TECHS/H44.html) - [H89](http://www.w3.org/TR/WCAG-TECHS/H89.html) - [H90](http://www.w3.org/TR/WCAG-TECHS/H90.html) - [F81](http://www.w3.org/TR/WCAG-TECHS/F81.html) - [SCR18](http://www.w3.org/TR/WCAG-TECHS/SCR18.html) - [SCR32](http://www.w3.org/TR/WCAG-TECHS/SCR32.html) - [ARIA1](http://www.w3.org/TR/WCAG-TECHS/ARIA1.html) - [ARIA2](http://www.w3.org/TR/WCAG-TECHS/ARIA2.html) - [ARIA6](http://www.w3.org/TR/WCAG-TECHS/ARIA6.html) - [ARIA9](http://www.w3.org/TR/WCAG-TECHS/ARIA9.html) - [ARIA16](http://www.w3.org/TR/WCAG-TECHS/ARIA16.html) - [ARIA21](http://www.w3.org/TR/WCAG-TECHS/ARIA21.html)
