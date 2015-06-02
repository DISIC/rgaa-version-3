Principe=>Perceptible
Principe=>Utilisable
Principe=>Compréhensible
Principe=>Robuste
Niveau=>A

*   Test 7.1.1 : Chaque [script](#script) qui génère ou contrôle un composant d'interface vérifie-t-il, si nécessaire, une de ces conditions ?
    *   [Le nom, le rôle, la valeur, le paramétrage et les changements d'états](#le-nom-le-rle-la-valeur-le-paramtrage-et-les-changements-dtats) sont accessibles aux technologies d'assistance via une API d'accessibilité
    *   un composant d'interface accessible permettant d'accéder aux mêmes fonctionnalités est présent dans la page ;
    *   une [alternative](#alternative--script) accessible permet d'accéder aux mêmes fonctionnalités.
*   Test 7.1.2 : Chaque fonctionnalité d'insertion de contenu contrôlée par un [script](#script) utilise-t-elle des [propriétés et méthodes conformes à la spécification DOM (Document Object Model)](#proprits-et-mthodes-conformes--la-spcification-dom) ?
*   Test 7.1.3 :Chaque [script](#script) qui génère, met à jour ou contrôle un composant d'interface qui comporte des rôles des états ou des propriétés correspondant à un [motif de conception](#motif-de-conception) défini par l'API ARIA vérifie-t-il une de ces conditions ?
    *   Le composant d'interface est conforme au [motif de conception](#motif-de-conception) défini par l'API ARIA
    *   Un composant d'interface présent sur la page, permettant d'accéder aux mêmes fonctionnalités, est conforme au [motif de conception](#motif-de-conception) défini par l'API ARIA
    *   Le composant d'interface [adapte un motif de conception](#adapter-un-motif-de-conception-aria) défini par l'API ARIA.
    *   Une [alternative](#alternative--script) accessible permet d'accéder aux mêmes fonctionnalités.
*   Test 7.1.4 : Chaque [modification du rôle natif](#modification-du-rle-natif-dun-lment-html) d'un élément HTML respecte-t-elle les règles et préconisations indiquées dans la spécification HTML5 et les notes techniques associées ?
*   Test 7.1.5 : Chaque [script](#script) qui génère ou contrôle un composant d'interface via des rôles, des états ou des propriétés définis par l'API ARIA respecte-t-il une de ces conditions ?
    *   Le composant d'interface est [](#correctement-restitue-par-les-technologies-dassistance)[correctement restitué](#correctement-restitue-par-les-technologies-dassistance) par les technologies d'assistance
    *   Une [alternative](#alternative--script) accessible permet d'accéder aux mêmes fonctionnalités.
*   Test 7.1.6 : Chaque composant d'interface qui utilise un role ARIA `application` respecte-t-il une de ces conditions ?
    *   Le composant d'interface est [](#correctement-restitue-par-les-technologies-dassistance)[correctement restitué](#correctement-restitue-par-les-technologies-dassistance) par les technologies d'assistance
    *   Une [alternative](#alternative--script) accessible permet d'accéder aux mêmes fonctionnalités.

**Note technique :** [Consulter la note technique au sujet des alternatives à JavaScript](#alternative--javascript-et-compatibilit-avec-les-technologies-dassistance-des-composants-dinterface)

**Correspondances WCAG 2.0**

Critère(s) de succès WCAG 2.0 : [4.1.2](http://www.w3.org/Translations/WCAG20-fr/#ensure-compat-rsv)

Technique(s) suffisante(s) et/ou échec(s) WCAG 2.0 : [G10](http://www.w3.org/TR/WCAG-TECHS/G10.html) - [G135](http://www.w3.org/TR/WCAG-TECHS/G135.html) - [G136](http://www.w3.org/TR/WCAG-TECHS/G136.html) - [ARIA4](http://www.w3.org/TR/WCAG-TECHS/ARIA4.html) - [ARIA5](http://www.w3.org/TR/WCAG-TECHS/ARIA5.html) - [ARIA18](http://www.w3.org/TR/WCAG-TECHS/ARIA18.html) - [ARIA19](http://www.w3.org/TR/WCAG-TECHS/ARIA19.html) - [SCR21](http://www.w3.org/TR/WCAG-TECHS/SCR21.html) - [F15](http://www.w3.org/TR/WCAG-TECHS/F15.html) - [F19](http://www.w3.org/TR/WCAG-TECHS/F19.html) - [F42](http://www.w3.org/TR/WCAG20-TECHS/F42.html) - [F59](http://www.w3.org/TR/WCAG20-TECHS/F59.html) - [F79](http://www.w3.org/TR/WCAG20-TECHS/F79.html) - [F20](http://www.w3.org/TR/WCAG-TECHS/F20.html)
