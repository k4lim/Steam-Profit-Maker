<p align="center">
  <img width="160" height="160" alt="CacheLib" src="https://em-content.zobj.net/thumbs/160/microsoft/319/coin_1fa99.png">
</p>
<h1 align="center"> SPM - Steam Profit Maker </h1>
<p align="left">
  <img src="https://img.shields.io/badge/license-GPL-blue">
  <img src="https://img.shields.io/badge/poetry-1.3-60A5FA?logo=poetry&color=60A5FA">
  <img src="https://img.shields.io/badge/python-v^3.9-3776AB?logo=python&color=3776AB">
  <img src="https://img.shields.io/badge/release%20date-pending-yellow">
  <img src="https://img.shields.io/badge/status-in%20development-yellow">
  <br>
  <img src="https://img.shields.io/github/stars/JLCareglio?style=social">
</p>

## Índice
* [📝 Índice](#índice)
* [ℹ️ Descripción](#descripción)
* [🔎 Requisitos](#requisitos)
* [🐾 Primeros Pasos](#primeros-pasos)
* [👀 Ejemplo de Uso](#ejemplo-de-uso)
* [💥 Posibles Errores](#posibles-errores)
* [❤️ Contribuciones](#contribuciones)
  * [🧑‍💻 Aporta Programando](#aporta-programando)
  * [🗨️ Aporta Traduciendo](#aporta-traduciendo)
  * [🪙 Aporta Económicamente](#aporta-económicamente)

## Descripción
<p>
  Herramienta para encontrar juegos rentables en Steam donde el precio de sus cromos supere el coste del propio producto 📈.
  <br>
  🤔 ¿Cómo funciona?, simple, solo introduces uno o varios AppIDs o URLs de juegos de steam y analizará los cromos del mismo en el mercado para luego dar datos detallados sobre si su compra es rentable, posibles ganancias y comentarios útiles 💪.
  <img src="https://user-images.githubusercontent.com/23004689/215903955-2bd0bf4f-83b9-4f22-a763-0a0687dd1643.png">
</p>

## Requisitos
- [Python v3.9 o superior](https://www.python.org/downloads/)
- Siguientes librerias de Python:
  - beautifulsoup4
  - bs4
  - certifi
  - charset-normalizer
  - colorama
  - idna
  - python-dotenv
  - requests
  - soupsieve
  - urllib3

Puedes usar el siguiente comando para instalar todas las librerías mencionadas:
```
pip3 install beautifulsoup4 bs4 certifi charset-normalizer colorama idna python-dotenv requests soupsieve urllib3
```

## Primeros Pasos
1. Primero asegúrate de cumplir con los [requisitos](#requisitos)
2. Clona el repositorio y ábrelo desde una terminal (shell, bash, zsh, powershell, etc)
```
git clone --depth 1 https://github.com/JLCareglio/Steam-Profit-Maker.git
cd ./Steam-Profit-Maker
```
3. Ejecuta main.py usando Python 3.9 o superior
```
python3 main.py
```

## Ejemplo de Uso

<p>
  Puedes buscar ofertas de juegos que tengan cromos y guarda sus URLs o AppIDs, usando la siguiente página: 👇
  <br>
  https://steamdb.info/sales/?min_reviews=0&min_rating=0&min_discount=0&category=29
</p>
<p>
  Luego de abrir el programa ingresa los juegos de los que quieras saber su rentabilidad, este es un ejemplo con 8 juegos introducidos de formas diferentes pero todas válidas:
  <br>
  <img src="https://user-images.githubusercontent.com/23004689/216166787-52e2303f-b397-4d55-b028-6c1ec28e59e0.png">
</p>
<p>
  Al pulsar enter empezará el escaneo de los cromos de cada juego, ahora solo toca esperar a que termine 👏.
  <br>
  ℹ️ Nota: se van a ir mostrando y guardando datos y avisos útiles sobre la rentabilidad de cada juego a medida que se escaneen 👀💾:
  <br>
  <img src="https://user-images.githubusercontent.com/23004689/216167513-8a601318-7894-437c-807a-302794861051.png">
</p>
<p>
  Cuando terminen todos los escaneos, verás un resumen completo con los datos extraídos y ordenados en 3 categorías como las siguientes:
  <br>
  <img src="https://user-images.githubusercontent.com/23004689/216172113-3a2519ee-43b3-41ab-8ed9-d2f41205bee6.png">
  <img src="https://user-images.githubusercontent.com/23004689/216172220-81bb4c7b-f2a5-4b10-b719-06a8baa77398.png">
  <img src="https://user-images.githubusercontent.com/23004689/216172279-c4f14066-24f4-47eb-b038-bf98c265c316.png">
  <br>
  También encontrarás un informe dentro de la carpeta data en un archivo .csv con la fecha actual en la que comenzaste el escaneo de juegos. Puedes abrir y ver este archivo con algún programa como "Hojas de Cálculo de Google" 😉.
</p>

## Posibles Errores
<p>
  🔴 Puede que algunos juegos no consigan ser escaneados ni aun activando o cambiando de Proxy o VPN, estos aparecerán listados en último lugar dentro del resumen al finalizar todos los escaneos de juegos, ejemplo de un error:
  <br>
  <img src="https://user-images.githubusercontent.com/23004689/216780380-3b6b566f-072f-4bed-a324-473600c6e9ce.png">
  <br>
  ℹ️ Nota: los juegos que produzcan errores bajo ninguna circunstancia afectaran a aquellos que si fueron escaneados correctamente ni tampoco deberían detener la aplicación, si esto ocurre, por favor reportarlo en <a href="https://github.com/JLCareglio/Steam-Profit-Maker/issues">issues</a>.
</p>

🟢 Posibles soluciones
- Intentar volver a escanear los juegos que dieron errores pero en otro día u horario.
- Reinstalar o actualizar las librerías listadas en [🔎 Requisitos](#requisitos).
- No utilizar ninguna VPN o Proxy.
- Ejecutar el programa desde una terminal diferente como por ejemplo [GitBash](https://git-scm.com/downloads) o PowerShell.

🔵 Si el problema persiste, por favor reportarlo creando una nueva issue en:
https://github.com/JLCareglio/Steam-Profit-Maker/issues

## Contribuciones
🚧 Sección en construcción 🚧.
[Esto significa que el texto a continuación está incompleto y será actualizado en un futuro]

### Aporta Programando
El proyecto acepta contribuciones por lo que siéntete libre de hacer un [Forck](https://github.com/JLCareglio/Steam-Profit-Maker/fork) al mismo para poder modificarlo aportando solución a errores o nuevas características.
- Formatear codigo con [Black](https://black.readthedocs.io/en/stable/getting_started.html)
- Usar convenciones dadas por [GitMoji](https://gitmoji.dev/) para los commits (recomendado)

### Aporta Traduciendo
Aún se está considerando si tiene sentido traducir el proyecto o localizarlo para las monedas de más países, ya que actualmente solamente funciona en Argentina y personalmente desconozco si es posible conseguir un profit positivo con juegos fuera de este país.

### Aporta Económicamente
🚧 Sección en construcción 🚧
