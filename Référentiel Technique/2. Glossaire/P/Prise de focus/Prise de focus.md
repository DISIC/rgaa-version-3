La prise de focus est l'état renvoyé par un élément qui reçoit l'attention suite à une action de l'utilisateur. Il y a trois moyens en HTML de donner le focus à un élément :

*   en activant l'élément par un dispositif de pointage (souris) ;
*   en activant l'élément par la touche tabulation ;
*   en activant l'élément par un raccourci clavier (`accesskey`).

Certains éléments reçoivent naturellement le focus, par exemple : `a`, `area`, `button`, `input`, `object`, `select`, `label`, `legend`, `optgroup`, `option` et `textarea`. Le comportement de l'élément, lors de la prise de focus, dépend de sa nature ; un lien, par exemple, devra être activé après la prise de focus (sauf utilisation de script). En revanche, un élément de formulaire, comme `textarea`, devra autoriser la saisie suite à la prise de focus. Les éléments `label` et `legend` ne reçoivent la prise de focus que via le pointeur souris. Pour l'élément `label`, le comportement attendu est de transférer la prise de focus sur l'élément qui lui est associé.

**Note 1** : la spécification WAI-ARIA étend le rôle attribué à l'attribut `tabindex` en définissant que tout élément html peut acquérir la possibilité de recevoir le focus en lui attribuant la valeur `tabindex="0"`. En revanche, aucun comportement n'est attribué via la seule présence de `tabindex`. De même, la valeur `tabindex="-1"` retire l'élément qui en est affecté du plan de tabulation en inhibant sa capacité à signaler la "prise de focus". L'utilisation de `tabindex`, conformément à la spécification WAI-ARIA, peut valider certains tests relatifs à la gestion du focus de tabulation, notamment.

**Note 2** : l'indication visuelle du focus ne doit pas être dégradée, c'est à dire amoindrie au moyen de valeurs qui en dégrade le style par rapport à son style par défaut.
