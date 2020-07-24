# myngrok
127.0.0.1:4040


host php files with this code in same folder to deploy

php -S 127.0.0.1:8000 -t .

u can change port 8000 to match diff websites created in folders
e.g:

php -S 127.0.0.1:8000 -t .   in a folder named test1 will launch website on 8000 nd display all php files in folder test1 (might need sudo)

then run ngrok as ./ngrok 8000  (change port to match folders port)
