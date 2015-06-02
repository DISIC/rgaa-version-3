indication de la langue de traitement principale du document qui peut être présente sur l'élément racine `html` ou sur chaque élément de la page concerné via les attributs `lang` et/ou `xml:lang` selon le schéma suivant :

*   pour HTML jusqu'à la version 4.01 : attribut `lang` obligatoire, attribut `xml:lang` non supporté
*   pour XHTML 1.0 servi en `"text/html"` : attribut `lang` et `xml:lang` obligatoires
*   pour XHTML 1.0 servi en `"application/xhtml+xml"` : attribut `xml:lang` obligatoire, attribut `lang` recommandé
*   pour XHTML 1.1 : attribut `xml:lang` obligatoire, attribut `lang` non supporté
*   pour HTML5 : attribut `lang` obligatoire
