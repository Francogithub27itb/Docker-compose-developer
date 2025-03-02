# Docker-compose-developer

🚀 1️⃣ Construcción de la imagen

docker build -t fcl2005/developer_image .

▶️ 2️⃣ Ejecución del contenedor

docker run -d --name developer_container -p 33333:22 -p 5901:5901 fcl2005/developer_image

🖥 3️⃣ Conexión a los servicios

Para conectar vía SSH a Developer:

ssh -p 33333 developer@localhost

Para acceder a Developer vía VNC: Configurar Remmina con localhost:5901.

📌 4️⃣ URL de Docker Hub

https://hub.docker.com/r/fcl2005/developer_image
