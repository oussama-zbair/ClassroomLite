# Classroom

## 📖 About  
In today’s era of online learning, a dedicated digital platform is essential for seamless communication between students and teachers. **Classroom** is a mini Google Classroom–style web application that allows students to submit assignments and teachers to review, grade, and return feedback efficiently.  


---

## ⚙️ Tech Stack  
- **Backend**: Django  
- **Database**: SQLite  
- **Frontend**: HTML, CSS, Bootstrap, jQuery  

---

## 🚀 Installation  

Follow these steps to set up the project locally:  

```bash
# Clone the repository
git clone https://github.com/oussama-zbair/classroom-lite.git

# Navigate into the project
cd classroom-lite

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py makemigrations
python manage.py migrate
```

### 🔑 Environment Variables  
Create a `.env` file in the root directory and configure the following:  

```
EMAIL_HOST=your_email_host
EMAIL_PORT=your_email_port
EMAIL_HOST_USER=your_email_id
EMAIL_HOST_PASSWORD=your_email_password
SECRET_KEY=your_secret_key
```

---

## ▶️ Run the Application  

```bash
python manage.py runserver
```

The application will be available at **http://127.0.0.1:8000/**.  

---

## ✨ Features  
- Student assignment submission  
- Teacher grading and feedback system  
- Simple, intuitive interface  
- Lightweight and easy to deploy  

---

