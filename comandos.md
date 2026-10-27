# comandos

## navegacion

- `pwd`= me muesrtra donde estoy ubicado ej: Jose@MacBook-Air-de-Lorena Learning pwd
  /Users/Jose/Development/Learning
- `ls` = me mustra que hay donde estoy ubicado ej: Jose@MacBook-Air-de-Lorena fase-0 ls
  apuntes.txt

- `cd` = me lleva a cualquier otro espacio de mi proytecto es como cambiar de habitaciones ej:Jose@MacBook-Air-de-Lorena mi-codigo cd fase-0

## archivos

- `mkdir`= crear carpertas ej: Jose@MacBook-Air-de-Lorena Learning mkdir mi-codigo

- `touch`= crea un archivo ej: Jose@MacBook-Air-de-Lorena Learning touch mi-codigo/notas.txt
- `cp`= copia un archivo ej: Jose@MacBook-Air-de-Lorena mi-codigo cp notas.txt fase-0

- `mv`= renombrar o mover archivo ej: Jose@MacBook-Air-de-Lorena mi-codigo mv notas.txt apuntes.txt
- `rm`= borrar archivo ej: Jose@MacBook-Air-de-Lorena fase-0 rm apuntes.txt
- `rm -r`= borrar carpeta ej: Jose@MacBook-Air-de-Lorena Learning rm -r ccd
- `cat`= ver dentro de un archivo por completo ej: Jose@MacBook-Air-de-Lorena mi-codigo cat notas.txt
  claude aveces no te entiendo
  gracias claude
- `>`= es redirecionar un salida hacia otro lado reescribiendo lo que ya habia en ese lugar ej:echo "claude aveces no te entiendo" > notas.txt
- `>>`= es agregar una sin sobreponer una salida en otro lugar ej: echo "gracias claude" >> notas.txt

## busqueda

- `find`= buscar algun elemento dentro del proyecto ej: Jose@MacBook-Air-de-Lorena Learning find . -name "\*.txt"
  ./mi-codigo/fase-0/apuntes.txt

## repositorio

- `git status` = te dice que es lo que hay en repositorio y si hay cambios desde elultimo commit ej: Jose@MacBook-Air-de-Lorena mi-codigo git status
- `git add` = manda la carpeta modificada a la ante sala antes de tomar la foto ej: Jose@MacBook-Air-de-Lorena mi-codigo git add .
- `git commit` = es el momento en el que se toma la captura del cambio que realizaste con su respectiva nota ej: Jose@MacBook-Air-de-Lorena mi-codigo git commit -m "agrega comando git add a comandos.md con su uso"
