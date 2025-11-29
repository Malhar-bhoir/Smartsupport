
# SmartSupport 🎓🛠️

SmartSupport is a **Django-based web application** designed to simplify the process of reporting and managing campus maintenance issues. Students can raise tickets (e.g., broken fan, damaged bench), and admins can verify, update, and resolve them efficiently.

---

## 🔧 Features
- 🎫 **Raise Tickets**: Students can submit issues with title, description, and optionally attach an image.  
- 📋 **Ticket Dashboard**: Admins can view all submitted tickets.  
- ✅ **Status Tracking**: Tickets move through statuses: *Pending → Accepted → Resolved*.  
- 🔐 **Login System**: Separate login for Admin and Student.  
- 📷 **Image Upload**: Students can upload photos to provide better issue context.  

---

## 🚀 Tech Stack
- **Backend**: Django (Python)  
- **Frontend**: HTML, CSS, Bootstrap  
- **Database**: SQLite (Default Django DB)  
- **Authentication**: Django built-in auth system  

---

## Project structure (ASCII-safe)

```text
SmartSupport/
|-- SmartSupport/           # Django project settings
|-- ticket/                 # Main app handling tickets
|   |-- templates/          # HTML templates
|   |-- static/             # CSS/JS/Images
|   |-- models.py           # Ticket model
|   |-- views.py            # View logic
|   `-- urls.py             # App URLs
|-- media/                  # Uploaded images
|-- db.sqlite3              # SQLite database
`-- manage.py
```

---

## 🧪 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/JustCodeIT199/SmartSupport.git
   cd SmartSupport
   ```

2. **Set up a virtual environment** (optional but recommended)
   ```bash
   python -m venv env
   source env/bin/activate
   ```
   On Windows:
   ```bash
   env\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Create a superuser for admin access**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the server**
   ```bash
   python manage.py runserver
   ```

7. **Access the site**
   - Student Page → [http://127.0.0.1:8000/](http://127.0.0.1:8000/)  
   - Admin Panel → [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)

---



---

## ✍️ Author
- **JustCodeIT199**  
- **Malhar Bhoir**

---

## 🤝 Contributing
Pull requests are welcome! If you have ideas to improve the app, feel free to fork and contribute.

---

## 📜 License
This project is open-source under the **MIT License**.





