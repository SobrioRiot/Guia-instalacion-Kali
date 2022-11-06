[English](https://github.com/NeverWonderLand/kali-inst-guide) | [Español](https://github.com/SobrioRiot/Guia-instalacion-Kali)

# Cómo instalar Kali Linux en VirtualBox en Windows - Paso a Paso
-----------------------------------------------
- Última actualización: 07/09/2022

- NOTA: Los siguientes enlaces descargarán los archivos automáticamente, así que sólo haz clic en ellos desde donde vayas a instalarlos. 
----------------------------------------------  
1- Descargar VirtualBox: 

   * For Windows: https://download.virtualbox.org/virtualbox/7.0.2/VirtualBox-7.0.2-154219-Win.exe

2- Descarga el paquete de extensiones: 
                  
   * https://download.virtualbox.org/virtualbox/6.1.36/Oracle_VM_VirtualBox_Extension_Pack-6.1.36a-152435.vbox-extpack

3- Descarga kali Linux: 

   * https://kali.download/virtual-images/kali-2022.3/kali-linux-2022.3-virtualbox-amd64.7z

4- Debes activar el subsistema de Windows para Linux. Para ello, escriba "Características de Windows" en la barra de búsqueda del menú de Windows, luego abra, baje y marque la casilla "Subsistema de Windows para Linux", luego guarde, salga y reinicie su ordenador.

- LINUX: Desde cualquier distrito, solo sigue solo los pasos 1, 2 y 3.


![photo_2022-06-10_14-44-13](https://user-images.githubusercontent.com/64184513/175776446-b373d0e5-4672-471f-a78a-93e0f2891313.jpg)

5- Abre VirtualBox y sigue las instrucciones de instalación.

6- Haz clic en "archivo" en el menú, y en "preferencias" y luego en "extensión", añade el paquete de extensión que descargaste anteriormente.

![8](https://user-images.githubusercontent.com/64184513/175776890-4f44fdbd-97ec-4bf9-bcf1-8db3aafa4459.jpg)

7- NEcesitaras un programa para extraer Kali del archivo .zip file
 
Lo podras descargar aqui : [7-zip](https://www.7-zip.org/download.html)

8- Abre tu carpeta de descargas y da doble click en el archivo .zip de Kali, crea una carpeta en tu escritorio y extrae el archivo dentro.

9- Ahora abre esta carpeta y da doble click en el archivo .vbox - icono azul - y sigue las intrucciones.

![1](https://user-images.githubusercontent.com/64184513/196248353-103d6d04-bc9a-4e6d-96df-6a1fe4fb753c.png)


10- Abre la "configuración" de tu nueva Kali, y pon al menos 2 CPUs por cuestiones de rendimiento + 4GB de RAM. (no sobrepasar la línea roja)

![4](https://user-images.githubusercontent.com/64184513/175776404-1eb16270-54d3-4d42-9741-2d2bbb0ce29b.jpg)
![5](https://user-images.githubusercontent.com/64184513/175776405-1227974e-c82f-4272-9b58-8163c14687e0.jpg)


11- En la sección de "red", pon el "Attached to" a "Bridge Adapter" y aleatoriza la dirección Mac.

![7](https://user-images.githubusercontent.com/64184513/175776409-de0300c0-4908-4e94-ac28-6ac0e980f2b0.jpg)

12- Salga del panel de configuración.

13- Inicie Kali, llegará a la pantalla de inicio de sesión:

Username: kali
Password: kali

---------------------------------------
## Comenzando con Kali Linux - Paso a Paso

- Ahora que estás en tu nueva máquina, haz clic en el menú y abre una terminal ROOT (la roja)
contraseña: kali

escribe este Comando;

    apt-get update && apt-get upgrade -y
- ¡Ahora vamos a continuar en esta página!
https://github.com/SobrioRiot/no-more-esp

