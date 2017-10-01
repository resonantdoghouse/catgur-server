# catgur-server

- server ip: 138.68.252.41
- port: 22
- url of hosted app: http://webdev.coffee/

## Summary of software installed and configuration changes made.

Software includes, apache, mod_wsgi, pip, sqlite.
git was used for cloning in the project but has been uninstalled.

Fixed lots of issues bringin in the project. Oauth was a challenge, especially fbconnect since it seems to have changed.
It also took a bit of time setting up wsgi, this article was helpful [flask-apache-wsgi](https://www.jakowicz.com/flask-apache-wsgi/)

## A list of any third-party resources you made use of to complete this project.

- digital ocean
- fb & google OAuth
- appdirs
- click
- Flask
- Flask-Login
- gunicorn
- httplib2
- itsdangerous
- Jinja2
- MarkupSafe
- oauth2client
- packaging
- pyasn1
- pyasn1-modules
- pyparsing
- requests
- rsa
- six
- SQLAlchemy
- Werkzeug
