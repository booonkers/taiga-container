# taiga-container

create an .env file & setup the required env. variables:

~~~
TAIGA_DEBUG=True|False
EMAIL_SERVER_TLS=True|False
EMAIL_SERVER=yourEmailHost
MAIL_SERVER_SMTP_PORT=XXX
EMAIL=yourEmail
EMAIL_PASSWORD=yourEmail'sPassword
~~~

run the container using docker compose:

~~~
docker-compose up -d
~~~
