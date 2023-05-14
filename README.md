Skeleton Django Application
===========================

This Docker compose project creates a database container running MariaDB 10.11.2 (http://mariadb.org) - https://hub.docker.com/_/mariadb.

The server 'applicationDBMS' contains a database for the django backend ('django_backend') with a default user 'django'.

It also runs an instance of phpMyAdmin 5.2.1 (https://www.phpmyadmin.net/) on localhost:80 - https://hub.docker.com/_/phpmyadmin.

And a Python 3.11.3 running environment (https://www.python.org/) - https://hub.docker.com/_/python.
That environment uses Django 4.2.1 (https://www.djangoproject.com/).
