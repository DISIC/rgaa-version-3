Les rôles WAI-ARIA `list` et `listitem` peuvent nécessiter l'utilisation des propriétés `aria-setsize` et `aria-posinset` dans le cas où l'ensemble de la liste n'est pas disponible via le DOM généré au moment de la consultation.

Bien que possédant un rôle `definition`, utilisé en combinaison avec la propriété `aria-labelledby`, WAI-ARIA ne propose pas de rôle équivalent à une liste de définition HTML. Le rôle `definition` ne peut donc pas être utilisée comme équivalent à une liste de définition HTML `dl`.

Les rôles `tree`, `tablist`, `menu`, `combobox` et `listbox` ne sont pas équivalents à une liste HTML `ul` ou `ol`.

Références : [The Role Model, List Role](http://www.w3.org/WAI/PF/aria/roles#list) et [The role model - ARIA SETSIZE](http://www.w3.org/WAI/PF/aria/states_and_properties#aria-setsize)
