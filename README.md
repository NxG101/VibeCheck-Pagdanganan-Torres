# VibeCheck-Pagdanganan-Torres

VibeCheck is a simple Node.js + Express API with a HTML + JavaScript frontend.
The frontend uses buttons to fetch JSON data from the backend and display it on screen.

Project Structure
VibeCheck-<yourname>/
├── backend/
│   ├── index.js
│   └── package.json
└── frontend/
    ├── index.html
    └── app.js

How to Run
1. Install backend dependencies
cd backend
npm install

2. Start the backend server
node index.js


Expected output:

VibeCheck API running at http://localhost:3000

3. Open the frontend

Open frontend/index.html in your browser and click the buttons to test the API.

API Endpoints

GET /api/fortune – returns a random fortune

GET /api/joke – returns a random joke

GET /api/vibe?mood=happy|tired|stressed – returns a mood message

POST /api/smash – increases smash counter

GET /api/smashes – returns current smash count

GET /api/secret?code=411L – returns a secret message if code is correct

All endpoints return JSON.
