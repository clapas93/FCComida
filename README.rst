FCComida
========

.. contents:: :local:

Instalación
-----------

.. code:: bash

    $ virtualenv FCComida
    $ source bin/activate
    (FCComida)$ git clone https://github.com/UNAM-FCiencias-TDI/FCComida.git
    (FCComida)$ cd FCComida
    (FCComida)$ pip install -r requirements.txt


Configuración de la base de datos (PostgreSQL)

.. code:: bash

    (fcsocial_dev)$ python manage.py migrate
    (fcsocial_dev)$ python manage.py createsuperuser

Ejecución
---------

.. code:: bash

    (fcsocial_dev)$ python manage.py runserver
