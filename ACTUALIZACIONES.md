# Actualizaciones de Pulse

La versión instalada aparece siempre abajo a la izquierda.

En **Ajustes → Versiones** puedes elegir:

- **Preguntar antes** (inicial): comprueba al abrir el juego y pregunta antes de descargar. Al aceptar, la actualización queda preparada para instalarse al cerrar Pulse.
- **Automáticamente**: comprueba y descarga al abrir. Instala cuando cierras; nunca interrumpe una partida.
- **Manualmente**: solo consulta GitHub al pulsar **Buscar actualizaciones**. Puedes descargar y decidir cuándo instalar.

La descarga se puede cancelar. Una descarga completa muestra **Instalar al cerrar** o **Posponer instalación**. Si no hay conexión, puedes seguir jugando. No necesitas una cuenta de GitHub para actualizar.

## Qué se conserva

El paquete de actualización solo contiene el programa, sus recursos incluidos y las guías/licencias. No contiene ni reemplaza `data`, tus canciones, niveles, skins personales, ajustes, biblioteca, puntuaciones o `override.cfg`.

Antes de instalar se comprueban el tamaño, SHA-256 y una firma de Pulse. El instalador vuelve a verificar la firma y cada archivo, rechaza rutas ajenas al programa y espera a que el juego termine. Guarda una copia de recuperación en `.pulse-update`, dentro de la instalación. Si una sustitución falla, restaura los archivos anteriores; un cierre inesperado durante la sustitución se recupera al abrir Pulse. Si el primer inicio no llega a cargar el menú, el siguiente intenta recuperar la versión anterior.

Si Windows impide escribir, hay otro Pulse abierto o falta espacio, la actualización no se fuerza. Consulta **Ajustes → Versiones** y vuelve a intentarlo. Mantén el juego en una carpeta donde tu usuario pueda escribir.

## Descargas e historial

[Versiones de Pulse en GitHub](https://github.com/XhuzZombie/Pulse/releases).

- `Pulse-Windows.zip`: juego portátil completo. Descomprime toda la carpeta y abre `Pulse.exe`.
- `Pulse-Update-Windows.zip`: lo utiliza el actualizador; no es una instalación completa para una carpeta vacía.

Las versiones anteriores a **0.35.0** necesitan descargar manualmente una primera versión con actualizador. Las betas y versiones preliminares no se instalan por el canal estable.
