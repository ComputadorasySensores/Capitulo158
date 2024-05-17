# Frigate NVR

Instalación de docker

curl -sSL https://get.docker.com | sh

sudo usermod -aG docker $USER

Probar docker

docker run hello-world

Instalación de Frigate en Raspberry Pi

mkdir ~/frigate-nvr/storage

nano ~/frigate-nvr/config.yml

Modelo de achivo yml (Solo como referencia)

Ver archivo config.yml

nano ~/frigate-nvr/docker-compose.yml

En archivo docker-compose.yml cambia tu home y el password

cd ~/frigate-nvr

docker compose up -d

# Paso a paso

La explicación completa la podrás ver en el siguiente video de Youtube:
https://youtu.be/wiCSOdZPs28

