![image](https://github.com/user-attachments/assets/2863ff8d-6bd9-4b2a-b5c5-d872f11c48ee)


Project Title: Online Book Publishing and Sales Platform

Description:

This project focuses on designing and implementing a relational database system for an online book publishing and sales platform. The system handles information related to books, authors, publishers, customers, orders, payments, and more. It simulates real-world e-commerce functionalities including wishlists, multi-item orders, shipping, and payment tracking.

Key Components of the Project:

Entity-Relationship Model:

BOOK: Stores details like title, ISBN, edition, publication year, price, and publisher.

AUTHOR: Contains author profiles including biography and associations with multiple books.

PUBLISHER: Holds publisher information and their published books.

GENRE: Stores book genres; each book can belong to multiple genres.

CUSTOMER: Stores customer profiles along with their purchase history.

Customer Features:

Customers can manage multiple shipping addresses, maintain a wishlist, and place orders containing multiple books.

Each order includes order date, shipping info, and shipment status.

Payments are tracked with methods (e.g., Credit Card, PayPal) and status (Completed, Pending).

Order System:

The ORDER and ORDER_ITEM tables support complex order scenarios like multiple books per order, item-level discounts, and price tracking.

Example: An order might contain multiple books such as The Great Gatsby and 1984, each with its quantity and unit price.

Junction Tables:

BOOK_AUTHOR: Supports many-to-many relationships between books and authors (e.g., co-authored books).

BOOK_GENRE: Links books to multiple genres (e.g., Fiction, Dystopian).

Data Insertions:

Sample data includes books like The Great Gatsby and 1984, authors like F. Scott Fitzgerald and George Orwell, and customers like Alice Johnson and Bob Smith.

Orders, payments, shipping details, and wishlists are populated to simulate real-world usage.

Conclusion:

This SQL project successfully demonstrates the modeling of a robust and scalable database for a digital bookstore and publishing system. It incorporates real-world complexities like multi-author books, multiple editions, customer personalization, and transaction tracking—making it ideal for an actual e-commerce backend.

![image](https://github.com/user-attachments/assets/5d40de20-8af4-4058-a83b-b0de7e235554)


