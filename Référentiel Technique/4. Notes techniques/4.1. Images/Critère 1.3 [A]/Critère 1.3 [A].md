La note WCAG interdit l'utilisation de l'attribut `title` en remplacement de l'attribut `alt`, néanmoins il est souvent utile d'utiliser l'attribut `title` pour faire apparaître une infobulle (<span lang="en">tooltip</span>) sur les images particulièrement obscures. Si l'attribut `title` est utilisé de cette manière, le contenu de l'attribut `title` doit être strictement identique à celui de l'alternative.

Le manque de support de l'élément `<title>` par les technologies d'assistance crée une difficulté dans le cas de l'utilisation de l'élément `<desc>` pour implémenter l'alternative courte de l'image si l'image nécessite une description détaillée. Dans ce cas il est recommandé d'utiliser un texte adjacent ou un lien adjacent pour créer la description détaillée.

Les tests 1.3.7 et 1.3.9 sont utilisés pour vérifier que l'implémentation de l'alternative est compatible avec l'accessibilité (e.g avec la [base de référence](#5 base de rfrence) considérée).
