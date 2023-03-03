# image de partida
from nginx:latest
# run ejecuta comandos dentro del contenedor
run apt-get update -y && apt-get install -y git
run mkdir /home/usuario
workdir /home/usurio
copy caca.txt /usr/share/nginx/html
#establecer una variable
env password=abc123.
# exponer puerto
expose 80
