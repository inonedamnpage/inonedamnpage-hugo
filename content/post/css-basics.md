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

{{< highlight css >}}
div {
    color: blue;
}
{{< /highlight >}}

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
