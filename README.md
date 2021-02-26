Servidor de correo

instalación del docker:

paso 1
- sudo apt-get update
- dependencias:
  - sudo apt-get install apt-transport-https ca-certificates curl gnupg2 software-properties-common
paso2
  - Descargue la clave GPG oficial de Docker para verificar la integridad de los paquetes antes de instalar:
    - curl -fsSL https://download.docker.com/linux/debian/gpg | sudo apt-key add -
  - Agregue el repositorio de Docker al repositorio de su sistema con el siguiente comando:
    - sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/debian buster stable"
paso 3 
  -Actualice el repositorio de apt:
    -sudo apt-get update
paso 4 
  - Instale Docker Engine - Community (la última versión de Docker) y containerd:
    - sudo apt-get install docker-ce docker-ce-cli containerd.io
paso 5 
  - El servicio se iniciará automáticamente después de la instalación. Verifique el estado escribiendo:
    - sudo systemctl status docker

instalacion de una certificadora 
