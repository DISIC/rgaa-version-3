Un motif de conception (<span lang="en">Design Pattern</span>) est un modèle défini par l'API WAI-ARIA qui décrit la structure, les rôles et propriétés et le comportement que doit respecter un composant JavaScript (<span lang="en">widget</span>).

Les motifs de conception sont décrits dans le document : [WAI-ARIA 1.0 Authoring Practices](http://www.w3.org/TR/wai-aria-practices/).

Un composant développé avec JavaScript doit respecter le motif de conception correspondant au rôle WAI-ARIA utilisé.

**Note 1:** compte tenu du manque de support de certaines propriétés et de certains rôles WAI-ARIA et de la grande variabilité des situations dans lesquelles un composant JavaScript peut être proposé, il est possible d'adapter des motifs de conception à des contextes ou des utilisations particulières. Dans ce cas, le motif de conception adapté doit :

*   respecter la structure générale, par exemple un ensemble de panneaux (rôle `tabpanel`) d'un système d'onglets est forcément lié à un ensemble d'onglets (rôle `tablist`) ;
*   utiliser en remplacement d'un role ou d'une propriété WAI-ARIA mal supporté, un rôle ou une propriété WAI-ARIA équivalent, offrant un comportement et une restitution similaire.

**Note 2:** Cela ne concerne pas le fait d'enrichir un motif de conception de rôles ou propriétés WAI-ARIA supplémentaires dont la compatibilité avec l'accessibilité est contrôlée par le test de restitution sur la base de référence. Par exemple l'ajout de la propriété `aria-hidden` sur les panneaux (rôle `tabpanel`) d'un système d'onglets ne définit pas un motif de conception adapté.
