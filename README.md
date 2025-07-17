# ✅ TaskZen – A Smart MERN Stack Task Manager

![TaskZen App Demo](https://taskzen04.netlify.app/assets/screenshot-e7b5f00c.png)
*(This is a great screenshot! For even more impact, you could replace it with a GIF showing your app in action.)*

---

### 🌐 Live Demo

- **Frontend (Netlify):** **[https://taskzen04.netlify.app](https://taskzen04.netlify.app)**
- **Backend API (Render):** **[https://taskzen-backend-82od.onrender.com](https://taskzen-backend-82od.onrender.com)**

---

TaskZen is a full-stack MERN web application designed to help users manage their daily tasks with a clean, intuitive, and distraction-free user interface. It provides robust user authentication and a full suite of CRUD (Create, Read, Update, Delete) functionalities for tasks.

---

### ✨ Key Features

- **User Authentication**: Secure user registration and login using JSON Web Tokens (JWT).
- **Password Security**: Passwords are encrypted using `bcryptjs` before being stored.
- **Full Task Management**:
    - **Create**: Add new tasks with a title and description.
    - **Edit**: Modify existing tasks seamlessly.
    - **Delete**: Remove tasks that are no longer needed.
    - **Toggle Completion**: Mark tasks as "Complete" or "Incomplete" with a single click.
- **Filtering & Searching**:
    - Filter tasks by status (All, Completed, Incomplete).
    - Search for specific tasks by their title.
    - Sort tasks to show the most recently created ones first.
- **Responsive Design**: A fluid and modern UI that works perfectly on desktops, tablets, and mobile devices.

---

### 🛠️ Built With

This project was built using the following technologies:

| Frontend | Backend | Database | Authentication |
| :--- | :--- | :--- | :--- |
| ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) | ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) | ![MongoDB](https://img.shields.io/badge/MongoDB-%234EA94B.svg?style=for-the-badge&logo=mongodb&logoColor=white) | ![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens) |
| ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) | ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=white) | Mongoose | Bcrypt.js |
| ![Axios](https://img.shields.io/badge/axios-671ddf?&style=for-the-badge&logo=axios&logoColor=white) | | | |
| ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) | | | |


---

### 🚀 Getting Started

To get a local copy up and running, please follow these simple steps.

#### Prerequisites

You must have the following installed on your machine:
* Node.js (v18.x or later)
* npm (Node Package Manager)
* Git

#### Installation

1.  **Clone the repository**
    ```sh
    git clone [https://github.com/aaditya0004/taskzen-project.git](https://github.com/aaditya0004/taskzen-project.git)
    cd taskzen-project
    ```

2.  **Set up the Backend**
    ```sh
    # Navigate to the backend folder
    cd taskzen-backend

    # Install NPM packages
    npm install

    # Create a .env file in this directory and add the variables below
    touch .env

    # Start the backend server
    npm start
    ```

3.  **Set up the Frontend**
    ```sh
    # Navigate to the frontend folder (from the root directory)
    cd taskzen-frontend

    # Install NPM packages
    npm install

    # Create a .env file in this directory and add the variable below
    touch .env

    # Start the frontend development server
    npm run dev
    ```
The frontend will be available at `http://localhost:5173` and the backend at `http://localhost:5000`.

---

### 🔑 Environment Variables

To run this project, you will need to add the following environment variables to your `.env` files. Remember to replace the placeholder values with your actual secrets.

#### `taskzen-backend/.env`

---

### 📁 API Endpoints

The backend provides the following RESTful API endpoints:

| Method | Endpoint | Description | Requires Auth |
| :--- | :--- | :--- | :--- |
| `POST` | `/api/users/register` | Register a new user | No |
| `POST` | `/api/users/login` | Log in a user and get a JWT | No |
| `GET` | `/api/tasks` | Get all tasks for the logged-in user | Yes |
| `POST` | `/api/tasks` | Create a new task | Yes |
| `PUT` | `/api/tasks/:id` | Update an existing task | Yes |
| `DELETE`| `/api/tasks/:id` | Delete a task | Yes |

---

### 🙋‍♂️ Author

**Aaditya Tyagi**

- **GitHub:** [@aaditya0004](https://github.com/aaditya0004)
- Feel free to connect with me!
