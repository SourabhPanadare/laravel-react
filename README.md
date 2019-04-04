# laravel-react Reference

  https://itsolutionstuff.com/post/laravel-5-simple-crud-application-using-reactjs-part-1example.html
  https://itsolutionstuff.com/post/laravel-5-simple-crud-application-using-reactjs-part-2example.html
  https://getcomposer.org/download/

# Installation Steps

  composer create-project --prefer-dist laravel/laravel laravel-react
  follow https://getcomposer.org/download/
  php artisan key:generate
  .env database credentials
  php artisan make:migration create_books_table
  php artisan make:model Book
  php artisan make:controller BookController --resource

  php artisan preset react
  npm install
  npm install --save react-router@3.2.0

  npm run dev
  php artisan serve