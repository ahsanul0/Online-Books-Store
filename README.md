📚 _____Online Book Store_____

An Online Book Store web application built to allow users to browse, search, and purchase books conveniently. This project demonstrates core Java concepts, JDBC database connectivity, and web development fundamentals using technologies like Servlets, JSP, and MySQL.

🚀 _______Features__________

>>👤 User Authentication – Secure login and signup for users and admins.

>>🔍 Book Search – Search books by title, author, or category.

>>📖 Book Details – View detailed information about each book.

>>🛒 Shopping Cart – Add or remove books before purchase.

>>💳 Order Management – Place and view orders easily.

>>🧾 Admin Panel – Add, update, or delete books from the catalog.

>>🗃️ Database Integration – Connected to a MySQL database using JDBC.

🏗️______Technologies Used_________
Layer	Technology
Frontend	HTML, CSS, JavaScript, JSP
Backend	Java, Servlets, JDBC
Database	MySQL
Tools	Eclipse / IntelliJ IDEA, Apache Tomcat, GitHub


___🧰 Installation and Setup______

Follow these steps to set up the project locally:

1. Clone the Repository

git clone https://github.com/yourusername/online-book-store.git


2. Open in IDE
Import the project into Eclipse or IntelliJ IDEA as a Java web project.

3. Configure Database

4. Create a MySQL database named bookstore.

5. Run the SQL script in /database/bookstore.sql to create tables.

6. Update database credentials in the DBConnection.java file:

String url = "jdbc:mysql://localhost:3306/bookstore";
String username = "root";
String password = "yourpassword";


7. Deploy on Tomcat Server

Set up Apache Tomcat in your IDE.

Run the project on http://localhost:8080/OnlineBookStore.

📂 Project Structure
OnlineBookStore/
│
├── src/
│   ├── com.bookstore.dao/         # Database access objects
│   ├── com.bookstore.model/       # Java model classes
│   ├── com.bookstore.servlet/     # Servlets for handling requests
│   └── com.bookstore.util/        # Database connection utilities
│
├── WebContent/
│   ├── css/                       # Stylesheets
│   ├── js/                        # JavaScript files
│   ├── images/                    # Book cover images
│   ├── index.jsp                  # Home page
│   ├── login.jsp                  # Login page
│   ├── register.jsp               # Registration page
│   ├── cart.jsp                   # Shopping cart
│   └── admin/                     # Admin panel pages
│
├── database/
│   └── bookstore.sql              # SQL file for creating tables
│
├── README.md                      # Project documentation
└── pom.xml / build.xml            # Build configuration (if using Maven/Ant)

🗄️ ___Database Tables______

users – Stores user login information.

books – Contains book details like title, author, price, category.

orders – Records customer purchases.

cart – Temporary cart storage for each user.

📸 Screenshots (Optional)

(Add screenshots of your application UI here — home page, book details, admin panel, etc.)
You can upload them to a /screenshots folder and embed like this:

![Home Page](screenshots/home.png)
![Book Details](screenshots/book-details.png)

💡 ____Future Enhancements___

📦 Integrate with online payment gateways.

⭐ Add user reviews and ratings.

🔔 Implement email notifications for order confirmation.

📱 Make the UI fully responsive for mobile users.

🧑‍💻 ___Author___

Ahsanul Haque
💼 Java Developer | Passionate about Web & Database Development
📧 ahsanulhaque000007@gmail.com

🔗 GitHub Profile

📝 License

This project is licensed under the MIT License – see the LICENSE
 file for details.
