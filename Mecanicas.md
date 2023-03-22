## Armas

Un cazador puede ser experto en varias armas, pero con ciertas limitantes

- 4 armas ligeras
- 2 armas ligeras y 1 pesada o técnica
- 1 arma pesada y 1 técnica u otra arma pesada

### Armas ligeras

Puedes elegir el modificador que quieres usar al inicio de la campaña para estas armas, entre fuerza y destreza

- [Arco](./Armas/Arco/Arco.md)
- Hojas duales
- Espada y Escudo
- Espada Larga

### Armas pesadas

- Gran Espada
- Martillo
- Lanza
- Hacha Cargada

### Armas técnicas

- Hacha Espada
- Magnet Spike
- Cornamusa
- Lanza pistola

## Daño elemental

Los monstruos y armaduras de cazadores tienen de 0 a 3 estrellas de debilidado resistencia elemental
al recibir un ataque elemental, reciben o reducen un 20% extra de daño por cada estrella (mientras no sea un daño elemental fijo)

Las resistencias elementales de las armaduras pueden ser tanto positivas como negativas

3 estrellas de resistencia = 60% daño reducido a ese elemento
-3 estrellas de resistencia = 60% daño recibido de ese elemento

## Daño contundente

### vs el monstruo
Los monstruos pueden ser aturdidos (a menos que tengan inmunidad) y para poder ser aturdidos deben ser alcanzados
por una cierta cantidad de daño contundente en su cabeza, el daño contudente se calcula en base al daño realizado + un % a la
vulnerabilidad al aturdimiento del monstruo

la cantidad necesaria para aturdir monstruos varia dependiendo de su tamaño

Se necesitan un numero de Hit Dice del monstruo para poder aturdirlos, es decir, si un monstruo tiene un d8 como hit dice,
el daño necesario seria #d8, siendo # un valor dependiendo del tamaño del monstruo, este valor es calculado al inicio del
combate y luego por cada vez que el monstruo es aturdido

Hit Dices necesarios por tamaño de monstruo:

- Pequeños y medianos: 4 Hit Dice
- Grandes: 1/3 de sus Hit Dice + 10
- Gigantes: 1/2 de sus Hit Dice + 20

La vulnerabilidad al aturdimiento se mide en estrellas, llendo desde 0 hasta 3 estrellas, cada estrella aumenta un 20% del
daño realizado al daño acumulado necesario para aturdir

Al ser aturdidos, los monstruos son tirados al piso por 1 min, teniendo que hacer una DC de 10 de constitucion al final de cada turno
para terminar el efecto y no acumulan daño contundente hasta haber pasado 1 turno despues de levantarse

Por ejemplo entonces:

Si un monstruo tiene 10d10 como Hit Dice, es catalogado como monstruo Grande y tiene una debilidad de 2 estrellas al aturdimiento,
el calculo para saber cuanto daño contundente se necesita seria:

10 / 3 ~ 3.33333... redondeado a 3

3d10 + 10, podria ir desde 13 hasta 33 el daño contudente necesario por cada vez que es aturdido

si recibe un impacto de 10 puntos de daño contudente, el calculo final seria 10 + 40% = 10 + 4 = 14

### vs el cazador

Los cazadores pueden ser aturdidos al recibir 1/2 + 10 o más de sus hit dice como daño en un solo ataque contundente, al igual que los monstruos,
al inicio del combate y cada vez que el cazador es aturdido, debe recalcularse el daño necesario para ser aturdido.

Cuando los cazadores van a ser aturdidos, deben hacer una tirada de DC de 10 de constitución, si fallan pueden repetir la tirada al final de cada
uno de sus turnos para terminar el efecto o un compañero que este lo suficientemente cerca (1 metro / 5 pies) puede ayudarle a salir del efecto teniendo
que enfundar su arma y ayudarle como accion bonus o puede utilizar su accion bonus para dar un golpe a melee con su arma haciendole 1d4 de daño
y terminando el efecto

## Plagas Elementales

Los cazadores pueden verse afectados por plagas elementales inflingidas por el entorno o ataques de los monstruos, todas pueden ser curadas
gastando una accion de "Usar item" para comer una curibaya de la bolsa de objetos.

Los monstruos pueden ser afectados por plagas elementales, pero queda a decision del DM como aplicarlas

Las distintas plagas posibles y sus efectos son:

### Plaga de rayo

Da desventajas en tiradas de constitución, disminuye en 1 hit dice lo necesario para aturdirte, cualquier ataque cuenta como daño contundente para
aturdirte (a menos que sea elemental) y al recibir un ataque de rayo estando afectado por la plaga, serás aturdido inmediatamente sin hacer tirada de DC.

### Plaga de agua

Da desventajas en tiradas de destreza, no puedes usar ataques que requieran cargar o mantener
tu posición, solo puedes usar tu accion o accion bonus, no ambas, ademas te aumenta la debilidad al rayo en 1 estrella

### Plaga de fuego

Te estas quemando, al final de tu turno disminuye tu vida en base a lo que diga la acción que ocasionó la plaga, los ataques de agua
que recibas o usar una acción bonus para rodar encima de liquidos no inflamables te quitaran la plaga, tambien puedes gastar tu turno
en rodar por el suelo para quitar la plaga

### Plaga de hielo

Da desventajas en tiradas de fuerza, no puedes usar tu reacción, tu velocidad se reduce a la mitad, solo puedes hacer 1 ataque en cada turno

### Plaga de draco

Anula el daño elemental de tu arma, en caso de que tu arma fuera puramente elemental, la convierte en el daño del tipo de arma (cortante,
contundente o perforante) y ve su potencial reducido a la mitad, es decir, si un ataque realizara 2d10 de daño, solo haria 2d5

## Romper Partes de Monstruos

Todos los monstruos tienen mas o menos partes rompibles, romper partes de monstruos debilita sus capacidades ofensivas o defensivas, por lo que
es bueno idear una estrategia en contra de cada monstruo priorizando las partes a romper, cada parte es mas vulnerable a cierto tipo daño de daño
(cortante, perforante o contundente) de 0 a 3 estrellas, aumentando el daño que recibe al ser golpeado por el daño correcto en esas partes en un 10%
del daño realizado y un 20% como daño acumulado para romper la parte.

Para romper una parte del monstruo es necesario alcanzar un daño acumulado definido para la parte en especifico, generalmente esto es definido por el DM
para añadir mayor o menor dificultad a las cacerias, haciendo que las partes que mas benefician a un monstruo (como sus garras o alas) sean mas duras de
romper pero dando un mayor beneficio al romperlas

Un posible calculo para el daño necesario para romper una parte de monstruo puede ser 2 Hit Dice + 30 por cada parte, esto tambien da la posibilidad de que
el monstruo muera antes de que les rompan todas las partes.


## Crafteo de Armas y Armaduras

Al momento de cazar un monstruo consigues la posibilidad de hacerte full armadura del monstruo cazado, lo cual te altera las resistencias y te da habilidades
extras a manera de buffos.

Tambien puedes decidir hacer hasta 2 armas en lugar de la armadura, logrando conseguir armas que tienen un elemento nativo en sus ataques a manera de daño
elemental

Entre mayor nivel de peligro del monstruo cazado, mayores habilidades en la armadura y mejores numeros de daño elemental en el arma
