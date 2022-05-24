# Instalación y Configuración Windows 10

Herramientas utilizadas:

<a href="https://www.virtualbox.org/">- Oracle VirtualBox</a><br>
<a href="https://www.microsoft.com/es-es/software-download/windows10">- Windows 10 ISO</a>

Lo primero de todo antes de proceder a la instalación de Windows 10 en VirtualBox será acceder a la página oficial de Microsoft y descargar la herramienta de creación de medios, la cual ofrece la posibilidad de obtener la imagen ISO de Windows 10. El siguiente paso consisitirá en la descarga de Oracle Virutal Box y su instalación. A continuación se proseguirá con los siguientes pasos.

1. Se ha de abrir Oracle Virtual Box, a continuación se ha de presionar el botón "Nuevo" para crear una nueva máquina virtual.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169855029-8f26deef-dc0c-4c9c-8986-ec91c8054c9b.png">
 </p>
 
2. El siguiente paso consistirá en la parametrización de la máquina virtual, como se podrá observar en la siguiente captura se ha de definir el nombre de la máquina virtual, la ubicación, el tipo de sistema operativo a instalar junto a su versión, la memória ram necesaria para su correcto funcionamiento (recomendado 4GB) y la creación del disco duro virtual.

 <p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169855041-3e6d9f7b-23eb-4a80-a653-ef9720a3a156.PNG">
 </p>
 
3. Una vez pulsado el botón aceptar de la anterior pre-configuración habrá que activar la unidad óptica virtual para introducir la imagen ISO del sistema operativo a instalar, para ello se seleccionará la máquina virtual y se presionará el botón configuración. 
 
 <p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169855051-231c5ff6-f71c-4983-af0f-dde1e86cffb1.png">
 </p>
 
4. Se ha de seleccionar sistema en la sección de la ventana ubicada en la izquierda y seleccionar la unidad óptica para acceder a su menú de configuración. 
 
 <p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169855065-1b7ac31c-21ec-4e00-8444-80c618383b68.png">
 </p>
 
5. En la siguiente imagen se puede observar como se ha entrado en la pestaña almacenamiento, se selecciona la unidad óptica, se marca la opción de CD/DVD vivo para que al arrancar la máquina detecte la unidad óptica y se carga la imagen ISO del sistema operativo.
 
 <p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169855073-d940e5ca-4f98-418e-8e2b-569a61e6b799.png">
 </p>
 
8. El siguiente paso será seleccionar la máquina virtual y presionar el botón iniciar.
 
 <p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169857969-4d7f64f0-c0be-43e9-84e7-8af7f051b7c3.png">
 </p>
 
9. En la siguiente imagen se puede observar que la máquina virtual ha entrado en funcionamiento, la flecha indica el "CD/DVD" en vivo con la imagen ISO de windows 10 cargada. En este punto solo cabe esperar que avance hasta el primer menú del instalador de Windows.

 <p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169858047-168e6605-18c2-43f6-817d-eb0d6ec84765.png">
 </p>
 
10. En el siguiente menú se tendrá que elegir el idioma del sistema operativo, el sistema de fecha y moneda y el idioma del teclado, una vez seleccionado se ha de pulsar siguiente.
 
  <p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169858501-19f62b5e-e244-4550-b1b5-134a56b165f0.PNG">
 </p>
 
11. En el siguiente menú se hanrá de pulsar el icono de instalar ahora, en la parte inferior de la ventana de instalación se puede observar también la opción de reparar el equipo, esta solución es utilizada en caso de rotura de sistema de arraque u otras opciones como el haber olvidado la contraseña del propio Windows.
 
 <p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169858575-a9572f92-1f2f-4325-983d-317f6a7b0daf.PNG">
 </p>
 
12. Windows preparará la instalación. 
 
<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169859242-85642ca6-72d2-4a19-a0c5-85b0f8d394e0.PNG">
</p>

13. Se introducirá la clave de activación de Windows en caso de tenerla, y en caso de no disponer de ella en este preciso momento se deberá presionar la opción de "No tengo clave de producto", muy recomendable tener el sistema operativo activado.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169859294-0bd16ead-64e3-427b-9302-b392efed19e1.PNG">
</p>

14. En este menú se tendrá que seleccionar la versión del equipo operativo que se desea instalar, en esta guía se instalará el windows 10 pro de arquitectura 64 bits. La arquitectura se elegirá en función del procesador y ram del dispositivo, en dispositivos con la ram superior a 4GB y un procesador superior a un Dual Core es recomendable instalar Windows 10 de 64 bits. 

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169859336-72966a31-4c70-4867-8268-7b6cc5f6d881.PNG">
</p>

15. Se aceptan los términos de licencia de Windows.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169859397-6ebd0122-b668-4bea-bae6-e97bd09ad19d.PNG">
</p>

16. Se selecciona la opcioón personalizada de instalación para poder manipular los discos duros y particionar el sistema operativo.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169859454-8ccf1886-9260-4ebf-9e68-9131c09dce2a.png">
</p>

17. En el caso de esta guía solo se ha utilizado un disco duro de 25GB, lo que será una única partición, en el caso de disponer de varios discos aparecerán espacios sin asignar en diferentes unidades, a la hora de crear particiones se ha de seleccionar la unidad y pulsar nuevo.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169859504-9096e738-0761-4d15-9588-674d3a44cfb4.PNG">
</p>

18. A continuación se selecciona el tamaño de la particion deseada y se aplicarán los cambios. Cada vez que se desee crear una partición se realizará el mismo procedimiento. Lo más recomendable es tener una partición de sistema, una de datos y otra de seguridad, preferiblemente la de seguridad en otro disco duro.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169860463-dbcba8d5-dcc8-4ea7-b607-cef043b7cdfc.PNG">
</p>

19. Se seleccionará la partición donde se desea instalar el sistema operativo y se presionará el botón siguiente.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169860499-6223bb4a-a025-41a1-86d5-c88e8a51827d.PNG">
</p>

20. Comenzará la instalación del sistema operativo.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169860533-0a5a1399-53d3-4b12-aae1-9806066dcb09.PNG">
</p>

21. Se finaliza la instalación del sistema operativo.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169860573-5576ec11-accb-4e70-8683-9a7abf03faaf.PNG">
</p>

22. A continuación el instalador nos pedirá que se reinicie el equipo, se presiona el botón reiniciar.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169861407-31f59663-650a-4d95-9538-3bf0500c85cc.png">
</p>

23. Se extrae la imagen del sistema operativo de la unidad óptica para evitar que vuelva a entrar en la instalación.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169861452-2c2089f7-e059-4a54-9063-bc68af30f52d.png">
</p>

24. A continuación se muestra el sistema operativo instalado.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169861500-bf16b739-1b8c-4647-9887-6c395a235685.png">
</p>

25. Se habrá de esperar a que arranque el configurador de la instalación para acabar de parametrizar Windows 10.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169861563-dac864d4-83e6-4568-abf6-dc1814f22d07.PNG">
</p>

26. A continuación se ha de seleccionar la región.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169862592-ca27290d-a274-482d-9074-9c8032245f94.PNG">
</p>

27. Se añade la distribución de teclado que se desea utilizar en Windows.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/169862665-08c52295-0bd1-4a94-a497-8d974ff6d315.PNG">
</p>

28. Se selecciona el tipo de organización a la que pertenecerá el equipo.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170004048-d5e3b299-e8e2-4eeb-ba98-9ce491a718d7.PNG">
</p>

29. Se añade la cuenta de hotmail o se selecciona cuenta sin conexión, dicha opción permite tener una cuenta sin vincular con el correo electronico.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170004195-e64f6632-508a-4662-8886-9eba5d8e39eb.PNG">
</p>

30. Se define el nombre de usuario.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170004552-bb53a210-7fbe-4c61-8fe7-b1206647b764.PNG">
</p>

31. Se define la contraseña del usuario.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170004688-0b338fe2-21e8-49c6-bc7f-c9c5bf1536ec.PNG">
</p>

32. Se selecciona la compartición de ubicación con microsoft.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170004913-4e0428cb-f857-4d03-81b2-7d999e32ab02.PNG">
</p>

33. Se selecciona la opción deseada en eonctrar mi dispositivo.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170005231-df62a006-bcec-4b7f-bf12-c0990220cdc0.PNG">
</p>

34. Se selecciona el envio de datos diagnósticos a microsoft.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170005436-3155d0ae-7245-45b4-ae44-bc070f739086.PNG">
</p>

35. Se selecciona la definición de entradas manuscritas.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170005640-50b46399-b8cb-479c-af9c-36114f5eb77f.PNG">
</p>

36. Se selecciona la obtención de experiencias personalizadas según el diagnóstico realizado.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170005952-2651225d-324d-4196-856e-2175a0592bed.PNG">
</p>

37. Se selecciona que las aplicaciones usen el id de la publicidad.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170006488-46eebb78-42e2-48ca-895c-a0d7268def1c.PNG">
</p>

38. Se selecciona la personalización de la experiencia de usuario.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170006684-5eb0a59d-d5f0-461f-8362-d46c0c9cafcf.PNG">
</p>

39. Se selecciona la opción de cortana, se puede tanto aceptar como no aceptar.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170007122-5826e039-8f42-43de-9a55-511e780c13f4.PNG">
</p>

40. Se configurará el sistema operativo, este este paso habrá que esperar a que se apliquen los cambios y se muestre el escritorio de Windows 10.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170007358-a6ec9a97-45a4-483a-9aaf-6bd9e5b26e8e.PNG">
</p>

41. A continuación se muestra por fin el escritorio de Windows 10.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170007832-55880796-d0f5-4f78-bb9d-2fb6e88811ae.PNG">
</p>

42. Para proseguir se realizarán configuraciones básicas de rendimiento para optimizar el funcionamiento del sistema operativo. Lo primero de todo será quitar todos los add-on de la barra de navegación, todos los componentes que sean extras consumen memória.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170008245-c72ff6c8-be0b-46c1-9aa1-fef76ec3e761.PNG">
</p>

43. Se deshabilitará la barra de búsquedas y navegación, para ello se pulsará botón derecho en la barra de navegación y se pulsará en el botón de ocultar.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170008543-72387627-4a17-49db-95f5-d696fd9d412c.PNG">
</p>

44. El siguiente paso será ocultar el botón de cortana, para ello se pulsará el botón derecho en la barra de herramientas y se quitará la marcación del botón de cortana.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170008834-ee95288a-60a1-4524-a874-db1869c3a961.PNG">
</p>

45. A continuación se parametrizarán las propiedades de sistema para aumentar el rendimiento, para ello se ha de pulsar en el icono de la carpeta en la barra de herramientas, este equipo, propiedades del sistema.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170010435-8273370b-d842-4075-a675-6d403c0c2f97.PNG">
</p>

46. Se presionará la opción de "Configuración avanzada de sistema" en la parte inferior de la ventana.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170010837-0d1bbc03-36b0-49d8-9ac9-f8b8facf6750.PNG">
</p>

47. Se configurará el rendimiento del sistema e, la pestaña de "Opciones avanzadas", rendimiento, botón configuración, se abrirán las opciones de configuración y en la pestaña de efectos visuales se seleccionará la opción ajustar para un mejor rendimiento, se aplicarán cambios y se aceptará este proceso.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170011259-1b43ae75-b4a5-4b32-b11b-448ff7cda108.PNG">
</p>

Una vez configurado el rendmiento básico del sistema operativo faltará instalar las aplicaciones necesarias para su utilización, es recomendable para no perder tiempo utilizar herramientas de instalación de software automatizado, uno de ellos es "NINITE" en el que se podrán seleccionar los diferentes programas a instalar, se presionará el botón de descargar y se obtendrá un instalador, se ejecuta y automáticamente se instalarán las aplicaciones.

<p align="center">
  <img src="https://user-images.githubusercontent.com/103035621/170011752-6245930e-a0cc-4ab2-928c-813af87ff980.png">
</p>

* Imagen obtenida del búscador.
