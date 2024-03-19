# installation on an existing environment


## Introduction

If you already have a website and would like to add our theme to it, you need to install the theme and then the modules in two parts (it is important to respect this order).
<br>
NB: you must first make sure that your environment is up to date by following your Drupal 9 or 10 distribution.
## Process
The modules you need are in "opendata/old-installation/modules/custom/", transfer its contents to your environment in the "modules/custom/" folder. The themes are in "opendata/old-installation/themes/custom/", transfer their contents to your environment in the "themes/custom/" folder.
To install the theme, go to "structure > appearance", then install the theme: "opendata" (it will install its dependencies automatically). (You'll need an illustrative image).
To install the modules, go to "structure > extends", then install the "bestlayouts" module. It will automatically select all the modules it needs to work. 
