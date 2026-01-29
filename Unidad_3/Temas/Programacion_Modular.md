# 🧩 Programación Modular

La **programación modular** es una técnica de diseño de software que consiste en dividir un programa complejo en **partes más pequeñas y autónomas** llamadas *módulos*. Cada módulo contiene un conjunto de instrucciones que realizan una tarea específica, lo que facilita la comprensión, el mantenimiento, la reutilización y la verificación independiente del código. :contentReference[oaicite:1]{index=1}

Este enfoque surge históricamente con la necesidad de gestionar programas cada vez más grandes y complejos, donde el desarrollo secuencial clásico puede generar código difícil de depurar, extender o comprender. A finales de los años sesenta y comienzos de los setenta se inició la práctica de descomponer programas en módulos para mejorar la organización y reducir la complejidad general. :contentReference[oaicite:2]{index=2}

---

## 🎯 Definición

La programación modular es el proceso de diseñar un programa como un conjunto de **módulos independientes** que se integran para formar una solución completa. Cada módulo puede ser probado, depurado y entendido de forma aislada, reduciendo la complejidad cognitiva del sistema global. :contentReference[oaicite:3]{index=3}

En el lenguaje C, la modularidad se implementa principalmente mediante **funciones**, las cuales encapsulan lógica específica que puede ser reutilizada en diferentes partes del programa. :contentReference[oaicite:4]{index=4}

---

## 🧠 Ventajas de la Programación Modular

La programación modular ofrece múltiples beneficios académicos y prácticos:

- **Claridad y legibilidad:** El código modular es más fácil de leer y entender, pues cada módulo realiza una función específica. :contentReference[oaicite:5]{index=5}  
- **Mantenibilidad:** Los cambios en el programa se pueden realizar en módulos aislados sin afectar la totalidad del sistema. :contentReference[oaicite:6]{index=6}  
- **Reutilización de código:** Un módulo bien diseñado puede ser reutilizado en múltiples programas o contextos. :contentReference[oaicite:7]{index=7}  
- **Depuración independiente:** Permite probar y corregir cada módulo por separado, mejorando la calidad general del producto. :contentReference[oaicite:8]{index=8}  
- **Trabajo colaborativo:** Facilita la asignación de diferentes módulos a distintos integrantes de un equipo de desarrollo. :contentReference[oaicite:9]{index=9}

---

## 📐 Conceptos Fundamentales

### 📌 Módulo

Un módulo es una unidad funcional del programa que ejecuta una tarea específica. En C, un módulo se puede representar mediante una **función**, la cual recibe parámetros de entrada y puede retornar valores al módulo que lo invoca. :contentReference[oaicite:10]{index=10}

---

### 📌 Función

Una **función** es un bloque de código que realiza un conjunto de instrucciones definido bajo un nombre. La función puede ser llamada desde cualquier parte del programa principal (o desde otros módulos), transmitiéndole valores conocidos como **argumentos**. :contentReference[oaicite:11]{index=11}

Cada función en C se compone de:

- **Prototipo o declaración:** Indica el tipo de valor que la función devolverá y los tipos de sus parámetros.
- **Definición o cuerpo de la función:** Contiene las instrucciones que componen el módulo.
- **Llamada a la función:** Invoca la ejecución del módulo desde otra parte del programa. :contentReference[oaicite:12]{index=12}

---

## 🛠 Estructura en C

En C, todo programa contiene al menos la función `main()`, la cual actúa como punto de entrada del programa. Además, los programas modulares contienen otras funciones definidas por el programador:

```c
// Prototipo de función
tipo_de_retorno nombreFuncion(tipo parametro1, tipo parametro2);

// Función principal
int main() {
    // Código principal
    nombreFuncion(valor1, valor2); // Llamada a función
    return 0;
}

// Definición de la función
tipo_de_retorno nombreFuncion(tipo parametro1, tipo parametro2) {
    // Código de la función
}

