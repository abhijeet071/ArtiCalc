**ArtiCalc**
===

**Overview**
---
ArtiCalc is an innovative web application designed to provide intuitive and efficient calculations through handwritten input recognition.
Built with a robust and scalable front-end and back-end, the application offers seamless user experience and computational features.

**Features**
---
* Handwritten text and drawing recognition for calculations.
* Intuitive and responsive user interface.
* Rich feature set with accurate results for arithmetic problems.
* Accessible across devices with modern design principles.


**Tech Stack**
---


## Frontend
* TypeScript – Ensures scalable and type-safe development.
* JavaScript – Core scripting for dynamic interactions.
* CSS – Styled components and animations.
* HTML – Structured and semantic web layout.
* Vite – Modern and fast build tool for optimized development.


## Backend
* Python – For a robust, reliable server-side application.
* FastAPI – Lightweight and fast back-end framework for API development.
* Pillow – Image manipulation library for processing inputs.
* Uvicorn – ASGI server for high-performance back-end.
* Dotenv – Manages environment variables for security.


## Installation and Setup
Prerequisites
Ensure you have the following installed:

Node.js (v16 or higher)
Python (v3.9 or higher)
pip (Python package manager)


**Steps** : 
Clone the Repository
```
git clone https://github.com/abhijeet071/ArtiCalc.git
```



## Frontend Setup:

Navigate to the frontend directory:
```
cd frontend
```
Install dependencies:
```
npm install
```
Start the development server:
```
npm run dev
```

## Backend Setup:

Navigate to the backend directory:
```
cd backend
```
Create a virtual environment:
```
python -m venv venv
```
```
Windows: venv\Scripts\activate   LINUX/MAC: source venv/bin/activate  
```

## Install dependencies:

```
pip install -r requirements.txt
```
Start the server:
```
python main.py
```

Open the application in your browser at ``` http://localhost:5173 ```.


## Usage
* Draw or input text in the interactive area on the front end.
* Select "Run" to process the drawing or text.
* The resuts are shown on the screen.