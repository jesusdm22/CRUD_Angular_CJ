                            ___   _   _  _____  _   _  _       ___  ______        ___
                           / _ \ | \ | ||  __ \| | | || |     / _ \ | ___ \      /   |
                          / /_\ \|  \| || |  \/| | | || |    / /_\ \| |_/ /     / /| |
                          |  _  || . ` || | __ | | | || |    |  _  ||    /     / /_| |
                          | | | || |\  || |_\ \| |_| || |____| | | || |\ \     \___  |
                          \_| |_/\_| \_/ \____/ \___/ \_____/\_| |_/\_| \_|        |_/

                       TRABAJO REALIZADO POR JESÚS DÍAZ MUÑOZ Y CRISTIAN CABRERA GONZÁLEZ
                       
                                      CREA TU APLICACIÓN CON ANGULAR 4

-----------------------------------------------------------------------------------------------------------


A continuación, realizaremos la instalación e implementación en el servidor de la Aplicación Angular.
Para este proyecto hemos desarrollado una aplicación CRUD la cual nos permite listar, añadir, modificar
y eliminar empleados de una lista en tiempo real y sin necesidad de recargar la página en ningún momento.
Además, esta aplicación que usa Angular, va de la mano de Bootstrap, Popper y jQuery, tecnologías las
cuales ya vienen implementadas en la aplicación. 

Es recomendable realizar los pasos detallados en el archivo INSTALACION1 antes de ponerse a hacer los
pasos que se van a indicar a continuación. En caso de que ya los hayas realizado y tengas NodeJS en tu
servidor, tienes vía libre para lanzar este proyecto en tu servidor.


-----------------------------------------------------------------------------------------------------------


IMPLEMENTACIÓN DE LA APLICACIÓN EN TU SERVIDOR

1. La aplicación como bien hemos indicado anteriormente, será lanzada a través de NodeJS así que para
comenzar debemos situarnos en la carpeta /opt.

2. Cuando ya nos hemos situado en la carpeta /opt, lo que debemos hacer es muy simple:

                         git clone https://github.com/jesusdm22/CRUD_Angular_CJ.git

3. Esto comenzará a extraer todo el contenido de este contenedor Git el cual aloja la aplicación con la
que queremos trabajar.

4. Una vez se haya extraido, entramos dentro de la carpeta que nos habrá dejado y solo nos quedará lanzar
la aplicación mediante el siguiente comando:

                                 ng serve --host <Tu IP donde lanzarás la app>
                                      EJ: ng serve --host angularapp.com
                          
5. Todo debe salir correctamente y el proyecto debe empezar a compilar hasta el 100%. Una vez llegamos a
este punto, el proyecto se iniciará y se podrá acceder a él desde nuestro navegador web con la dirección:

                                            <Tu IP o host>:4200
                                          EJ: angularapp.com:4200
                                     
                            ¡Y listo... ya tendríamos nuestra app Angular funcionando!
