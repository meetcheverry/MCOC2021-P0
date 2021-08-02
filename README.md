# MCOC2021-P0

# Mi computador principal

* Marca/Modelo: hp OMEN 15
* Tipo: Notebook
* Año Adquisicion: 2021
* Procesador:
  * Marca/Modelo: intel Core i5-10300H
  * capacidad base: 2,5GHz
  * Velocidad Maxima: 3,9GHz
  * Numero de nucleos: 4
  * Numero de hilos: 8
  * Arquitectura: Nehalem
  * Set de instrucciones: 64-bit
* Tamaño de las caches del procesador
  * L1: 256 kb
  * L2: 1 mb
  * L3: 8 Mb
* Memoria
  * Total: 15.8 Gb
  * Tipo Memoria: DDR4
  * Velocidad Memoria: 2933 MHz
  * Numero de (SO)DIMM: 2
* Tarjeta Grafica
  * Marca/Modelo: Intel UHD Graphics
  * Meoria dedicada: NVIDIA GeForce RTX 2060
  * Resolucion: 1920 x 1080
* Disco Unico:
  * Marca: hp
  * Tipo: SSD
  * Tamaño: 500 GB
  * Particiones: 3
  * Sistema de archivos: NTFS
* Dirección MAC de la tarjeta wifi: 58-00-53-F1-31-3D
* Dirección IP (Interna, del router): 192.168.100.1 
* Dirección IP (Externa, del ISP): 181.43.140.65
* Proveedor de internet: Entel

# Desempeño MATMUL

![AB_plot_performance](/Figure_1.png)

* ¿Como difiere del gráfico del profesor/ayudante?
 * El el grafico obtenido se puede notar que aumenta mucho mas el tiempo a medida que aumentan las dimensiones de la matriz
* ¿A qué se pueden deber las diferencias?
 * Esto puede deberse a las distintas caracteristicas de cada ordenador, al tener distintos procesadores y memoria se pueden obtener distintos resultados
* El gráfico de uso de memoria es lineal con el tamaño de matriz, pero el de tiempo transcurrido no lo es ¿porqué puede ser?
 * Esto puede deberse a que al medir memoria se esta evaluando el almacenamiento ocupado al desarrollar este ejercicio(no depenede de la operacion para obtener el resultado), mientras que el tiempo depende de la cantidad de operaciones que se deben realizar(al aumentar las dimensiones aumenta exponencialmente las operaciones a realizar).
 * ¿Qué versión de python está usando?
  *Python 3.6
 * ¿Qué versión de numpy está usando?
  * 1.14
 * Durante la ejecución de su código ¿se utiliza más de un procesador? Muestre una imagen de su uso de procesador durante alguna corrida para confirmar. 
 
![Processor_performance](/proce.jpg)

  * Se utilizan 4 procesadores
