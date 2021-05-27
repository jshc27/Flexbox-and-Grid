# ¿Flexbox o Grid Layout?

En este repositorio vas a encontrar el diseño de una interfaz visual que se utiliza para practicar las técnicas de Flexbox y Grid Layout. 

### Ejemplo práctico

#### ¿Como se hizo la maquetación?

En primer lugar utilizamos div para crear una sección o agrupar contenidos. Por lo tanto, funciona semanticamente para que sea el contenedor principal de la UI.
Esto significa que podemos colocar cualquier tipo de contenido dentro; teniendo en cuenta que esta definido como un elemento en bloque. 

Dentro del contenedor principal agregamos tres etiquetas (nav, div, div). A nivel de arquitectura nos divide la UI en las partes generales de interacción.
Cada etiqueta cuenta con su respectiva clase alimentada por la metodologia BEM. 


#### ¿Por qué nav?
Representa una sección cuyo proposito es proporcionar enlaces de navegación. Nos permite recrear un "menu" y acceder a sus elementos para interactuar
con ellos.

![Captura de pantalla 2021-05-22 115529](https://user-images.githubusercontent.com/56690309/119234661-b1a37c00-baf4-11eb-9c43-40dfdff1a329.png)

En la etiqueta nav con clase "container_left" se agregaron imagenes en representación de los iconos con su respectivo pixelaje. Se utilizó, display: grid;
place-items: center; con el proposito de que tomara una alineación vertical centrada. 

![Captura de pantalla 2021-05-26 171001](https://user-images.githubusercontent.com/56690309/119737658-3d930c00-be45-11eb-90e0-5d470165a5df.png)

En la etiqueta div con clase "container_center" es un contenedor principal(general) la cual tiene los elementos especificos, se agregarón los 6 contenedores internos. Dentro de cada uno se trabajo con display: flex para dar organizacion horizontal de cada elemento.   

![Captura de pantalla 2021-05-26 170556](https://user-images.githubusercontent.com/56690309/119737352-c3628780-be44-11eb-8c89-d4c397e6c4fa.png)


Finalmente se repitió el mismo proceso para la etiqueta div con clase "container_right" agregando los espaciados e imagenes correspondientes. 

![Captura de pantalla 2021-05-26 171251](https://user-images.githubusercontent.com/56690309/119738043-a4182a00-be45-11eb-8558-43fc13d04c7a.png)

Conclusión: Las tecnicas Flexbox & Grid se deben utilizar de acuerdo a la maquetación del proyecto, haciendo uso adecuado de sus etiquetas y semanatica. Grid layout para diseños multidimensionales donde se aprecien varias filas y columnas al mismo tiempo y flexbox para diseño de una dimension para fila y columna.


![Captura de pantalla 2021-05-28 a las 14 50 51-fullpage](https://user-images.githubusercontent.com/56690309/119888550-18f96b80-befb-11eb-85e7-15d799e9bce4.png)


Fuente:  https://www.figmafinder.com/figma-e-learning-ui
     



