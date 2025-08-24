# Full-Stack Online Code IDE

An online code editor and compiler built with a full-stack architecture.  
This project provides a web-based IDE where users can write, run, and test code in different programming languages directly in the browser.


##  Features
- Write and run code in multiple programming languages
- Real-time code execution using backend APIs
- Full-stack architecture (Frontend + Backend)
- Modern UI for seamless coding experience
- Extensible for adding more languages and features


##  Project Structure
Full-Stack-Online-Code-IDE/
│── client/ # Frontend (React / Next.js)
│── server/ # Backend (Node.js / Express)
│── package.json # Root configuration
│── README.md


---

## 🛠️ Prerequisites
Make sure you have the following installed:
- [Node.js](https://nodejs.org/) (>= 16.x recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Docker](https://www.docker.com/) (optional, if using containerized execution)


## Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/anilhosalli18/Online-code-IDE-Using-MERN-stack.git
cd Online-code-IDE-Using-MERN-stack


## intall for backend
cd server
npm install


## Frontend
cd ../client
npm install

## create .env inside the server/folder
PORT=5000
NODE_ENV=development
# Add any API keys or execution service configs here

## inside client folder/.env file
REACT_APP_API_URL=http://localhost:5000

## START BACKEND
cd server
npm start

## START FRONTEND OPEN NEW TERMINAL
cd client
npm start

## Then App will running
Frontend: http://localhost:3000
Backend:  http://localhost:5000

Option 1: Deploy with Docker

## Build Docker images:
docker-compose build

## Start containers:
docker-compose up -d

#then
Access the app at http://localhost:3000

