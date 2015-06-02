Un composant doit avoir un rôle et un nom appropriés, ses valeurs, états et paramètres éventuels doivent également être accessibles et correctement transmis aux APIs d'accessibilité notamment.

Le nom peut être l'intitulé du composant comme l'intitulé d'un bouton par exemple.

La valeur est, par exemple, l'élément sélectionné d'une liste déroulante ou la valeur actuelle d'un curseur (slider).

Le rôle correspond au type d'élément défini par la spécification HTML ou l'API WAI-ARIA (comme la balise `button` ou le rôle ARIA `role="button"`).

Le paramétrage correspond aux informations particulières d'un composant, généralement mis à disposition par l'API WAI-ARIA. Par exemple `aria-controls` est un paramètre qui transmet aux APIs l'information que le composant contrôle tel ou tel contenu (référencé par son identifiant - attribut `id`).

Les changements d'états sont également mis à disposition par l'API WAI-ARIA. Par exemple `aria-expanded` est un état permettant de signaler aux APIs que le composant est "ouvert" ou "fermé". **Note :** un état peut également être transmis via le nom, lorsque l'intitulé est changé dynamiquement pour correspondre à l'état de la zone contrôlée notamment.

Ces paramètres ne sont pas obligatoires mais peuvent être requis s'ils sont indispensables pour rendre le composant accessible. C'est à l'auditeur de considérer les cas où ces paramètres sont indispensables en fonction du contexte lié à l'utilisation du composant.

L'auditeur doit également vérifier que, lorsqu'il sont présents, ces paramètres sont correctement utilisés.

**Note :** les rôles, propriétés et états ARIA s'implémentent via des attributs, par exemple `role="banner"`, `aria-hidden="true"`.
