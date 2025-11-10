# Entregable 01 (Desarrollo de una aplicación para probar I.A. en distintos tipos)
Primer paso para la instalacion:
copiamos el repositorio:
```bash
git clone https://github.com/DiggyT02/Entregable-TALLER-DE-DESARROLLO-DE-APLICACIONES-CON-ML.git
```
Ejecutamos abriendo el archivo index.html en el navegador tu navegador, de preferencia **Google Chrome**.

## Uso:
para usar la aplicacion solamente necesitas conexión a internet, y una camara para el reconocimiento de objetos.

### `index.html`
    Este archivo solamente es una vista para navegar entre los diferentes tipos de I.A. los cuales son:
    . Login con I.A.
    . Reconocimiento de Imagenes.
    . Reconocimiento de Objetos en vivo.

### `reconocimiento_imagenes.html`
En este archivo podemos encontrar un formulario con un imput para seleccionar imagenes. En esta parte subimos la imagen a la cual queremos hacer la predicción y enviamos la imagen para ver los resultados.
Luego de ello nos deberia aparecer una seccion donde se muestren los resultados:

[!Imagen resultado de la prediccion](./imagenes/resultado.png)

### `actividad2.html`
El login con I.A. 

### `reconocimiento_objetos.html`
Para usar esta funcion si o si necesitamos una camara y un navegador web con soporte para sintetización de voz.
Al abrir el archivo inmediatamente se abrira la camara y comenzara a realizar predicciones. para comprobar el funcionamiento de este archivo se debe mostrar a la camara uno de los siguientes objetos: 
- Vicunia o llama.
- Tarjeta de Credito o Debito.
- Cuaderno.
- Llave.
prueba del funcionamiento:

[!Imagen del funcionamiento](./imagenes/resultados.png)