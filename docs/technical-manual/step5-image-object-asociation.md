# Asociar Imágenes con GameObjects

Se puede asociar un solo objeto, regularmente un objeto 3D, al conjunto de imágenes agrupadas por el “AR Tracked Image Manager” asignando el objeto al campo “Tracked Image Prefab”. De esta forma, al ser reconocida alguna de las imágenes por medio de la realidad aumentada se mostrará en pantalla el objeto asociado.

![image](https://github.com/devemg/historiAR/assets/43097082/4d0e731d-45c0-4cb8-bb48-70e5cae4c260)

Para usos de este proyecto, el campo se deberá quedar vacío dado que la asociación imagen-objeto se realizará por medio de código fuente. A continuación, crear un script dando clic derecho sobre la carpeta de “assets/scripts” y crear un script C#. 

![image](https://github.com/devemg/historiAR/assets/43097082/8af96fd6-2736-4b59-ae2e-76759389022e)
![image](https://github.com/devemg/historiAR/assets/43097082/9357ec5b-84c7-46e8-a6c1-044d2e8fe8c7)

Dar doble clic sobre el archivo para abrirlo en su editor favorito. 

![image](https://github.com/devemg/historiAR/assets/43097082/32c31bd2-23d9-4b12-b395-559852484815)

El código se debe asociar el script al objeto “AR Session Origin”, seleccionando el objeto, arrastrando y soltando el script en el panel de configuración ubicado en el panel derecho del editor.	

![image](https://github.com/devemg/historiAR/assets/43097082/791dfc8b-1b6b-434f-8622-0c9ca56a033e)
![image](https://github.com/devemg/historiAR/assets/43097082/5f07f3b7-447c-4c3c-9b34-fd762ae6bd6f)

El script utilizado se puede encontrar en la carpeta `scripts/image-tracking.cs`.

