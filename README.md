🧱 1. How to Clone and Run the Project
Prerequisites
Python 3.9+

pip

Virtualenv (optional but recommended)

Git

Clone the Repo
bash
Copy
Edit
git clone https://github.com/ayasalam0/AIT-Python.git
cd AIT-Python
Setup Virtual Environment (optional)
bash
Copy
Edit
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
Setup Environment Variables
Create a .env file in the root directory using the example:

bash
Copy
Edit
cp .env.example .env
Then update the .env file with your local settings.

Run Migrations and Start Server
bash
Copy
Edit
python manage.py migrate
python manage.py runserver
Visit http://127.0.0.1:8000

🌿 2. Branch Naming Rules
We follow a branch naming convention to keep our git history clean:

Type	Format	Example
Feature	feature/<short-description>	feature/user-auth
Bugfix	bugfix/<short-description>	bugfix/fix-task-status-bug
Refactor	refactor/<short-description>	refactor/clean-views
Documentation	docs/<short-description>	docs/update-readme

Always branch from dev unless instructed otherwise.

🗂 3. Task Assignment Process
Tasks will be assigned in the GitHub Issues tab or in the GitHub Projects board.

Each intern should:

Pick/receive a task.

Create a branch.

Work on the task and commit regularly.

Open a Pull Request to dev branch.

Wait for review and merge.

Use clear commit messages:
git commit -m "Add login form to users app"

🛠 4. Tools and Extensions
.env config: Keeps sensitive/local settings out of source control.

GitHub Actions CI: Automatically runs tests on push (configured in .github/workflows).

Pre-commit hooks (optional): Linting & formatting checks before each commit (to be added later).

PostgreSQL support: Future-ready for production database.





# 🗂️ Task Management Web App

A Trello-like collaborative task management tool built with Python and Flask/Django.

## 🌟 Features

- User Authentication
- Create and Manage Boards
- Create Tasks and Assign Status (TODO / In Progress / Done)
- Activity Log of Actions
- Drag-and-Drop UI (optional)
- RESTful APIs

## 🛠 Tech Stack

- **Frontend**: HTML, CSS, JS, Bootstrap / Jinja Templates
- **Backend**: Flask or Django REST
- **Database**: SQLite / PostgreSQL
- **CI/CD**: GitHub Actions
- **Deployment**: Heroku / Render

## 👥 Team Roles

| Role       | Member(s)              |
|------------|------------------------|
| Frontend   |      |
| Backend    |      |
| Database   |            |
| DevOps/QA  |              |

## 🚀 Getting Started

### Prerequisites

- Python 3.10+
- pip / pipenv
- Git

 

 
