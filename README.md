elemental_django
================
-- INSTALATION
 # python 
# as root
# wget https://bitbucket.org/pypa/setuptools/raw/bootstrap/ez_setup.py -O - | python
# wget https://raw.github.com/pypa/pip/master/contrib/get-pip.py
# python get-pip.py
# git clone git://github.com/django/django.git django-trunk
# pip install -e django-trunk/
# django lives in /usr/local/bin/django-admin.py
$  python
Python 2.7.3 (default, Apr 10 2013, 06:20:15) 
[GCC 4.6.3] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>> import django
>>> print(django.get_version())
1.7.dev20130915181426

-- START REPOSITORY
$ django-admin.py startproject  elemental-django
$ mv elemental_django/ elemental_django.cop
$ git clone https://github.com/lascar/elemental_django.git elemental_django
$ mv elemental_django.cop/* elemental_django
$ git push origin master
$ vim elemental_django/settings.py
$ python manage.py syncdb
