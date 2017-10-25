# Framework_css
A scss/css framework

Installation (FR) :

Le framework SCSS est composé de 7 fichiers SCSS. Chaque fichiers SCSS definie des parties du framework.
- _Variable.scss (gères les varibles des autres fichiers scss, à utiliser pour écraser les varibles par défault; 
- _Alert.scss (gères les boites d'alert);
- _Button.scss (gères l'apparence et la taille des boutons);
- _Typos.scss (gères la typographie du framework);
- _Nav.scss (gères l'apparence de la barre de navigation);
- _Grid.scss (gères la grille permettant l'affichache propre d'élements);
- _Etc.scss (gères l'apparance des autre élements présents dans le framework);
Les 7 fichiers sont importé dans Framework.scss
L'un d'eux comporte les variables pour modifier directement certaint mixin (variable par default définie directement dans les fichiers en question).

Pour utiliser le framework sous la forme scss, on peut définir des classes dans framework.scss grâce au mixin créés dans les autres fichiers scss.

Pour utiliser le framework sous la forme css, des classes css on déja été définie dans le fichier css/Framework.css.
Ce fichier comporte des classes génerées par défault pour tous les élements créés par des mixins. Il comporte aussi plusieurs grilles, de 12, 16 et 24 colonnes.
