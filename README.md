# LeetCode Evaluator
LeetCode Evaluator is a web application that allows users to fetch and analyze their LeetCode profile statistics. By entering a LeetCode username, the application retrieves data such as total problems solved, ranking, and difficulty-wise breakdown (Easy, Medium, Hard) using the LeetCode API.

## Project Structure
The project consists of two main parts:

### Frontend (excelr-leetcode-evaluator)
- Built with React.js (using Vite for fast development).
- Provides an interactive UI to input a LeetCode username and display the fetched data.
### Backend (leetcode_api-master)
- Built with Node.js.
- Integrates with an external LeetCode API to fetch user statistics.

## Features
- Fetch LeetCode User Data – Get details on problems solved, rankings, and question difficulty levels.
- React.js Frontend – Modern UI with a smooth user experience.
- Node.js Backend – Efficient data handling and API communication.
- Fast Performance – Utilizes Vite for rapid frontend development.
- REST API Integration – Connects to an external LeetCode API for real-time updates.

## Prerequisites
Ensure you have the following installed:

- Node.js (version 14 or higher)
- npm or yarn
- VS Code (or any preferred code editor)
- A stable internet connection (for fetching data from LeetCode API).
  
## Installation and Setup
### 1. Clone the repository
```bash
git clone https://github.com/Spidy111/LeetCode-Evaluator-Project.git
cd LeetCode Evaluator
```
### 2. Setup Backend (leetcode_api-master)
```bash
cd leetcode_api-master
npm install
```
#### Run the Backend
```bash
node index.js
```
The backend server will start on `http://localhost:3000`.

### 3. Setup Frontend (excelr-leetcode-evaluator)
```bash
cd ../excelr-leetcode-evaluator
npm install
```
#### Run the Frontend
```bash
npm run dev
```
The application will be available at `http://localhost:5173`.

### 4.Add data in the document
Add `leetcode_id`, `username` and `email` in the `demo.xlsx` document.

### 5. Upload the document
- Upload the `demo.xlsx` document.
- Click on generate the report.
- Download the report.

## API Configuration
The frontend communicates with the backend via API. Ensure that the backend is running and update the API URL in the frontend's environment file (.env):

```ini

VITE_API_BASE_URL=http://localhost:5000
```
## Build and Deploy
### Frontend Deployment
To build the frontend for production:

```bash
npm run build
```
The optimized files will be in the dist directory. You can deploy them on:

- Vercel
- Netlify
- GitHub Pages
- Firebase Hosting

### Backend Deployment
For production deployment, host the Node.js backend on:
- Render
- Vercel
- Heroku
- AWS EC2
  
## Resources
- React.js Documentation
- Vite Documentation
- Node.js Documentation
- LeetCode API Reference
