Principe=>Perceptible
Principe=>Utilisable
Principe=>Compréhensible
Principe=>Robuste
Niveau=>A

*   Test 7.3.1 : Chaque élément possédant un gestionnaire d'événement contrôlé par un [script](#script) vérifie-t-il une de ces conditions ([hors cas particuliers](#critre-73 "Cas particuliers pour le critère 7.3")) ?
    *   L'élément est [accessible par le clavier et la souris](#accessible-et-activable-par-le-clavier-et-la-souris)
    *   Un élément [accessible par le clavier et la souris](#accessible-et-activable-par-le-clavier-et-la-souris) permettant de réaliser la même action est présent dans la page
*   Test 7.3.2 : Chaque élément possédant un gestionnaire d'événement contrôlé par un [script](#script) vérifie-t-il une de ces conditions ([hors cas particuliers](#critre-73 "Cas particuliers pour le critère 7.3")) ?
    *   L'élément est [activable par le clavier et la souris](#accessible-et-activable-par-le-clavier-et-la-souris)
    *   Un élément [activable par le clavier et la souris](#accessible-et-activable-par-le-clavier-et-la-souris) permettant de réaliser la même action est présent dans la page
*   Test 7.3.3 : Un [script](#script) ne doit pas supprimer le `focus` d'un élément qui le reçoit. Cette règle est-elle respectée ([hors cas particuliers](#critre-73 "Cas particuliers pour le critère 7.3")) ?
*   Test 7.3.4 : Chaque composant d'interface implémenté via un rôle défini par l'API ARIA et correspondant à un [motif de conception](#motif-de-conception) respecte-t-il une de ces conditions ?
    *   Les interactions au clavier sont conformes au comportement défini par le [motif de conception](#motif-de-conception) pour les touches `Echap`, `Barre d'espace`, `Tabulation` et `Flèches de direction` au moins
    *   Un composant d'interface présent sur la page, permettant de réaliser la même action, possède des interactions au clavier conformes au comportement défini par le [motif de conception](#motif-de-conception) , pour les touches `Echap`, `Barre d'espace`, `Tabulation` et `Flèches de direction` au moins
    *   Une alternative permettant d'accéder aux mêmes fonctionnalités est contrôlable par le clavier et à la souris.

**Note technique :** [Consulter la note technique au sujet des interactions au clavier via l'API ARIA](#critre-73 a)

**Correspondances WCAG 2.0**

Critère(s) de succès WCAG 2.0 : [1.3.1](http://www.w3.org/Translations/WCAG20-fr/#content-structure-separation-programmatic) - [2.1.1](http://www.w3.org/Translations/WCAG20-fr/#keyboard-operation-keyboard-operable) - [2.1.3](http://www.w3.org/Translations/WCAG20-fr/#keyboard-operation-all-funcs) - [2.4.7](http://www.w3.org/Translations/WCAG20-fr/#navigation-mechanisms-focus-visible)

Technique(s) suffisante(s) et/ou échec(s) WCAG 2.0 : [G202](http://www.w3.org/TR/WCAG-TECHS/G202.html) - [SCR2](http://www.w3.org/TR/WCAG-TECHS/SCR2.html) - [SCR20](http://www.w3.org/TR/WCAG-TECHS/SCR20.html) - [SCR29](http://www.w3.org/TR/WCAG-TECHS/SCR29.html) - [SCR35](http://www.w3.org/TR/WCAG-TECHS/SCR35.html) - [G90](http://www.w3.org/TR/WCAG-TECHS/G90.html) - [F42](http://www.w3.org/TR/WCAG-TECHS/F42.html) - [F54](http://www.w3.org/TR/WCAG-TECHS/F54.html) - [F55](http://www.w3.org/TR/WCAG-TECHS/F55.html)
