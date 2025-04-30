# Hospital-Management-System
This is a simple Hospital Management System desktop application built using Java Swing for the GUI and MySQL for the backend database.

✨ Features:
Patient & Doctor Dropdowns: Select patients and doctors from dynamically populated combo boxes.

Book Appointments: Users can book an appointment by selecting a patient, doctor, and date. The system ensures that:

Both patient and doctor are selected.

The date is in the correct format and not in the past.

The doctor is available on the selected date (no double booking).

Cancel Appointments: Allows users to cancel existing appointments by entering the appointment ID.

Error Handling: Displays appropriate messages for invalid input, unavailable dates, and database errors.

🛠️ Technologies Used:
Java Swing: For creating the graphical user interface.

MySQL: As the database for storing appointment data.

JDBC: To connect Java with the MySQL database.
