![image](https://github.com/user-attachments/assets/3f08bffb-698b-4809-ab98-4372be1bf709)
![Uploading image.png…]()
# Full-Stack Django Project

This is a full-stack web application built using Django that mimics a simple Twitter-like functionality. Users can register, log in, create, edit, and delete tweets. The project demonstrates a robust backend-driven implementation with an integrated front-end.

---

## Features

### **User Management**
- User registration with validation.
- Secure login and logout.
- Password reset functionality.

### **Tweet Management**
- Create, edit, and delete tweets.
- View all tweets by users.
- Manage personal tweets.

### **Frontend**
- Responsive UI for an enhanced user experience.
- Interactive pages using HTML, CSS, and JavaScript.

---

## Technologies Used

- **Backend**: Django Framework (Python)
- **Frontend**: HTML, CSS, JavaScript (integrated with Django templates)
- **Database**: SQLite (default)
- **Version Control**: Git and GitHub

---

## Prerequisites

Before running the application, make sure you have the following installed:

- Python 3.8 or higher
- pip (Python package manager)
- Virtualenv (recommended)

---

## Installation and Setup

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/Sheesikram/fullStackDjangoProject.git
   cd fullStackDjangoProject
   ```

2. **Create a Virtual Environment**  
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install Dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply Database Migrations**  
   ```bash
   python manage.py migrate
   ```

5. **Run the Development Server**  
   ```bash
   python manage.py runserver
   ```

6. **Access the Application**  
   Open your browser and navigate to [http://127.0.0.1:8000/](http://127.0.0.1:8000/).

---

## Project Structure

```
fullStackDjangoProject/
│
├── app/                   # Main application containing models, views, templates
├── fullStackDjangoProject/ # Project configuration and settings
├── static/                # Static assets (CSS, JS, images)
├── templates/             # HTML templates
├── db.sqlite3             # SQLite database
├── manage.py              # Django management script
└── requirements.txt       # Project dependencies
```

---

## Usage Instructions

1. **Sign Up**  
   Create a new account using the registration page.

2. **Log In**  
   Log in with your credentials to access the main dashboard.

3. **Tweet Management**  
   - Create a tweet via the "Create Tweet" button.
   - Edit or delete existing tweets.

4. **Profile Management**  
   Update user details through the profile page.

---

## Future Enhancements

- Add a "Like" and "Comment" feature for tweets.
- Implement a search function for finding tweets and users.
- Add hashtag functionality for better tweet categorization.
- Integrate API endpoints using Django REST Framework.

---

## Contributing

Contributions are welcome! Please follow the steps below:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push to your branch.
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

For more details, visit the GitHub repository: [Sheesikram/fullStackDjangoProject](https://github.com/Sheesikram/fullStackDjangoProject).
