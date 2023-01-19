# Set up for wordpresss with phpmyadmin and mysql-db on local machine
___
## Before you start make sure you got docker installed on your local machine!
___
> ## Follow:
>- cp .env .env.example
>- provide username and password for wordpress and phpmyadmin in .env file
>- docker-compose up -d
> ## Https adresses:
>- phpmyadmin 
>> 127.0.0.1:8080
>- wordpress
>>- 127.0.0.1:80
___
## Check if your containers are running
> ## In your CLI:
>- docker ps
>- docker ps -a
___
## Your db will store your session in mysql folder