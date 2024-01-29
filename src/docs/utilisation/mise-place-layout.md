<p class="alert alert-info"><i> Ce partie est resevé à ceux qui souhaite aller un peu plus loin sur drupal, ce necesite d'avoir un peu de base sur l'eco-system Drupal, ( entité, node, taxonomies ...) </i></p>
# Mise en place d'un layout.

On peut crrer un layout pour tout entité drupal. Certaines entites peuvent necessiter un peu plus d'effort pour y parvenir, mais les entites les plus utilisé sont deja pre-configurer.( utilisateur, articles, pages, taxonomies, blocks personnalisés ).

## Processus

La creation d'un layout se fait en 4 phases :

<ol>
  <li> identication de l'entité à utiliser </li>
  <li> Ajout du contenu </li>
  <li> Configuration du layout </li>
  <li> Affichage de notre layout </li>
</ol>

## identication de l'entité à utiliser

En fonction de vos besoins vous devez pouvoir determiner quel est l'entité qui est adapté à votre situation. si vous souhaitez configuer la page de l'utilisateur alors l'entité user est adpaté, ou si vous souhaitez ajoute une section sur certaine page, dans ce cas block personnalisé est plus approprie.

## Ajout du contenu

Pour l'ajout de contenu cela est deja bien traiter par l'equipe de Drupal, [gestion des nodes](https://www.drupal.org/docs/core-modules-and-themes/core-modules/node-module), [gestion des blocks pernalisées](https://www.drupal.org/docs/8/core/modules/block-content), [gestion des taxonomies](https://www.drupal.org/docs/8/core/modules/taxonomy).

## Configuration du layout

La configuration du layout se fait dans l'onglet "gestion de l'affichage" :

<figure class="figure">
  <img src="../../assets/images/Manage-display-Events.png" class="figure-img img-fluid rounded" alt="...">
  <figcaption class="figure-caption"> page de configuration du layout </figcaption>
</figure>

Cocher le champs "Use Layout Builder" et vous obtiendrez la capture ci-dessous :

<figure class="figure">
  <img src="../../assets/images/Manage-display-Events-1.png" class="figure-img img-fluid rounded" alt="...">
  <figcaption class="figure-caption"> page de configuration du layout </figcaption>
</figure>

Ensuite cliquez sur "Manage layout" :

<figure class="figure">
  <img src="../../assets/images/Edit-layout-for-Article-content-items-Events.png" class="figure-img img-fluid rounded" alt="...">
  <figcaption class="figure-caption"> page de configuration du layout </figcaption>
</figure>
Nous vous conseillons de decocher "Show content preview".
<figure class="figure">
  <img src="../../assets/images/Edit-layout-for-Article-content-items-Events-3.png" class="figure-img img-fluid rounded" alt="...">
  <figcaption class="figure-caption"> Presentation de la page de configuration du layout </figcaption>
</figure>

### Explication

<ol>
  <li> Permet d'afficher le contenu ou les champs, (de preference decochez le).</li>
  <li> Permet d'effectuer la sauvegarde </li>
  <li> Permet de supprimer le layout </li>
  <li> Permet d'afficher le formulaire de configuration du layout. </li>
  <li> Ce sont les champs de votre entité </li>
  <li> Permet d'ajouter un autre layout au dessus de celui encours. </li>
  <li> Permet d'ajouter un champs provenant de votre entité ou d'une autre ressource. </li>
  <li> Permet d'ajouter un autre layout au dessous de celui encours. </li>
</ol>

De maniere generale vous devez supprimer le layout par defaut et choisir un model qui soit plus adapté. Cliquer sur la croix (fleche 3), confirmé la suppression.
Puis cliquer, sur "add section" :

<figure class="figure" >
  <img src="../../assets/images/Edit-layout-for-Article-content-items-Events-4.png" class="figure-img img-fluid rounded" alt="...">
  <figcaption class="figure-caption"> Presentation de la page de configuration du layout </figcaption>
</figure>
Vous selectionnez le layout qui vous interesses et ensuite cliquez sur "Add section"
<figure class="figure" >
  <img src="../../assets/images/Edit-layout-for-Basic-block-custom-blocks-Events-5.png" class="figure-img img-fluid rounded" alt="...">
  <figcaption class="figure-caption"> Presentation de la page de configuration du layout </figcaption>
</figure>

## Affichage de notre layout

L'affichage d'un layout depend principalement de la structure de l'entité. Pour des entités qui possedent des routes pour le rendu (nodes), vous pouvez directement visualiser le resultat à travers un contenu. Pour des entités ne possedant pas de route de rendu (bloc personnalisé) vous devez passer par "block layout" afin de selectionner le bloc et choisir une region ou l'afficher.
