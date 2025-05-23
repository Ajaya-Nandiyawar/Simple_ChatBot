# Simple Chatbot UI

This project is a simple chatbot user interface built with modern web technologies. It serves as the frontend for a chatbot application.

## Features

- Clean and responsive design.
- Easy integration with chatbot backends.
- Customizable UI components.

## Installation

### 1. Backend Setup

#### Create a virtual environment (optional but recommended):
```bash
python -m venv venv
```

#### Activate the virtual environment:
On Windows:
```bash
venv\Scripts\activate
```
On macOS/Linux:
```bash
source venv/bin/activate
```

#### Install the required Python packages:
```bash
pip install -r requirements.txt
```

#### Start the Backend Server:
Ensure the `.env` file contains a valid `GROQ_API_KEY`.

Run the FastAPI server:
```bash
uvicorn main:app --reload
```
The backend will start on `http://localhost:8000`.

### 2. Frontend Setup

#### Install Dependencies:
Open a new terminal and navigate to the `frontend/chatbotui` directory:
```bash
cd frontend/chatbotui
```

Install the required Node.js packages:
```bash
npm install
```

## Usage

Start the development server:
```bash
npm start
```
The application will be available at `http://localhost:3000`.

#   S i m p l e _ C h a t B o t  
 