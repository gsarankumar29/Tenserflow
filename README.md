**Technologies Used**
Frontend: React.js
Backend: Node.js (Express.js)
Authentication: Google OAuth
Email Service: Postmark API

STEPS FOR SETTING UP:

1) ADD .ENV FOR BOTH SERVER AND CLIENT
     **CONTENT IN CLIENT**
   REACT_APP_API_URL = http://localhost:8080
   REACT_APP_POSTMARK_API_TOKEN= YOUR POSYMARK API TOKEN
    **CONTENT IN SERVER**
   CLIENT_ID = YOUR CLIENT_ID.
   CLIENT_SECRET = YOUR CLIENT_SECRET.
   CLIENT_URL = http://localhost:3000/

   2) INSTALL NECESSARY THINGS
      
      **FOR BACKEND**
npm init -y
npm install express mongoose passport passport-google-oauth20 body-parser postmark

        **FOR FRONTEND**
npx create-react-app CLIENT
cd CLIENT
npm install axios

**Running the Application:**

          Start the Backend Server:
cd communication-backend
npm start
The backend server will start running on http://localhost:8080.

            Start the Frontend Development Server:
cd communication-frontend
npm start

The frontend development server will start running on http://localhost:3000.
Access the Application:
Open your web browser and go to http://localhost:3000 to access the application.

   
