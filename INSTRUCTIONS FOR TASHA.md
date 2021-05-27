
python3 -m virtualenv virtual
source virtual/bin/activate
pip install -r requirements.txt


Change the values in .env to your own
Run python .env




python manage.py makemigrations projects
python manage.py migrate

python manage.py runserver


Change cloudinary values to your own in  lines 190-192 of  settings.py inside awward folder