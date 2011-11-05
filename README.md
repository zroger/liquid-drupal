# Liquid Theme Engine for Drupal

A new theme engine for Drupal 7 based on [Liquid Markup](http://liquidmarkup.org).

# Why create a new theme engine?

Drupal theming is getting more and more complex, especially with the introduction
of render arrays in Drupal 7.  This is an experiment to see how simple theming 
in Drupal 7 can be, especially for experience front-end developers (HTML/CSS/JS)
who are probably familiar with templated systems, but not necessarily Drupal.

Also, by having a non-executable templates, it becomes more feasible to allow
templates to be editable in the administrative interface.

# About Liquid

Liquid is a simple markup language that provides basic conditionals, looping and
variable formatting.  It is extensible, giving developers the opportunity to 
provide additional tags and filters. 

Liquid was first created for use with Ruby, but has since been ported to many
different languages.  Shopify, the project Liquid was originally built for, has
very good documentation for Liquid.

* [Liquid Markup](http://liquidmarkup.org/)
* [Liquid Documentation](https://github.com/Shopify/liquid/wiki)
* [php-liquid](https://github.com/harrydeluxe/php-liquid)

# Usage

```
cd sites/all/themes
mkdir engines
cd engines
git clone --recursive https://github.com/zroger/liquid-drupal.git liquid
```
