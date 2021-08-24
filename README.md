# pdfTranslate

*Este script sirve para traducir pdf's de cualquier tama;o*


### instalacion

```bash 
git clone https://github.com/CeramicCodes/pdfTranslate.git # clonamos el repositorio remoto
cd pdfTranslate # entramos al directorio pdfTrsanlate
pip install -r requirements.txt # instalamos las dependencias necesarias
```

### Modo de ejecucion/uso:

```bash

python pdfTranslate.py -l en -t es -c -o salida.pdf archivo_a_traducir.pdf

# esto permitira traducir un documento de ingles a espa;ol

# si solo queremos traducir y convertir el pdf a word

python pdfTranslate.py -l en -t es -noC -o salida.pdf archivo_a_traducir.pdf

```

##opciones:

```bash

-l lenguaje en el que esta el documento [requiere que pases un argumento por ejemplo en -> english]
-t lenguaje a traducir [requiere que pases un argumento por ejemplo es -> espa;ol]
-c convertir a pdf [no requiere que pases un argumento es una bandera]
-noC no convertir a pdf [no requiere que pases un argumento es una bandera]
-o el nombre del archivo de salida [requiere que pases como argumento el nombre del archivo nuevo]
-um use multiprocess (usar multiprocesamiento) (consultar comandos en face de desarollo) [no requiere que pases un argumento es una bandera] [actual mente se ha quitado]
-h help o ayuda [no requiere que pases un argumento es una bandera]
--help [no requiere que pases un argumento es una bandera]
path la ruta del documento a traducir [requiere como argumento una ruta del archivo a traducir]


```


### comandos en fase de desarollo:

```bash

al usar la opcion -um se convertira el pdf a word mas rapido, aun se esta probando el implementar una traduccion mas rapida
sin hacer uso de la API de google, sin embargo si se hace uso de threading o multiprocess google bloqueara nuestras peticiones con captchas
por ser bots.


solo use esta opcion si tiene una pc algo buena.
```

[si se tiene algun inconveniente con el script por favor mandenos una captura de el en un ticket en nuestra comunidad de discord](https://discord.gg/Y8G4GY4xTu)

