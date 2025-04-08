# 📇 Contacts Agenda - Django Web App

**A web application designed to manage personal contacts. Users can:**

- Register & Log In: Securely create an account and access their personalized contact list.
- Organize Contacts: Categorize contacts into groups such as Friends, Family, Work, etc.
- Add Contact Cards: Professional or personal details (name, phone, email, description) and upload a photo to visually represent each contact.


 # 🛠️ Technologies


- Python 3.12+
- Django 5.1.7
- SQLite 
- Faker (generation of fake data for testing)
- Pillow (Images manipulation)
- HTML5 + CSS3 (Django Templates)

# 📦 **Installation**  

Follow these steps to set up the project locally:  

### 1. Clone the repository
```bash
git clone https://github.com/BrenoGustavo/Agenda.git
cd Agenda
```
### 2. Create and activate a virtual environment
_(Windows)_
```bash
python -m venv venv 
.\venv\Scripts\activate
```
_(Linux/macOS)_

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```
### 4. Run migrations
```bash
python manage.py migrate
```
### 5. Start the development server
```bash
python manage.py runserver
```

### 6. Access the app

Open your browser and go to:
> _http://127.0.0.1:8000/_

## Optional: Generate Fake Data

If you want to populate your database with sample contacts, execute the file
> _utils/create_contacts.py_






