
## PostgreSQL
/----------------------------------------------
# learn basic command
    - check version in postgress command : ``` select version(); ```
    - see database list : ```  \l ```
    - switch database  :``` \c database_ name ```
    - find all table  :``` \d ```
    - sell all server user  :``` \du ```
    - exicute previous command  :``` \g ```
    - exit command panel  :``` \q ```
 
        -create database command  :```create database database_name; ```
        -create new user :``` create user user_name with encrypted password '1234'; ```
        -create table  :```create table table_name(name varchar(20)) ```
        -show table  :```\dt+ ```
        -assign access users in database :``` grant all privileges on database_name to user_name; ```
        -drop database :```drop database database_name ```
        -rename database :```alter database current_database_name rename to new_database_name; ```
    
    -change password user :```ALTER USER user_name WITH PASSWORD 'new_password'; ```
   

