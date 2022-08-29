# Cómo instalar Kali Linux en VirtualBox en Windows - Paso a Paso
-----------------------------------------------
- Última actualización: 20/07/2022

- NOTA: Los siguientes enlaces descargarán los archivos automáticamente, así que sólo haz clic en ellos desde donde vayas a instalarlos. 
----------------------------------------------  
1- Descargar VirtualBox: https://download.virtualbox.org/virtualbox/6.1.36/VirtualBox-6.1.36-152435-Win.exe

2- Descarga el paquete de extensiones: https://download.virtualbox.org/virtualbox/6.1.36/Oracle_VM_VirtualBox_Extension_Pack-6.1.36a-152435.vbox-extpack

3- Descarga kali Linux: https://kali.download/virtual-images/kali-2022.2/kali-linux-2022.2-virtualbox-amd64.ova

4- Debes activar el subsistema de Windows para Linux. Para ello, escriba "Características de Windows" en la barra de búsqueda del menú de Windows, luego abra, baje y marque la casilla "Subsistema de Windows para Linux", luego guarde, salga y reinicie su ordenador.

![photo_2022-06-10_14-44-13](https://user-images.githubusercontent.com/64184513/175776446-b373d0e5-4672-471f-a78a-93e0f2891313.jpg)

5- Abre VirtualBox y sigue las instrucciones de instalación.

6- Haz clic en "archivo" en el menú, y en "preferencias" y luego en "extensión", añade el paquete de extensión que descargaste anteriormente.

![8](https://user-images.githubusercontent.com/64184513/175776890-4f44fdbd-97ec-4bf9-bcf1-8db3aafa4459.jpg)

7- Vuelve a hacer clic en "archivo" en el menú, y luego en "Importar dispositivo".

![1](https://user-images.githubusercontent.com/64184513/175776398-7038d85a-a306-4c4c-ad89-325b5c938383.jpg)

8- Selecciona el Kali que descargaste (archivo .ova) y haz clic en continuar.

![2](https://user-images.githubusercontent.com/64184513/175776400-a41767db-3686-4a3b-b978-bf136286f9f0.jpg)

9- Haga clic en "Importar".

![3](https://user-images.githubusercontent.com/64184513/175776402-4eff95b8-9785-47e1-9877-67df34d808e2.jpg)

10- Abre la "configuración" de tu nueva Kali, y pon al menos 2 CPUs por cuestiones de rendimiento + 4GB de RAM. (no sobrepasar la línea roja)

![4](https://user-images.githubusercontent.com/64184513/175776404-1eb16270-54d3-4d42-9741-2d2bbb0ce29b.jpg)
![5](https://user-images.githubusercontent.com/64184513/175776405-1227974e-c82f-4272-9b58-8163c14687e0.jpg)

11- En la sección de "red", pon el "Attached to" a "Bridge Adapter" y aleatoriza la dirección Mac.

![7](https://user-images.githubusercontent.com/64184513/175776409-de0300c0-4908-4e94-ac28-6ac0e980f2b0.jpg)

12- Salga del panel de configuración.

13- Inicie Kali, llegará a la pantalla de inicio de sesión:
Nombre de usuario: kali
Contraseña: kali

---------------------------------------
## Comenzando con Kali Linux - Paso a Paso

- Ahora que estás en tu nueva máquina, haz clic en el menú y abre una terminal ROOT (la roja)
contraseña: kali

escribe este Comando;

    apt-get update && apt-get upgrade -y
- ¡Ahora vamos a continuar en esta página!
https://github.com/HowardlRoark/no-more.git


## Si gustas apoyar mi trabajo de traducciones, puedes invitarme un cafe.
![image](https://user-images.githubusercontent.com/110576526/187119843-58ad3b99-0da1-454f-a8bf-481088d3e6e1.png)
