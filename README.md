# 🍏 Fruit Management Project 🍎

This is a **React** and **FastAPI** project for managing a list of fruits. It allows users to enter a fruit name via a form and add it to a visible list on the interface.

## 🚀 Technologies Used

- **Frontend**: React with Vite
- **Backend**: FastAPI

## 📥 Installation and Setup

### Backend (FastAPI) 🖥️
1. Clone the repository:
   ```sh
   git clone https://github.com/user/fruit-project.git
   cd fruit-project/backend
   ```
2. Create and activate a virtual environment:
   - On Windows:
     ```sh
     python -m venv venv
     .venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```sh
     python3 -m venv venv
     source venv/bin/activate
     ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the FastAPI server:
   ```sh
   python main.py
   ```
5. The backend will be available at `http://localhost:8000`

### Frontend (React) 🎨
1. Navigate to the frontend directory:
   ```sh
   cd ../frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Run the project:
   ```sh
   npm run dev
   ```
4. The frontend will be available at `http://localhost:5173`

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/db08fcf5-710e-412e-872d-0419dea78238)

## 📌 Usage
1. Open the application in your browser (`http://localhost:5173`).
2. Enter a fruit name in the form.
3. Click "Add Fruit" to include the fruit in the list.
4. View the updated list with the entered fruits.

## 📡 API Endpoints

| Method | Endpoint  | Description               |
|--------|----------|---------------------------|
| GET    | /fruits  | Retrieves the fruit list  |
| POST   | /fruits  | Adds a new fruit          |

## Contact
If you would like to contact me, you can reach me through:
- Email: [dev.lukab@gmail.com](mailto:dev.lukab@gmail.com)
- LinkedIn: [https://www.linkedin.com/in/luka-barbakadze-78b9352b8/](https://www.linkedin.com/in/luka-barbakadze-78b9352b8/)
