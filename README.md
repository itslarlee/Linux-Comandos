# Comandos Básicos de la Terminal de Linux

| Comando | Descripción | Ejemplo |
| --- | --- | --- |
| `ls` | Lista todos los archivos y directorios en el directorio actual | `ls` |
| `cd` | Cambia el directorio actual | `cd Documentos` |
| `mkdir` | Crea un nuevo directorio | `mkdir mi_carpeta` |
| `touch` | Crea un nuevo archivo | `touch mi_archivo.txt` |
| `rm` | Elimina un archivo o directorio | `rm mi_archivo.txt` |
| `rm -R` | Elimina un directorio y todo su contenido | `rm -R mi_carpeta` |
| `cp` | Copia un archivo o directorio | `cp mi_archivo.txt copia_de_mi_archivo.txt` |
| `mv` | Mueve o renombra un archivo o directorio | `mv mi_archivo.txt mi_carpeta/` |
| `pwd` | Imprime el directorio de trabajo actual | `pwd` |
| `cat` | Muestra el contenido de un archivo | `cat mi_archivo.txt` |
| `head` | Muestra las primeras líneas de un archivo | `head -n 10 mi_archivo.txt` |
| `head -n` | Muestra un número específico de líneas de un archivo | `head -n 10 mi_archivo.txt` |
| `tail -n` | Muestra las últimas líneas de un archivo | `tail -n 10 mi_archivo.txt` |
| `archivo largo \| less` | Muestra el contenido de un archivo grande de manera paginada | `cat archivo_largo.txt \| less` |
| `man` | Muestra el manual de un comando | `man ls` |
| `clear` | Limpia la pantalla de la terminal | `clear` |
| `history` | Muestra el historial de comandos ejecutados | `history` |
| `ps -aux` | Muestra la lista de procesos en ejecución | `ps -aux` |
| `ps -aux \| grep "firefox"` | Muestra la lista de procesos en ejecución que contengan "firefox" | `ps -aux \| grep "firefox"` |
| `sudo su` | Cambia a usuario superadministrador | `sudo su` |
| `whoami` | Imprime el nombre del usuario actual | `whoami` |
| `adduser` | Crea un nuevo usuario | `adduser nuevo_usuario` |
| `sudo apt update` | Revisa qué paquetes se pueden actualizar | `sudo apt update` |
| `sudo apt upgrade` | Descarga los paquetes actualizados | `sudo apt upgrade` |
| `sudo` | Da permisos de administrador a cualquier comando que se escriba | sudo apt update |
| apt | Comando donde están los repositorios | apt search paquete |
| update | Actualiza los paquetes del repositorio | sudo apt update |
| sudo apt install neofetch | Para instalar el paquete neofetch | sudo apt install neofetch |
| Ctrl + C | Cancela el comando actual | Ctrl + C |
| sudo apt search paquete | Busca un paquete en los repositorios | sudo apt search neofetch |
| sudo kill -9 [id] | Mata un proceso por id específico | sudo kill -9 1234 |
| snap | Comando para manejar paquetes snap | snap find |
| sudo apt install snapd | Instala el sistema snapd | sudo apt install snapd |
| snap find | Busca paquetes en el sistema snap | snap find neofetch |
| sudo snap install | Instala un paquete snap | sudo snap install neofetch |
| sudo add-apt-repository ppa:numix/ppa -y | Añade el repositorio PPA de Numix | sudo add-apt-repository ppa:numix/ppa -y |
| sudo apt install numix-icon-theme-circle | Instala el tema de iconos Numix Circle | sudo apt install numix-icon-theme-circle |
| sudo apt install numix-gtk-theme | Instala el tema de GTK Numix | sudo apt install numix-gtk-theme |

**Nota de precaución:**
Estos comandos deben usarse con precaución, especialmente `rm` y `cp` que pueden eliminar o sobrescribir archivos importantes.
