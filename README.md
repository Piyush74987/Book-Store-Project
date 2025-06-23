<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
</head>
<body>
    <h1>📚 Book Store Management System</h1>
    <p>This is a <strong>Java-based Book Store Management System</strong> that allows users to perform CRUD operations (Create, Read, Update, Delete) on a book inventory. It uses <strong>Java (OOPs)</strong> with <strong>JDBC</strong> to connect to a <strong>MySQL database</strong> and was developed using <strong>Eclipse IDE</strong>.</p>

  <h2>📌 Features</h2>
    <ul>
        <li>📖 Add new books (title, author, price, quantity)</li>
        <li>🔍 View all available books</li>
        <li>✏️ Update book details</li>
        <li>❌ Delete book entries</li>
        <li>📋 Menu-driven console interface</li>
    </ul>

  <h2>🛠️ Technologies Used</h2>
    <table border="1">
        <tr><th>Technology</th><th>Purpose</th></tr>
        <tr><td>Java</td><td>Core logic using OOP principles</td></tr>
        <tr><td>JDBC</td><td>Database connectivity</td></tr>
        <tr><td>MySQL</td><td>Relational database</td></tr>
        <tr><td>Eclipse</td><td>Development IDE</td></tr>
    </table>

   <h2>🗃️ Database Structure</h2>
    <pre><code>CREATE TABLE books (
    id INT PRIMARY KEY AUTO_INCREMENT,
    title VARCHAR(100),
    author VARCHAR(100),
    price DECIMAL(10,2),
    quantity INT
);</code></pre>

   <h2>▶️ How to Run</h2>
    <ol>
        <li>Clone the repository:<br><code>git clone https://github.com/Piyush74987/Book-Store-Project.git</code></li>
        <li>Open the project in <strong>Eclipse IDE</strong></li>
        <li>Configure the MySQL connection string in the Java code</li>
        <li>Run <code>Main.java</code> to launch the console app</li>
    </ol>

  <h2>📸 Sample Output</h2>
    <pre>
====== Book Store Menu ======
1. Add Book
2. View Books
3. Update Book
4. Delete Book
5. Exit
    </pre>

   <h2>📈 Future Improvements</h2>
    <ul>
        <li>Build a GUI using JavaFX or Swing</li>
        <li>Add user authentication for admin access</li>
        <li>Enable book search by title, author, or category</li>
    </ul>

   <h2>📃 License</h2>
    <p>This project is licensed under the <a href="#">MIT License</a>.</p>
</body>
</html>
