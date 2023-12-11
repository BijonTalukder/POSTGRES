<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>


    <h2>check version in postgress command : select version();</h2>
    <h2>see database list :\l</h2>
    <h2>switch database : \c database_ name</h2>
    <h2>find all table :\d</h2>
    <h2>sell all server user :\du</h2>
    <h2>exicute previous command :\g</h2>
    <h2>exit command panel :\q</h2>
    <ul>
        <li>create database command :create database database_name;</li>
        <li>create new user: create user user_name with encrypted password '1234';</li>
        <li>create table :create table table_name(name varchar(20))</li>
        <li>show table :\dt+</li>
        <li>assign access users in database: grant all privileges on database_name to user_name;</li>
        <li>drop database:drop database database_name</li>
        <li>rename database:alter database current_database_name rename to new_database_name;</li>
    
    <li>change password user:ALTER USER user_name WITH PASSWORD 'new_password';</li>
    </ul>
    
</body>
</html>
