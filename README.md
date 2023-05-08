# High Desert theme for Drupal 10

An experiment with Drupal 10 theming.

Created using [Starterkit](https://www.drupal.org/docs/core-modules-and-themes/core-themes/starterkit-theme).

![Screenshot from 2023-05-08 09-31-52](https://user-images.githubusercontent.com/87952/236879208-0c5997b1-343b-4b87-8c2a-54285bcdad1c.png)

## Requirements

* [Node.js](https://nodejs.org/)

## Quick set up

`npm install`

## Editing and Compiling Sass

This theme makes use of [Sass](https://sass-lang.com/), which means CSS files
are not edited directly, but compiled from the files in the /sass directory.

To compile CSS files once:

`npm run sass:build`

To watch for changes to SCSS files and compile as you edit:

`npm run sass:watch`

To check for problems with SCSS files:

`npm run sass:lint`
