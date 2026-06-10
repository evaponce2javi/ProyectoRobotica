# worlds/

Coloca aquí tus mundos `.wbt` (uno por escenario). Recordatorios:

- El `translation`/`rotation` del e-puck debe coincidir con `pose_inicial` del
  escenario en `config.py` (φ = 0 → robot mirando +X con `rotation 0 0 1 0`).
- Los obstáculos del mundo deben coincidir con la lista `obstaculos` declarada
  en `config.py` (mismas posiciones y tamaños, en coordenadas de mundo).
- Asigna `controller = "epuck_navegacion"` al e-puck.
- Para ground-truth, añade en `turretSlot` un `GPS` llamado `gps` y un
  `Compass` llamado `compass` (opcional: sin ellos navega solo con odometría).
- Se asume Webots moderno con coordenadas ENU (piso X–Y, Z arriba).
