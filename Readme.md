# Introducción al Cloud Computing

## Contenido

- Definición y características
- Modelos de servicio Cloud
- Tipos de Cloud
- Beneficios, limitaciones y retos en la nube
- Servicios Emergentes de Cloud Computing


## Actividad en AWS

- Accede a AWS Educate y entra en la AWS Console
- Cear una máquina virtual t2.micro con Ubuntu Server 18.04 permitiendo el tráfico SSH y HTTP. Deja el resto de las opciones por defecto y guarda la key SSH para acceder
- Accede a la máquina con ssh -i SSH-KEY ubuntu@IP-MAQUINA
- Clona el repositorio https://github.com/MII-CC2021/actividad1.git
- Instala el servidor web NGINX y copia el fichero index.html a /var/www/html
```
sudo apt update
sudo apt install nginx
```
- Accede desde un navegador a http://IP-MAQUINA
- Cuando hayas terminado, detiene la máquina, para no incurrir en gastos innecesarios
