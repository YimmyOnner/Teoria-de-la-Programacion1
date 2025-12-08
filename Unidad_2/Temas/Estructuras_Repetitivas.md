# 🔁 Estructuras Repetitivas en C  

Las estructuras repetitivas, también llamadas **bucles o ciclos**, permiten que un bloque de instrucciones se ejecute múltiples veces mientras se cumpla una condición determinada. Constituyen una de las herramientas más importantes en la programación estructurada, ya que permiten automatizar tareas, procesar grandes volúmenes de datos, realizar cálculos iterativos y optimizar el tiempo de ejecución de un programa.

De acuerdo con *Martínez y Pineda (UNAM, 2025)*, las estructuras repetitivas representan un mecanismo esencial para resolver problemas en los cuales se necesita repetir acciones de forma controlada. Sitios como *GeeksforGeeks*, *Newtum*, *JDoodle* y *W3Schools* explican que los bucles permiten implementar procesos eficientes, reduciendo código innecesario y facilitando operaciones complejas que de otro modo serían inviables mediante instrucciones secuenciales.

En C existen tres estructuras repetitivas principales:

- **while**
- **for**
- **do–while**

Cada una de ellas tiene un propósito particular, una sintaxis propia y una forma distinta de controlar la repetición del bloque de instrucciones.

---

# 📘 1. Estructura `while`

## 💡 Definición  

El ciclo `while` es una estructura repetitiva que ejecuta un conjunto de instrucciones **mientras una condición lógica sea verdadera**. Antes de iniciar cada iteración, el programa evalúa la condición; si esta se cumple, se ejecuta el cuerpo del bucle, y el proceso continúa hasta que la condición resulte falsa.

Según *W3Schools* y *GeeksforGeeks*, este tipo de bucle se conoce como **bucle de condición inicial**, pues verifica la condición *antes* de ejecutar las instrucciones. Esto garantiza un control riguroso, ya que es posible que el ciclo nunca se ejecute si la condición es falsa desde el principio.

## 🛠 Usos comunes  

El ciclo `while` se utiliza cuando:
- Se desconoce la cantidad exacta de repeticiones.  
- La repetición depende del valor de una variable que cambia en cada iteración.  
- Se espera que el usuario ingrese un dato válido y se pregunta repetidamente hasta lograrlo.  
- Se deben procesar datos mientras exista un criterio lógico que lo permita.  

Es ideal para operaciones dependientes de condiciones dinámicas, como lecturas desde archivos, menús interactivos o cálculos que requieren validar un estado antes de continuar.

## 🧱 Sintaxis  

```c
while (condición) {
    // instrucciones mientras la condición sea verdadera
}
```

## 📌 Características importantes  

- Puede ejecutar **cero o más** iteraciones.  
- Si la condición nunca cambia, puede provocar un **bucle infinito**.  
- Es una opción flexible para condiciones complejas.  

---

# 📘 2. Estructura `for`

## 💡 Definición  

El ciclo `for` es una estructura repetitiva diseñada para realizar iteraciones controladas que requieren un número determinado de repeticiones. Está formado por tres expresiones fundamentales:

1. **Inicialización**  
2. **Condición de continuación**  
3. **Actualización del contador**

Como explican *Newtum* y *JDoodle*, esta estructura es muy útil cuando se conoce por adelantado el número de veces que el ciclo debe repetirse. Además, agrupa sus tres componentes en una sola línea, lo cual permite un código más compacto y legible.

## 🛠 Usos comunes  

Se utiliza en situaciones como:
- Recorrer un rango numérico.  
- Iterar sobre arreglos o listas.  
- Realizar operaciones repetitivas con un contador.  
- Ejecutar procesos de forma predecible y estructurada.  
- Algoritmos matemáticos y computacionales (sumatorias, factoriales, secuencias, etc.).  

## 🧱 Sintaxis  

```c
for (inicialización; condición; actualización) {
    // instrucciones que se repiten
}
```

## 📌 Características importantes  

- Es ideal cuando se conoce la cantidad exacta de repeticiones.  
- Su estructura compacta mejora la lectura del código.  
- Evita errores de actualización del contador, ya que lo incluye en su sintaxis.  
- Es más eficiente al recorrer estructuras de datos.

---

# 📘 3. Estructura `do–while`

## 💡 Definición  

El ciclo `do–while` es similar al `while`, pero con una diferencia fundamental:  
**primero ejecuta el bloque de instrucciones y luego evalúa la condición.**

Esto garantiza que el cuerpo del ciclo se ejecute **al menos una vez**, independientemente del valor inicial de la condición. *W3Schools* destaca que este bucle se usa cuando se necesita una ejecución mínima garantizada, como en menús, validaciones iniciales o procesos interactivos con el usuario.

## 🛠 Usos comunes  

Se utiliza cuando:
- Se necesita ejecutar el ciclo al menos una vez.  
- El usuario debe ingresar un dato y se debe validar posteriormente.  
- Se implementan menús que se repiten hasta que el usuario elija salir.  
- Se debe realizar una acción antes de comprobar la condición.  

## 🧱 Sintaxis  

```c
do {
    // instrucciones que se ejecutan al menos una vez
} while (condición);
```

## 📌 Características importantes  

- Garantiza **una ejecución inicial obligatoria**.  
- Es útil en estructuras de interacción con el usuario.  
- Puede provocar bucles infinitos si no se controla adecuadamente.  
- Representa un bucle de condición **final**, no inicial.

---

# 🧠 Comparación general de los tres bucles

| Estructura | Evalúa antes o después | ¿Puede ejecutarse 0 veces? | ¿Cuándo usarla? |
|-----------|------------------------|----------------------------|------------------|
| **while** | Evalúa **antes** | Sí | Cuando no se conoce cuántas veces se repetirá |
| **for** | Evalúa **antes** | Sí | Cuando se conoce el número exacto de iteraciones |
| **do–while** | Evalúa **después** | No (mínimo 1 vez) | Menús, validaciones o procesos que requieren ejecución inicial |

---

# 🧩 Importancia de las estructuras repetitivas  

Las estructuras repetitivas permiten:

- Automatizar procesos repetitivos.  
- Reducir el código redundante.  
- Implementar cálculos iterativos complejos.  
- Trabajar con grandes volúmenes de datos.  
- Crear menús, bucles interactivos y simulaciones.  
- Optimizar el rendimiento del programa.  

Sin los bucles, los programas serían extremadamente largos, rígidos e incapaces de manejar tareas repetidas de manera eficiente.

---

📝 *Aquí puedes agregar tus diagramas de flujo, ejercicios en C o ejemplos de aplicación.*

