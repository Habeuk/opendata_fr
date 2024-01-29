# installation

### pre-requis

Pour l'environnement de Drupal, [voir la configuration recommandée](https://www.drupal.org/docs/understanding-drupal/how-drupal-9-was-made-and-what-is-included/environment-requirements-of-drupal-9).
Nous vous conseillons egalement d'utiliser composer pour gerer le telechargement des fichiers (coeur, modules et themes) et les mises à jour.

## Introduction

Nous verrons dans cette partie comment installer le site web à partir de zero.

## Processus

Les données de base pour l'installation sont dans le fichier public/public.zip, copier le contenu et dézipper le dans votre dossier racine de votre hebergement. (En regle general, il s'agit du dossier public_html, mais si vous avez des doutes reseigner vous aupres de votre hebergeur).
Ensuite, ouvrir un navigateur, saisir le nom de domaine par example http://architecte-sao.com.

La page d'installation du site se charge et vous etez appellé à selectionner la Langue.

<figure class="figure">
  <img src="../assets/images/Choose-language-HABEUK-template-by-habeuk-com.png" class="figure-img img-fluid rounded" alt="...">
  <figcaption class="figure-caption"> Chose language </figcaption>
</figure>
Etape suivante, vous devez configurer la base de données :
<figure class="figure">
  <img src="../assets/images/Database-configuration-HABEUK-template-by-habeuk-com.png" class="figure-img img-fluid rounded" alt="...">
  <figcaption class="figure-caption"> Paramettre de connexion à la base de données </figcaption>
</figure>
Etape suivante, L'instation des modules, cette etape se fait de maniere automatique :
<figure class="figure">
  <img src="../assets/images/Installing-HABEUK-template-by-habeuk-com-HABEUK-template-by-habeuk-com.png" class="figure-img img-fluid rounded" alt="...">
  <figcaption class="figure-caption"> Installation de modules. </figcaption>
</figure>
Et la derniere etape, vous devez configurer les informations concernant votre site :
<figure class="figure">
  <img src="../assets/images/Installing-HABEUK-template-by-habeuk-com-HABEUK-template-by-habeuk-com.png" class="figure-img img-fluid rounded" alt="...">
  <figcaption class="figure-caption"> Configuration de base du site. </figcaption>
</figure>

et voilà votre site web est pres et ne reste plus qu'à mettre à jour son contenu en function de vos données.
Si vous souhaitez en savoir plus sur l'instalation de drupal, nous vous conseillons la [documentation officiel](https://www.drupal.org/docs/getting-started/installing-drupal).
