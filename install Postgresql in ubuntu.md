# Install PostgreSQL

* Ubuntu’s default repositories contain Postgres packages, so you can install these using the apt packaging system.

> sudo apt update
>  
> sudo apt install postgresql postgresql-contrib -y
> 
> sudo systemctl start postgresql.service
> 
> psql -h <REMOTE HOST> -p <REMOTE PORT> -U <DB_USER> <DB_NAME>


