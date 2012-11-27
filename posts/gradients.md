feature: gradients
status: use
tags: fallback prefixes gtie8
kind: css
polyfillurls:

We strongly recommend you use most prefixes (`-o-`, `-ms-`, `-moz-`) when you provide gradients as image values (`background` or `border-image`). Do provide a fallback color if you are using this as a value for `background` so browsers that do not support the gradients can render a solid background color. 

WebKit can use the [latest syntax](http://www.broken-links.com/2012/01/11/the-new-and-hopefully-final-linear-gradient-syntax/), as [the specification](http://www.w3.org/TR/css3-images/) has hit Candidate Recommendation. 
