# 📚 EstructurasDeDatosMenu

Proyecto educativo en Java que demuestra diferentes estructuras de datos organizadas en 3 cortes académicos.

## 🎯 Descripción

Este proyecto presenta un menú interactivo en consola que permite explorar y ejecutar ejemplos prácticos de diversas estructuras de datos y algoritmos, desde conceptos básicos hasta avanzados.

## 📁 Estructura del Proyecto

```
proyecto-final/
├── src/
│   ├── Menu.java                    # Menú principal interactivo
│   │
│   ├── corte1/                      # 🟦 Corte 1: Fundamentos
│   │   ├── ArraysDemo.java
│   │   ├── LinkedListDemo.java
│   │   ├── DoubleLinkedListDemo.java
│   │   └── FundamentosDemo.java
│   │
│   ├── corte2/                      # 🟩 Corte 2: Estructuras Intermedias
│   │   ├── StackDemo.java
│   │   ├── QueueDemo.java
│   │   ├── HashTableDemo.java
│   │   └── BinaryTreeDemo.java
│   │
│   └── corte3/                      # 🟧 Corte 3: Estructuras Avanzadas
│       ├── AVLTreeDemo.java
│       ├── BSTDemo.java
│       ├── GraphDemo.java
│       └── ComplejidadDemo.java
│
└── README.md
```

## 🟦 Corte 1 - Fundamentos

### 1. Arrays
- Crear y llenar arrays
- Calcular promedio, máximo y mínimo
- Búsqueda de elementos

### 2. Listas Enlazadas Simples
- Insertar (inicio, final, posición)
- Eliminar elementos
- Búsqueda y recorrido

### 3. Listas Doblemente Enlazadas
- Navegación bidireccional
- Operaciones adelante/atrás
- Inserción y eliminación

### 4. Fundamentos de Programación
- Condicionales (if-else, switch)
- Ciclos (for, while, do-while)
- Funciones y recursividad

## 🟩 Corte 2 - Estructuras Intermedias

### 1. Stack (Pilas)
- Push, Pop, Peek
- Invertir palabras
- Operaciones LIFO

### 2. Queue (Colas)
- Enqueue, Dequeue
- Sistema de atención de clientes
- Cola de impresión

### 3. Tablas Hash
- Insertar pares clave-valor
- Búsqueda O(1)
- Factor de carga y colisiones

### 4. Árboles Binarios
- Inserción de nodos
- Recorridos (InOrden, PreOrden, PostOrden)
- Propiedades del árbol

## 🟧 Corte 3 - Estructuras Avanzadas

### 1. Árboles AVL (Balanceados)
- Auto-balanceo
- Rotaciones (simple y doble)
- Operaciones O(log n)

### 2. BST (Binary Search Tree)
- Inserción y búsqueda
- Eliminar nodos
- Sucesor y predecesor

### 3. Grafos
- BFS (Breadth-First Search)
- DFS (Depth-First Search)
- Camino más corto
- Detección de ciclos

### 4. Complejidad Algorítmica
- Comparación de tiempos: O(1), O(log n), O(n), O(n log n), O(n²), O(2^n)
- Medición con System.nanoTime()
- Ejemplos prácticos

## 🚀 Compilación y Ejecución

### Requisitos
- Java 17 o superior
- JDK instalado y configurado

### Opción 1: Compilar y ejecutar manualmente

```bash
# Navegar al directorio del proyecto
cd proyecto-final

# Compilar todos los archivos
javac -d bin src/Menu.java src/corte1/*.java src/corte2/*.java src/corte3/*.java

# Ejecutar el programa
java -cp bin Menu
```

### Opción 2: Compilar con un solo comando

```bash
# Windows (PowerShell)
javac -d bin src\Menu.java src\corte1\*.java src\corte2\*.java src\corte3\*.java
java -cp bin Menu

# Linux/Mac
javac -d bin src/Menu.java src/corte1/*.java src/corte2/*.java src/corte3/*.java
java -cp bin Menu
```

### Opción 3: Script rápido (Windows)

Crear un archivo `ejecutar.bat`:

```batch
@echo off
echo Compilando proyecto...
if not exist bin mkdir bin
javac -d bin src\Menu.java src\corte1\*.java src\corte2\*.java src\corte3\*.java
if %errorlevel% == 0 (
    echo Compilacion exitosa!
    echo Ejecutando programa...
    echo.
    java -cp bin Menu
) else (
    echo Error en la compilacion!
)
pause
```

### Opción 4: Script rápido (Linux/Mac)

Crear un archivo `ejecutar.sh`:

```bash
#!/bin/bash
echo "Compilando proyecto..."
mkdir -p bin
javac -d bin src/Menu.java src/corte1/*.java src/corte2/*.java src/corte3/*.java
if [ $? -eq 0 ]; then
    echo "Compilación exitosa!"
    echo "Ejecutando programa..."
    echo
    java -cp bin Menu
else
    echo "Error en la compilación!"
fi
```

Dar permisos de ejecución:
```bash
chmod +x ejecutar.sh
./ejecutar.sh
```

## 🎮 Uso del Programa

1. Al ejecutar el programa, verás el menú principal con 3 opciones de cortes
2. Selecciona un corte (1, 2 o 3)
3. Dentro de cada corte, elige el tema que deseas explorar
4. El programa ejecutará el demo correspondiente
5. Presiona Enter para volver al menú
6. Selecciona 0 para salir

## 💡 Características

✅ **Código completo y funcional** - No son esqueletos, cada demo está completamente implementado  
✅ **Comentarios educativos** - Código bien documentado y fácil de entender  
✅ **Ejemplos prácticos** - Casos de uso reales para cada estructura  
✅ **Visualización clara** - Salida formateada con símbolos y colores textuales  
✅ **Navegación intuitiva** - Menús bien organizados y fáciles de usar  
✅ **Java 17** - Utiliza características modernas de Java  

## 📖 Ejemplos de Salida

Cada demo muestra:
- Operaciones paso a paso
- Visualización de la estructura
- Mediciones de rendimiento (cuando aplica)
- Casos de uso prácticos
- Propiedades y características

## 🎓 Objetivos Educativos

Este proyecto es ideal para:
- Estudiantes de estructuras de datos
- Preparación para entrevistas técnicas
- Repasar conceptos de algoritmos
- Entender complejidad algorítmica
- Practicar implementaciones en Java

## 👨‍💻 Autor

Proyecto educativo para el curso de Estructuras de Datos

## 📄 Licencia

Este proyecto es de uso educativo libre.

---

**¡Disfruta explorando las estructuras de datos!** 🚀

