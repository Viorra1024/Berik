# Главное осыны жазу керек
cd library_project

# Create venv
python -m venv venv

# Activate it
venv\Scripts\activate

# Install deps
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Run the project
python manage.py runserver


pip install django mysqlclient

pip install django
