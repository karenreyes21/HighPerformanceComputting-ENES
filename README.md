# Proyectos UNIDADII - Cómputo paralelo utilizando OpenMP ó CUDA

## 1. Lenguajes de programación

Se deberá Utilizar C o C++ para implementar los proyectos, y será de libre elección el uso de CUDA u OpenMP para la implementación paralela.

## 2. Consideraciones para la entrega

### 2.1 Conformación de equipos

Los equipos deberán estar conformados por dos personas. 

La evaluación se hará de forma individual valorando las aportaciones que cada integrante haya hecho al proyecto.

### 2.2 Entregables

Se deberá crear un repositorio público en Git Hub por cada equipo donde se puedan apreciar la contribuciones de cada integrante. Este repositorio deberá incluir un README que describa la forma de uso del proyecto:

El repositorio deberá contener:
1. Código fuente
2. Binarios compilados
3. Presentación del proyecto 
4. Reporte en PDF en formato de artículo con los resultados obtenidos (de preferencia en LATEX). En este reporte se deberá hacer un análisis del rendimiento del algoritmo propuesto tomando tiempos de ejecución.

Este reporte en PDF deberá contener:
* Título 
* Abstract (Resumen)
* Introducción 
* Trabajos relacionados
* Descripción de la paralelización
* Resultados
* Conclusiones
* Referencias

### 2.3 Fecha de entrega 

Todos los proyectos deberán entregarse el día 21 de mayo del 2018 hasta las 11:59 pm. Los commits posteriores a esa fecha serán penalizados.

Se deberá realizar una presentación del proyecto el día 22 de mayo 2018 a la hora de clase, en esta presentación se deberá replicar el proceso de compilación y se deberá mostrar un demo funcional. Adicionalmente, se deberán describir de forma detallada las actividades realizadas en cada proyecto.


## 3. Proyectos Disponibles

## 3.1 Paralelización de transformaciones y pruebas de intersección para Ray tracing 
### Área de aplicación: Gráficos por computadora (Ray tracing)
![alt text](https://i.pinimg.com/736x/d9/e4/49/d9e44950d7ebc6ef04cc9f48e3d437f4--motion-blur-scary.jpg "Ray tracing")

### **Actividades**
    
#### 3.1.1 Descargar, compilar y hacer pruebas con alguno de los siguientes raytracers (solo elegir 1):
        * Simple Raytracer: https://github.com/cem/simple-raytracer
        * Minimal Raytracer: https://github.com/mzucker/miniray
        * Ray tracing https://github.com/bnaveenkr/raytracer

#### 3.1.2 Se deberán paralelizar las siguientes transformaciones en un ray tracer:
      * Traslación
      * Escalación
      * Rotación

#### 3.1.3 De la misma se deberán paralelizar las pruebas de intersección entre rayos y la geometría poligonal para producir una imagen de salida.

## 3.2 Paralelización de algoritmos de optimización para la localización espacial de plantas de producción de energía eléctrica 
### Área de aplicación: Sistemas de información geográfica
![GIS](http://adevaherranz.es/GEOGRAFIA/GEOGRAFIA%20UNIVERSAL%20Paises/Eurasia/Rusia/Geo%20Cartografia%20Rio%20Lena%20Delta%20Rusia-Siberia%20Satelite%20NASA_small.gif "Ray tracing")

### **Actividades**

#### 3.2.1 Se deberá programar y paralelizar la función de costo-distancia descrita en: https://desktop.arcgis.com/es/arcmap/10.3/tools/spatial-analyst-toolbox/how-the-cost-distance-tools-work.htm

#### 3.2.2 Se deberá paralelizar la exploración del algoritmo de optimización cuyo código fuente se encuentra en: 
    https://github.com/ulises1229/Optimization-2018/tree/master/src

#### Los requerimientos, dependencias e instrucciones de instalación se podrán encontrar en: 
    https://github.com/ulises1229/Optimization-2018/blob/master/Instalacion.md

## 3.3 Paralelización de algoritmos de distancia de k-meros y distancia genética.

### Área de aplicación: Bioinformática
![GIS](http://baranzinilab.ucsf.edu/sites/baranzinilab.ucsf.edu/files/wysiwyg/genetics_final.png)
### **Actividades**

#### 3.3.1 Se deberá consultar el siguiente artículo científico
      https://ieeexplore.ieee.org/document/7050241/
      
#### 3.3.1 Se deberá programar una implementación serial y una paralela del algoritmo de distancia de k-meros descrito en la sección         **2.1.1** del artículo antes mencionado. Como resultado se deberá obtener la matriz de distancia de k-meros.
      
#### 3.3.2 Se deberá programar una implementación serial y una paralela del algoritmos para evaluar la distancia genética.
      
      


