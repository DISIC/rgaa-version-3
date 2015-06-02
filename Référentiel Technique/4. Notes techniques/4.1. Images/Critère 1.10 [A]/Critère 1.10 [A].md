L'implémentation d'un `role="group"` sur l'élément parent `figure` est destiné à pallier le manque de support actuel des éléments `figure` par les technologies d'assistance. Bien que recommandée, l'utilisation d'un élément `figcaption` dans un élément `figure` est optionnelle. En revanche l'utilisation d'un élément `figcaption` pour associer une légende à une image impose l'utilisation d'un élément parent `figure`. La référence à la légende adjacente peut être une expression du type "image 1" ou équivalent lorsque cette expression est reprise dans la légende.

Bien que recommandé par HTML5, la note WCAG stipule que le `title` ne peut pas être utilisé pour "labelliser" l'image.

Les attributs `aria-labelledby` et `aria-describedby` ne peuvent pas être utilisés actuellement par manque de support par les technologies d'assistance.
