Uniquement à des fins de présentation : utilisation de balises HTML pour une finalité différente de celle prévue dans les spécifications (au regard du type de document déclaré). Exemples : utilisation des balises `h` à seule fin de créer un effet typographique ; utilisation de la balise `blockquote` à seule fin de mettre un paragraphe en retrait, etc.

**Note 1** : l'utilisation d'éléments `div` ou `span` pour créer des paragraphes est considérée comme non conforme et invalide le critère.

**Note 2** : WAI-ARIA propose un rôle `presentation` permettant de supprimer la sémantique d'un élément, par exemple `<h1 role="presentation"> Titre</h1>`. Dans ce cas, le texte sera correctement restitué mais le titre lui ne le sera plus (l'élément restitué sera un élément indéterminé du type `<>Titre</>`.L'utilisation du rôle `presentation` peut être requise lorsqu'on utilise un motif de conception ARIA.

L'utilisation du rôle `presentation` peut être également utilisé pour supprimer la sémantique d'un élément lorsque ce dernier est utilisé uniquement à des fins de présentation, par exemple `<blokquote role="presentation">` aura le même effet qu'une absence d'élément `blockquote`.

Même si cette utilisation est fortement déconseillée (dans le cas de technologie d'assistance qui n'implémenteraient pas ARIA par exemple) elle peut être considérée conforme à WCAG. En revanche l'utilisation d'un rôle `presentation` sur un élément dont la nature (e.g la sémantique) est essentielle à la compréhension du contenu est une violation des règles WCAG (particulièrement de l'échec F92) et invalide le critère.
