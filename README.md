# Fundamentos de unix

## Directorios

```sh
pwd - imprime el directorio de trabajo /home/benji/Documentos/Devops/Bases-linux-cf
ls - lista archivos del directorio actual
cd - change directory
clear - limpia la pantalla
```
## Crear Directorios

```sh
mkdir nombre_carpeta - mkdir archivos
echo "texto" - echo "My texto"
Guardar contenido en un archivo - echo "mi texto de prueba" > echo.txt
ver contenido de un archivo - cat echo.txt 
crear un archivo vacio - touch touch.txt
modificar un archivo - nano touch.txt
```

## Comandos head & tail

```sh
nano frankestain.txt

head frankestain.txt # primeras 10 lineas de un archivo
head -n 5 frankestain.txt # primeras 5 lineas del archivo

tail frankestain.txt # ultimas 10 lineas
tail -n 5 frankestain.txt # ultimas 5 lineas
```

## Comando WC work count

```sh
wc echo.txt # 1  4 19 echo.txt = 1 linea, 4 palabras y 19 caracteres
wc frankestain.txt  # 248  2228 12813 frankestain.txt
wc -m frankestain.txt  # 12813 caracteres
wc -c frankestain.txt  # 12813 bytes
wc -w frankestain.txt  # 2228 palabras
wc -l frankestain.txt  # 248 lineas
```
## Comando ls y opciones

```sh
ls # lista archivos del directorio
ls -a # lista archivos del directorio + ocultos
ls -l # detalles de los archivos

-rw-rw-r-- 1 benji benji    19 abr 12 04:42 echo.txt
-rw-rw-r-- 1 benji benji 12813 abr 12 04:35 frankestain.txt
-rw-rw-r-- 1 benji benji    27 abr 12 04:28 touch.txt

Tiene 8 columnas que se dividen en
```