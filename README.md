# socket-chat

composer install

docker-compose up -d

docker exec -it php sh -c "php chat.php --type=server"

docker exec -it php sh -c "php chat.php --type=client"
