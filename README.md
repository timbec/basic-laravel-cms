This is a basic Laravel CMS, including LTE Admin panel. For the moment lacks ability to add/manage/delete users, which stops it from being a full CMS. I will be improving this in the weeks and months to come. 

To use: 
    git clone
    cp env.example .env

open in your favorite dev environment (I use Laravel Valet, if you use Homesetead or Vagrant configure as per usual)

    composer install
    php artisan key:generate

If you want to recreate the login/ registration panel: 

    php artisan key:generate

If not, its already included. 

Connect to a Database, including credentials in .env file. 

To generate tables: 

    php artisan migrate

Register user - login!

You'll see Admin Page. 

Create some test categories/tags then create Posts. Basic, but it's a start.

To re-initialize the git file: 
    rm -rf .git

otherwise your changes will be pushed up to my repo in the form of a pull request. 