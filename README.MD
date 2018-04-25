# Happy Readers Club (HTML + CSS template)

## Functional requirements
- You can view a list with all the books that are in stock
- A book can have several copies available
- You can borrow up to 3 books at a time
- You can return the borrowed books by clicking on a button
- You can borrow books only if you have no books due
- A history of borrowed books should be available
- `localStorage` should be used for currently borrowed books and for previously borrowed ones (ideally stored separately)
- Any book has a title, an author, a release year and an available quantity

## Frontend app
It should provide an easy way of viewing books that are available. Books can be selected for checkout. 
After selecting the books they want to borrow, the user can click on the **checkout** button. 
This will record a transaction for the borrowed books with a due date and update the library stock. 
If the due date for the currently active transaction has passed, a warning message should be displayed on-screen.

## Backend app:
It should provide JSON data for the books in stock.

## Deployment
Both frontend and backend apps should be deployed using Heroku.

## Testing
Unit tests should at least check that:
- you can only borrow a maximum of 3 books
- you can only borrow new books when all others have been returned

## Notes
Feel free to use the books.json data and files in /images/books to have a more interesting stock of books

## References
Book list (books.json) and images taken from [here](https://github.com/benoitvallon/100-best-books).

Skeleton.CSS and Normalize.CSS taken from [here](https://github.com/dhg/Skeleton).