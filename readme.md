## CSS3 Flex Box Layout Module for TextMate

A TextMate bundle module which provides basic support for the new interface design optimized layout module for web sites and applications.

Includes vendor-prefixed (and non-prefixed) properties for Firefox and Safari/Chrome.

* box-orient
* box-pack
* box-align
* box-flex
* box-flex-group
* box-ordinal-group
* box-direction
* box-lines

## Abstract

The draft describes a CSS box model optimized for interface design. It provides an additional layout system alongside the ones already in CSS. [CSS21] In this new box model, the children of a box are laid out either horizontally or vertically, and unused space can be assigned to a particular child or distributed among the children by assignment of “flex” to the children that should expand. Nesting of these boxes (horizontal inside vertical, or vertical inside horizontal) can be used to build layouts in two dimensions. This model is based on the box model in the XUL user-interface language used for the user interface of many Mozilla-based applications (such as Firefox).

For more information, see: http://www.w3.org/TR/css3-flexbox/

## Version History

1.0.1 - Added an example HTML5/CSS3 template showing some of the properties in use
1.0 - Initial version. Includes basic vendor-prefixed properties for the CSS3 Flex-Box layout module