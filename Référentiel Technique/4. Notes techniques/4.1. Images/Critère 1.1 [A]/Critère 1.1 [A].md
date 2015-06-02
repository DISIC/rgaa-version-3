À l'exception de `svg`, les attributs `aria-label` et `aria-labelledby` permettant de créer une alternative ou de lier l'image à un passage de texte faisant office d'alternative ne peuvent pas être utilisés par manque de support des technologies d'assistance.

La spécification SVG préconise d'utiliser un élément `<title>` pour la description "courte" et un élément `<desc>` pour la description longue. Actuellement, seul l'élément `<desc>` est correctement restitué par les technologies d'assistance. L'usage de l'élément `<title>` est donc considéré comme incompatible avec l'accessibilité.
