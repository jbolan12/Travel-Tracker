# Travel-Tracker

Country Tracker API
This API allows users to track countries they have visited. It connects to a PostgreSQL database to store and retrieve country data.

-Features:
View the list of countries marked as visited.
Add a new country to the visited list.
Error handling for duplicate entries and invalid country names.
Setup Instructions
Prerequisites
Node.js and npm installed
PostgreSQL database running
dotenv package for environment variable management

-Installation
Clone the repository:

bash
git clone (https://github.com/jbolan12/Travel-Tracker)
cd country-tracker

-Install dependencies:

bash
npm install

-Set up environment variables:

Create a .env file in the project root directory and add your PostgreSQL database credentials:

plaintext
Copiar código
DB_USER=postgres
DB_HOST=localhost
DB_NAME=postgres
DB_PASSWORD=yourpassword
DB_PORT=5432
Run the application:

bash
node index.js
The server should be running at http://localhost:3000.

->Folder Structure
bash
Copiar código
├── public/               # Static files (CSS, JS, images)
├── views/                # EJS templates
├── index.js              # Main server file
└── .env                  # Environment variables file (not tracked in Git)

-Usage:
Home Page: Access at http://localhost:3000 to view the list of visited countries.
Add a Country: Use the form to add a new country. The app will display a message if the country is already in the visited list or doesn’t exist.

-Example Environment Variables (.env)

plaintext
DB_USER=postgres
DB_HOST=localhost
DB_NAME=postgres
DB_PASSWORD=yourpassword
DB_PORT=5432

Note: Ensure the .env file is included in .gitignore to keep your credentials secure.
