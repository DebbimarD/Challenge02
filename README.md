# Challenge 02 - Kirby

## Integrantes del equipo
- Debbimar Díaz Santiago
- Jonlier Díaz Rivera
- Jeremy Curry Romero

## Reglas del reto
Hacer un prefab de Kirby y 4 variantes (4 kirbys diferentes). Crear un terreno y intepretar un área de Puerto Rico.

---

## Proceso

### Kirby Prefab
<div align="center">
  <img src="kirby prefab.png" width="50%" />
  <p><i>Iniciando con el prefab.</i></p>
</div>

Lo primero que se hizo fue ir a Objetos 3D y seleccionar la esfera para hacer el cuerpo de Kirby y luego volvimos a seleccionar en el área de objetos, pero esta vez son dos cápsulas y estas se modifican de tamaño, con la herramienta de escala se hacen más pequeñas y luego con la herramienta de mover se colocan enfrente de la esfera (cuerpo) y con esto se hicieron los ojos. Una vez esos primeros pasos se arrastra ese objeto al área de assets para crear un prefab. 

### Rigidbody
<div align="center">
  <img src="kirby prefab rigidbody.png" width="50%" />
  <p><i>Se agrega el rigidbody.</i></p>
</div>

En el prefab, en la opción de de agregar componentes, se selecciona y se busca la opción de rigidbody y la agregamos.

### Variants
<div align="center">
  <img src="kirby prefab variants.png" width="50%" />
  <p><i>Se crean 4 variantes del prefab</i></p>
</div>

Después de haber creado el prefab, se hacen 4 variantes para los diferentes Kirbys y esto se hace arrastrando el prefab principal al área de assets y unity te da un aviso de si quieres crear un prefab variants y al marcar que si ya tenemos el primer variant. Se hacen los mismos pasos para el resto de los variants.

### Kirby Normal Prefab Variant 1

Para la primera variante, hicimos un Kirby normal. Primero, añadimos una cápsula, la redimensionamos y movimos el objeto de tal forma que quede como si fuera un pie de Kirby. Luego, al tener el primer pie, lo dublicamos y rotamos para posicionarlo en el otro lado. Similarmente, añadimos otra cápsula nueva para crear un brazo. Para ello, modificamos y escalamos los ejes X, Y y Z del objeto. Lo duplicamos y lo reposicionamos al otro lado para que quede terminado sus brazitos. Por otro lado, insertamos al proyecto una esfera para crear ese rubor característico que tiene en la cara de Kirby. Fue un poco complicado ya que se jugó con las herramientas de posicionamiento para que quede así de ovalados, como se muestra en la imagen. Una vez más, añadimos otra esfera para darle una sonrisa a Kirby. Se aplastó la esfera, se movió el objeto y se rotó para que quedar una pequeña sonrisa. Finalmente, para este Kirby, se le añadió a los ojos el típico reflejo de los ojos cuando le da la luz. Para eso, se creó una cápsula, se puso más pequeño el cilindro y se posicionó en la parte superior y se duplicó para que lo tengan los dos ojos. 


### Kirby Mike Prefab Variant 2 
<div align="center">
  <img src="micro.png" width="50%" />
  <p><i>Microfono</i></p>
</div>

Para el segundo Kirby en este caso la version de Mike, en el cual es un Kirby con micrófono y audífonos. Lo que se hizo para este Kirby fue acomodar los brazos y los pies con la herramienta de mover y rotar. Aqui lo principal era crear el micrófono, para este se fue al área de objetos y se escogió un cilindro y con la opción de escala se minimizó para que fuera el tamaño correcto para nuestro Kirby. Luego con una esfera y la herramienta de escala como que la aplastamos para hacer una especie de plato hondo y luego duplicamos eso y con la herramienta de escala se agranda un poco para que quede más redondo y hacer la base del microfono con más detalle. Por último, con un cubo, se uso la herramienta de escala para ponerlo más pequeño y luego hacer la base de arriba del micrófono y ese cubo se duplicó para hacer algo similar que se hizo para la base del tubo y luego de que tenemos el cubo ya pues se edita la escala para hacerlo un poco más pequeño y que quede el micrófono dentro de la base del micrófono y con la herramienta de mover se coloca arriba del cilindro y base que en cojunto hacian el agarre del micrófono.

<div align="center">
  <img src="kirby mic adjustment.png" width="50%" />
  <p><i>Posicionamiento del micrófono.</i></p>
</div>

Aquí con la herramienta de mover y rotar se colocó el micrófono en la mano de Kirby.

<div align="center">
  <img src="kirby mike final.png" width="50%" />
  <p><i>Kirby Mike terminado.</i></p>
</div>

Finalmente, se hicieron los audífonos. Primero, con algo similar que se hizo la base del agarre del micrófono pues se hicieron las almohadillas de los audífonos. Con una esfera que se aplasto y otra que quedó más redonda se hizo una almohadilla y luego se duplicó para colocarla una en cada lado del cuerpo de Kirby. Por último, se utilizaron 3 cilindros para hacer el "casco", es decir, lo que conecta las almohadillas y crea el auricular. Con la herramienta de escala se puso el cilindro más pequeño y se colocó en la parte de arriba del cuerpo de Kirby y se duplicó ese cilindro y se puso aún más pequeño y. Para finalizar, con la herramienta de rotar y mover, se colocó uno en cada lado conectando las almohadillas.

### Kirby Sword Prefab Variant 3
<div align="center">
  <img src="cejas sphere.png" width="50%" />
  <p><i>Cejas.</i></p>
</div>

Para la variante 3, Kirby Sword. Lo primero que se hizo fue agregar una esfera de objetos y con la herramienta de escala se hicieron más pequeñas y se estiró para hacer una especie de ceja. Luego, con la herramienta de rotar y mover se colocaron sobre los ojos y así lograr la expresión más ruda de Kirby.

<div align="center">
  <img src="sword handheld with sphere.png" width="50%" />
  <p><i>Mango de la espada.</i></p>
</div>

La cosa más importante para lograr este Kirby es la espada. Para esto, primero se agregó un cilindro y se hizo más ancho que el del micrófono. Con la herramienta de escala fue que se minimizó un poco. Luego, se agregó otro cilindro el cual, con la herramienta de escala, se aplasto bastante para el diseño del mango, con una esfera la cual se editó y se puso más pequeña con la escala pues se coloca en el centro del diseño arriba del agarre y se duplicó para colocarlo en ambos lados de la espada y quedara el mango asi. Para el resto de la espada, especificamente para el filo y la espada como tal se utilizó un bloque y con la opción de escala se alargó y se colocó encima del mango. Despues con dos cubos pequeños, se coloco la punta de la espada, es decir, se creó el efeccto de diamante o filo en la espada. Con la rotación y lo de mover, se colocó la espada en la mano del Kirby. Para este Kirby, los pies y brazos se movieron y rotaron de posición para poder recrear la pose de la imagen. Una vez la espada en su sitio, con una esfera y la opción de escala se aplastó para hacer la base del gorrito. Acto seguido, con otra esfera, se alargó para recrear el gorro y se colocó encima del Kirby y se posicionó para que pareciera el gorro más o menos caido. Por último, se minimizó una esfera para crear la punta del gorro.

<div align="center">
  <img src="gorro spheres.png" width="50%" />
  <p><i>Kirby Sword terminado.</i></p>
</div>

### Kirby Ness Prefab Variant 4
<div align="center">
  <img src="https://github.com/user-attachments/assets/72d0d017-a0a8-4399-a260-dacb19d858fd" width="50%" />
  <p><i>Parte 1 (Prefab)</i></p>
</div>


Para hacer a Kirby Ness, primero utilizamos el Kirby Simple como prefab y creamos una variante del mismo.

<div align="center">
  <img src="https://github.com/user-attachments/assets/fa0a87db-62fc-43c9-937d-e9aeb0178497" width="50%" />
  <p><i>Parte 2 (Corona de la gorra)</i></p>
</div>


Luego de haber creado el prefab, utilizamos una esfera para crear la corona de la gorra (la parte superior). Aplastamos ligeramente la esfera para que quedara un poco plana y la agrandamos de modo que sobresaliera de la cabeza de Kirby, simulando así la gorra. Esta parte tomó algo de trabajo, ya que fue un reto lograr que la parte superior se viera circular y, al mismo tiempo, que los lados se vieran planos para que pareciera una gorra real.

<div align="center">
  <img  src="https://github.com/user-attachments/assets/f87c6f73-a189-4bce-ab22-6d9e8c97d281" width="50%" />
  <p><i>Parte 3 (Visera de la gorra)</i></p>
</div>

Al terminar la corona, comenzamos a crear la visera de la gorra. Para esto utilizamos otra esfera, se redujo bastante de tamaño y la aplanamos de forma pronunciada para que quedara bien plana en la parte inferior. Luego estiramos un poco la parte superior para darle la curva característica de la visera. Por último, la colocamos en la parte frontal de la cabeza de Kirby.

<div align="center">
  <img  src="https://github.com/user-attachments/assets/c70b4f43-da99-4b66-b34d-89138e322595" width="50%" />
  <p><i>Parte 4 (Botón de la gorra)</i></p>
</div>


Después de terminar la visera, creamos el botón superior de la gorra. Simplemente utilizamos una esfera y la redujimos bastante para que quedara como una pequeña bolita. Cuando el tamaño pareció adecuado, la colocamos en la punta superior de la gorra.

<div align="center">
  <img  alt="colored ness" src="https://github.com/user-attachments/assets/ef63c5bb-2297-494b-a58b-54ff0fe56c2c" width="50%" />
  <p><i>Parte 5 colorear a Kirby Ness)</i></p>
</div>


Una vez colocadas todas las partes de la gorra de Kirby, comenzamos a colorearlas. Para esto, en la parte inferior de Unity creamos materiales para cada color. Cambiamos los colores al tono correspondiente y luego arrastramos el material sobre cada objeto que queriamos pintar.



### Terrain

<div align="center">
  <img src="kirby mike in terrain.png" width="50%" />
  <p><i>Kirby Mike en Terrain.</i></p>
</div>

<div align="center">
  <img src="kirby sword in terrain.png" width="50%" />
  <p><i>Kirby Sword en Terrain.</i></p>
</div>

<div align="center">
<img alt="complete ness" src="https://github.com/user-attachments/assets/70a8e4a9-da94-4e75-8278-ecb6ed3a8192" width = "50%"/>
  <p><i>Kirby Ness on Terrain and ready to fight!.</i></p>
</div>

### Memoria o Historia
"Cuando era pequeña, cuando estaban de moda los Nintendo DS, yo tenía uno y un juego que jugaba bastante. Era sino mal recuerdo Kirby Súper Star Ultra. Lo jugaba mucho juntos al resto de juegos de la franquicia de Nintendo. Pero Kirby específicamente es un juego que me marcó bastante y de los que más recuerdo, junto a Starfy que era similar y Yoshi Island. Hace mucho no juego ninguno de Kirby ya que no sentía el mismo “hype” a los antiguos que habían de plataforma en DS. Esos juegos tenían ese toque que sin importar que no te aburrías. Actualmente me ha llamado la atención el juego más reciente que han sacado de Kirby in The Forgotten Land que es parecido al Mario Odissey en cuestión del mundo abierto y se ve interesante pero aún no me he tomado la oportunidad de comprármelo." - Debbimar

"Cuando era pequeño me gustaba mucho jugar Super Smash Bros., desde la versión de Nintendo 64 hasta Brawl. Uno de los personajes que más me gustaba usar era Kirby, ya que era muy fácil de manejar y tenía buenas habilidades. Lo que más me llamaba la atención de él era su habilidad única: podía imitar las habilidades de sus oponentes cada vez que los “chupaba”. La que más me gustaba imitar era la del personaje Ness, porque cuando Kirby le robaba su habilidad también se ponía la gorra de Ness, y se veía bien cute con ella. Al realizar este proyecto me dio mucha nostalgia, porque Kirby es un personaje que me recuerda mucho a mi infancia y me hizo dar un verdadero viaje al pasado." - Jeremy

### Esperiencia Ganada
"De este challenge lo que más me sorprendió fue la cantidad de veces que utilice esferas. Al kirby ser un personaje redondo y casi todas sus extremidades ser de la misma forma pues muchas cosas eran con esferas, pero en otros Kirbys se utilizaron también cubos, cilindros e incluso cápsulas. Me sorprendió como con objetos 3D simples se logro hacer "objetos" o assets mas complejos como el microfono y la espada." - Debbimar

"Este challenge me gustó mucho, ya que tuve la oportunidad de crear a Kirby, uno de los personajes que marcó mi infancia. La parte que más trabajo me dio fue la de crear sus zapatos, porque no sabía qué objeto utilizar. Al final terminé usando la esfera, con la que pude hacerlos lo más parecidos posible al Kirby original. Espero que algún día pueda aprender a utilizar más herramientas de Unity para crear personajes como Kirby de forma más precisa y elaborada." - Jeremy
