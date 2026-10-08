# Método de Eliminación Gaussiana
## Hecho por Marco Antonio Pavia Flores
Este proyecto implementa el método numérico de Eliminación Gaussiana con sustitución regresiva para resolver sistemas de ecuaciones lineales de manera modular.

## Lenguaje de Programación
* **Lenguaje:** Java

## Estructura del Proyecto

Ecuaciones_lineales/
│── Gauss.java              # Lógica de eliminación gaussiana y sustitución regresiva
│── defmatrizz.java         # Definición e inicialización de la matriz aumentada
└── Lanzador_gauss.java     # Clase principal (ejecutable)

## Compilación y Ejecución

### Desde Terminal / Consola
1. Ubícate en la carpeta raíz donde se encuentra el paquete `Ecuaciones_lineales`:
   ```bash 
   cd ruta/de/tu/proyecto

2. Compila las clases de Java:
    ```bash 
    javac Ecuaciones_lineales/*.java

3. Ejecuta la clase principal:
    ```bash 
    java Ecuaciones_lineales.Lanzador_gauss

## Desde un IDE (usaremos IntelliJ en este caso)
* Importa la carpeta del proyecto.

* Abre el archivo Lanzador_gauss.java.

* Ejecuta directamente la clase mediante la opción Run / Ejecutar.

##  Ejemplo de Prueba y Salida
* Matriz Aumentada [A | b] Entrada:
* $$\begin{bmatrix} 3.0 & -0.1 & -0.2 & \vert{} & 7.85 \\ 0.1 & 7.0 & -0.3 & \vert{} & -19.3 \\ 0.3 & -0.2 & 10.0 & \vert{} & 71.4 \end{bmatrix}$$

## Salida Obtenida en Consola:
1. Soluciones del sistema:
   * x1 = 3.0
   * x2 = -2.5
   * x3 = 7.0
