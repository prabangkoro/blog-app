# blog-app
This is a laravel project for tutorial on [my blog](https://www.blog.babangcreator.com/).

## How to use
1. clone this repo
2. switch to desired branch
3. install composer package dependencies
    ```
    composer install
    ```
4. install node package dependencies
    ```
    npm install
    ```
5. configure `.env` file (create a new file if it doesn't exist)
    * generate key application
    
        ```
        php artisan key:generate
        ```
    
    * create a new database, fill database information on `.env` file
    * migrate database
        
        ```
        php artisan migrate
        ```
        
## Contribute
Feel free to discuss any difficulties or issues on this repo, or email me :D
