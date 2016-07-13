# [Material Kit - Free Bootstrap UI Kit](http://demos.creative-tim.com/material-kit/index.html)

![alt text](http://s3.amazonaws.com/creativetim_bucket/products/38/original/opt_mk_thumbnail.jpg "Material Kit Free")

Material Kit is a Free Bootstrap UI Kit with a fresh, new design inspired by Google's material design. You asked for it, so we built it. It's a great pleasure to introduce to you the material concepts in an easy to use and beautiful set of components. Along with the restyling of the Bootstrap elements, you will find three fully-coded example pages, to help you design your next project.

Material Kit makes use of light, surface and movement. It uses a deliberate color choice, edge-to-edge imagery and large scale typography. The general layout resembles sheets of paper following multiple different layers, so that the depth and order is obvious. The navigation stays mainly on the left and the actions on the right.

This new design has elements that have been the result of research regarding ink and paper and the way objects and materials interact in real life. The result is a beautiful and consistent set of elements that can get you started with your next project. Material Kit is a great tool if you are looking to create a web presence for your Android application and need to be consistent, leaving the impression of visually similar elements. It is also a great resource in its own right, looking gorgeous and helping you build your web pages.

Material Kit is based on the Github Repo from Fez (http://fezvrasta.github.io/bootstrap-material-design/) who did an amazing job creating the backbone for the material effects, animations and transitions. Big thanks to his team for their forward thinking efforts.

## Links:

+ [Live Preview](http://demos.creative-tim.com/material-kit/index.html)
+ [Material Kit PRO](http://demos.creative-tim.com/material-kit-pro/presentation.html) (from $79)

## Quick start

Quick start options:

- [Download from Github](https://github.com/timcreative/material-kit/releases/tag/v1.1.0).
- [Download from Creative Tim](http://www.creative-tim.com/product/material-kit).
- Clone the repo: `git clone https://github.com/timcreative/material-kit.git`.


### What's included

Within the download you'll find the following directories and files:

```
x_mk/
├── assets/
|   ├── css/
|   |   ├── bootstrap.min.css
|   |   ├── material-kit.css
|   |   └── demo.css
|   ├── js/
|   |   ├── bootstrap-datepicker.js
|   |   ├── bootstrap.min.js
|   |   ├── jquery.min.js
|   |   ├── material-kit.js
|   |   ├── material.min.js
|   |   └── nouislider.min.js
|   ├── sass/
|   |    ├── material-kit
|   |    └── material-kit.scss
|   └── img/
|
├── changelog.txt
├── examples/
├── components-documentation.html
├── Creative Tim License.pdf
├── index.html
├── template.html
└── tutorial.html

```

### Version logs

V1.0 - 15 March 2016 initial release

- V1.0.1, 21 June 2016 - Bugfixing
 - fixed sidebar in documentation
 - fixed checkboxes and radios on Firefox
 - fixed Dropdown in Navbars for mobile
 - fixed broken link in documentation

IMPORTANT! Before upgrading from V1.0/V1.0.1 to V1.1.0, please read all the change long and then follow the instructions for the upgrade.

- V1.1.0, 11 July 2016 - Minor Updates and Bug Fixes
 - Added colored shadows under the Buttons, Pagination & Nav Pills
 - Removed ".btn-raised" class and made the raised button default (too many persons are using the .btn-raised as the default state so let's keep it simple and with less classes). Find more details in on the Upgrading Info below.
 - Added ".btn-simple" class instead of the default link like buttons. Find more details in on the Upgrading Info below.
 - Added a new color for buttons: White, you can use it with ".btn-white"
 - Change the structure of \_buttons.scss and made it more easy to be customized
 - Added subtile animation on Tooltips
 - Removed Glyphicons from bootstrap.min.css
 - Update Bootstrap to v3.3.6
 - Change structure of the "Feature with Icon and Title" to "Info Area with Icon and Title" to keep classes consistency with the PRO version. Find more details in on the Upgrading Info below.
 - Update Font Awesome to the latest Version
 - Added animations and transitions vendor prefixes for old browsers on Checkboxes and Radios

UPGRADING V1.0/V1.0.1 to V1.1.0

1. Buttons:
Please remove all the "btn-raised" classes from all the buttons. Now all the buttons have the "Raised" style on the default state. If you want to use the buttons without that style, like the old "Default" state from the V1.0 please add the class "btn-simple" to those buttons.

2. Features Area:
Please change the all structure:

<div class="feature feature-primary">
    <i class="material-icons">chat</i>
    <h4 class="title">First Feature</h4>
    <p class="description">Divide details about your product or agency work into parts. Write a few lines about each one. A paragraph describing a feature will be enough.</p>
</div>

with the new one:

<div class="info">
    <div class="icon icon-primary">
        <i class="material-icons">chat</i>
    </div>
    <h4 class="info-title">First Feature</h4>
    <p>Divide details about your product or agency work into parts. Write a few lines about each one. A paragraph describing a feature will be enough.</p>
</div>



## Useful Links

More products from Creative Tim: <http://www.creative-tim.com/products>

Tutorials: <https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w>

Freebies: <http://www.creative-tim.com/products>

Affiliate Program (earn money): <http://www.creative-tim.com/affiliates/new>

Social Media:

Twitter: <https://twitter.com/CreativeTim>

Facebook: <https://www.facebook.com/CreativeTim>

Dribbble: <https://dribbble.com/creativetim>

Google+: <https://plus.google.com/+CreativetimPage>

Instagram: <https://instagram.com/creativetimofficial>
