### Docker configuration using docker-compose.yml for multiple laravel application

#### how to add new application
- add new .conf file in nginx/conf folder (you can using template from tracey.conf)
- just add your new application folder to '~/Documents/www'

#### application default folder
by default it is using bind volume, it will sync from:
'~/Documents/www' to nginx/php container in '/var/www'