# Project 0: **Speech School**

Web Programming with Python and JavaScript

This application was developed using HTML and CSS/SCSS.
**Speech School** is a language coaching centre which offers intensive training in languages such as French, Spanish and German. This web page allow the user to browse through the **Speech School** website which contains informations of the courses offered and contact details.

## Download
``` bash
git clone https://github.com/firaan1/speechschool.git
```

## Start **Speech School**
From the browser, open the file [home.html](./home.html)

## Contents
The directory structure is shown below,
``` bash
speechschool
├── about.html # html page containing informations about the speech school
├── contact.html # containing contact informations
├── course.html # Contains the offered course informations
├── home.html # Home page
├── images # Folder containing images used in the web pages
│   ├── img1.jpg
│   ├── img2.jpg
│   └── img3.jpg
├── mystyle.css # style sheets created by sass
├── mystyle.css.map # style sheet map created by sass
├── mystyle.scss # definitions of styles used in the web pages
└── README.md # readme
```

## Requirements from project 0
CS50W project0 requirements and my explanations are below.
* Your website must contain at least four different .html pages, and it should be possible to get from any page on your website to any other page by following one or more hyperlinks.
  - [home.html](./home.html), [course.html](./course.html), [about.html](./about.html) and [contact.html](./contact.html)
* Your website must include at least one list (ordered or unordered), at least one table, and at least one image.
  - Unordered and Ordered lists in [course.html](./course.html)
  - Table in [about.html](./about.html)
  - Images in [home.html](./home.html) and [contact.html](./contact.html)
* Your website must have at least one stylesheet file.
  - [mystyle.css](./mystyle.css)
* Your stylesheet(s) must use at least five different CSS properties, and at least five different types of CSS selectors. You must use the #id selector at least once, and the .class selector at least once.
  - used div, a, h1, body, .class and #id in the [css](./mystyle.css) file.
* Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.
  - mobile-responsive @media used in [css](./mystyle.css) file.
* You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component, and using at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.
  - Bootstrap 4 is linked in all html pages. bootstrap button classes and containers were used as well. Bootstrap row and column grid models were used in the [contact.html](./contact.html) and [home.html](./home.html) pages.
* Your stylesheets must use at least one SCSS variable, at least one example of SCSS nesting, and at least one use of SCSS inheritance.
  - The [css](./mystyle.css) file is created from [mystyle.scss](./mystyle.scss) file using sass tool. It contains nesting, inheritance and variables as well.
* In README.md, include a short writeup describing your project, what’s contained in each file, and (optionally) any other additional information the staff should know about your project.
