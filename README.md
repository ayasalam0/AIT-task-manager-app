# 🗂️ Task Management Web App

A Trello-like collaborative task management tool built with Python and Flask/Django.

## 🌟 Features

* User Authentication
* Create and Manage Boards
* Create Tasks and Assign Status (TODO / In Progress / Done)
* Activity Log of Actions
* Drag-and-Drop UI (optional)
* RESTful APIs

## 🛠 Tech Stack

* **Frontend:** HTML, CSS, JS, Bootstrap / Jinja Templates
* **Backend:** Flask or Django REST
* **Database:** SQLite / PostgreSQL
* **CI/CD:** GitHub Actions
* **Deployment:** Heroku / Render

## 🚀 Getting Started

### Prerequisites

* Python 3.9+ (Python 3.10+ recommended for development)
* pip
* Virtualenv (optional but recommended)
* Git

### 1. How to Clone and Run the Project

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/ayasalam0/AIT-Python.git](https://github.com/ayasalam0/AIT-Python.git)
    cd AIT-Python
    ```

2.  **Setup Virtual Environment (optional but recommended):**
    ```bash
    python -m venv env
    source env/bin/activate # On Windows: env\Scripts\activate
    ```

3.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Setup Environment Variables:**
    Create a `.env` file in the root directory by copying the example:
    ```bash
    cp .env.example .env
    ```
    Then, update the `.env` file with your local settings.

5.  **Run Migrations and Start Server:**
    ```bash
    python manage.py migrate
    python manage.py runserver
    ```
    Visit `http://127.0.0.1:8000` in your browser.

## 🌿 2. Branch Naming Rules

We follow a branch naming convention to keep our Git history clean:

| Type        | Format             | Example                      |
| :---------- | :----------------- | :--------------------------- |
| Feature     | `feature/<name>`   | `feature/user-auth`          |
| Bugfix      | `bugfix/<name>`    | `bugfix/fix-task-status-bug` |
| Refactor    | `refactor/<name>`  | `refactor/clean-views`       |
| Documentation | `docs/<name>`      | `docs/update-readme`         |

**Always branch from `dev` unless instructed otherwise.**

## 🗂 3. Task Assignment Process

Tasks will be assigned in the GitHub Issues tab or in the GitHub Projects board.

Each intern should:

1.  Pick/receive a task.
2.  Create a branch according to the naming rules.
3.  Work on the task and commit regularly. Use clear commit messages (e.g., `git commit -m "Add login form to users app"`).
4.  Open a Pull Request to the `dev` branch.
5.  Wait for review and merge.

## 🛠 4. Tools and Extensions

* **.env config:** Keeps sensitive/local settings out of source control.
* **GitHub Actions CI:** Automatically runs tests on push (configured in `.github/workflows`).
* **Pre-commit hooks (optional):** Linting & formatting checks before each commit (to be added later).
* **PostgreSQL support:** Future-ready for production database.

## 👥 Team Roles

| Role       | Member(s) |
| :--------- | :-------- |
| Frontend   |           |
| Backend    |           |
| Database   |           |
| DevOps/QA  |           |
