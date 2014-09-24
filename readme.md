# CSS Cheat Sheet
A quick go to guide for CSS goodness. Checkout the [pretty version](http://adam-marsden.co.uk/css-cheat-sheet).

##Contributing
If you have a bug to report about the [pretty CSS Cheat Sheet](http://adam-marsden.co.uk/css-cheat-sheet) or something to add onto the CSS Cheat Cheet follow the [contribution guidelines](https://github.com/AdamMarsden/css-cheat-sheet/blob/master/CONTRIBUTING.md).

##CSSCS Nav

  * [Selectors](https://github.com/AdamMarsden/css-cheat-sheet#selectors)
  * [Pseudo Selectors](https://github.com/AdamMarsden/css-cheat-sheet#pseudo-selectors)
  * [Font Styling](https://github.com/AdamMarsden/css-cheat-sheet#font-styling)
  * [Position](https://github.com/AdamMarsden/css-cheat-sheet#position)
  * [Background](https://github.com/AdamMarsden/css-cheat-sheet#background)
  * [Box properties](https://github.com/AdamMarsden/css-cheat-sheet#box-properties)
  * [List Styling](https://github.com/AdamMarsden/css-cheat-sheet#list-styling)


###Selectors

Universal Selector `* {}`

Type Selector `h1, h2 ,h3 {}`

Child Selector `ul &gt; li {}`

Descendant Selector `p a {}`

Class Selector `.class {}`

ID Selector `#id {}`

Adjacent Sibling Selector `h1 + p {}`

General Sibling Selector `h1 ~ p {}`

###Pseudo Selectors

Mouse Over Selector `a:hover {}`

Active Link Selector `a:active {}`

Focus Selector `input:focus {}`

Visited Links Selector `a:visited {}`

Link Selector `.class:link {}`

First Line Selector `p::first-line {}`

First Letter Selector `p::first-letter {}`

First Child Selector `p:first-child {}`

Last Child Selector `p:last-child {}`

:nth-child Selector `p:nth-child() {}`

###Font Styling

Font style `font-style: normal | italic | oblique`

Font Variant `font-variant: normal | small-caps`

Font Weight `font-weight: normal | bold | bolder | lighter | 100 - 900`

Vertical Alignment `vertical-align: baseline | 10px | sub | super | top |
text-top | middle | bottom | text-bottom | initial`

Font Size `font-size: 12px | 0.8em | 80%`

Text Transform `text-transform: capitalise | lowercase | uppercase`

Space Between Characters `letter-spacing: normal | 4px`

Line Height `line-height: normal | 3em | 34%`

Horizontal Alignment `text-align: left | right | center | justify`

Text Decoration `text-decoration: none | underline | overline | line-through`

Indent First Line `text-indent: 25px`

Font Family `font-family: 'Open Sans', sans-serif`

###Position

Position `position: static | relative | absolute`

Left Position `left: 10px | 10% | auto`

Top Position `top: 10px | 10% | auto`

Float Element `float: left | right | none`

Clear Floating Elements `clear: none | left | right | both`

Z Index `z-index: 3 | auto | inherit`

###Background

Background Image `background-image: url()`

Background Repeat `background-repeat: repeat-x | repeat-y | repeat | space |
round | no-repeat`

Background Color `background-color: #2AA9E0`

Background Position `background-position: top | right | bottom | left |
center`

###Box properties

Margin `margin-top: 2px` `margin-right: 4px | auto` `margin-bottom: 6px`
`margin-left: 8px | auto` `margin: 2px 4px 6px 8px | 0 auto`

Padding `padding-top: 2px` `padding-right: 4px | auto` `padding-bottom: 6px`
`padding-left: 8px | auto` `padding: 2px 4px 6px 8px | 0 auto`

Border Color `border-color: #2AA9E0`

Border Style `border-style: none | hidden | dotted | dashed | solid | double |
groove | ridge | inset | outset`

Border Width `border-width: 10px`

###List Styling

List Type `list-style-type: disc | circle | square | none`

List Position `list-style-position: inside | outside`

List Image `list-style-image: url();`

##Notes

Project by [Adam Marsden](https://twitter.com/AdamMarsdenUK)

Made with [Crumpet](http://suitedpixel.com/crumpet/)