🎨 Online Art Gallery
An online platform to showcase, upload, and explore artwork. Users can sign up, log in, view artwork collections, upload their own, and curate favorites in a cart-style gallery.

🔧 Features
✅ User Authentication (Sign Up / Login)

🖼️ Upload and Browse Artwork

📱 Responsive Landing Page & Gallery UI

🛒 "Favorites" Cart-like Collection System

🔐 Profile View with Access Control

🛠️ Custom Django Admin Interface

🛠️ Tech Stack
Backend: Django

Frontend: HTML, CSS, JavaScript

Database: SQLite3

Tools: Django Admin, Django Forms, Staticfiles

🚀 Getting Started
Follow these steps to run the project locally:

bash
Copy
Edit
# 1. Clone the repository
git clone https://github.com/yourusername/suryaakkala-online-art_gallery.git
cd suryaakkala-online-art_gallery

# 2. Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run migrations and start the server
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
🔗 Open your browser and visit: http://127.0.0.1:8000/

📁 Project Structure
php
Copy
Edit
suryaakkala-online-art_gallery/
├── art_gallery/           # Main Django project (settings, URLs)
├── gallery/               # Core app: models, forms, views, templates
├── login/                 # Optional separate login module
├── static/                # Static files: CSS, JS, images
└── templates/             # HTML templates for the UI
👥 Team
Surya Akkala – Team Lead, Backend Developer
🔗 GitHub: @suryaakkala

[Frontend Teammate 1 Name] – Frontend Developer

[Frontend Teammate 2 Name] – Frontend Developer

🔧 Feel free to add contributors with GitHub profile links.

📄 License
This project is intended for academic and demonstration purposes only.

