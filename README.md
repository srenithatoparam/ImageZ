# ImageZ

ImageZ is an AI-powered image generation web application that allows users to create images from text prompts, manage image galleries, and explore creative visuals. Built using the MERN stack, it leverages modern technologies for fast, interactive, and scalable performance.

## Features

- **AI Image Generation:** Generate images from custom text prompts using AI models.
- **User Authentication:** Secure signup and login with JWT-based authentication.
- **Image Gallery Management:** Save, view, and manage your generated images.
- **Responsive UI:** Works smoothly on desktop, tablet, and mobile devices.
- **Easy Deployment:** Built on the MERN stack for quick setup and deployment.

## Tech Stack

- **Frontend:** React, Vite, TailwindCSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **AI Integration:** OpenAI or any AI image generation API


# 🚀 Installation & Setup
Prerequisites

Node.js (v16 or higher)
MongoDB (local or cloud instance)
OpenAI API key (or alternative AI service)

Step 1: Clone the Repository
bashgit clone https://github.com/srenithatoparam/ImageZ.git
cd ImageZ
Step 2: Install Dependencies
bash# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install
Step 3: Environment Configuration
Create a .env file in the server folder:
env# Server Configuration
PORT=4000
NODE_ENV=development

# Database
MONGO_URI=your_mongodb_connection_string

# Authentication
JWT_SECRET=your_jwt_secret_key_here
JWT_EXPIRE=30d

# AI Service
OPENAI_API_KEY=your_openai_api_key

# Frontend URL
VITE_BACKEND_URL=http://localhost:4000
Create a .env file in the client folder:
envVITE_BACKEND_URL=http://localhost:4000
Step 4: Start the Application
Development Mode
bash# Start backend server (from server directory)
cd server
npm run dev

# Start frontend (from client directory, in a new terminal)
cd client
npm run dev
Production Mode
bash# Build frontend
cd client
npm run build

# Start backend with production build
cd ../server
npm start
Step 5: Access the Application
Open your browser and visit http://localhost:5173 to use the application.
📖 Usage
Getting Started

Sign Up: Create a new account or log in with existing credentials
Generate Images: Enter a descriptive text prompt and click "Generate"
Gallery Management: View all your generated images in the gallery
Download & Share: Save your favorite creations locally

Example Prompts

"A majestic mountain landscape at sunset with purple skies"
"A futuristic cityscape with flying cars and neon lights"
"A cute robot reading a book in a cozy library"
"Abstract art with vibrant colors and geometric shapes"

## 🏗️ Project Structure
ImageZ/
├── client/                
│   ├── public/            
│   ├── src/
│   │   ├── components/    
│   │   ├── pages/         
│   │   ├── utils/         
│   │   ├── context/       
│   │   └── styles/       
│   ├── package.json
│   └── vite.config.js
├── server/                
│   ├── controllers/      
│   ├── middleware/      
│   ├── models/            
│   ├── routes/            
│   ├── utils/             
│   ├── config/            
│   └── server.js          
├── README.md
└── LICENSE
## 🔌 API Endpoints
# Authentication

POST /api/auth/register - User registration
POST /api/auth/login - User login
GET /api/auth/profile - Get user profile

# Image Generation

POST /api/images/generate - Generate image from prompt
GET /api/images/gallery - Get user's image gallery
DELETE /api/images/:id - Delete specific image

# 🚢 Deployment
Heroku Deployment

Create a Heroku app
Set environment variables in Heroku dashboard
Connect your GitHub repository
Enable automatic deploys

# Vercel Deployment (Frontend)

Connect your GitHub repository to Vercel
Set environment variables
Deploy with automatic builds

# MongoDB Atlas

Create a cluster on MongoDB Atlas
Get connection string
Add to your environment variables

# 🤝 Contributing
Contributions are welcome! Here's how you can help:

Fork the repository
Create a feature branch
bashgit checkout -b feature/amazing-feature

Commit your changes
bashgit commit -m 'Add amazing feature'

Push to the branch
bashgit push origin feature/amazing-feature

Open a Pull Request

Development Guidelines

Follow existing code style and conventions
Write clear, descriptive commit messages
Add comments for complex logic
Test your changes thoroughly
Update documentation as needed

# 🐛 Bug Reports & Feature Requests

Bug Reports: Create an issue
Feature Requests: Start a discussion

# 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
MIT License

Copyright (c) 2024 Srenitha Toparam

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
🙏 Acknowledgments

OpenAI for providing the AI image generation API
React Team for the amazing framework
MongoDB for the reliable database solution
TailwindCSS for the utility-first CSS framework
Vite for the fast build tool

## 📞 Support

GitHub Issues: Report bugs or request features
Email: srenithatoparam4@gmail.co


Made by Srenitha Toparam
