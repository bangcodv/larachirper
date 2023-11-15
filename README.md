## Guides

- sail up -d -> to run server laravel sail
- php artisan make:model -mrc Chirp -> to make chirp model, migration and controllers
- php artisan route:list -> to view all of the routes in application.
- npm run dev -> to run vite development server

## Laravel Breeze
- composer require laravel/breeze --dev
- php artisan breeze:install blade
- npm run dev
- php artisan migrate:fresh  => to rebuild database migration from scracch
- php artisan make:policy ChirpPolicy --model=Chirp => to make policy.
- php artisan make:notification NewChirp => to make notification
- php artisan make:event ChirpCreated => create an event
- php artisan make:listener SendChirpCreatedNotifications --event=ChirpCreated => creating event listener


## livewire artisan command
- php artisan make:volt chirps/list --class -> to create new livewire component.
- php artisan make:volt chirps/list --class -> to create a new chirps list, livewire component
- php artisan make:volt chirps/edit --class



