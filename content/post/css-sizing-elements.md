+++
categories = [
  "",
]
tags = [
  "",
  "",
]
date = "2016-11-16T19:50:39+05:30"
title = "CSS Sizing Elements"
description = "All about sizing things in CSS."

+++

# The CSS Box Model

All elements in an HTML page can be broken down to and represented in boxes. So CSS provides a box model which is used to size elements.

The basic content of HTML is surrounded by `padding`, `border`, and `margin`. While by default (`box-sizing: content-box`), padding. border and margin are thought to be outside the element, you can change padding and border to be inside and margin on the outside.

{{< codecaption lang="css" title="CSS Box Sizing" >}}
* {
    box-sizing: border-box;
}
{{< /codecaption >}}

# CSS Display Properties

CSS elements can have two kind of display properties:

* `display: block`: Take up as much width as possible (with restraint from parent) and height according to the content. Eg: `<div>`.
* `display: inline`: Take up height and width according to content. Eg: `<span>`. You cannot set the height and width of these elements, but can set the border and padding (which gets applied to the sides but not in top and bottom). Inline elements wrap when the content is bigger than their parent.

# Most Used HTML Elements For Styling

`<div>` and `<span>` are the generic HTML elements can be used for applying styles. Divs are the most generic block elements while spans are most generic inline elements. 

# Semantic Elements

Semantic elements make it easier to organise content in an HTML page. They also make the markup readable and provide support for accessibility and SEO. Some kind of semantic elements are: `<header>, <footer>, <section>, <article>` etc.

# Some Advanced CSS Properties

* _float_: Incase of an image, the specify the direction the image will align to, and the text will take up rest of the page.
* _vertical-align_: Allows to align inline elements vertically, much like `text-align` but vertical.
