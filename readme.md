# .gitignore
/laravel-app
# install lararavel
> laravel new laravel-app
# install adminer
> mkdir adminer

> curl -L https://github.com/vrana/adminer/releases/download/v5.4.1/adminer-5.4.1.php -o adminer/index.php
# install wp-app
> wp core download --path=wp-app

> cd wp-app && wp config create --dbhost=127.0.0.1 --dbname=wp_database --dbuser=wp_user --prompt=dbpass

> wp db create

> wp core install --url=127.0.0.1:8080 --title="WP-CLI" --admin_user=admin --admin_password=wpcli --admin_email=info@wp-cli.org

> wp option update upload_path	uploads

> wp option update upload_url_path	/uploads

> wp server