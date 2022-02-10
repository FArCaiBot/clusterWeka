# Cluterización con Weka
### Pasos para ejecutar la aplicacion
1.  Descargar el repositorio
2.  Abrir el proyecto "Clustering" en el editor de código (Netbeans, recomendado)
3.  Agregar la librería weka.jar de la carpeta LibreriaWeka
4.  En el paquete interfaz ejecutar la clase EMClusterWeka.form

### Extras
Para realizar el instalador se ha incluido todas las librerías utilizadas en el proyecto, tanto las librerías propias de la interfáz gráfica de usuario como las librerías weka para la clusterización, esto se logró a través del bloque de configuración _target_ en el archivo [build](https://github.com/FArCaiBot/clusterWeka/blob/master/Clustering/build.xml).
* Opciones a modificar
1. Nombre de la carpeta donde se creará el archivo jar en la etiqueta _property_ de nombre _store.dir_ 
2. Nombre del archivo jar generado en la etiqueta _property_ de nombre _store.jar.name_.

Este archivo jar generado contiene toda la programación y las librerias integradas que será útil para generar el ejecutable a traves del software [Launch4j](http://launch4j.sourceforge.net/)
