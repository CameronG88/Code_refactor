# Code_refactor

This file is a code refactor of an already functional website for Horiseon Inc.

## html changes

```py

First thing I did working on this html code is changing the header title from"website" to "Horiseon SSS Inc." to be more descriptive.

Changed the 'div' class:header body into a simpler 'header'

Changed the navigation bar 'div' into a 'nav'

Added 'alt' to all images

Changed the 'div' class:content into a 'main'

changed all 'div' inside that to 'article' tags

Gave all articles in main the class:contentarticle and replaced all other article classes with the same

Changed search-engine-optimization's class tag into an id tag to function with the nav bar

changed the 'div' class:benefit tag into an 'aside'

Changed all 'div' within the aside to 'article' tags

Removed 3 seperate classes from the articles within the aside and replaced them with the single class benefit

Replaced the 'div' class:footer with a footer tag
```

## css changes

```py

Removed the class identifier from css targetting the class:header to match html

Replaced 'div' with 'nav' for navigation bar css to match html

Changed class:hero into 'figure' to match...you know what

Changed class:content to 'main'

Changed class:benefits to 'aside'

Combined 3 class:benefit-xxxx classes into one class:benefit

Combined all previously split css for those 3 classes into one combined code for the new class:benefit

Combined css code for the main sections old 3 classes into the class:contentarticle

Did the same for those old 3 classes 'img' and 'h2' css

Removed the class tag from footer code
```