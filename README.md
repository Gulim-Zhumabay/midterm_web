# BookVerse

Topic: an online library and book catalog website.

## Group members

- Gulim Zhumabay
- Aiymay Tleu
- Aktanbi Kusman

## Description

BookVerse (created from "Books Universe") is a multi-page responsive website about books. Visitors can browse the catalog, explore books by category, open a separate page with details about each book, compare and buy membership plans and send a message to admins.

Every book page has three buttons: read the ebook and listen to the audiobook (lead to the Telegram bot and special website), and buy the book (leads to an instagram page of the Marwin bookshop).

For the endterm project we made the same website more interactive with JavaScript and jQuery. The topic, the structure and all midterm pages stay the same, and the responsive layout still works. Now visitors can search and filter books, register and sign in, keep their own reading list and look at the book covers in a gallery.

## Pages

- Home (index.html)
- Books (books.html)
- Categories (categories.html)
- Contact (contact.html)
- Membership (membership.html)
- Gallery (gallery.html), new in the endterm project
- Register (register.html), new in the endterm project
- Sign in (signin.html), new in the endterm project
- Nine book pages: camellia-details.html, brain-details.html, gatsby-details.html, whisperer-details.html, psychology-details.html, eden-details.html, wolf-details.html, rose-details.html, dieu-details.html (we will add more books later)

## Features implemented

Midterm project:

- Navigation bar with a logo, visible on all pages and sticky when scrolling
- Home page with a hero section built from rotated book covers and a block with the top 3 books of the week
- Books page with a catalog of cards, each card links to its own book page
- Categories page where books are grouped into four categories and shown in a CSS Grid
- Book pages with a cover, author, year, genre, plot overview, list of characters and action buttons
- Membership page with a table that compares plans and a subscription form
- Contact page with contact information and a feedback form
- Hover effects on cards, navigation links and buttons
- Responsive layout: Bootstrap grid and media queries for desktop, tablet and mobile
- Lazy loading for images
- Consistent brown color theme across all pages

Endterm project:

- Search and filter on the books page: the cards are filtered while the user types. The search looks for the title and the author and does not care about capital letters. The buttons Fiction, Business, Detectives and Psychology work together with the search, and the page does not reload. If nothing is found, a short message appears.
- Registration form with validation on the register page: required fields, email check with a regular expression, a color bar that shows if the password is weak, medium or strong, and a check that both passwords are the same. Every field turns green or red right away and shows a short text. If something is wrong, the form is not sent.
- Sign up and sign in: a new user is saved in the browser (localStorage) in JSON format, and the sign in page checks the email and the password. This is only a demo without a server, so it is not real security. The Sign in and Sign up buttons are in the navigation bar of every page, and the Continue button on the membership page leads to registration.
- Reading list on the categories page: a table where a visitor can add a book in a modal window, see all books, edit a book and delete a book after a confirmation question. The list is saved in the browser with localStorage, so every visitor has their own list.
- Image gallery with lightbox on the gallery page: a grid of 18 book covers. A click opens the cover bigger, arrows and keyboard keys move to the next or the previous cover, and the jQuery effects fadeIn, fadeOut and animate make everything smooth.
- All the JavaScript code is in the file js/script.js

## Technologies used

- HTML5
- CSS3 (Flexbox, Grid, media queries, hover effects, positioning)
- Bootstrap 5 (grid system, navbar, cards, table, forms, modal window, buttons, utility classes)
- Bootstrap JavaScript bundle (for the collapsing mobile menu and the modal window)
- JavaScript (DOM, events, regular expressions, localStorage, JSON)
- jQuery (events, fadeIn, fadeOut, animate)
- Git and GitHub

## Individual contribution

Midterm project:

- Aktanbi Kusman: He created home page and categories.html. Analyzed each book and their genre then sorted them. Created logo of the project using AI tools.
- Aiymay Tleu: She wrote files contact.html, membership.html. Created table in the file membership, linked readers to us with contact. Came up with a name for the project
- Gulim Zhumabay: She created files books.html and all 9 detail files. Searched about every book, created clear files for each of them with related information, and fixed some errors of whole project at the end of the process. Wrote README.md
- We all worked together to come up with the theme, style, and color scheme for the entire project. We discussed everything together - the selection of books, the choice of colors for the logo, pages, buttons, and even the position of the elements.

Endterm project:

- Gulim Zhumabay: She made the search and the category filter on the books page, updated the navigation bar on all pages and updated README.md for the endterm project.
- Aiymay Tleu: She made the register page with the form validation and the password strength bar, the sign in page and the saving of users, and changed the Continue button on the membership page.
- Aktanbi Kusman: He made the reading list with add, edit and delete on the categories page and the gallery page with the lightbox.
- We tested the website together on a computer and on a phone and published it on GitHub Pages.

## Published website

https://gulim-zhumabay.github.io/midterm_web/