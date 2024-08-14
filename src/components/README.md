actions performed on the bots are reflected both in the UI and on the server.

Getting Started
Prerequisites To get started, you'll need the following installed on your machine:

 Git Installation Clone the Repository:

bash code git clone https://github.com/Yasir-moha/phase-2-code-challenge-Bot-battlr

bash Copy code npm install Set Up the JSON Server: Create a db.json file in the root of your project and populate it with the provided bot data.

Start the JSON Server:

bash Copy code json-server --watch db.json --port 8001

Running the App
Start the React application:

bash Copy code npm start Visit http://localhost:3000 in your browser to see the app in action.

Usage
Bot Collection The main page displays a list of all available bots. Each bot's details are displayed, including an avatar, name, class, health, damage, armor, and catchphrase. Click on a bot to enlist it into your army.

Your Bot Army
Your selected bots will appear in the "Your Bot Army" section. Click on a bot in your army to release it back to the collection. Click the red "x" button to discharge a bot permanently from your army and the server.

Advanced Features
Sort Bots: Sort bots by health, damage, or armor to better strategize your army composition. Filter Bots by Class: Filter bots based on their class (Support, Medic, Assault, etc.) to focus on specific types. Bot Details View: View more detailed information about each bot in a separate view.

Technologies Used
React: JavaScript library for building user interfaces. JSON Server: Simple backend for RESTful API mocking. CSS: Styling for the application.