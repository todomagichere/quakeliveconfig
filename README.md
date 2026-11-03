# Quake Live config

Configuración que carga Quake Live al arrancar (`baseq3`).

- `autoexec.cfg` — ajustes de red/FPS que se aplican en cada arranque (`rate 25000`, `cl_maxpackets 125`, `cl_packetdup 1`, `com_maxfps 250`, `cl_timeNudge 0`: suavidad antes que inmediatez).
- `repconfig.cfg` — preferencias de juego, ratón, red y binds (lo guarda el juego al salir).
- `qzconfig.cfg` — motor, vídeo, servidor y menús (lo guarda el juego al salir).

## Legacy

- `legacy/raziel.cfg` — config antigua (`[NBT]r4ziel`, 2013), guardada solo como recuerdo. El juego no la carga y **no hay que copiarla** a `baseq3`: empieza con `unbindall` y restauraría la sensibilidad, el FOV y la red de entonces.

## Instalación

Copiar los `.cfg` en:

```
~/.local/share/Steam/steamapps/common/Quake Live/<steamid64>/baseq3/
```

con el juego cerrado (al salir reescribe `qzconfig.cfg` y `repconfig.cfg`).
