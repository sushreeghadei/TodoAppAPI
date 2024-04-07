## Todo List API

This project has been forked from jamalhassouni/Todo-List-API:master. We are using it to see if you have the requisite skills to get it up and running by following all the instructions presented here. 

To complete this you must make the API and the UI work together. 

* [Todo API](https://github.com/richie-chauhan/TodoAppAPI) - This project
* [Todo UI](https://github.com/richie-chauhan/TodoAppUI)

## Details
Todo List PHP Application Programming Interface

PHP 7 script that adds a REST API to a MySQL 5.5 InnoDB database

### Requirements
* PHP 7.0 or higher with PDO drivers for MySQL, PgSQL or SqlSrv enabled
* MySQL 5.6 / MariaDB 10.0 or higher for spatial features in MySQL

## Installation and Configuration

Create the MySQL database in from the `todo.sql` file in the repo.  
  
Edit the following lines in the bottom of the file `config/Database.php`:  
  
```php
    private $host = 'xxx';
    private $db_name = 'xxx';
    private $username = 'xxx';
    private $password = 'xxx';
```

For local development you may run PHP's built-in web server:

`php -S localhost:8080`

Test the script by opening the following URL:

`http://localhost:8080/index.php/`

## API 
API methods are available here [api.md](https://github.com/richie-chauhan/TodoAppAPI/blob/master/api.md)
