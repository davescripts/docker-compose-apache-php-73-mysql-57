# Docker Compose: Apache, PHP 7.3, and MySQL 5.7

Docker Compose file for Containers with Apache, PHP 7.3, and MySQL 5.7, for Web Development.

<br>

## Build and Start the Containers

Create the Containers.

```sh
docker-compose up -d
```

<br>

## View Logs

Check the Docker Compose Logs.

```sh
docker-compose logs
```

<br>

## Test

Open the http://localhost:4000/test.php  url on your browser.

<br>

You should see the following text:

```sh
Connection successful!
```
<br>

## Stop the Containers

Stop the Containers.

```sh
docker-compose stop
```

<br>

## Remove the Containers

Remove the Containers.

```sh
docker-compose down
```
