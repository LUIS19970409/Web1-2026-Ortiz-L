# Declaración de uso de IA

> Obligatoria en todas las prácticas. Si usaste un asistente, descríbelo aquí con
> precisión. Si NO usaste ninguno, escribe eso y explica cómo resolviste la parte
> más difícil por tu cuenta — también cuenta como declaración válida.
>
> Recuerda: código de IA sin declarar se califica en CERO y no admite reintento.
> Declararlo honestamente NO baja tu nota. Lo que se evalúa es tu capacidad de auditar.

## Herramientas que usé
GEMINI

## Qué le pedí
<!-- -->

```
podrias ayudarme explicandome este ejercicio porfavor y anexe una iamgen del ejercicio
```

## Qué me devolvió
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ficha de Personaje</title>
</head>
<body>

  <h1>Geralt de Rivia</h1>

  <img src="geralt.jpg" alt="Brujo de cabello blanco sujetando una espada de plata con armadura de cuero">

  <h2>Estadísticas</h2>
  <table>
    <thead>
      <tr>
        <th>Atributo</th>
        <th>Puntuación</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Fuerza</td>
        <td>90 / 100</td>
      </tr>
      <tr>
        <td>Magia</td>
        <td>65 / 100</td>
      </tr>
    </tbody>
  </table>

  <h2>Habilidades Principales</h2>
  <ul>
    <li>Señal de Igni (Ataque de fuego)</li>
    <li>Alquimia y elaboración de pociones</li>
  </ul>

  <h2>Historia</h2>
  <p>Geralt fue sometido a intensas mutaciones en la fortaleza de Kaer Morhen durante su infancia...</p>
  <h3>El Continente y los Monstruos</h3>
  <p>A lo largo de sus viajes ha enfrentado criaturas legendarias mientras busca su propio destino...</p>

  <h2>Enviar Encargo</h2>
  <form>
    <p>
      <label for="nombre-cliente">Nombre del contratante:</label>
      <input type="text" id="nombre-cliente" name="cliente">
    </p>

    <p>
      <label for="detalles-mision">Detalles del monstruo o misión:</label>
      <textarea id="detalles-mision" name="mision"></textarea>
    </p>

    <button type="submit">Enviar solicitud</button>
  </form>

</body>
</html>



## Qué estaba mal
Ese no era el personaje que yo queria describir, y la ubicacion de la imagen no era la que estaba usando

## Qué corregí y por qué
cambie al personaje que se estaba utilizando ya que yo queria usar a otros, agregue algunas filas en la tabla para poner mas estadistica,
agregue mas habilidades para describir al personaje

```javascript
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ficha de Personaje</title>
</head>
<body>

  <h1>SEPHIROTH</h1>

  <img src="img/images.jpg" alt="El angel caido Sephiroth">

  <h2>Estadísticas</h2>
  <table>
    <thead>
      <tr>
        <th>Atributo</th>
        <th>Puntuación</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>armadura</td>
        <td>21</td>
      </tr>
      <tr>
        <td>puntos de ataque</td>
        <td>415</td>
      </tr>
      <tr>
        <td>velocidad</td>
        <td>50ft</td>
      </tr>
      <tr>
        <td>volar</td>
        <td>150ft</td>
      </tr>
    </tbody>
  </table>

  <h2>Habilidades Principales</h2>
  <ul>
    <li>Resistencia magica</li>
    <li>Armas magicas</li>
    <li>Recuperaión</li>
    <li>Teletransportación</li>
    <li>Lanzamiento de conjuros</li>
    <li>Masamune</li>
    <li>Rafaga sombria</li>
  </ul>

  <h2>Historia</h2>
  <h3>Creación</h3>
  <p>Feto modificado con células de Jénova por los científicos Hojo y Lucrecia.</p>
  <h3>Propaganda</h3>
  <p>Educado como un icono militar y héroe de la guerra de Wutai de primera clase.</p>
  <h3>Ilusión</h3>
  <p>Ilusión: Creyó erróneamente que Jénova era una Cetra (una antepasada del planeta) y que él era el heredero legítimo del mundo</p>
  <h3>Revelación</h3>
  <p>Leyó documentos en la mansión de Nibelheim y concluyó que era un monstruo.</p>
  <h3>Masacre</h3>
  <p>Enloqueció, quemó el pueblo de Nibelheim y masacró a sus habitantes.</p>
  <h3>Enfrentamiento</h3>
  <p>Enfrentamiento: Tras entrar al reactor, Cloud lo arrojó a la Corriente Vital, aunque su fuerte voluntad sobrevivió y se resguardó en el Cráter Norte</p>

  <h2>Enviar Encargo</h2>
  <form>
    <p>
      <label for="nombre-cliente">Nombre del contratante:</label>
      <input type="text" id="nombre-cliente" name="cliente">
    </p>

    <p>
      <label for="detalles-mision">Detalles de la ciudad a destruir: </label>
      <textarea id="detalles-mision" name="mision"></textarea>
    </p>

    <button type="submit">Enviar solicitud</button>
  </form>

</body>
</html>
```

## Qué escribí yo desde cero
<!-- Qué partes no delegaste, y por qué decidiste no delegarlas -->

## Reflexión
me ahorró mucho tiempo ya que me dio lo que se queria hacer, y una buena base para trabajar sobre ella y modificar a mi gusto los aspectos que yo quisiera
