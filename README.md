# laravel
# First you can create a new folder like src using mkdir src
# Create a laravel project source code
docker-compose run --rm composer create-project laravel/laravel .
# After that you create server
docker-compose  up --build server php mysql
