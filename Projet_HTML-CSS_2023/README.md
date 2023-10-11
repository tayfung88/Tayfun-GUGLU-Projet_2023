# Tayfun GUGLU - Projet : 

## Menus (*Header* / *Footer*)
Pour débuter ce projet, l'objectif était de placer deux menus, l'un en haut de la page et l'autre en bas de la page. 
J'ai opté pour cette approche afin d'éviter l'utilisation d'un menu "sticky" qui aurait occupé de l'espace et aurait pu gêner la lecture des éléments de la page. 

Pour réaliser cela, j'ai utilisé un **display: flex** avec **justify-content: flex-start** sur le **header nav** pour que mon logo et mon menu s'affichent en haut à gauche de ma page. Le menu s'affiche sur une ligne en format desktop. Des liens ont également été ajoutés sur les éléments du menu pour permettre une navigation efficace sur le site. 

Enfin, un effet de survol **hover** a été ajouté pour améliorer l'expérience utilisateur. Pour le **footer**, j'ai utilisé un **display: flex** avec **flex-direction: column** pour pouvoir placer mon menu et le copyright l'un au-dessus de l'autre.

## Page Index, *Main*
Ensuite, pour la partie **main** de ma page d'introduction, j'ai utilisé un **display: flex** avec **flex-direction: row** pour placer l'introduction du site sur une ligne. 

Pour la section sur les capitales, j'ai utilisé un **display: flex** avec **flex-wrap: nowrap** pour que les éléments reste aligner sur la même lignes. J'ai également utilisé **display: flex** avec **flex-direction: column** pour lister les articles les uns au-dessus des autres (titre, image, descriptions). 

Dans cette partie, j'ai également mis en place des transitions CSS avec la fonction **hover** pour permettre un effet de zoom sur les titres et les images, en abaissant également leur opacité.

## Pages Sites, *Main*
Enfin, pour les pages du site, dans la section d'introduction, j'ai utilisé un **display: flex** avec **flex-direction: row-reverse** pour aligner les éléments dans l'ordre que je souhaitais. 

Pour bien positionner les éléments sur la page, j'ai utilisé **justify-content: space-between** et **align-items: flex-start**. En-dessous, j'ai intégré deux images en utilisant **justify-content: space-evenly** pour présenter la capitale et sa localisation sur la carte. Finalement, j'ai ajouté un carrousel et un tableau centré juste en dessous.

## Responsive, *Media Queries*
Pour la partie responsive, j'ai d'abord adapté la taille des polices en fonction du support utilisé. Ensuite, j'ai modifié la disposition du menu en utilisant **display: flex** avec **flex-direction: column** pour que, au lieu de s'afficher sur une ligne, le menu s'affiche sur plusieurs lignes **(header / footer)** lorsque la largeur de l'écran est de 860px ou moins. 

Pour différents éléments dans la page index ou sur les autres pages, j'ai réadapté leur disposition qui passait d'un affichage côte à côte à un affichage les uns au-dessus des autres, bien centrés sur la page.
