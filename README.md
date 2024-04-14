This is a simple website used for Tshirt booking, payment and order tracking, built majorly using Laravel and also including Vue.js, Vite, Restful API's, Stripe, JQuery and other components.
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
