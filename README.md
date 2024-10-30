# IB Extended Essay Progress Tracker

Welcome to the **IB Extended Essay Progress Tracker**! 🎓 This Django-based web app makes it super easy for students to update their EE progress and for supervisors to stay in the loop. No more manual tracking—everything is automated! Built to reduce the stress of managing IB requirements, this project was a fun way to dive into web development while solving a real problem.

## Features ✨

- 🔐 **User Authentication**: Secure sign-up, login, and profile management
- ✏️ **Progress Updates**: Students can post and update their EE progress
- 🗂️ **Admin Controls**: Manage users and posts from an intuitive admin panel
- 📄 **Static Pages**: Helpful info for students like FAQs and advice
- 📜 **Pagination**: Organizes posts for easy navigation
- 📊 **Progress Analytics**: Visual tracking of completion status
- 📅 **Deadline Management**: Stay on top of important dates
- 📱 **Responsive Design**: Works perfectly on all devices

## Tech Stack 🛠️

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, Django templates
- **Database**: SQLite
- **Libraries**: Django-crispy-forms, Pillow

## Installation Guide 🚀

### 1. Clone and Set Up Environment
```bash
# Clone the repository
git clone <repository-url>
cd <project-directory>

# Create and activate virtual environment
python3 -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 2. Install Dependencies
```bash
# Install all required packages
pip install -r requirements.txt
```

### 3. Initialize the Project
```bash
# Run migrations
python manage.py migrate

# Create admin account
python manage.py createsuperuser

# Start the server
python manage.py runserver
```

Visit [http://127.0.0.1:8000](http://127.0.0.1:8000) to start using the application!

To deactivate the virtual environment when you're done:
```bash
deactivate
```

## Project Structure 📁
```
ib-essay-tracker/
├── src/
│   ├── manage.py
│   ├── essays/          # Main application logic
│   ├── templates/       # HTML templates
│   ├── static/          # CSS, JavaScript, images
│   └── media/           # User-uploaded content
└── requirements.txt
```

## Contribute 🙌

Feel free to fork this project and make it your own! Whether you want to:
- Add new features
- Improve the UI
- Fix bugs
- Enhance documentation

All contributions are welcome! Just fork the repo and submit a pull request.

## License 📝

This project is licensed under the MIT License - see the LICENSE file for details.

---
Made with ❤️ by IB students, for IB students
