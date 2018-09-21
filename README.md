Download or clone file and extract on your folder PC
Run in terminal "composer update"
Create a new database with the name "tesapi" on mysql
Edit ".env" and adjust to the settings database on your PC
Run in terminal "php artisan migrate"
Run in terminal "php artisan fetch:create"

#setting swapable

Edit ".env" at line 19 "DATA_FROM"
get data from database set "DATA_FORM=database"
get data from api raja ongkir set "DATA_FORM=rajaongkir"

Login to get token  url : "/login" 
                    param : "username", "password"
                    method : "POST"

Search Province url : "/search/province?id={province_id}&token_key={token_key}"

Search City url : "/search/city?id={city_id}&token_key={token_key}"
