# postgresql-docker

Docker image for PostgreSQL

**Get it running:**

``$ docker-compose up``

**Testing the running PostgreSQL**

To test the running container we can use any client, even the commandline one:


``psql -h localhost -p 5432 -U pguser -W pgdb``

When you are prompted for password, type: pguser

_Please note that localhost is only valid if you are running Docker on Ubuntu. If you are an OSX user, you need to discover the correct ip using: boot2docker ip_