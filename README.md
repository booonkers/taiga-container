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

If you encounter issues with files permissions in the mounted volumes, run the following:

~~~
sudo chown -R 1000 PATH_TO_VOLUMES
~~~
ex:
~~~
sudo chown -R 1000 /home/docker/volumes/
~~~


The data is persisted in /home/docker/volumes for all my lab containers, update the docker-compose file accordingly to fit your requirements.
