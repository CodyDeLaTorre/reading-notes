# Class 33 Reading Notes

## JSON Web Tokens

- A JSON Web Token is a way for securely transmitting information between parties as JSON
- You should use web tokens when you need to have a login or do information exchange on your websites
- structure of the token is header, payload, signature
- When a user logs in a a web token is returned and acts as credentials

EX of token: xxxxx.yyyyy.zzzzz

## DRF JWT Authentication

- have to install it in settings.py and urls.py

## Runserver != Production Server

- DONT USE MANAGE.PY RUNSERVER AS YOUR PRODUCTION SERVER
- has no security
- use gunicorn or ngnix instead

---

### Resources

[JSON Web Tokens](https://jwt.io/introduction/)

[DRF JWT Auth](https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html)

[runserver!!!?!!](https://vsupalov.com/django-runserver-in-production/)

---

[Back to Home](../README.md)
