Clone the repository

    git clone https://github.com/benzuri/laravel-todo-list.git

Switch to the app folder

    cd laravel-todo-list

Install all the dependencies using composer

    composer install

Make the required configuration changes in the .env file if you need

    cp .env.example .env

Generate a new application key

    php artisan key:generate

Run the database migrations (**Set the database connection in .env before migrating**)

    php artisan migrate:fresh

Start the local development server

    php artisan serve
