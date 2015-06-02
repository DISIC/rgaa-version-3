Dans un formulaire, ensemble des champs pouvant être regroupés par la nature des informations attendues. Le regroupement vise à identifier les champs devant être traités comme un ensemble.

Quelques exemples :

*   trois champs successifs pour saisir une date (jour/mois/année) ;
*   champs successifs pour un numéro de téléphone ;
*   un bloc destiné à saisir l'identité et l'adresse de l'utilisateur, lorsque le formulaire contient plusieurs blocs de contact ;
*   un ensemble de boutons radio ou de cases à cocher qui se rapportent à une question.

Ces champs doivent être regroupés par une balise `fieldset` accompagnée d'une balise `legend` pertinente. Dans le cas de boutons radio, la légende est généralement l'intitulé de la question.

**Note** : lorsque le formulaire est uniquement constitué d'un seul bloc d'informations de même nature (l'identité et l'adresse de l'utilisateur, par exemple) ou d'un champ unique (un moteur de recherche, par exemple), la présence de l'élément `fieldset` n'est pas obligatoire.
