# vestacp-web-template
Web template configuration for application

fix file_exists(): open_basedir restriction in effect. 

Each files should be put in in /usr/local/vesta/data/templates/web/apache2

If laravel show error 500, try:

    chmod 777 -R storage
