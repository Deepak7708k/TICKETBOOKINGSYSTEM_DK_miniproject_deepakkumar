🎟️ Advanced Ticket Booking Web App
📌 Overview
This is a simple and interactive Ticket Booking Web Application built using HTML, CSS, and JavaScript.
Users can select an event, choose seats, calculate total cost, and download a ticket as a PDF.
🚀 Features
🧑 User-friendly booking form
🎭 Multiple event options (Movie, Concert, Bus, Train)
📅 Date selection
💺 Interactive seat selection (20 seats)
💰 Automatic price calculation
✅ Booking confirmation display
📄 Download ticket as PDF
💾 Data stored using Local Storage
🛠️ Technologies Used
HTML5 – Structure of the app
CSS3 – Styling and animations
JavaScript (Vanilla JS) – Functionality
jsPDF Library – PDF generation
📂 Project Structure

project-folder/
│── index.html   # Main application file
⚙️ How It Works
1. Seat Generation
20 seats are dynamically created using JavaScript.
Users can click to select/deselect seats.
2. Booking Process
User enters:
Name
Event
Date
Seats
Total price is calculated based on event type.
3. Data Storage
Booking details are saved in localStorage:
JavaScript
localStorage.setItem("booking", JSON.stringify(booking));
4. PDF Download
Uses jsPDF to generate and download the ticket.
💵 Pricing Table
Event
Price (₹)
Movie
150
Concert
500
Bus
200
Train
300
▶️ How to Run
Copy the code into a file named index.html
Open it in any browser
Fill the form and select seats
Click Book Now
Click Download Ticket to get PDF
📸 UI Highlights
Gradient background 🎨
Smooth animations ✨
Responsive design 📱
Interactive seat selection 🎯
⚠️ Limitations
No backend (data not stored permanently)
No payment integration
No seat availability tracking across users
🔮 Future Improvements
Add login/signup system
Connect to database (Firebase / MySQL)
Real-time seat availability
Payment gateway integration
QR code in ticket
👨‍💻 Author
Developed by Deepakkumar
Institution: KIT Kalaignarkarunanidhi Institute of Technology
