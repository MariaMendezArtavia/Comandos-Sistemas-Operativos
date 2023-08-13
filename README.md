# Comandos-Sistemas-Operativos
Este es el repositorio de comandos de Sistemas Operativos de Maria Mendez Artavia
| Comandos      | Descripcion          |   Ejemplo   |
| ------------- | -------------------- | ------------|
| ip a          | Ver la direccion IP  | ip a
| clear         | borrar el contenido de la pantalla  | clear
| pwd           | para saber a donde esta   | pwd
| ls            | para ver todos los folders  | ls
| ls -l         | da los folders en forma de una lista y mas detalles  | ls -l
| ls -la        | Muestra los folder y los ocultos  | ls -la 
| man           | para ver el manual de parametros de un comando  | man ls
| sudo apt install (nombre de la app) | Para instalar una aplicacion  | sudo apt install apcalc
| sudo          | Da permisos de administrador | sudo apt install
| su root       | iniciar sesion con el admin user  | su root
| sudo passwd root | Cambiar el password de root  | sudo passwd root
| whoami        | para saber que usuario esta loggueado  | whoami
| exit          | salirse del user  | exit
| history       | para ver el historial de comandos usados  | history
| nano (nombre del archivo)  | Crear archivos  | nano archivo.txt
| cat (nombre del archivo)  | imprime el contenido del archivo  | cat archivo.txt
| mkdir (nombre del folder)  | crear folders (el nombre el folder es case sensitive | mkdir Maria 
| cd (nombre del folder)  | abrir una carpeta  | cd Maria
| cd ..         | se devuelve a la carpeta anterior  | cd ..
| cd (path del folder)  | abrir un folder especifico  | cd /home/mmendeza656
| cd            | se devuelve a la carpeta home  | cd
| rm (nombre del archivo) | eliminar un archivo  | rm archivo.txt
| cp (nombre del archivo) (path)  | copiar un archivo a otra carpeta  | cp archivo.txt /home/mmendeza656
| mv (nombre del archivo) (path)  | mover un archivo a otra carpeta  | mv archivo.txt /home/mmendeza656
| top  | muestra del administrador de procesos  |
| sudo apt install htop  | instala una app para ver los procesos mas bonitos | sudo apt install htop
| sudo apt install tree  | instala una app que organiza los folder como un arbolito  | sudo apt install tree
| tree.  | muestra los folders en arbolito | tree.
| ps -aux  | p-ara ver la lista de procesos | ps -aux
| sudo adduser (nombre del user)  | Crear usuarios nuevos | sudo adduser mmendeza656
| sudo deluser (nombre del user)  | Eliminar un usuario  | sudo deluser mmendeza656
| sudo chmod 777 -R* (nombre del file) | Para dar permisos de editor a un HTML  | sudo chmod 777 -R* archivo
| cat /proc/meminfo  | Muestra la memoria que tenemos  |
| sudo apt install ssh  | instalar el SSH   | sudo apt install ssh
| sudo apt install openssh-server  | instala un servidor de SSH  | sudo apt install openssh-server 
| sudo apt update  | actualizar  | sudo apt update
| sudo apt upgrade  | actualizar  | sudo apt upgrade
| curl (pagina web)  | hacer request a paginas web  | curl www.google.com
| wget  | bajar archivos de la web  | wget https://www.google.com/search?q=girasol&sca_esv=556595182&hl=es&tbm=isch&sxsrf=AB5stBiPo_xiGaa0PbPxsmDyNVj6xtUuMw%3A1691965655373&source=hp&biw=1366&bih=611&ei=11jZZPamFLyQwbkPm6qjyAU&iflsig=AD69kcEAAAAAZNlm5yegtW04Can-HkvTBKOjgAaNhtML&ved=0ahUKEwi27u6e19qAAxU8SDABHRvVCFkQ4dUDCAc&uact=5&oq=girasol&gs_lp=EgNpbWciB2dpcmFzb2wyCBAAGIAEGLEDMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAESKAkUMgLWJIicAV4AJABAJgBdqABkAiqAQM0Lja4AQPIAQD4AQGKAgtnd3Mtd2l6LWltZ6gCCsICBxAjGOoCGCfCAgQQIxgnwgILEAAYgAQYsQMYgwHCAgQQABgewgIGEAAYBRgewgIJEAAYGBiABBgK&sclient=img#imgrc=DVZvDZowRq-_xM
| find (nombre archivo)  | buscar un archivo  | find /home/mmendeza656 -name archivo.txt
| locate (nombre de archivo)  | buscar un archivo  | locate archivo.txt
| ping (direccion ip o pagina) | ver si accesa una direccion o pagina  | ping 8.8.8.8 o ping google.com
| zip (nombre de archivo)  | Comprimir un archivo | zip archivo.txt
| unzip (nombre de archivo)   | Descomprimir un archivo  | unzip archivo.zip
| useradd (nombre de usuario) | crear un usuario nuevo  | useradd mmendeza656
| netstat -tulpn  | informacion de puertos  | netstat -tulpn
| find /-name foo 2>/dev/null  | buscar texto  | find /-name foo 2>/dev/nul
| lsb_release  | imprime la informacio especifica de la distribucion  | lsb_release
| uname | muestra cierta informacion del sistema  | uname -a
| ps  | despliega informacion del proceso actual  | ps aux
| docker search ubuntu  | buscar en el repositorio de docker  | docker search ubuntu
| docker pull ubuntu  | descarga la imagen del contenedor  |  docker pull ubuntu 
| docker run ubuntu  | corre un nuevo contenedor usando una imagen  | docker run ubuntu
| docker images  | ver imagenes instaladas  | docker images
|  sudo docker ps -a | mostrar estado de contenedores  | sudo docker ps -a
| sudo docker start  | inicia un contenedor que estaba detenido | sudo docker start
| sudo docker stop  | detiene un contenedor que esta corriendo  | sudo docker stop
| docker rmi image image  | borra imagenes del contenedor | docker rmi image image
| docker run --rm image_name  | elimina un contenedor |  docker run --rm image_name 
| docker rm ID  | elimina contenedores |  docker rm ID 

