Principe=>Perceptible
Principe=>Utilisable
Principe=>Robuste
Niveau=>A

*   Test 10.13.1 : Dans chaque page Web, chaque [texte caché](#texte-cach) vérifie-t-il une de ces conditions ?
    *   Le texte n'a pas vocation à être restitué par les technologies d'assistance
    *   Le texte est rendu visible sur action de l'utilisateur sur l'élément lui-même ou un élément précédant le [texte caché](#texte-cach)
    *   Le texte caché fait partie d'un composant d'interface piloté par l'API ARIA, prenant en charge l'état affiché ou masqué du contenu.
*   Test 10.13.2 : Dans chaque page Web, chaque [texte caché](#texte-cach) qui utilise une propriété ARIA `aria-hidden` vérifie-t-il une de ces conditions ?
    *   Le texte n'a pas vocation à être restitué par les technologies d'assistance
    *   La valeur de la propriété ARIA `aria-hidden` est cohérente avec l'état visible ou caché du texte
*   Test 10.13.3 : Dans chaque page Web, chaque [texte caché](#texte-cach) qui utilise un attribut `hidden` vérifie-t-il une de ces conditions ?
    *   Le texte n'a pas vocation à être restitué par les technologies d'assistance
    *   Le texte est rendu visible sur action de l'utilisateur sur l'élément lui-même ou un élément précédent le texte caché
    *   Le texte caché fait partie d'un composant d'interface piloté par l'API ARIA, prenant en charge l'état affiché ou masqué du contenu.

**Note technique :** [Consulter la note technique au sujet de la propriété `aria-hidden` et de l'attribut `hidden`](#critre-1013-a)

**Correspondances WCAG 2.0**

Critère(s) de succès WCAG 2.0 : [4.1.2](http://www.w3.org/Translations/WCAG20-fr/#ensure-compat-rsv) - [1.3.2](http://www.w3.org/Translations/WCAG20-fr/#content-structure-separation-sequence)

Technique(s) suffisante(s) et/ou échec(s) WCAG 2.0 : [G57](http://www.w3.org/TR/WCAG20-TECHS/G57.html)
