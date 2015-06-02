Le manque de support de l'élément `<title>` par les technologies d'assistance crée une difficulté dans le cas de l'utilisation de l'élément `<desc>` pour implémenter l'alternative courte de l'image si l'image nécessite une description détaillée. Dans ce cas il est recommandé d'utiliser un texte adjacent ou un lien adjacent pour créer la description détaillée.

Si l'élément `<desc>` est utilisé pour implémenter la description détaillée, il est recommandé d'utiliser un attribut `aria-label` pour implémenter l'alternative courte de l'image.

L'utilisation de l'attribut `aria-describedby` n'est pas possible pour lier une image à sa description détaillée par manque de support des technologies d'assistance.

La description détaillée adjacente peut être implémentée via un élément `<figcaption>`, dans ce cas le critère 1.10 doit être vérifié (utilisation de `<figure>` et du rôle `group`, notamment).
