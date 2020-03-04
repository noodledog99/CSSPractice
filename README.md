# Simple-Tag HTML
The __most commonly__ used HTML tags are as follow :
- [p tag ](https://www.w3schools.com/tags/tag_p.asp)  - The p tag  **defines a paragraph** 
- [strong tag ](https://www.w3schools.com/tags/tag_strong.asp) - Defines **important** text 
- [em tag ](https://www.w3schools.com/tags/tag_em.asp) - **Emphasized** text 
- [small tag ](https://www.w3schools.com/tags/tag_small.asp) - Defines **small** text 
- [h1 tag ](https://www.w3schools.com/tags/tag_hn.asp) - For the **site title** 
- [h2 tag ](https://www.w3schools.com/tags/tag_hn.asp) - For the **webpage** 
- [h3 tag ](https://www.w3schools.com/tags/tag_hn.asp) - For a **article heading**
- [h4 tag ](https://www.w3schools.com/tags/tag_hn.asp) - For a **sub navigation** inside the article 
- [section tag](https://www.w3schools.com/tags/tag_section.asp) - The **section** tag defines sections in a document, such as **chapters**, **headers**, **footers**, or any other sections of the document.

## CSS (Style Sheets)
- CSS stands for **C**ascading **S**tyle **S**heets
- style sheet - a list of CSS rules/rule sets
- CSS describes **how HTML elements are to be displayed on screen, paper, or in other media**

### CSS Columns property
```
column-gap : Space of column gap
column-count : number of columns  
```

## Note
 - what a **element**? <br>
    A simple example is the **text box**, which allows you to enter some textual data on a webpage. Most commonly used web elements are :
    1. Text box
    1. Button
    1. Dropdown list
    1. Hyperlink
    1. Check Box
    1. Radio Button.

 - Inline Elements - Mostly of **letters**, **pictures** for instance *span, a, br, input, button, em, strong, textarea*
    - Don't take up and more room than their content need 
    - Inline Elements using **text-align** - Center used with **tag p** or **tag h** is a central way for content within that element, not the element itself
    - The span tag behavior is similar to div operation. Manage the HTML structure to use CSS to display of data. The span tag will be invoked only if you want to insert the existing information in that line. To display the results in a different format and style (Just the display format __Not__ about emphasizing the meaning) Such as different colors or underlines, colored edges, highlighted backgrounds
    - We can convert inline Element to block Element or revert by **display: block;** convert inline Element to block

- Block level Element Most of them are __tags__ that **automatically line up** for instant *div, p, h1, header, footer, nav, ul, ol, li, table, video*
    - Take up the whole width of a page regardless of content
    - Block-level Element uses margin - auto (Must also specify the width for the element to be placed in the middle of the page!) Usually used with div and other block-level elements. It is the center of the page that the element itself is not related to the content of that element.
    - It will reserve a section of the space as a whole block.

- used **equal** to get an exact match - a[href="example.com"]
- used **Asterix equal** to say it includes this somewhere in value - a[href*="example"]
- used **dollar sign** equal to say that this comes at the end of value - a[href$=".com"]
- Inherit is Value, which after following Properties, Will inherit the value from parent. Properties that have their own Default value are inherited and cannot use inherit with shorthand properties.

```
Pseudo-classes
span:nth-child(3) is mean span 3

< span > 1 < /span >
< span > 2 < /span >
< span > 3 < /span >
< span > 4 < /span >
```


## Margin & Padding
- Inline Elements - only margin left and right
![](images/inline-mp.PNG)

- Block level Element - padding and margin all the way around
![](images/div-mp.PNG)

## Semantic Element
- A semantic element clearly describes its meaning to both the browser and the developer.
    - Examples of non-semantic elements: div and span - Tells nothing about its content.
    - Examples of semantic elements: form, table, and article - Clearly defines its content.

## Position & Layout
- Static - Default of position, Stay still
- Relative - Similar to static but we can using **top, left, right, bottom** to set the position (Can move anywhere that we want along the axis x,y)
- Fixed - An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element.
- Absolute - Use with relative. For example, if we want the green box to be in the red box Must specify that the red box is relative and the color box is absolute
- Sticky - A mixture of **static** and **fixed**