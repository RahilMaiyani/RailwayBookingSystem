# 🚆 Railway Booking System

A **Python Railway Booking System** using **MySQL (via XAMPP)** for backend data management, with interactive command-line functionalities and analytics reports. Built for educational and internship projects to showcase database handling, booking workflows, and data visualization.

---

## 📂 Project Structure

```
RailwayBookingSystem/
├── fullcode.ipynb              # Main notebook with booking, payment, and reporting logic
├── RaillwaySystem.ipynb       # Additional analysis and experiments
├── RailwayBookingSystem.pptx   # Presentation slides explaining the project
├── Reports/                    # Generated analytics reports
├── Tickets/                    # Ticket files with booking details
├── .gitignore                  # Files to exclude from version control
```

---

## ✅ Features

**Passenger Management**
- Register, search, and delete passengers
- Validate user details like age and contact information

**Train Management**
- Add and manage trains, schedules, and pricing
- Search and remove trains as needed

**Booking System**
- Book tickets with seat availability checks
- Handle payments through Cash, Card, UPI, and Net Banking
- Generate ticket files with booking details
- Check and cancel bookings

**Reports**
- Generate bestseller and most-booked trains reports
- Save analytics as files for review

**Data Storage**
- MySQL database (via XAMPP) for storing users, trains, bookings, and payments
- Structured data interactions for real-time operations

---

## 🛠 Technologies Used

- Python 3.x  
- Jupyter Notebook  
- MySQL via **XAMPP**  
- Libraries: `mysql-connector-python`, `pandas`, `numpy`, `matplotlib`, `seaborn` (optional)

---

## 📥 Setup Instructions

1. **Install XAMPP**
   - Download and install XAMPP from https://www.apachefriends.org/
   - Start the MySQL module

2. **Clone the repository**
   ```
   git clone https://github.com/<your-username>/Railway-Booking-System.git
   ```

3. **Install Python dependencies**
   ```
   pip install mysql-connector-python pandas numpy matplotlib
   ```

4. **Setup MySQL database**
   - Open phpMyAdmin at `http://localhost/phpmyadmin/`
   - Create a database named `railway_booking_system`
   - Create tables (`user`, `trains`, `bookings`, `payments`) as defined in the notebook or schema
   - Insert sample data if needed

5. **Run the notebook**
   ```
   jupyter notebook fullcode.ipynb
   ```
   Follow the prompts to manage trains, passengers, bookings, and reports.

---

## ⚙️ MySQL Configuration

- Use **XAMPP** to run MySQL locally.
- Access phpMyAdmin via `http://localhost/phpmyadmin/` to create databases and tables.
- Use proper credentials (username, password) in your notebook connection settings.
- Avoid hardcoding credentials; use configuration files or environment variables for security.

---

## 📂 Reports and Tickets

- Reports are saved in the `Reports/` folder as charts or analytics files.
- Tickets are generated in the `Tickets/` folder as text files containing booking details.

---

## 📈 Future Improvements

- Provide `.sql` files for easier database setup
- Secure credentials using environment variables
- Build a web or GUI interface for improved interaction
- Enhance analytics with advanced forecasting models
- Add automated email notifications for bookings

---

This project offers a practical way to learn and demonstrate database integration, Python scripting, and data visualization in a controlled environment, suitable for coursework and internships.
