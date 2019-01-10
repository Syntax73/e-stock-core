# E-stock-core

Permissive REST API for information access control from a retail business environment.

# All you'll need

1. The text editor or IDE of your choice.
2. JDK8 [Or latest](https://www.oracle.com/technetwork/java/javase/downloads/index.html).
3. **Installation**

   Just clone the repository.
   * SSH:  `git clone git@github.com:DevVillageNortheast/e-stock-core.git`
   * HTTP: `git clone https://github.com/DevVillageNortheast/e-stock-core.git`

4. **Configure the Database**
   * Create a .env file on `src/main/resource/.env`
   * Create a txt file on any directory out of the project.
   * On this file insert the database configuration, like in this example.
        ```
        org.mariadb.jdbc.Driver
        jdbc:mariadb://localhost:3306/yourdatabase
        username
        password
        org.hibernate.dialect.MariaDB53Dialect
        ```
   * Point the txt file by adding this line on the .env `DATABASE_CONFIG_DIRECTORY=/path/to/the/file.txt`