# Project 0

Web Programming with Python and JavaScript

Vladyslav Los (GitHub: @vlalos)

I've made my first website as my personal website containing some information about me, my interests and some other things I know or use.

The project consists of five different pages, each of them is accessible from the others.
All the pages have common style and features in responsive design and mostly differ in the information they contain. (marked as _common_)
I used two main colors in my design: purple and white, and used some other colors for the navigation links.
I also tried to make as many blocks in design as possible to be responsive, so the users could interact with the interface.

#webpage0.html

The HTML-file of the starting main page which has all the basic elements that are then being used in the other pages.
I used a Bootstrap to create a 3-row layout on all pages of the website except the last one.
At the top of the page there is a heading which is also a link to the main page. _common_
Then there is a row with the navigation links, which change their color and background when interacted. (I used :hover selector in CSS there) _common_
Next lower there is a row with the main information of this page: some introductory stuff like citation, my foto, travel notes and a table about physics
Finally, there is a row with some contact information and some useful links to the other websites _common_

#toplinksstyle.CSS

It's the biggest stylesheet in this project and it contains the styling information for all the common blocks of the pages.
Using the :hover, .class and #id selectors it manages the look of the links and the columns in nearly all row on all pages.  
It also controls the styling of the tables using options like border and font-weight.

#webpage0style.CSS

This is the stylesheet with the styling information of the main page. It manages mainly the text styling and responsive features of the image using :hover selector.  

#webpage1.html #webpage2.html #webpage3.HTML

This three pages are pretty the same in their layout and they use the same Bootstrap blocks as the main page so their layouts styling is also mainly controlled by the common stylesheet. There are some differences in headings styles and there is also a "badge"-element from Bootstrap used in the webpage3.html.

#webpage4.html

This page is more a fotoalbum, so I used different columns in its rows so the fotos look better that way. These blocks were also made responsive by :hover selector in the stylesheet.

#webpage1style.scss #webpage2.scss #webpage3.scss #webpage4style.scss

As the stylesheets were getting a bit more complex I started using Sass to maintain them. All these stylesheets include pretty the same information about each of the pages. There are some images stylings, especially sizing, and text stylings: font-weight, -size, padding etc..  
