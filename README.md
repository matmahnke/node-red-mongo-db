

rodar o seguinte comando na raiz do projeto:
docker-compose up --build

nodered - http://localhost:1880/
mongo-express - http://localhost:8081/
mongo - http://localhost:27017/ 

Entrar em localhost:8081
login:devroot
senha:devroot
criar uma collection dentro da database padrão

configurar essa collection no modulo do nodered
no campo server: host.docker.internal - equivalente a localhost

