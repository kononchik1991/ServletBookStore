# ServletBookStore Project
Java stack:
  Servlet, 
  JSP,
  JSTL,
  Lombok,
  Maven,
  Postgres.
  
Run:
  clone this repository -->
  open project in IDEA IDE.
  
Description: book shop.
The dependency inversion principle was used in the project (different implementations of repositories: FileDB (working with files), InMemoryDB and PostgresDB (working with  JDBC)). 
It’s some key points are the following:
•	admin panel (creation of stores (name, city), books (title, author, description, price), order management)
•	viewing, searching, ordering books by the user with adding to the basket and further ordering (delivery or self-pickup)
•	personal account with user data, basket and history of orders
•	session and data storage in the database
  
  
