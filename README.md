# Tec-Medika-Prueba
Postulación para vacante por medio de micro proyecto

Pasos para correr servicio
* Tener instalado Docker en sistema a correr
* si no, instalar los siguientes comandos: 
sudo curl -L "https://github.com/docker/compose/releases/download/v2.12.2/docker-compose-$(uname -s)-$(uname -m)"  -o /usr/local/bin/docker-compose
sudo mv /usr/local/bin/docker-compose /usr/bin/docker-compose
sudo chmod +x /usr/bin/docker-compose

Una vez hechos hay que abrir el proyecto con visual code
y ejecutar los siguientes comandos
cd docker
sudo ./build.sh
sudo ./start.sh

para parar el proyecto eso 

sudo ./stop

para ver la consola del proyecto en su sistema interno de docker
sudo ./connect.sh

Application Access
Main Application: http://localhost:8080/
PhpMyAdmin: http://localhost:8181/

