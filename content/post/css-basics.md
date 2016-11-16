+++
title = "CSS Basics"
description = ""
draft = true
categories = [
  "",
]
tags = [
  "",
  "",
]
date = "2016-11-15T20:24:25+05:30"

+++

### Introduction

CSS forms the basis of styling of web pages. With CSS, you can apply styles to make your web pages more readable and beautiful.

All CSS in a webpage go inside a `<style></style>` tag, unless you are linking CSS from other files. All CSS are composed of CSS rulesets, which are the basic building block of CSS code. They look like this.

{{< codecaption lang="css" title="Code caption shortcode" >}}
div {
    color: blue;
}
{{< /codecaption >}}

The first part `div` is called a selector, and the next part is called a declaration.

#### Types of selectors

{{< highlight css >}}
/* tag selector */
div {
    color: blue;
}
/* class selector */
.book {
    color: blue;
}
/* id selector */
#siteHead {
    color: blue;
}
{{< /highlight >}}

#### Types of CSS Units

Units are used everywhere in CSS to specify length, width, height etc of content and tags. They are basically divided into absolute and relative units.

Absolute units include

* pixels (`px`)

Relative units:

* percentages (`%`)
* `em` which is mostly used for fonts
* `vw` and `vh`

#### Colors in CSS

Colors in CSS can be represented in two ways:

* `rgb(0,0,0)`
* `#000000`

#### Commonly used attributes in CSS

* _color_: Mostly refers to the font color of the element.
* _background_: can be a color or image, and can have different other properties as well.
