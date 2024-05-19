# 📝 Todo List Website

Welcome to the Todo List Website project! This project is built using Python, Django, HTML, and CSS. It allows users to manage their daily tasks efficiently.

## 🌟 Features

- ✅ Add new tasks
- 📝 Edit existing tasks
- ❌ Delete tasks
- 📋 View all tasks

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- Django 3.x or later

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/techy-kunj/todo-list-website.git
    cd todo-list-website
    ```

2. **Create a virtual environment and activate it:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the migrations:**

    ```bash
    python manage.py migrate
    ```

5. **Start the development server:**

    ```bash
    python manage.py runserver
    ```

    Open your browser and navigate to `http://127.0.0.1:8000/todo/` to see the Todo List website in action.

## 🛠️ Usage

- Navigate to the homepage to see your task list.
- Use the form to add new tasks.
- Click on a task to edit it.
- Use the delete button to remove a task from the list.

## 📂 Project Structure

todo-list-website/
├── todo/
│ ├── migrations/
│ ├── static/
│ │ ├── css/
│ │ │ └── styles.css
│ ├── templates/
│ │ └── todo/
│ │ └── index.html
│ ├── init.py
│ ├── admin.py
│ ├── apps.py
│ ├── models.py
│ ├── tests.py
│ └── views.py
├── todo_site/
│ ├── init.py
│ ├── settings.py
│ ├── urls.py
│ ├── wsgi.py
├── manage.py
└── requirements.txt

## 🎨 Customization

You can customize the appearance of the Todo List website by modifying the CSS file located at `todo/static/css/styles.css`.

## 💬 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## 📄 License

This project is licensed under the MIT License.

<div style="text-align: center;">
  <img src="[![image](https://github.com/TechyKunj/Todo/assets/120329440/7e3ed40f-d058-4cd5-a790-974baa78ee4c)](https://1drv.ms/i/s!AtsCbJYwVL-UvF2qb4FugaJNLI-G?e=xgORZn)" alt="Todo List Animation" width="300">
</div>

Happy Coding! 💻✨
