# Setup
```
    composer install
    # configure your .env file (you need to get your stripe secret keys in order to 
    # get the stripe checkout working, also your email service)
    
    cp .env.example .env (make necessary changes as per the DB)
    composer install
    php artisan key:generate
    php artisan migrate
    php artisan db:seed
    npm install
    php artisan serve
    npm run dev
`