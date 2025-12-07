# 🧩 Estructuras Condicionales en C  

Las estructuras condicionales representan uno de los fundamentos esenciales de la programación estructurada. Su objetivo principal es permitir que un programa pueda **tomar decisiones** basadas en la evaluación de una condición lógica. Esto permite modificar el flujo natural de ejecución y seleccionar qué instrucciones deben ejecutarse según el contexto, lo cual es indispensable en cualquier sistema interactivo o proceso que requiera validación.

Autores como Martínez y Pineda (UNAM, 2025) resaltan que las estructuras condicionales son el punto en el cual un programa deja de ser completamente lineal para convertirse en un sistema capaz de reaccionar ante situaciones específicas. De igual forma, recursos contemporáneos como GeeksforGeeks, W3Schools o Newtum explican que estas estructuras permiten implementar desde simples validaciones de datos hasta sistemas complejos de toma de decisiones.

A continuación, se presentan las estructuras condicionales más utilizadas en el lenguaje C: **if**, **if–else**, **if anidado** y **switch**, acompañadas de sus definiciones, usos más comunes y sintaxis general.

---

## 📘 1. La estructura `if`

### 📌 Definición  
La sentencia `if` es la forma más básica de decisión en C. Permite ejecutar un bloque de código únicamente si una condición resulta verdadera. Si la condición es falsa, el programa ignora dicho bloque y continúa con la siguiente instrucción.

De acuerdo con el libro *Introducción a la Programación* (2021), esta estructura corresponde al modelo fundamental de toma de decisiones:  
**“Si ocurre algo, entonces ejecuta una acción”**.

### 📌 Usos típicos  
- Validación de valores ingresados por el usuario.  
- Verificación de rangos o restricciones.  
- Control de procesos lineales que requieren una sola condición.  
- Activación de eventos o mensajes específicos.

### 📌 Sintaxis  
*/

if (condición) {
    // instrucciones a ejecutar si la condición es verdadera
}

/*


---

## 📘 2. La estructura `if–else`

### 📌 Definición  
El `if–else` extiende la funcionalidad del `if` permitiendo elegir entre dos bloques de instrucciones. Si la condición se cumple, se ejecuta el primer bloque; si no, se ejecuta el segundo.

La UNAM (2025) señala que esta estructura garantiza que el programa siempre ejecutará **una de las dos alternativas**, lo que es útil en situaciones donde siempre debe haber una respuesta.

### 📌 Usos típicos  
- Aprobación o reprobación de notas.  
- Clasificaciones binarias (mayor-menor, positivo-negativo).  
- Validación estricta de acceso.  
- Confirmaciones lógicas.

### 📌 Sintaxis  

if (condición) {  
  // instrucciones si verdadera  
} else {  
  // instrucciones si falsa  
}

---

## 📘 3. If anidado

### 📌 Definición  
El if anidado consiste en colocar una estructura if dentro de otra. Este tipo de estructura es ideal cuando se necesita evaluar múltiples condiciones en secuencia.

Según Martínez & Pineda, este mecanismo permite implementar decisiones “en capas”, útiles para clasificaciones de varios niveles y árboles lógicos más complejos.

### 📌 Usos típicos  
- Evaluación de rangos (bajo, medio, alto).  
- Selección entre múltiples opciones basadas en valores numéricos.  
- Validaciones que requieren varias etapas consecutivas.  
- Construcción de menús interactivos.

### 📌 Sintaxis  

if (condición1) {  
  // bloque 1  
} else if (condición2) {  
  // bloque 2  
} else if (condición3) {  
  // bloque 3  
} else {  
  // alternativa final  
}

---

## 📘 4. Estructura múltiple `switch`

### 📌 Definición  
El `switch` es una estructura condicional múltiple que permite seleccionar entre varias alternativas en función del valor específico de una variable o expresión. Sitios como JDoodle y GeeksforGeeks destacan que su sintaxis es más limpia y legible que una secuencia extensa de if–else cuando se comparan valores iguales.

### 📌 Usos típicos  
- Menús interactivos numéricos.  
- Selección de operaciones (suma, resta, multiplicación).  
- Conversión de valores (días, meses, niveles).  
- Procesos donde cada caso es independiente.

### 📌 Sintaxis  

switch (variable) {  
 case valor1:  
  // instrucciones  
  break;  

 case valor2:  
  // instrucciones  
  break;  

 default:  
  // instrucciones si ningún caso coincide  
  break;  
}

---

## 🧠 Importancia General de las Estructuras Condicionales  

- Permiten **modificar el flujo** del programa.  
- Hacen el algoritmo más **flexible** y adaptable.  
- Representan la base de la **toma de decisiones lógica**.  
- Facilitan la creación de sistemas interactivos y dinámicos.  
- Son indispensables en validaciones, filtrados y clasificación de datos.

---

📝 *Aquí puedes agregar tus ejemplos en C para cada estructura condicional.*  

