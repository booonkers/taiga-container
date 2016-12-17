# taiga-container

create an .env file & setup the required env. variables:

~~~
TAIGA_DEBUG=True|False
TAIGA_VOLUME=PATH_TO_VOLUMES
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

If you encounter issues with files permissions in the mounted volumes, run the following:

~~~
sudo chown -R 1000 PATH_TO_VOLUMES
~~~
