## Rattan CSS Framework

This is Rattan CSS, a simple CSS framework inspired by Blueprint and other CSS frameworks but minus the fat. 

## Features

* A stylesheet for printing
* Browser CSS reset
* Notice, error and message styles
* Growing support for common form elements including those used in Django, django-uni-form and Drupal
* No bloat
* Tested in Firefox, Safari, Google Chrome, IE8, IE6
* The maximum layout width (which you can easily override), is 980px, instead of the common 960px to maximize the use of horizontal real estate

## Features left out deliberately

* Grid system - these things shouldn't be difficult to do in the first place - but there are CSS definitions for #primary and #secondary.
* Typographic baseline. Not worth the hassle in my opinion.

## Setup Instructions

Include your code in your HTML head section like this:

    <!-- Rattan CSS -->
    <link type="text/css" rel="stylesheet" media="all" href="/css/rattan/rt.a.css" />
    <link type="text/css" rel="stylesheet" media="print" href="/css/rattan/rt.p.css" />
    <link type="text/css" rel="stylesheet" media="screen" href="/css/rattan/rt.s.css" />

For everything else, look at the example (index.html) and figure it out :)

## What's with the name?

Rattan is the name for various species of climbing palms that are **sturdy, light and flexible** and are widely used around the world, especially Southeast Asia, to make furniture._

## Bugs and feature requests

Please submit bugs and feature requests in the "Issues":http://github.com/kriskhaira/rattan/issues section.