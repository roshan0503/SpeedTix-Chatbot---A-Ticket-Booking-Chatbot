# 🎟️ SpeedTix Chatbot: AI-Based Ticket Booking System  

**SpeedTix Chatbot** is an interactive, web-based ticket booking system powered by a conversational chatbot interface. The project simplifies the traditional ticketing process by guiding users through event selection, transaction verification, and ticket generation in an intuitive and engaging way.  

---

## 🚀 Project Overview  

The SpeedTix Chatbot replaces complex booking systems with a **chat-driven interface** that allows users to:  
1. Choose events (e.g., movies, concerts, exhibitions).  
2. Enter required details like date, venue, and number of tickets.  
3. Verify payments using a 12-digit transaction ID.  
4. Generate and display a ticket with event details and a QR code.  

The system focuses on improving user engagement, efficiency, and accessibility while functioning as a **frontend-only solution**.  

---

## ⚙️ Features  

- **Chatbot Interface**: A conversational chatbot guides users through the ticket booking process.  
- **Event Selection**: Users can choose event type, venue, and schedule with ease.  
- **Transaction Verification**: A 12-digit Transaction ID validates bookings.  
- **Ticket Generation**: Tickets are displayed dynamically with event details and a QR code.  
- **Session Persistence**: Local storage temporarily retains user data during the booking flow.  
- **User-Friendly UI**: Responsive design with intuitive navigation.  

---

## 🛠️ Tools and Technologies  

- **Frontend**: HTML, CSS, JavaScript  
- **Libraries**:  
  - **Flatpickr**: For date and time selection.  
  - **html2canvas**: Generates downloadable ticket images.  
  - **Font Awesome**: For icons and enhanced UI components.  
- **Data Storage**: Browser local storage (temporary session data).  

---

## 📂 Project Structure  

```plaintext
SpeedTix-Chatbot/
│
├── welcome.html        # Welcome page for the system
├── chatbot.html        # Chatbot interface for event selection
├── payment.html        # Payment verification page
├── ticket.html         # Ticket display with QR code
│
├── css/                # Styling files
│   └── styles.css      # Custom CSS for responsive design
│
├── js/                 # JavaScript files
│   ├── chatbot.js      # Chatbot logic for interactive flow
│   ├── payment.js      # Transaction verification script
│   └── ticket.js       # QR code and ticket display logic
│
├── assets/             # Images, icons, and fonts
└── README.md           # Project documentation

---

🚀 Getting Started
Follow the steps below to set up and run the SpeedTix Chatbot locally:

Prerequisites
Modern web browser (Chrome, Firefox, Edge).
Code editor (e.g., VS Code).
Steps to Run
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/SpeedTix-Chatbot.git
cd SpeedTix-Chatbot
Open welcome.html:

Simply open the welcome.html file in your preferred browser to start the chatbot-driven ticket booking system.
🎥 Project Flow
Welcome Page: Introduction to the chatbot system.
Chatbot Interaction: Users input event details (type, venue, date, etc.) via the chatbot interface.
Payment Verification: Users enter a 12-digit Transaction ID for simulated payment confirmation.
Ticket Generation: A ticket with the Booking ID and QR code is dynamically displayed for download.
📈 Future Scope
Backend Integration: For multi-user support and secure data persistence.
AI-Powered NLP: Enhancing chatbot responses for natural language understanding.
Multi-Platform Support: Expanding to mobile apps and messaging platforms.
Real-Time Updates: Integration with live ticket availability systems.
