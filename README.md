# Quake Live config

Configuración que carga Quake Live al arrancar (`baseq3`).

- `autoexec.cfg` — ajustes de red/FPS que se aplican en cada arranque (`rate 25000`, `cl_maxpackets 125`, `cl_packetdup 1`, `com_maxfps 250`).
- `repconfig.cfg` — preferencias de juego, ratón, red y binds (lo guarda el juego al salir).
- `qzconfig.cfg` — motor, vídeo, servidor y menús (lo guarda el juego al salir).

## Instalación

Copiar los `.cfg` en:

```
~/.local/share/Steam/steamapps/common/Quake Live/<steamid64>/baseq3/
```

con el juego cerrado (al salir reescribe `qzconfig.cfg` y `repconfig.cfg`).
