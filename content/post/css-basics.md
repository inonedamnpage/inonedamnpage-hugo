+++
title = "CSS Basics"
description = "CSS Basics In One Damn Page"
categories = [
  "",
]
tags = [
  "",
  "",
]
date = "2016-11-15T20:24:25+05:30"

+++

# Introduction

CSS forms the basis of styling of web pages. With CSS, you can apply styles to make your web pages more readable and beautiful.

All CSS in a webpage go inside a `<style></style>` tag, unless you are linking CSS from other files. All CSS are composed of CSS rulesets, which are the basic building block of CSS code. They look like this.

{{< codecaption lang="css" title="A typical CSS Selector" >}}
div {
    color: blue;
}
{{< /codecaption >}}

The first part `div` is called a selector, and the next part is called a declaration.

# Types of selectors

{{< codecaption lang="css" title="Types of CSS Selectors" >}}
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
{{< /codecaption >}}

# Types of CSS Units

Units are used everywhere in CSS to specify length, width, height etc of content and tags. They are basically divided into absolute and relative units.

Absolute units include

* pixels (`px`)

Relative units:

* percentages (`%`)
* `em` which is mostly used for fonts
* `vw` and `vh`

# Colors in CSS

Colors in CSS can be represented in two ways:

* `rgb(0,0,0)`
* `#000000`

# Simple commonly used attributes in CSS

* _color_: Mostly refers to the font color of the element.
* _background_: can be a color or image, and can have different other properties as well.
* _width_: mostly used to specify the width of an element. Can be in pixels if absolute, or percentage, relative to it's parent element.
* _text-align_: Used to specify which side the text of the element will align. Examples include left, right or center. 
* _line-height_: How much space will be between the text lines.
* _font-size_: The size of the font, normal being `1em`.
* _font-weight_: To specify `bold` of the font.
* _font-style_: To specify `italic` of the font.
* _font-family_: Type or family of the font.
* _text-decoration_: To `underline` a text.
* _border_: The border width, style and color around an element. eg `2px dotted blue`.
* _border-radius_: How rounded the borders are, in pixels. Length are given in clockwise direction.
* _box-shadow_: The shadow around box elements. Any number of shadows can be specified. Eg `10px 10px gray, 20px 20px`.