
# PrepWise AI — Intelligent Interview Preparation Platform

PrepWise AI is an AI-powered interview preparation platform designed to help candidates prepare for technical interviews, organize their interview reports, and generate resumes in PDF format.

The platform combines a React-based frontend with a Node.js backend and generative AI integration to provide an interactive interview preparation experience.

## Features

- **AI-Powered Interview Preparation:** Generate interview preparation content using a generative AI model.
- **Interview Reports:** Generate and access interview reports through the application.
- **Resume PDF Generation:** Generate and download resumes in PDF format.
- **Interactive User Interface:** Navigate interview preparation features through a React frontend.
- **REST API Integration:** Communicate between the frontend and backend through API endpoints.
- **Database Integration:** Store application data using MongoDB, where configured.
- **Authentication:** Supports the authentication features implemented in the application.

## Tech Stack

### Frontend
- React.js
- JavaScript
- HTML5
- CSS3

### Backend
- Node.js
- Express.js
- REST APIs

### Database and AI
- MongoDB
- Google Gemini API

### Development Tools
- Git
- GitHub
- Visual Studio Code
- npm

## Project Structure

```text
PrepWise-AI/
├── Backend/
│   └── src/
│       └── services/
├── Frontend/
│   └── src/
│       └── features/
│           └── interview/
│               ├── hooks/
│               └── pages/
├── .gitignore
└── README.md
```

*The structure above is a simplified overview. Refer to the repository for the complete project structure.*

## Getting Started

### Prerequisites

Install the following before running the application:

- Node.js and npm
- Git
- A MongoDB database, if required by your configuration
- A Google Gemini API key

### 1. Clone the Repository

```bash
git clone https://github.com/SonaliYedage/PrepWise-AI.git
cd PrepWise-AI
```

### 2. Configure the Backend

Open a terminal in the backend directory:

```bash
cd Backend
npm install
```

Create a `.env` file using the environment variables required by the backend.

Example:

```env
PORT=5000
GOOGLE_GENAI_API_KEY=your_gemini_api_key
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

**Important:** These variable names are examples. Check the backend source code to confirm the exact names required by your application. Add real credentials only to your local `.env` file, never to GitHub.

Start the backend using the development script configured in `Backend/package.json`. For example:

```bash
npm run dev
```

### 3. Configure the Frontend

Open another terminal:

```bash
cd Frontend
npm install
```

Configure the frontend API base URL using the environment variable expected by the application.

Start the frontend using its configured development script. For example:

```bash
npm run dev
```

Open the local URL printed in the terminal.

*Available scripts and environment variable names depend on the project's configuration.*

## Environment Variables

Configure the following as needed:

| Variable | Purpose |
|---|---|
| `GOOGLE_GENAI_API_KEY` | Access the generative AI API |
| `MONGO_URI` | Connect to the MongoDB database |
| `JWT_SECRET` | Sign authentication tokens, if applicable |
| `PORT` | Configure the backend server port |

Never commit API keys, database credentials, or authentication secrets.

## Deployment

The application can be deployed using separate frontend and backend hosting services.

- **Frontend:** Vercel
- **Backend:** Render
- **Database:** MongoDB Atlas, if required

Production deployment requires configuring environment variables, the frontend's backend API URL, CORS, and the hosted database connection.

**Live Demo:** Coming soon.

## Learning Outcomes

- Full-stack application development using React and Node.js.
- Integrating generative AI into a web application.
- Working with REST APIs and asynchronous requests.
- Managing application configuration and environment variables.
- Generating downloadable PDF documents.
- Using Git and GitHub for source code management.

## Author

**Sonali Vijay Yedage**

- GitHub: [@SonaliYedage](https://github.com/SonaliYedage)

---

*PrepWise AI — Prepare smarter. Interview with confidence.*
