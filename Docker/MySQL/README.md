# MySQL

- **Pull Image:**
  ```sh
    docker pull mysql
  ```

- **Run Container:**
  ```sh
    docker run --name mysql-server -e MYSQL_ROOT_PASSWORD=my-secret-pw -p 3306:3306 -d mysql:latest
  ```
