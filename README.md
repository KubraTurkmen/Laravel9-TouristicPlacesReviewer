# to run project

composer install

npm install

php artisan serve

# to run database

docker-compose -f mysql_docker.yml up -d

# site 

http://127.0.0.1:8000

# admin panel

http://127.0.0.1:8000/admin

###to create admin user

php artisan voyager:admin your@email.com --create

###

Voyager for Admin Panel

JetStream for Authentication 
