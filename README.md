HYDROPONIC SYSTEM🌳🌲 A web-based application to monitor and manage a hydroponic system using real-time sensor data. It includes a responsive front end, backend integration with MongoDB, and a contact form that stores messages in a database.

Feature Realtime and historical sensor data display (e.g., pH, EC, temperature, etc.)

Responsive layout with dark mode support Contact form storing user messages in MongoDB Clean and minimal UI with modern CSS Easy to deploy and extend PROJECT STRUCTURE hydroponic-system/ ├── index.html # Home Page ├── sensor.html # Sensor Data Page ├── guidebook.html # Guidebook / Info Page ├── contact.html # Contact Form Page ├── style.css # Main CSS Styles ├── server.js # Node.js Express Backend ├── package.json # Project Dependencies

🧰 Tech Stack Frontend**: HTML5, CSS3, JavaScript Backend**: Node.js, Express.js Database**: MongoDB (MongoDB Atlas or local MongoDB)

📦 Installation & Setup Clone the repository**

bash git clone https://github.com/brajesh01/hydroponic-system.git cd hydroponic-system

Install dependencies bash Copy Edit npm install

Start the backend server node server.js By default, it runs at http://localhost:5000.

📬 Submitting Contact Forms The form in contact.html sends data to the backend at http://localhost:5000/api/contact, and the messages are saved in the contacts collection of your MongoDB.

🌐 Hosting Locally Just open the .html files in a browser. If using VS Code, you can install the "Live Server" extension to run them locally.

✨ Future Improvements Add Firebase integration for sensor data

Include charts and historical trends

Authentication for admin

Mobile optimization
