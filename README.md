🎥 Cinema Ticket Booking System (Java + MySQL)
📌 Project Description

The Cinema Ticket Booking System is a console-based Java application that allows users to manage movies and book cinema tickets efficiently using a MySQL database. The project connects Java with MySQL through JDBC, ensuring real-time data storage, updates, and retrieval.

Users can add movies, view the list of movies, book tickets, view bookings, and cancel bookings. The system automatically manages seat availability and ensures that users cannot book more seats than available.

This project highlights important concepts such as CRUD operations, Prepared Statements, JOIN queries, exception handling, and database connectivity—making it ideal for academic mini-projects or beginner-level DBMS applications. 🎓💻

⭐ Key Features
🎬 1. Add Movie

Add new movie name and available seats.

Stores movie details in the database.

📋 2. View Movies

Displays movie ID, name, and available seats.

🎟️ 3. Book Ticket

User selects movie ID, enters name, and seats to book.

Checks availability and books tickets.

Updates the seats automatically.

📝 4. View Bookings

Shows all bookings with:

Booking ID

Movie Name

Customer Name

Seats booked

Uses SQL JOIN for combined data.

❌ 5. Cancel Booking

Cancels a ticket and restores seats back to the movie.

🔚 6. Exit

Safely closes the application.

🛠️ Technologies Used

☕ Java (Core + JDBC)

🗄️ MySQL Database

🔌 JDBC Connector

⚙️ SQL (CRUD operations)

🗂️ Database Structure
🗃️ movies Table
Column	Description
movie_id	🎫 Primary Key (Auto Increment)
movie_name	🎬 Movie Title
available_seats	💺 Seats Remaining
🗃️ bookings Table
Column	Description
booking_id	🔢 Primary Key
movie_id	🎞️ Linked Movie ID
customer_name	👤 Customer Name
seats_booked	🎟️ Tickets Booked
