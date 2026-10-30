# BACKFIRE · Project Backfire

**FPS táctico para móvil y PC con controles poco habituales: toques en la parte trasera del móvil, espejo táctil, voz, cabeza… y ahora también mando.**

> ⚠️ **PRE-ALPHA.** Es un prototipo jugable: las mecánicas cambian con cada versión, hay fallos y los gráficos son provisionales (casi todo está hecho con cubos). Lo comparto para que lo pruebes y me digas qué te parece.

## Descargar

👉 **[Descargar la última versión](../../releases/latest)**

En **Assets** encontrarás:
- `ProjectBackfire-…-prealpha.apk` → **Android** 7.0 o superior (32 y 64 bits).
- `ProjectBackfire-…-prealpha-Windows.zip` → **PC con Windows** (64 bits).
- `ProjectBackfire-…-prealpha-Quest.apk` → **Meta Quest** (versión de pruebas en realidad virtual).

Desde la v0.40 el juego **avisa solo cuando hay una versión nueva** y te deja descargarla desde el menú.

## Cómo instalarlo

### Android
1. Abre el enlace de arriba desde el móvil y descarga el `.apk`.
2. Ábrelo desde las notificaciones o desde **Descargas**.
3. Si el móvil no permite instalar apps de este origen, pulsa **Ajustes**, activa **Permitir de esta fuente** y vuelve atrás.
4. Si aparece **Play Protect**, pulsa **Más detalles → Instalar de todas formas** (sale porque no viene de la Play Store).
5. Para actualizar, instala la nueva versión encima. No hace falta desinstalar.

### Meta Quest
1. Instala `ProjectBackfire-…-Quest.apk` con SideQuest o con `adb install`.
2. Ábrelo desde **Biblioteca → Orígenes desconocidos**.

### Windows
1. Descarga el `.zip`, descomprímelo y abre `BACKFIRE.exe` (deja el `.dll` en la misma carpeta).
2. Si Windows avisa de una app desconocida: **Más información → Ejecutar de todas formas**.
3. Arranca en pantalla completa; **F11** o **Alt+Intro** cambia a ventana.

## Controles

### Móvil (pantalla táctil)
- **Stick izquierdo:** al tope corres, poco andas despacio.
- **Espejo (trackpad):** el pulgar mueve la vista como un ratón. En el borde sigue girando; toques rápidos a un lado giran más.
- **Toques traseros:** atrás a la izquierda apunta, atrás a la derecha dispara. En móviles sin giroscopio se usa el **toque único**: cualquier toque detrás dispara.
- **Botones en pantalla (opcionales):** DISPARAR y APUNTAR junto al espejo, CORRER y CUBRIRSE junto al stick (agarre de hombro). Se configuran en **Ajustes → Controles → Botones en pantalla**.
- **Botones de volumen:** disparan (se puede desactivar).
- **Opcionales:** gestos con el móvil, giroscopio (o **inclinar el móvil** si no tienes giroscopio), control con la cabeza y órdenes de voz.

### PC (teclado y ratón)
`WASD` moverse · ratón mirar · clic disparar · clic derecho apuntar · `R` recargar · `Espacio` saltar · `Ctrl`/`C` agacharse · `Shift` andar despacio (cadera) o esprintar (hombro) · `E` bomba · `F` pegarse a la pared (hombro) · `G` agarre · rueda/`Q` arma · `Esc` ajustes

### Mando (Bluetooth o cable, en móvil y PC)
Se detecta solo al conectarlo y pulsar un botón. Botones por defecto (reasignables en **Ajustes → Mando**):

| Acción | Botón |
|---|---|
| Moverse / mirar | Stick izquierdo / stick derecho |
| Disparar / apuntar | RT (R2) / LT (L2) |
| Saltar / agacharse | A (Cruz) / B (Círculo) |
| Recargar / cambiar arma | X (Cuadrado) / Y (Triángulo) |
| Cambiar agarre / bomba | LB (L1) / RB (R1) |
| Correr (hombro, un toque) o andar despacio (cadera) | L3 |
| Pegarse a la pared (hombro); apuntar para asomarse | R3 |
| Ajustes | Start (Options) |

En los menús: cruceta para moverte, **A** aceptar, **B** volver.

## Modos de agarre

- **Cadera:** más precisión; quieto aciertas casi siempre; algo más lento; sin esprint ni deslizamiento.
- **Hombro:** menos preciso, pero apuntas con cualquier arma, disparas moviéndote, esprintas con el arma alzada y te deslizas agachándote al esprintar.

## Modos de juego

- **Sala de pruebas:** dianas, parkour y zona de velocidad para probar los controles.
- **Policías vs Terroristas:** combate por equipos contra bots.
- **Modo bomba · Favela:** por rondas, al estilo Counter-Strike. Los terroristas plantan en **A** (la cancha) o **B** (la iglesia) y la policía defiende.
- **Tus mapas:** cualquier mapa hecho con el editor, en Todos contra todos, Equipos o Bomba.

## Editor de mapas

Desde el menú, **EDITOR DE MAPAS** (móvil y PC):
- Más de 40 piezas: muros, puertas, ventanas, suelos, escaleras, casas, edificios, coches, cajas, sacos, contenedores, apariciones y zonas de bomba.
- **Pieza maestra:** un cubo de 1 m al que cambias ancho, alto, fondo, elevación, color y giro libre.
- Las piezas no se pueden solapar: si chocan se marcan en rojo.
- **Guardar**, **Compartir** con un código, **Importar** el código de otra persona y **PROBAR** al momento con bots.

## Ajustes de gráficos

Calidad rápida (Mínimo, Medio, Máximo, Por defecto), resolución 3D, FPS, sombras, espejo y más. Para móviles muy antiguos existe el **Modo J7** (optimización extrema).

## Permisos (Android)

- **Sensores de movimiento:** toques traseros y gestos.
- **Micrófono (opcional):** mejora los toques traseros y permite las órdenes de voz.
- **Cámara (opcional):** solo si activas el control con la cabeza.
- **Internet:** solo para comprobar si hay una versión nueva en GitHub.

Todo se procesa en el dispositivo. El juego no graba, no guarda audio ni imágenes y no envía nada tuyo a internet.

## Dame tu opinión

Abre un **[Issue](../../issues)** contando qué dispositivo tienes, qué ha fallado o qué cambiarías, o escríbeme por Instagram en los comentarios de los vídeos. Muchas mecánicas salen de ideas de la comunidad.

---

Hecho por **WillianD** · Bribón Rojo Studios
