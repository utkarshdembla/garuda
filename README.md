How to install-

pip install -r requirements.txt

Create a copy of local_settings.py.sample and rename it to local_settings.py and add your MySQL settings there.

python manage.py syncdb

python manage.py runserver





Requirements-
Django==1.6.5
MySQL-python==1.2.5
argparse==1.2.1
httplib2==0.9
requests==2.2.1
simplejson==3.4.1
wsgiref==0.1.2
