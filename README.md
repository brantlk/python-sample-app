# python-sample-app

To run this as a developer:

```
 $ tox --notest
 $ .tox/py27/bin/gunicorn wsgi
```

Then make a request like:

```
 $ curl http://127.0.0.1:8000
```

A sample config file (must be `/etc/sample_app/sample-app.conf`):

```
 [sample_app]
 message = something
```
