Principe=>Utilisable
Principe=>Compréhensible
Niveau=>A

*   Test 12.10.1 : Dans chaque page Web, chaque groupe de liens importants est-il implémenté dans une balise commune ?
*   Test 12.10.2 : Dans chaque page Web, chaque groupe de liens importants vérifie-t-il une de ces conditions ?
    *   La balise structurant le groupe de liens importants possède un attribut `id`
    *   La balise structurant le groupe de liens importants est immédiatement précédée, dans le code source, d'une `ancre nommée`
    *   La balise lien du groupe est immédiatement précédée, dans le code source, d'une `ancre nommée`
*   Test 12.10.3 : Dans chaque page Web, la zone de contenu vérifie-t-elle une de ces conditions ?
    *   La zone de contenu possède un attribut `id`
    *   La zone de contenu est immédiatement précédée, dans le code source, d'une `ancre nommée`
    *   Le premier élément de la zone de contenu est immédiatement précédé, dans le code source, d'une `ancre nommée`
*   Test 12.10.4 : Dans chaque page Web, la structure du document vérifie-t-elle ces conditions ?
    *   La [zone d'en-tête de la page](#zone-dune-image-ractiveHeader) possède un rôle ARIA `banner`
    *   Le [menu de navigation](#menu-de-navigation) principal possède un rôle ARIA `navigation`
    *   La [zone de contenu principal](#zone-dune-image-ractiveMain) possède un rôle ARIA `main`
    *   La [zone de pied de page](#zone-dune-image-ractiveFooter) possède un rôle ARIA `contentinfo`
    *   Le [moteur de recherche](#moteur-de-recherche-interne--un-site-web) sur le site possède un rôle ARIA `search`
    *   Les rôles ARIA `banner`, `main`, `contentinfo` et `search` sont uniques dans la page.
    *   Le rôle ARIA `navigation` est réservé aux zones de navigations principales et secondaires

**Note technique :** [Consulter la note technique au sujet des role `landmark` et des liens d'évitement.](#critre-1210 a)

**Correspondances WCAG 2.0**

Critère(s) de succès WCAG 2.0 : [1.3.1](http://www.w3.org/Translations/WCAG20-fr/#content-structure-separation-programmatic) - [2.4.1](http://www.w3.org/Translations/WCAG20-fr/#navigation-mechanisms-skip) - [4.1.2](http://www.w3.org/Translations/WCAG20-fr/#ensure-compat-rsv)

Technique(s) suffisante(s) et/ou échec(s) WCAG 2.0 : [G115](http://www.w3.org/TR/WCAG-TECHS/G115.html) - [H50](http://www.w3.org/TR/WCAG-TECHS/H50.html) - [ARIA4](http://www.w3.org/TR/WCAG20-TECHS/ARIA4.html) - [ARIA11](http://www.w3.org/TR/WCAG20-TECHS/ARIA11.html)
