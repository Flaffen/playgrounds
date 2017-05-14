In order to deploy and develop "playgrounds" on your local machine you should have <a href="https://getcomposer.org">Composer</a> installed. The following instructions suggest you have Composer installed globally.

Deploying "playgrounds" on your local machine:
- Clone repo
- Within project directory type `composer install` and wait until all dependencies are downloaded
- Copy **.env.example** and rename it to **.env**
- Inside of **.env** file replace **APP_NAME**, **APP_URL** and database settings to your own
- Type `php artisan key:generate`

That's all! You can check if you've done it successfully by typing `php artisan serve` and going to <a href="http://127.0.0.1:8000" target="_blank">127.0.0.1:8000</a>
