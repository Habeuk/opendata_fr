# installation

### requirements

<p class="alert alert-info"><i> you must first ensure that your environment is up to date by following your Drupal 9 or 10 distrubution.

If you're new to Drupal, please take a look at the system requirements on drupal.org
PHP 8.1 or higher MySQL 5.7.8, or, higher, node 20, npm 10
For the Drupal environment, see the recommended configuration (opens new window). We also recommend using composer to manage file downloads (core, modules and themes) and updates.</i></p>



## Introduction

In this section, we'll look at how to install the website from scratch.

## Process

The installation package consists of the complete Drupal site with theme, various modules, sample content and is excellent for beginners to explore the back-end settings and sample content. Installing the demo theme is just like installing Drupal, but you'll have the full demo website installed on your server.

Localhost installation: Create a new folder in the htdocs folder for Xampp (www folder for Wamp) or on linux simply create a "siteweb" folder at the root of your computer. Unzip all demo theme files and folders into the folder you've just created and open the demo folder.

The basic installation data is in the file public/public.zip, copy the contents and unzip it into your hosting root folder. (Usually, this is the public_html folder or the home folder of your site, but if in doubt, contact your hosting provider). Next, open a browser and enter the domain name, for example http://opendata.com.

We'll then create a database in our database manager (e.g. adminer) and import the database downloaded from public/web/database/opendata.sql.gz.


<figure class="figure">
  <img src="../assets/images/bd.png" class="figure-img img-fluid rounded" alt="...">
  <figcaption class="figure-caption"> database </figcaption>
</figure>

The site installation page loads and you are asked to select the Language.

<figure class="figure">
  <img src="../assets/images/Choose-language-HABEUK-template-by-habeuk-com.png" class="figure-img img-fluid rounded" alt="...">
  <figcaption class="figure-caption"> Chose language </figcaption>
</figure>
The next step is to configure the database:
<figure class="figure">
  <img src="../assets/images/Database-configuration-HABEUK-template-by-habeuk-com.png" class="figure-img img-fluid rounded" alt="...">
  <figcaption class="figure-caption"> Paramettre de connexion à la base de données </figcaption>
</figure>
The next step is to install the modules automatically:
<figure class="figure">
  <img src="../assets/images/Installing-HABEUK-template-by-habeuk-com-HABEUK-template-by-habeuk-com.png" class="figure-img img-fluid rounded" alt="...">
  <figcaption class="figure-caption"> Installation de modules. </figcaption>
</figure>
your installation is complete
<figure class="figure">
  <img src="../assets/images/config_4.png" class="figure-img img-fluid rounded" alt="...">
  <figcaption class="figure-caption"> Configuration de base du site. </figcaption>
</figure>

and all that's left to do is update the content according to your data.
If you'd like to find out more about installing drupal, we recommend the [official documentation](https://www.drupal.org/docs/getting-started/installing-drupal).
