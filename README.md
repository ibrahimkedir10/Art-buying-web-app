# Art-buying-web-app
web application using JavaScript ,html, CSS, and json. 
## Discription:
The page allows users to select a book from a dropdown list, and upon selection, it displays information about the chosen book, such as the author, ISBN, number of pages, and price. Users can also add books to their cart, which dynamically updates the total price and displays the selected books in a textarea.

## components and functionality of the page:

Title and Header:

The title of the webpage is "Ibrahim's Art Anatomy Books."
The header within an h1 tag displays "Ibrahim Kedir's Art Anatomy Books."
Book Information Display:

The page has a grid layout (using CSS Grid) to display book information.
It includes a dropdown select (HTML select element) that lists the available art anatomy books.
Upon selecting a book from the dropdown, the page fetches data from the "ArtAnatomy.json" file using JavaScript fetch API. This JSON data contains details of various art anatomy books.
When a book is selected, the JavaScript function "selectArt" is called to update the displayed information (author, ISBN, number of pages, price, and book cover image) based on the selected book.
Cart Functionality:

The page includes a "Add to Cart" button beside the book details.
When the "Add to Cart" button is clicked, the "handlecart" JavaScript function is executed.
The "handlecart" function calculates the total price of the selected books and updates the displayed total.
It also keeps track of the selected books and their prices in the "cart" array.
The selected books with prices are displayed in a textarea with the id "totalCart" as a list.
Styling:

The page is styled using inline styles and CSS within the "style" tag.
The background colors, font families, and grid layout are defined using CSS styles.
The books' information is displayed in colored boxes with black borders.

### Instructions for Running the Page:

Place the "ArtAnatomy.json" file containing the book details in the same directory as the HTML file.
Open the HTML file (index.html) in a web browser.
The page will load with a randomly selected book from the "ArtAnatomy.json" data.
Use the dropdown to select different books and view their details.
Click the "Add to Cart" button to add the selected book to the cart and update the total price.
