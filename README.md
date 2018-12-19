# Docker-laravel

## How to use
1. Place the unpacked folder in a folder with laravel projects.
2. Rename env.example to .env
3. Check ./nginx/sites/ and add your site. Use laravel.conf.example as an example conf.
4. Check ./mysql/docker-entrypoint-initdb.d/createdb.sql to add a database and user for your project.
5. Run docker-compose build to start, run docker-compose up -d to hide console.
6. Run docker-compose exec php-fpm bash to acces php host and run commands (composer, node, artisan, etc.)
