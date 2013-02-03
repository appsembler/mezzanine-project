Mezzanine skeleton project
==========================

Start a new Mezzanine project by forking this repo, editing the local_settings.py file, and running the following commands::

	$ pip install -r requirements/project.txt
	$ python manage.py syncdb --migrate
	$ python manage.py collectstatic
	$ python manage.py runserver


