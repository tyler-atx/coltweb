 41 - unit objectives


1. Define "general rule" of CSS
2. Correctly include CSS in HTML files
3. Select elements by tag name, class and ID
4. Style elements with basic properties like color and background
5. Use Chrome CSS Inspector to debug HTML and CSS

CSS Selector Scavenger Hunt



-------


42 - CSS basics

Cascading Style Sheets

www.csszengarden.com

The general rule. Always follow this format!

>selector {
>    property: value;
>    anotherProperty: value;
>}


Below code will modify all h1 tags

>h1 {
>    color: purple;
>    font-size: 56px;
>}


Prior to CSS, all elements contained their style tags
E.g. <li style="color: purple;">Hobby</li>

Can also add a <style></style> tag with all selectors in the <head> tag of the html (see aboutMe.html)

Latest selector is the one that is used in conflicting situations


Use an <link> tag to get the CSS out of the html tag.


-----

45 - CSS Colors


Named Colors

colours.neilorangepeel.com is a site with all CSS colors

typically the default colors are only used for debugging


Hexidecimal colors

Hexadecimal values: #000000 - black
Hash (octothorpe) and six hexidecimal values

First two digits RED, second two digits GREEN, last two digits BLUE

www.colorpicker.com for hexidecimal colors


RGB colors

color: rgb(0, 255, 0)

Higher numbers will white out the color (white is all colors)


RGBA

a = transparency value, increases with opaqueness

color: rgb(0, 255, 0, .5)


-------

46 - Background and Border













