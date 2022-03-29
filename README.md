# What is this App? 
This is a demo Web App built with Laravel5 + Vue2

## Project Introduction
#### 1. Using Laravel5.3 and Vue2.0 to complete the SPA application, this project mainly uses Vue, Vue-router, Vuex and some animation plug-ins.
#### 2. Including the functions of publishing, modifying, deleting, commenting, replying, and internal communication of articles.
#### 3. I use the valet development environment under Mac, which is more convenient.

## Environmental requirements
> It is best to set up a homestead or vlate environment. If there is an error in an integrated environment such as Windows' XAMPP, you are responsible for it.

## installation steps
### 1. Copy the project to the local
````
git clone https://github.com/LaravelChen/laravel-vue.git
````
### 2. Enter the directory
````
cd laravel-vue
````
### 3. Give permissions to some folders
````
sudo chmod -R 777 storage bootstrap public //Decide whether to execute this command according to your own environment
````

### 4. Configuration file
#### Copy the contents of ``.env.example``` in the directory to the ```.env``` file, but this ```.env``` file is created separately. Then copy the corresponding The database configuration is complete and it's ok!

### 5. Generate corresponding dependencies
````
composer install
````

### 6. Install front-end dependencies
##### Install Gulp

````
npm install --global gulp
````
#### Or you can use yarn instead of npm to save download and install time:

````
yarn add global gulp
````
#### Install Laravel Elixir and Vuejs dependencies:
````
npm install
````
#### or
````
yarn
````
### 7. Compile
#### You can do a single compilation:
````
gulp
````
#### Or you can monitor resource file modifications:
````
gulp watch
````
#### Of course, you can also run all tasks and minify all CSS and JavaScript:
````
gulp --production
````
### 8. Generate data
````
 php artisan create:data
````
#### The user and post that will generate the response

### 9. Create administrator
````
php artisan blog:admin //Follow the prompts to create your administrator information step by step
````

### 10. Finally, I hope you can create a perfect success
