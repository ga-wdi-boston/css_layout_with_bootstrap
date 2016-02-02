[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# CSS: Layout with Bootstrap

## Prequisites

-   [ga-wdi-boston/html-css-layout](https://github.com/ga-wdi-boston/html-css-layout)
-   [ga-wdi-boston/html-css-sass](https://github.com/ga-wdi-boston/html-css-sass)
-   [ga-wdi-boston/js-template-installation](https://github.com/ga-wdi-boston/js-template-installation)

## Objectives

By the end of this lesson, students should be able to:

-   Install `bootstrap-sass` into a front-end project.
-   Create mobile-first, responsive site layouts using
    [bootstrap](http://getbootstrap.com).
-   Maintain semantic HTML markup using Sass mixins provided by
    `bootstrap-sass`.
-   Reference bootstrap documentation.

## Preparation

1.  [Fork and clone](https://github.com/ga-wdi-boston/meta/wiki/ForkAndClone)
    this repository.
1.  Install dependencies with `npm install`.


## Exercise: Holy Grail Layout

The goal of our exercise is to recreate the "Holy Grail" layout. This
traditional layout is challenging in CSS. It is defined by a set of constraints
that may be difficult to achieve all at once:

1.  A header, a footer, and a main content area.
1.  The main content area is divided into left, right, and center columns.
1.  The left and right columns are "sidebars".
1.  The middle column is for content.
1.  Any column should be the "longest" and display without scrollbars, pushing
    the footer down if necessary.
1.  The center should be "fluid" and resize with the browser window.
1.  Columns should remain a fixed width. If the viewport isn't wide enough, the
    columns should stack below content.
1.  The middle column should appear first in the source, since early content is
    ranked higher in importance by search engines.

We'll start by including bootstrap and creating our three columns. Then we'll
proceed by adding a navbar and a footer. Lastly, we'll experiment to see how
many of the constraints we can meet using built-in bootstrap styling classes.

## Bonus

For an extra challenge, make the header and footer sticky, even when the content
doesn't fill the page.

Next, try using JavaScript to have the header and footer hide on `scrolldown`
and display on `scrollup`.

## Additional Resources

-   [In Search of the Holy Grail · An A List Apart Article](http://alistapart.com/article/holygrail)
-   [Solving the Holy Grail Layout | appendTo](http://appendto.com/2014/03/solving-the-holy-grail-layout-2/)
-   [Bootstrap: Template](http://getbootstrap.com/getting-started/#template)
-   [Bootstrap: Examples](http://getbootstrap.com/getting-started/#examples)
-   [Bootstrap: Grid](http://getbootstrap.com/css/#grid)
-   [Bootstrap: CSS](http://getbootstrap.com/css/)
-   [Bootstrap: Components](http://getbootstrap.com/components/)
-   [Bootstrap: JavaScript](http://getbootstrap.com/javascript/)

## [License](LICENSE)

Source code distributed under the MIT license. Text and other assets copyright
General Assembly, Inc., all rights reserved.
