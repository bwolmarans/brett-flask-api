touch hello.sock

gunicorn --bind 0.0.0.0:5000 wsgi:app &

curl 127.0.0.1:5000

"Hello, World"

curl 127.0.0.1

"Hello, World"
