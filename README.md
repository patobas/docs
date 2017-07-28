
[![N|Solid](https://theeye.io/landpage/images/logo.png)](https://theeye.io)]

[![N|Solid](https://github.com/patobas/docs/blob/master/eye.png)]

# Docs

### Contents

## Scripts

+ [Writing Scripts](https://github.com/theeye-io-team/theeye-docs/tree/master/scripts/write.md)

+ [Scripts RunAs](https://github.com/theeye-io-team/theeye-docs/tree/master/scripts/runas.md)

+ [Samples](https://github.com/theeye-io-team/theeye-docs/tree/master/scripts)


## TheEye-Agent

+ [Build Agent Binary](https://github.com/theeye-io-team/theeye-docs/tree/master/agent/binary_build.md)



## TheEye-CLI

+ [CLI Util](https://github.com/theeye-io-team/theeye-docs/tree/master/cli)

# HOWTO

### Scripts:






### Create Monitor:
There are several types of monitor
+ Script (tiene que devolver true de lo contrario siempre asume failure).
+ API/WEB check, chequea el endpoint web con el payload y se puede machear string o 200/404/500
+ Tipo proceso, busca un proceso.

### Create Task:
+ Se puede crear una tarea de tipo script. Se puede concatenar con eventos.
+ Se puede crear una tarea de tipo endpoint API/WEB. le pega a una web/api.
+ Las tareas se pueden schedular, y en scheduled view se pueden ver todas las tareas programadas.

### Agent installation:
+ Lo de ir a profile, copiar y pegar en la consola.

### Templates:
+ Cuando llegues acá lo vemos.

### Webhooks:
+ Forma de acceder desde otro sistema, genera un link que al pegarle puede ejecutar una tarea si está vinculada.
