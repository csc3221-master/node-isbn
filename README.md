# Verifying ISBN using Forms and Node
These assignment has several parts:
1. Create a page that has a form with a text input field [25]
   1. The page must use bootstrap (use CDN link) [5]
   1. The page should have the following layout: ![layout](https://github.com/csc3221-master/node-isbn/blob/master/isbn-checker-layout.png)   [5]
   1. The form's action should be `checkisbn` with method GET [5]
   1. The input field should validate that the text has length 10 or 13 made of digits only, except last digit that it may be an X. You might get ideas from the midterm files. [10]
1. Create a node application that will respond to the form on the page [25]
   1. The node program should use Express [5]
   1. Node should serve the page and the image used in the page as a static resource [5]
   1. It would have a route to handle GET requests with `checkisbn` resource, this request should respond if the isbn is valid. See: [Wikipedia ISBN Article](https://en.wikipedia.org/wiki/International_Standard_Book_Number) [15]
   
   
# How to submit
1. Work on the repository created for your assignment and work there. The repository will not accept push after the due date.
1. Publish your work on Leia by cloning the repository inside your home directory (NOT ON `public_html`), upload on Canvas images showing your working site, make sure the address bar shows the program running on Leia.

