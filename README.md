<img width="1700" height="460" alt="github-header-banner (1)" src="https://github.com/user-attachments/assets/df232d2d-578b-42d7-b465-18dfc61d5387" />

<p align="center">
  <a href="[https://skillicons.dev](https://skillicons.dev)">
    <img src="[https://skillicons.dev/icons?i=git,vscode,docker,py,arch,postman,windows,mysql](https://skillicons.dev/icons?i=git,vscode,docker,py,arch,postman,windows,mysql)" />
  </a>
</p>

<p align="center">
  <img src="[https://img.shields.io/badge/Status-Completed-success?style=for-the-badge](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)" />
  <img src="[https://img.shields.io/badge/Python-3.12+-blue?style=for-the-badge&logo=python&logoColor=white](https://img.shields.io/badge/Python-3.12+-blue?style=for-the-badge&logo=python&logoColor=white)" />
  <img src="[https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)" />
  <img src="[https://img.shields.io/github/repo-size/Sera-DAI/tasks-creator?style=for-the-badge](https://img.shields.io/github/repo-size/Sera-DAI/tasks-creator?style=for-the-badge)" />
  <img src="[https://img.shields.io/github/last-commit/Sera-DAI/tasks-creator?style=for-the-badge](https://img.shields.io/github/last-commit/Sera-DAI/tasks-creator?style=for-the-badge)" />
</p>

---

## 📝 About

> [!NOTE]
> This is a simple application developed to apply my personal studies regarding the core concepts of Flask, REST APIs, and CRUD operations. The main focus of this project is to improve my skills in Python backend development.

> [!IMPORTANT]
> Since this project was designed for learning purposes and to practice fundamental architecture, it handles data persistence temporarily in-memory (using Python lists) or through lightweight integration, making it straightforward to run and experiment with.

## 📖 Concept

The application allows users to manage a task workflow via standard HTTP requests (e.g., creating tasks, updating their status, and deleting them). You can easily interact with the application using API clients like **Postman** or `curl`.

## 📂 Dependencies

The project relies on the following main libraries:
* **Flask** — Core microframework for routing and handling HTTP requests.
* **Flask-SQLAlchemy** — Database ORM integration (where applicable).
* **Flask-Cors** — Cross-Origin Resource Sharing support for API fetching.
* **Werkzeug** — WSGI web application library.
* **Pytest** — Framework for running automated tests.

## 🛠️ How to Run the Application

Follow the steps below to set up and run this application on your local machine.

### 1. Pre-requirements

Make sure you have Python 3.12 or higher installed. You can check your current version by running:

```bash
python --version  # or python3 --version
```

If you don't have Python installed, download it from the [Official Website](https://www.python.org/downloads/).

### 2. Clone the Repository

Clone this repository to your preferred local directory and navigate into the project folder:

```bash
git clone https://github.com/Sera-DAI/tasks-creator.git
cd tasks-creator
```

### 3. Create a Virtual Environment

Isolate the project dependencies by creating and activating a Python virtual environment:

**On Windows:**
```bash
python -m venv .venv
.venv\Scripts\activate
```

**On Linux/macOS:**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 4. Install Dependencies

Install all the required packages listed in the `requirements.txt` file:

```bash
pip install -r requirements.txt
```
 
## 🌐 API Documentation

You can test and explore the available API endpoints directly via Postman:
[![Run in Postman](https://run.pstmn.io/button.svg)](https://documenter.getpostman.com/view/52076750/2sBXcAHMui)

## 🖥️ Usage

1. Start the Flask local development server.
2. Use Postman or any API client to send HTTP requests (`GET`, `POST`, `PUT`, `DELETE`) to interact with your tasks.
3. Once you are done, you can stop the server by pressing `Ctrl + C` in your terminal.

> [!IMPORTANT]
> If your current setup uses in-memory storage (Python lists), stopping the server application will wipe the stored tasks. Remember to keep the instance running while testing!
