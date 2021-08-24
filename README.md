# pdfTranslate

*Este script sirve para traducir pdf's de cualquier tama;o*


### instalacion

```bash 
pip install -r requirements.txt

```

### Modo de ejecucion/uso:

```bash

python pdfTranslate.py -l en -t es -c -o salida.pdf archivo_a_traducir.pdf

# esto permitira traducir un documento de ingles a espa;ol

# si solo queremos traducir y convertir el pdf a word

python pdfTranslate.py -l en -t es  -o salida.pdf archivo_a_traducir.pdf

```

### comandos en face de desarollo:

```bash

al usar la opcion -um se convertira el pdf a word mas rapido, aun se esta probando el implementar una traduccion mas rapida
sin hacer uso de la API de google, sin embargo si se hace uso de threading o multiprocess google bloqueara nuestras peticiones con captchas
por ser bots.


solo use esta opcion si tiene una pc algo buena.
```


