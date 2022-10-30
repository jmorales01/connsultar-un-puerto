# Consultar el puerto
Para poder consultar un puerto de tu PC y saber que programa esta usando ese puerto.

**paso 1:**  abrir el panel de comando conlas teclas Windosws + R
[![panel-de-control.png](https://i.postimg.cc/2jTwSkCC/panel-de-control.png)](https://postimg.cc/vDg9Pd1K)

**paso 2:**  añadir el comando que se muestar a continuacion con el puerto que quieres buscar.

```cpp
netstat -aof | findstr :3306
```
[![panel-de-control-comando.png](https://i.postimg.cc/fLDcMFF3/panel-de-control-comando.png)](https://postimg.cc/3yf4BL37)


**paso 3:**  buscar ese PID que devuelve en el administrador de tareas - recursos.

[![administrador-de-tareas.png](https://i.postimg.cc/xThLXqhV/administrador-de-tareas.png)](https://postimg.cc/6yV8S6BM)


**paso 4:**  por ultimo finalizar arbol de procesos en el administrador de tareas.

[![administrador-de-tareas-paso-2.png](https://i.postimg.cc/g0PRKQGM/administrador-de-tareas-paso-2.png)](https://postimg.cc/w107qWyJ)


# End
