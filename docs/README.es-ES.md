# Los Sims Cuatro Estaciones

**Primera beta pública · 1.0.0-beta.1**

[English](../README.md) · [Polski](README.pl-PL.md) · [Dansk](README.da-DK.md) · [Deutsch](README.de-DE.md) · **Español** · [Suomi](README.fi-FI.md) · [Français](README.fr-FR.md) · [Italiano](README.it-IT.md) · [日本語](README.ja-JP.md) · [한국어](README.ko-KR.md) · [Norsk bokmål](README.nb-NO.md) · [Nederlands](README.nl-NL.md) · [Português (Brasil)](README.pt-BR.md) · [Svenska](README.sv-SE.md) · [ไทย](README.th-TH.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md)

Las cuatro estaciones llegan a The Sims Legacy Collection. Una tormenta puede hacer que tus Sims corran a refugiarse y la nieve recién caída se acumula en el jardín. Al cargar una partida, recuperas el tiempo y el calendario de tu solar. Este mod es una creación no oficial de la comunidad.

![Niebla en un solar residencial de The Sims Legacy Collection](../media/weather.png)

[Colores de otoño](../media/autumn.png) · [Un jardín nevado](../media/winter.png) · [Galería completa (ZIP, 8 imágenes)](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/download/v1.0.0-beta.1/The-Sims-1-Four-Seasons-Screenshots.zip)

## El tiempo en tu solar

- La lluvia, las tormentas, el granizo, la nieve, las ventiscas y la niebla siguen el ciclo de las estaciones. Con la estación meteorológica opcional también puedes elegir el tiempo, incluida la lluvia o la niebla mágicas.
- En otoño cambian de color las hojas. En invierno cuaja la nieve en las carreteras, las plantas y los objetos al aire libre, incluidas las lápidas. Los niños pueden chapotear en los charcos y los Sims pueden hacer un muñeco de nieve cuando se haya acumulado suficiente nieve.
- Los Sims, los perros y los gatos pueden empaparse y buscar cobijo. La lluvia puede apagar incendios al aire libre. Puedes ajustar por separado los efectos del tiempo en la partida. Durante la carga suena un tema original, *Pocztówka z doliny*.

## Descarga e instalación

Necesitas tener instalada la versión completa de The Sims Legacy Collection **1.10.0** o **1.10.7** en Windows de 64 bits, además de [Microsoft .NET Desktop Runtime 10 (x64)](https://dotnet.microsoft.com/download/dotnet/10.0). Reserva varios GB de espacio libre y espacio adicional para una copia de tus partidas guardadas.

1. Abre [Releases](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/tag/v1.0.0-beta.1) en GitHub, selecciona la versión **1.0.0-beta.1** y descarga `TheSimsCzteryPoryRoku-1.0.0-beta.1.zip` en **Assets**.
2. Guarda la partida y cierra el juego y la aplicación del tiempo. Extrae todo el ZIP en una carpeta nueva. Deja la carpeta `data` junto a `Setup.exe`.
3. Ejecuta `Setup.exe` y selecciona la carpeta del juego que contiene `sims.exe`. Pulsa **Comprobar compatibilidad** y después **Instalar**. El instalador verifica los archivos, hace copias de seguridad y aplica los parches a los archivos de tu juego. Si detecta un conflicto en un archivo necesario, detiene la instalación.
4. Espera a que termine. Para jugar, utiliza el acceso directo **The Sims Cztery Pory Roku** del escritorio o `Launch-weather.cmd` en la carpeta de la aplicación instalada. Así se inician juntos el juego, el tiempo y el componente que recupera el tiempo de la partida guardada.

Deja que el instalador aplique los parches a los archivos del juego. Comprueba sus sumas de verificación antes y después de cada cambio y conserva `sims.exe` intacto. Solo modifica los objetos opcionales si ya tienes instalada una versión compatible de esos objetos.

## En el juego

Carga un solar para que el tiempo cambie de forma automática. Pulsa `Ctrl+Alt+R` para ajustar las precipitaciones, el sonido, el calendario y los efectos en la partida. Los menús de los objetos usan el idioma del juego. El panel del tiempo también lo utiliza de forma predeterminada. Si eliges otro idioma para el panel, el cambio se aplicará la próxima vez que inicies el juego.

## Copias de seguridad, actualizaciones y desinstalación

El instalador hace copias de los archivos afectados, de tus partidas guardadas y de los datos del tiempo. Conserva `backups` y `install-state.json` en la carpeta de la aplicación, dentro de `%LOCALAPPDATA%\TS1CzteryPoryRoku`. Los datos del tiempo de los solares también se guardan en `%LOCALAPPDATA%\TS1RainOverlay`. Puedes restaurar las partidas manualmente con el juego cerrado. Deja las carpetas del juego y de la aplicación en su ubicación original.

La copia incluye `Electronic Arts\The Sims 25` en la carpeta de partidas guardadas de Windows y las carpetas `UserData`, `UserData2` que haya en el directorio del juego. Cada copia tiene su propia carpeta. Consulta en `save-backup.json` las rutas originales y las sumas de verificación para identificar los archivos que quieres recuperar.

Para actualizar el mod, cierra el juego y la aplicación del tiempo, extrae el nuevo ZIP en otra carpeta y selecciona la misma carpeta del juego en el nuevo instalador. Para quitar el mod, cierra ambos programas y elige **Opciones → Desinstalar** en la copia de `Setup.exe` que hayas conservado. Se restauran los archivos originales y se conservan las partidas y sus copias de seguridad. Si piensas volver a usar los objetos del mod, guarda una copia del solar antes de jugar sin él.

Si se interrumpe la instalación, elige **Opciones → Revertir cambios**. Si al restaurar aparece un aviso de que un archivo ha cambiado, conserva el mensaje y las copias de seguridad. Si Windows deniega el acceso de escritura, ejecuta `Setup.exe` como administrador desde la misma cuenta de Windows.

## Pruebas de la beta y errores

Las pruebas del instalador abarcan las dos versiones compatibles del juego. Agradecemos las pruebas en otros equipos, en ordenadores menos potentes y en partidas largas en cualquiera de los 17 idiomas. Si los efectos meteorológicos van lentos con la superposición de NVIDIA activada, prueba a desactivarla.

Comunica los problemas en [Issues](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/issues) en GitHub. Indica las versiones del juego y del mod, el idioma y los pasos para reproducir el fallo. Si el problema es visual, añade una captura de pantalla, el tiempo, el nivel de zoom, el ángulo de la cámara, el piso y el modo de las paredes. En caso de error de instalación, incluye el mensaje completo. Revisa los registros por si contienen rutas personales antes de compartirlos.
