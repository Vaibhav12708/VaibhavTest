# VaibhavTest

#PART A
   
   1) Mention the working of Internet Website in Terms of Front-end & Back-end Divisions 

The front-end and the back-end are typically the two main divisions involved in how an internet website functions. Let's examine these divisions and their different responsibilities in more detail: 

Front-end: The client-side, or front-end, of a website is where users interact with it directly. It entails designing and displaying the website's user interface. HTML (Hypertext Markup Language), CSS (Cascading Style Sheets), and JavaScript are the primary technologies used for front-end development. 
The following are the division's main constituents: 
- HTML: It uses markup tags to define the structure and content of a web page. 
- CSS: It controls the web page's appearance and styling by defining how items should be presented. 
- JavaScript is a computer language that gives websites liveliness and dynamic behaviour. It makes it possible to do tasks like form validation, animations, and more. 

Designing the website's buttons, forms, buttons, colour schemes, and other user-interaction-related features is known as user interface (UI). The responsiveness of the website is ensured by front-end developers, who make sure that it responds to various devices and screen sizes and shows properly on each. By making the website aesthetically pleasing, practical, and accessible, front-end developers concentrate on providing a user-friendly and engaging experience. 


Back-end: The server-side, sometimes referred to as the back-end, is responsible for the functionality and powering of a website. Database administration, server-side programming, and the whole server infrastructure are all involved. 

The following are the main elements of the back-end division: 
Server: It is in charge of handling client-side requests, running the required code, and returning the result. 
Server-side programming is the act of creating server-side logic and managing data processing using programming languages like Python, PHP, Ruby, Java, or Node.js. 
Websites frequently rely on databases to store and retrieve data effectively. To handle data storage and retrieval, back-end developers use database systems like MySQL, PostgreSQL, MongoDB, or Oracle. 
Application Programming Interfaces, or APIs, allow data to be exchanged and communications to occur between various software programmes or services. They provide smooth data interchange and interaction between the front end and back end. Security mechanisms, including user authentication, encryption, and secure communication protocols, are put in place by back-end developers to guard against unauthorised access to the website and its contents. 

Back-end developers put their attention on creating dependable and effective systems that manage data processing, business logic, and connection with other services, ensuring the website runs efficiently and safely. 



   2) What are tags in HTML? Explain the each category of tag with an Example. 

The structure and components of a web page are defined by tags. Tags are often used in pairs, with an opening tag and a closing tag, and are encased in angle brackets (">" and "/>"). Between the opening and closing tags, there is space for the tag's content. 

HTML has six levels of headers, ranging from h1> to h6>. With h1> being the highest level (primary heading) and h6> being the lowest level (subheading), these tags are used to specify multiple levels of headings.  
Example: 
<h1>Heading</h1> 
<h2>Subheading</h2> 
<h3>sub sub heading</h3> 

Tags for paragraphs: The p> tag is used to identify paragraphs on a website. It is frequently employed for textual content organisation and presentation. Consider this: 

 <p>This is a paragraph of text.</p> 

The a> (anchor) element is used in HTML to generate hyperlinks. By clicking the link, visitors can go to another web page or a specific spot on the current page. The link's destination is specified using the href property. 

<a href="https://www.example.com">Visit Example Website</a> 

HTML has two different list types: ordered lists (ol>) and unordered lists (ul>). In contrast to an unordered list, which utilises bullets, an ordered list employs li> (list item) tags to designate each list item with a number. For instance: 

<ul> 
  <li>Item 1</li> 
  <li>Item 2</li> 
  <li>Item 3</li> 
</ul> 
<ol> 
  <li>First item</li> 
  <li>Second item</li> 
  <li>Third item</li> 
</ol> 

Table Tags: The HTML table, table row, and table data tags are used to structure tables. You may specify rows and cells in a table using these tags. For instance, CSS 

<table> 
  <tr> 
    <td>Row 1, Cell 1</td> 
    <td>Row 1, Cell 2</td> 
  </tr> 
  <tr> 
    <td>Row 2, Cell 1</td> 
    <td>Row 2, Cell 2</td> 
  </tr> 
</table> 

 


   3) Explain the working Procedure of Virtual DOM 

The virtual DOM provides a mechanism that abstracts manual DOM manipulations away from the developer, helping us to write more predictable code. It does so by comparing two render trees to determine exactly what has changed, only updating what is necessary on the actual DOM. 
Like React, Vue also employs this strategy. However, Svelte proposes another approach to ensure that an application is optimized, compiling all components into independent, tiny JavaScript modules, making the script very light and fast to run. 
By using the Virtual DOM, React minimizes the number of direct manipulations on the actual DOM, which can be expensive in terms of performance. The Virtual DOM acts as an intermediary layer that allows React to efficiently track and apply only the necessary updates to the DOM, resulting in faster and more optimized rendering. 

 

   4)Mention some Differences between MySQL and No SQL.

Transactions:
MySQL: It provides support for ACID-compliant transactions, ensuring data integrity and consistency.
NoSQL: NoSQL databases often sacrifice full transaction support in favor of scalability and performance, offering eventual consistency or relaxed transactional guarantees.

Data Storage:
MySQL: It stores data in structured tables using fixed schemas.
NoSQL: NoSQL databases offer various storage formats based on the data model, such as JSON-like documents, key-value pairs, or columnar storage.

Use Cases:
MySQL: It is commonly used for traditional relational data scenarios, such as content management systems, e-commerce platforms, and data-driven applications.
NoSQL: NoSQL databases are often used in scenarios requiring scalability, real-time analytics, handling large volumes of unstructured or semi-structured data, and rapid development iterations.

Flexibility:
MySQL: It provides strong data consistency and ensures data integrity through strict schema definitions and relationships.
NoSQL: NoSQL databases prioritize flexibility, allowing for agile development, accommodating changing data structures, and handling unstructured or semi-structured data efficiently.

Joins:
MySQL: It supports complex joins between tables for querying data across related entities.
NoSQL: NoSQL databases often avoid joins and favor denormalization or embedding of related data within a single document or record.

Vertical Scaling:
MySQL: It is typically well-suited for vertical scaling, where a single server can handle increased workloads by adding more powerful hardware.
NoSQL: NoSQL databases are designed for horizontal scaling, allowing them to distribute data across multiple servers to handle increased traffic.


   5)Explain any one DBMS Technology in your own words.

RDBMS (Relational Database Management System) is a technology that manages and organizes data based on the relational data model. It is widely used in the industry and has been the dominant database technology for several decades. Here's a further expansion on RDBMS technology:

Relational Data Model:
RDBMS follows the relational data model, which organizes data into tables or relations. Each table consists of rows (also known as tuples) and columns (also known as attributes). The relationships between tables are established through keys, such as primary keys and foreign keys, ensuring data integrity and enforcing referential integrity constraints.

Data Normalization:
RDBMS encourages data normalization, which is the process of organizing data into well-structured tables. Normalization minimizes data redundancy and ensures data integrity by eliminating data anomalies, such as update anomalies, insert anomalies, and delete anomalies. It results in efficient storage, reduced redundancy, and improved data consistency.

ACID Properties:
RDBMS offers ACID properties, which are critical for reliable and consistent data management. ACID stands for Atomicity, Consistency, Isolation, and Durability.

Atomicity: Ensures that a transaction is treated as a single unit of work. It either succeeds completely or is rolled back entirely if any part fails.

Data Integrity:
RDBMS provides mechanisms for maintaining data integrity. It supports the enforcement of constraints, such as primary key constraints, foreign key constraints, unique constraints, and check constraints. These constraints ensure that data remains consistent and accurate, preventing invalid or inconsistent data from being inserted or modified.

Structured Query Language (SQL):
SQL is the standard language used to interact with RDBMS. It provides a comprehensive set of commands for creating, querying, modifying, and managing relational databases. SQL allows users to define tables, insert data, retrieve specific data with powerful queries, update records, and perform various other database operations.


