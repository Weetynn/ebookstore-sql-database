# Architecting Success: A Tailored Database System for Efficient E-Bookstore Management

## 📚 Introduction
The E-Bookstore, based in Kuala Lumpur, Malaysia, houses an extensive collection of books across various genres, sourced from multiple publishers. As the business expanded, the management initiated the development of an online store to reach a broader customer base and streamline book purchases. 

The project at hand involves designing and implementing a robust database system to support the operations of this newly established electronic bookstore.

## 📋 Business Rules
- The bookstore purchases books from publisher which are then sell to its members. The bookstore manager compiles a list of needed books and sends an order to the publishers. The publisher supplies the ordered books to the university. The bookstore manager records the details of a new books that have arrived at the bookstore. An invoice is sent to the accounts department to be processed and payment made.
- Anyone who wish to purchase books online, need to initially register as members. Members will be able to view the book info and read reviews.
- Members who wish to purchase can select their books into the shopping cart. The cart will show the summary of the selection and total cost to be paid. Once the payment is made, the bookstore will send the books to the members within 7 working days.
- The database should manage information about books in the bookstore, members and books they have ordered.
- Member can also provide review for a book, as a rating (1-10 which is 1= terrible, 10= masterpiece) along with optional short text. No changes are allowed; only one review per member per book is allowed.

## 📈 Diagrams
                                      Entity Relationship Diagram (Crow’s Foot Notation)
![Entity Relationship Diagram](https://github.com/user-attachments/assets/1397badc-92df-4620-b47b-becbab40df02)

                                                          Database Diagram
![Database Diagram](https://github.com/user-attachments/assets/d3ac0e46-cd6a-4e6f-afd3-682756abede4)

## ❓Business Queries to be Addressed
- Find the total number of feedbacks per book. Show book ID, book title, and total number of feedbacks per book.
- Find the total number of feedbacks per member. Show member ID, member name, and total number of feedbacks per member.
- Find the total number of books published by each publisher. Show publisher ID, publisher name, and number of books published.
- Find the total number of books for each category. Show category ID, category name, and number of books for each category.
- List the books where the quantity is more than the average quantity of all books (from the book table).
- Show how many books are there for each genre.
- Show the members who did not place any orders.
- Find the average rating for each book.
- Show the total number of books added to the shopping cart.
- Show the members who made more than 2 orders.

## 🖇️ Addtional Aspect Covered in the Project
- Benefits of databases and Database Management System in managing electronic bookstores.
