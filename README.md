# WIK-DPS-TP01
TP1 DevOps

Voici la liste des commandes à faire :

1/ git clone https://github.com/Erxansen/WIK-DPS-TP01

2/ Linux : export PING_LISTEN_PORT=7878 && cargo run
   Windows : set PING_LISTEN_PORT=7878
             cargo run
             
3/ La commande "curl localhost:7878/ping -v" retourne "HTTP/1.1 200 OK" avec les headers de la requête. (à noter que si la commande "export" n'est pas renseignée, il faudra donc faire "curl localhost:8080/ping -v")

4/ La commande "curl localhost:7878 -v" retourne "HTTP/1.1 404 Not Found" avec "Content-lenght=0" qui annonce une page vide.
