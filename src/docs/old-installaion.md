# installation on an existing environment

## Introduction

if you already have a website and would like to add our theme to it, this is a two-part process: first, install the theme; second, install the modules (it's important to respect this order).
NB: you must first ensure that your environment is up to date by following your Drupal 9 or 10 distribution.

## Process

The modules you need are in "public/web/modules/custom/", transfer their contents to your environment in the "modules/custom/" folder. The themes you need are in "public/web/themes/custom/", transfer their contents to your environment in the "themes/custom/" folder. To install the theme, go to structure > appearance, then install the theme: "opendata" (it will install its dependencies automatically). (You'll need an illustrative image). To install modules, go to structure > extends, then install the "bestlayouts" module, which will automatically select all the modules it needs to function.
