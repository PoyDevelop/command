
.env // Config File



php artisan key:generate




php artisan route:list

php artisan make:controller BlogController --resource

php artisan crud:generate Posts --fields='title#string; content#text; category#select#options={"technology": "Technology", "tips": "Tips", "health": "Health"}' --view-path=admin --controller-namespace=Admin --route-group=admin --form-helper=html