# MY TAKEAWAYS

- This project is part of the HTML pre-course homework for the CodeSquad Full-Stack Bootcamp. The objective was to create a comics website using solely HTML. 
- I gained a better understanding of how to create a navigation bar. I didn't realize it was not good practice to wrap an a tag around the list item tag, but instead preferred to have the list item wrapped around the a tag instead.
- I learned how to disable features using the "disabled" attributes, and how to select in a drop down menu using the "selected" attribute. 
- Inputting values, especially to pre-fill fields is still a little confusing but it makes more sense than before. 
- I learned about sections and articles and have tried to make my project accessible using semantic HTML and hopefully easy to read.
- The instructions on how to build this comic store website is listed below.
  
-----

# OBJECTIVES:

We are finally going to start using our HTML skills to build all the pages needed for the CodeSquad Comics web application.

## DIRECTIONS:

- Create a new folder
- Open VSCode and then open this folder
  - Click "File" at the top menu
  - Click "Open"
  - Find the folder and click "Open"
- Create 6 HTML files with the following names:
  - about.html
  - admin.html
  - create.html
  - index.html
  - login.html
  - update.html
- Download the "starter-files" folder to your computer
- Inside the "starter-files" folder, you'll find mockups for the six HTML pages that are part of the project, a README.md file that contains these directions, and a folder called "public".
- Inside the "public" folder, there's a folder called "images," and inside the "images" folder, you'll find all the images you need to complete this assignment.
  Move the "public" folder into the root directory. Do not include any images that have the words "mockup" in the project folder.

Use the mockups included in the "starter-files" folder to create the six web pages. Use the hints below to help you with specific pages.

## GENERAL HINTS

- Utilize the target="\_blank" and the rel=”noopener noreferrer” attributes for links that take users to a new website. Find out more: target attribute and target vulnerability.
- Use the attribute href="#" in any links that you don't want to navigate somewhere else. The pound sign just tells the computer to stay at the current location instead of navigating somewhere else. Find out more: href attribute

## NAVBAR AND FOOTER

- Perfect the navbar and footer on one page, and then just copy and paste the code onto the other 5 pages. This will greatly reduce the time it takes you to code these pages.
- The navbar consists of the CodeSquad Comics logo and the bulleted list of the three navigation links directly below.
- The footer consists of the "VISIT US" header and everything below it.
- The logo in the footer should link to http://codesquad.org/, and this should open in a new tab in the browser.
- The logo in the navbar should link to the index.html page, and this should NOT open in a new tab in the browser.
- The links under the "FOLLOW US" header in the footer can link to your personal social media pages or you can make the href attribute equal to "#" to keep the user on the same page when the link is clicked.

## INDEX PAGE

- Put the attribute style="width: 200px;" on all the comic book cover images to make them smaller. (You will eventually take this out and style the images with CSS, but adding in the attribute at this step in the design will help make your page easier to view in this first version.)
- All book cover images should also be links but utilize the href="#" because they won't link anywhere specific until later versions of this project.
- Also utilize the href="#" for each "Details" link under each comic's title, author, and rating. Eventually, these will link to a "Details" page for each comic, but that comes in a later version.

TEXT NEEDED FOR THIS PAGE:

"CodeSquad Comics is a collection of graphic novels read by <YOUR NAME>. The site is intended to display comic book covers along with information about each book, including the author, a rating, and other details about the graphic novel. Browse through the complete collection below. Click on the cover image or the Details link to see even more information about each graphic novel including the publisher, genre, number of pages, and a brief synopsis. The About page includes meta information about this collection. Login is only available to the site administrator at this time."

## ABOUT PAGE

TEXT NEEDED FOR THIS PAGE:

"CodeSquad Comics is a collection of graphic novels read by <YOUR NAME>. Copyrighted images are used for review purposes only. Meta information about this collection can be found below. A detailed list of all the graphic novels in this collection can be found on the homepage. Additional details about each comic book, including the author, genre, number of pages, and a brief synopsis, can be found by navigating to the homepage and clicking the image of the book cover or the Details link for the desired graphic novel."

## ADMIN PAGE

The content on this page is contained in a table.

## LOGIN PAGE, UPDATE PAGE, & CREATE PAGE

- Each of these pages contains a form. Use the action="#" attribute on the opening form tag for now. We won't do anything with the form submission until a much later version of the course project.
- Each label for the input should have an "for" attribute that matches the "id" and "name" attributes in the corresponding input tag. These may not make any sense until we start working with databases later in the course, but they are needed in every input tag, so it's a good idea to get in the habit of including them now.
- Many inputs utilize the "placeholder" attribute.
- For the select tag on the Create page and the Update page, the possible options are:
  - BOOM! Box
  - DC Comics
  - Harry N. Abrams
  - Icon Books
  - Image Comics
  - Marvel
  - Simon & Schuster
  - Top Shelf Productions
  - VIZ Media LLC

The form inputs on the Update page are pre-filled with the following values:

- "title value stored in the database"
- "author value stored in the database"
- "publisher value stored in the database"
- "genre data stored in the database"
- "255"
- "5"
- "synopsis value stored in the database"

## BONUS

- Use the "value" attribute for input tags on the Update page to pre-populate an answer. Learn more about the "value" attribute: value attribute.
- For the select options, utilize the "selected" and "disabled" attributes to make it look exactly like the mockups that show the dropdowns. Learn about the "selected" attribute: selected attribute. Learn about the "disabled" and other form attributes: input attributes.

Submission:

- When you are done with this assignment, zip the files and submit them to this assignment
