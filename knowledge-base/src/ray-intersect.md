# Déterminer si notre rayon touche notre forme

# Cercle

On reprend l'équation du [cercle](equation-forme-vecteur.md##cercle) vu précédement : $$ (x - a)² + (y - b)² = r² $$
<br><br>
L'idée générale c'est que l'on va plug l'équation du vecteur du [rayon](equation-forme-vecteur.md##rayon), dans l'équation du [cercle](equation-forme-vecteur.md##cercle).
On sépare le calcul par axe. (<b>x</b>,<b>y</b>, et <b>z</b> si on a)
<br><br>
Donc ici : (x - a)² + (y - b)² - r² = 0 ; On va définir le x et le y, avec notre équation du rayon.
<br>

Soit : ( <span style="color:#e05000">(aₓ + bₓ * t)</span> - a)² + ( <span style="color:#001be0">(aᵧ + bᵧ * t)</span> - b)² - r² = 0 (c'est pas les même a, désolé pour la confusion, aₓ != a)
<br><br>
Avec des vrais valeurs cette fois-ci. <br>
<ul>
<li>Notre rayon se situe en position (-3, -3) et se dirige vers (1,1)</li>
<li>L'origine de notre cercle se situe en (1,1)</li>
<li>Le rayon de notre cercle est 2</li>
<li></li>
</ol>
Soit : ( <span style="color:#e05000">(-3 + 1 * t)</span> - 1)² + ( <span style="color:#001be0">(-3 + 1 * t)</span> - 1)² - 4 = 0
<br>
Soit : (Et là je ne sais pas comment on résoud l'équation)
<br>

## Résultat

Si le résultat est <b>> 0</b>, c'est que notre rayon travers notre forme à deux endroit.
S'il est <b>= 0</b>, notre rayon traverse notre forme à un endroit
Sinon, s'il est <b>< 0</b>, notre rayon ne traverse pas notre cercle

## Déterminer la distance

Revoir [cette vidéo youtube](https://www.youtube.com/watch?v=4NshnkzOdI0&list=PLlrATfBNZ98edc5GshdBtREv5asFW3yXl&index=2) à 32:00.
<br>
Comme j'ai pas su résoudre l'équation au début, et qu'il utilise la formule quadratique (?) pour ensuite résoudre la distance, je ne peux pas résoudre la distance.

# Sphere

Pareil que pour le cercle, faut juste rajouter le z.