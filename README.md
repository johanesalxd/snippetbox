Snippetbox
-----------------------------
To be added.

# Additional notes
To be added.

## Related links
* [MySQL using Docker](https://www.datacamp.com/tutorial/set-up-and-configure-mysql-in-docker)

## Code snippets

```
docker volume create test-mysql-data

docker run \
   --name test-mysql \
   -v test-mysql-data:/var/lib/mysql \
   -e MYSQL_ROOT_PASSWORD=password \
   -p 3306:3306 \
   -d mysql

mysql --host=127.0.0.1 --port=3306 -u root -p
```