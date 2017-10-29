# Bootstrap Grid
A page just to show how Twitter's bootstrap handles ```.rows``` ```.columns``` ```.container```

## A Little About Bootstrap
Build responsive, mobile-first projects on the web with the world's most popular front-end component library.

Bootstrap is an open source toolkit for developing with HTML, CSS, and JS. Quickly prototype your ideas or build your entire app with our Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful plugins built on jQuery. 

*I copy pasted this from their site*

## Using Bootstrap 4
So how do you use the world's most popular framework?

Easy. Go [here.](https://getbootstrap.com/docs/4.0/getting-started/introduction/)

### ...and for the extra lazy


1. Copy-paste the stylesheet <link> into your <head> before all other stylesheets to load the CSS which does all of the fancy styling for BootStrap.

```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/css/bootstrap.min.css" integrity="sha384-PsH8R72JQ3SOdhVi3uxftmaW6Vc51MKb0q5P2rRUpPvrszuE4W1povHYgTpBfshb" crossorigin="anonymous">
```

*That's a whole lotta mumbo jumbo.* 
Well when using a Content Delivery Network (CDN) for stylesheets, and scripts, you can imagine that modern and "secure" browsers don't want to just receive random files/code from random servers when loading your website. 

That is just sus. 

So they have secure hashes to help identify that this is the original file that Bootstrap team made without any funny business. Don't like that, well you could always [download the files](https://getbootstrap.com/docs/4.0/getting-started/download/) and load them directly from your site.

2. Lots of the compoonents on Bootstrap need some JavaScript. If you want fancy media queries, modals, and other funcionality you are going to need three more scripts.

```
<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.3/umd/popper.min.js" integrity="sha384-vFJXuSJphROIrBnz7yo7oB41mKfc8JzQZiCq4NCceLEaO4IHwicKwpJf9c9IpFgh" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/js/bootstrap.min.js" integrity="sha384-alpBpkh1PFOepccYVYDB4do5UnbKysX5WZXm3XxPqe5iKTfUKjNkCk9SaVuEZflJ" crossorigin="anonymous"></script>
```

### Oh look...Bootstrap tells us which components need JavaScript

 - Alerts for dismissing
 - Buttons for toggling states and checkbox/radio functionality
 - Carousel for all slide behaviors, controls, and indicators
 - Collapse for toggling visibility of content
 - Dropdowns for displaying and positioning (also requires Popper.js)
 - Modals for displaying, positioning, and scroll behavior
 - Navbar for extending our Collapse plugin to implement responsive behavior
 - Tooltips and popovers for displaying and positioning (also requires Popper.js)
 - Scrollspy for scroll behavior and navigation updates

## Suhhhweeet... now what
Well those nice guys at Bootstrap already give you your HTML structure. So start your project with this code:

```
<!doctype html>
<html lang="en">
  <head>
    <title>Hello, world!</title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/css/bootstrap.min.css" integrity="sha384-PsH8R72JQ3SOdhVi3uxftmaW6Vc51MKb0q5P2rRUpPvrszuE4W1povHYgTpBfshb" crossorigin="anonymous">
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.3/umd/popper.min.js" integrity="sha384-vFJXuSJphROIrBnz7yo7oB41mKfc8JzQZiCq4NCceLEaO4IHwicKwpJf9c9IpFgh" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/js/bootstrap.min.js" integrity="sha384-alpBpkh1PFOepccYVYDB4do5UnbKysX5WZXm3XxPqe5iKTfUKjNkCk9SaVuEZflJ" crossorigin="anonymous"></script>
  </body>
</html>
```

### normalize.css / reset.css / reboot.css

Use one of those please


### Markdown notes

A good resource on how to write a nicely formatted readme.md [here](https://blog.ghost.org/markdown/)



