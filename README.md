
# Práctica Unidad 5: QuickSort y ShellSort en Java

**Asignatura:** Estructura de Datos (AED-1026) — Unidad 5  

## Descripción
Implementación en Java de los algoritmos de ordenamiento **QuickSort** (con partición por esquema de Lomuto) y **ShellSort** (con reducción de intervalos `n / 2`), estructurados dentro del paquete `Metodos_de_ordenamiento`.

## Estructura del Proyecto

src/
└── Metodos_de_ordenamiento/
    ├── QuickSort.java
    ├── MainQuick.java
    └── ShellSort.java
Cómo clonar, compilar y ejecutar localmente
1. Clonar el repositorio
Bash
git clone <URL_DE_TU_REPOSITORIO_PUBLICO>
cd <NOMBRE_DE_LA_CARPETA>
2. Compilar y ejecutar desde terminal
Ubícate en la carpeta raíz del proyecto (donde se encuentra src) y ejecuta:

Bash
javac -d out src/Metodos_de_ordenamiento/*.java
java -cp out Metodos_de_ordenamiento.MainQuick
java -cp out Metodos_de_ordenamiento.ShellSort
3. Ejecutar desde IntelliJ IDEA
Abre el proyecto en IntelliJ IDEA (asegúrate de que src esté marcado como Sources Root).

Abre MainQuick.java y haz clic en el ícono de Run (▷) junto a main.

Abre ShellSort.java y haz clic en el ícono de Run (▷) junto a main.

Salida esperada en consola
QuickSort (MainQuick):

Plaintext
Arreglo original:
[6, 1, 5, 8, 3, 2, 7, 4]
Arreglo ordenado con Quicksort:
[1, 2, 3, 4, 5, 6, 7, 8]
ShellSort (ShellSort):

Plaintext
Arreglo original (ShellSort):
[6, 1, 5, 8, 3, 2, 7, 4]
Arreglo ordenado (ShellSort):
[1, 2, 3, 4, 5, 6, 7, 8]
