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

Can also add a <style> tag with all selectors in the <head> tag of the html (see aboutMe.html)

Latest selector is the one that is used in conflicting situations


Use an <link> tag to get the CSS out of the html tag.








