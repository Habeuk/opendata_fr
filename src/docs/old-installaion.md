# installation sur un environnement existant

## Introduction

vous disposez deja d'un site web vous souhaitez y ajouter notre theme, cela fait en deux partie l'installation du theme et afin l'installation des modules. (il est important de respecter cette ordre)
<br>
NB: vous devez au prealable vous rassurer que votre environnement est à jour en suivant votre distrubution Drupal 9 ou 10.

## Processus

Les modules donc vous avez besoin sont dans "old-installation/modules/custom/", transferez son contenu sur votre environnement dans le dossier "modules/custom/". Pour les themes, ils sont dans "old-installation/themes/custom", transferez son contenu vers votre environnement dans le dossier "themes/custom/".<br>
Pour l'installation du theme, dirigez vous sur structure > apparence, ensuite installé le theme : "habeukevent" (il installera ses dependances de maniere automatique).
( il faut une image illustrative).<br>
Pour l'installation des modules, diriger vous sur structure > extends, ensuite installé le module "bestlayouts", il selectionnera automatiquement tous les modules donc il a besoin pour functionner.
( il faut deux images qui illustre cela ).
<br>

### Generer votre theme

Vous devez generer votre theme. Cela vous permet de definir les couleurs, taille de polices et bien d'autre.
allez sur structure > Creation/MAJ du styles des themes, ensuite cliquez sur " + Add Config theme entity ":

<figure class="figure">
  <img src="../assets/images/Add-config-theme-entity-Events.png" class="figure-img img-fluid rounded" alt="...">
  <figcaption class="figure-caption"> Generation de votre theme </figcaption>
</figure>
( L'utilisateur doit avoi la possibilité de generer un theme ou pas en function de son env, on doit fournir un theme generer ).<br>
( il ya aussi des petits bug lors de la creation d'un model de theme ). <br>
( il faudra egalement installer wbu-atomique dans librarie ). <br>
( il faudra ajouter un module de transliteration des fichiers dans le coeur ). <br>
( l'accordeon doit etre par defaut sur dynamique content ) <br>
Une foix cela effectué, VOUS DEVEZ ABSOLUMENT configurer votre site. Voir la section sur <strong>Gestion du contenu</strong>.
