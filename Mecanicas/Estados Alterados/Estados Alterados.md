<link rel="stylesheet" href="../../base.css">

# Estados Alterados

Cuando aplicas un estado alterado la criatura objetivo deberá superar una tirada de <span style='color:var(--ataque)'>8</span> + <span style='color:var(--competencia)'>tu modificador de competencia</span> + <span style='color:var(--ataque)'>el modificador de daño</span>, a menos que la habilidad o ataque que aplica el estado alterado indique otro cálculo.

Siempre que una criatura sea victima de un estado alterado puede repetir la tirada inicial al final de cada uno de sus turnos para salir del efecto a menos que la habilidad o el ataque que aplica el estado alterado indique lo contrario.

## Parálisis

Una criatura que ha sido paralizada no puede reaccionar, ve reducida su <span style='color:var(--velocidad)'>velocidad</span> a 0 y solo puede realizar 1 ataque por turno.

## Sueño

Una criatura que ha sido dormida quedará fuera de combate, el primer golpe exitoso que reciba una criatura dormida siempre será crítico.

## Veneno

Una criatura que ha sido <span style='color:var(--veneno)'>envenenada</span> vera reducida su salud en un 1 Hit Dice por turno, a menos que la habilidad o ataque que aplica el veneno indique lo contrario.

# Aturdimiento

Este es un estado alterado especial, únicamente es aplicado por las armas que hagan daño <span style='color:var(--contundente)'>contundente</span> o los ataques que especifiquen debe ser considerado como tal.

### Aturdimiento vs el monstruo

Los monstruos pueden ser aturdidos (a menos que tengan inmunidad) y para poder ser aturdidos deben ser alcanzados por una cierta cantidad de daño <span style='color:var(--contundente)'>contundente</span> en su cabeza, el daño contudente se calcula en base al daño realizado + un % a la vulnerabilidad al aturdimiento del monstruo. 

La cantidad necesaria para aturdir monstruos varia dependiendo de su tamaño, se necesitan un numero de Hit Dice del monstruo para poder aturdirlos, es decir, si un monstruo tiene un d8 como Hit Dice, el daño necesario seria #d8, siendo # un valor dependiendo del tamaño del monstruo, este valor es calculado al inicio del combate y luego por cada vez que el monstruo es aturdido.

Hit Dices necesarios por tamaño de monstruo:

- Pequeños y medianos: 4 Hit Dice
- Grandes: 1/3 de sus Hit Dice + 10
- Gigantes: 1/2 de sus Hit Dice + 20

La vulnerabilidad al aturdimiento se mide en estrellas, llendo desde 0 hasta 3 estrellas, cada estrella aumenta un 20% del daño realizado al daño acumulado necesario para aturdir.

Al ser aturdidos, los monstruos son tirados al piso por 1 min, teniendo que hacer una DC de 10 de constitucion al final de cada turno para terminar el efecto y no acumulan daño <span style='color:var(--contundente)'>contundente</span> hasta haber pasado 1 turno despues de levantarse

Por ejemplo entonces:

Si un monstruo tiene 10d10 como Hit Dice, es catalogado como monstruo Grande y tiene una debilidad de 2 estrellas al aturdimiento, el calculo para saber cuanto daño <span style='color:var(--contundente)'>contundente</span> se necesita seria:

```10 / 3 ~ 3.33333... redondeado a 3```

3d10 + 10, podria ir desde 13 hasta 33 el daño <span style='color:var(--contundente)'>contundente</span> necesario por cada vez que es aturdido

Si recibe un impacto de 10 puntos de daño <span style='color:var(--contundente)'>contundente</span>, el cálculo final seria 10 + 40% = 10 + 4 = 14

### Aturdimiento vs el cazador

Los cazadores pueden ser aturdidos al recibir 1/2 + 10 o más de sus Hit Dice como daño en un solo ataque <span style='color:var(--contundente)'>contundente</span>, al igual que los monstruos, al inicio del combate y cada vez que el cazador es aturdido, debe recalcularse el daño necesario para ser aturdido.

Cuando los cazadores van a ser aturdidos, deben hacer una tirada de DC de 10 de constitución, si fallan pueden repetir la tirada al final de cada uno de sus turnos para terminar el efecto o un compañero que este lo suficientemente cerca (1 metro) puede ayudarle a salir del efecto teniendo que enfundar su arma y ayudarle como accion bonus o puede utilizar su accion bonus para dar un golpe a melee con su arma haciendole <span style='color:var(--ataque)'>1d4</span> de daño y terminando el efecto.