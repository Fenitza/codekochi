codeKochi Website
=================

Overview
--------
codeKochi is a simple, responsive single-page website introducing coding
programmes in Kochi. It is built with HTML and CSS and does not require a
framework or package installation.

Project files
-------------
index.html   Page content and registration form
style.css    Page layout, colours, typography, cards, and responsive styles
readme.txt   Project information and run instructions

Page sections
-------------
- Header navigation links to the Home, Programmes, and Register sections.
- Home introduces codeKochi.
- Programmes displays Web Development, Data Science, and Mobile App
  Development in a responsive grid. Each card links to the registration form.
- Register contains fields for name, email, programme choice, and an optional
  message. The browser checks the required fields and email format.
- Footer displays the copyright notice.

Run locally
-----------
1. Keep index.html and style.css in the same folder.
2. Open index.html in a web browser:
   - Double-click the file in File Explorer, or
   - Open it from the browser using Ctrl+O.
3. After editing either file, save it and refresh the browser page.

Responsive layout
-----------------
The programme cards use CSS Grid and adjust to the available width. At widths
below 800px, the registration introduction and form stack into one column.
Below 550px, the header stacks the logo and navigation links, the programme
cards display in one column, and section padding is reduced for smaller screens.

Registration form note
----------------------
The form is a front-end demo only. It has no server or registration service
connected, so submitted information is not saved or sent anywhere.
