<link rel="stylesheet" href="../../base.css">

# Progresión de Personaje

## Rangos

Las habilidades de un cazador y los peligros que puede enfrentar dependen del rango en el que se encuentren, cada rango por encima de 1 ✪ cuenta como 4 niveles de personaje, en la siguiente tabla se encuentra detallado las mejoras adquiridas en cada nivel:

<table>
  <thead>
    <tr>
      <th>Rango</th>
      <th>Nivel de personaje</th>
      <th><span style='color:var(--competencia)'>Bonus de Competencia</span></th>
      <th>Puntos de Estadística</th>
      <th>Hit Dice</th>
      <th>Puntos de Vida Adquiridos</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>✪ (1)</td>
      <td>1</td>
      <td><span style='color:var(--competencia)'>+2</span></td>
      <td>0</td>
      <td><span style='color:var(--constitucion)'>d8</span></td>
      <td><span style='color:var(--constitucion)'>3d8+10</span></td>
    </tr>
    <tr>
      <td>✪✪ (2)</td>
      <td>4</td>
      <td><span style='color:var(--competencia)'>+2</span></td>
      <td><span style='color:var(--ataque)'>+2d4</span></td>
      <td><span style='color:var(--constitucion)'>d10</span></td>
      <td><span style='color:var(--constitucion)'>1d10+10</span></td>
    </tr>
    <tr>
      <td>✪✪✪ (3)</td>
      <td>8</td>
      <td><span style='color:var(--competencia)'>+3</span></td>
      <td><span style='color:var(--ataque)'>+2d4</span></td>
      <td><span style='color:var(--constitucion)'>d10</span></td>
      <td><span style='color:var(--constitucion)'>1d10+10</span></td>
    </tr>
    <tr>
      <td>✪✪✪✪ (4)</td>
      <td>12</td>
      <td><span style='color:var(--competencia)'>+4</span></td>
      <td><span style='color:var(--ataque)'>+2d4</span></td>
      <td><span style='color:var(--constitucion)'>d12</span></td>
      <td><span style='color:var(--constitucion)'>1d12+15</span></td>
    </tr>
    <tr>
      <td>✪✪✪✪✪ (5)</td>
      <td>16</td>
      <td><span style='color:var(--competencia)'>+5</span></td>
      <td><span style='color:var(--ataque)'>+2d6</span></td>
      <td><span style='color:var(--constitucion)'>d12</span></td>
      <td><span style='color:var(--constitucion)'>1d12+15</span></td>
    </tr>
    <tr>
      <td>✪✪✪✪✪✪ (6)</td>
      <td>20</td>
      <td><span style='color:var(--competencia)'>+6</span></td>
      <td><span style='color:var(--ataque)'>+2d6</span></td>
      <td><span style='color:var(--constitucion)'>d20</span></td>
      <td><span style='color:var(--constitucion)'>1d20+20</span></td>
    </tr>
  </tbody>
</table>

```Una estadística no puede sobrepasar los 20 puntos```

## Puntos de Vida

Cuando subes de rango, tu vida máxima aumentará en 1 Hit Dice del rango en que te encuentres.

Por ejemplo:

Comienza la partida, tu personaje empieza en rango 1 con

```3d8 + 10 = [4]+[4]+[1]+10 = 19 de Vida Máxima```

Subes a rango 2, adquieres 1 Hit Dice del rango que se suma a tu vida máxima

```1d10 + 10 = [6] + 10 + 19 = 35 de Vida Máxima```

Subes a rango 3

```1d10 + 10 = [4] + 10 + 35 = 49 de Vida Máxima```

Subes a rango 4

```1d12 + 15 = [12] + 15 + 49 = 76 de Vida Máxima```

Subes a rango 5

```1d12 + 15 = [12] + 15 + 76 = 103 de Vida Máxima```

Subes a rango 6

```1d20 + 20 = [15] + 20 + 103 = 138 de Vida Máxima```

### Mínimos y Máximos de Puntos de Vida por Rango

<table>
  <thead>
    <tr>
      <th>Rango</th>
      <th>Mínimo de Vida Máxima</th>
      <th>Máximo de Vida Máxima</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>✪ (1)</td>
      <td>13</td>
      <td>34</td>
    </tr>
    <tr>
      <td>✪✪ (2)</td>
      <td>24</td>
      <td>54</td>
    </tr>
    <tr>
      <td>✪✪✪ (3)</td>
      <td>35</td>
      <td>74</td>
    </tr>
    <tr>
      <td>✪✪✪✪ (4)</td>
      <td>51</td>
      <td>101</td>
    </tr>
    <tr>
      <td>✪✪✪✪✪ (5)</td>
      <td>67</td>
      <td>128</td>
    </tr>
    <tr>
      <td>✪✪✪✪✪✪ (6)</td>
      <td>88</td>
      <td>168</td>
    </tr>
  </tbody>
</table>

Adicionalmente sumarás la estadística de <span style='color:var(--constitucion)'>Constitución</span> a tus puntos de vida máxima a partir de rango 2.