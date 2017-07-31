
[![](https://theeye.io/landpage/images/logo.png)](https://theeye.io)

![](https://github.com/patobas/docs/blob/master/eye.png)

# Contents

### TheEye-CLI

+ [CLI Util](https://github.com/theeye-io-team/theeye-docs/tree/master/cli)

### Scripts

+ [Writing Scripts](https://github.com/theeye-io-team/theeye-docs/tree/master/scripts/write.md)

+ [Scripts RunAs](https://github.com/theeye-io-team/theeye-docs/tree/master/scripts/runas.md)

+ [Samples](https://github.com/theeye-io-team/theeye-docs/tree/master/scripts)

Para crear un script: 

![](https://github.com/patobas/docs/blob/master/script.gif)


### Monitor:
Hay muchos tipos de monitor. Nos sirve para controlar los servicios de nuestros equipos.
Por otro lado, nos ofrece la posibilidad de modificar los umbrales de monitoreo de las estadísticas de los equipos 
(Host Stats Monitor) y que nos alerte cuando alcanza dicho umbral.

+ Stats:

![](https://github.com/patobas/docs/blob/master/monitor_stats.gif)

+ Script (tiene que devolver true de lo contrario siempre asume failure).

................

+ API/WEB check, chequea el endpoint web con el payload y se puede machear string o 200/404/500

................

+ Tipo proceso, busca un proceso.

................

### Create Task:
+ Se puede crear una tarea de tipo script. Se puede concatenar con eventos.

................

+ Se puede crear una tarea de tipo endpoint API/WEB. le pega a una web/api.

................

+ Las tareas se pueden schedular, y en scheduled view se pueden ver todas las tareas programadas.

................

### TheEye-Agent. Instalación:

+ [Build Agent Binary](https://github.com/theeye-io-team/theeye-docs/tree/master/agent/binary_build.md)

................

+ Lo de ir a profile, copiar y pegar en la consola.

### Templates:

................

+ ................

### Webhooks:
+ Forma de acceder desde otro sistema, genera un link que al pegarle puede ejecutar una tarea si está vinculada.
