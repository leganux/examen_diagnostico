Aquí tienes una encuesta de 40 preguntas para evaluar candidatos de desarrollo Full Stack, dividida en categorías:
	•	Preguntas generales (8)
	•	Python (6)
	•	SQL (6)
	•	MongoDB (6)
	•	Node.js (7)
	•	TypeScript (7)



📋 Encuesta de Evaluación - Full Stack Developer

## 1. Preguntas Generales (8)
1.	¿Qué es el desarrollo Full Stack y qué tecnologías se usan comúnmente en este rol? (Pregunta abierta)
2.	¿Cuál es la diferencia entre HTTP y WebSockets? (Pregunta abierta)
3.	¿Qué significa el principio SOLID en programación orientada a objetos? (Pregunta abierta)
4.	¿Cuál es la diferencia entre una API REST y GraphQL? (Pregunta abierta)
5.	¿Qué es un CDN y para qué se utiliza? (Pregunta abierta)
6.	¿Cuál es el propósito de un ORM en una aplicación? (Pregunta abierta)
7.	¿Cuál de las siguientes opciones representa un entorno de ejecución de JavaScript del lado del servidor?
        a) Django
        b) Flask
        c) Node.js
        d) Angular
	8.	¿Qué significa CI/CD en el contexto del desarrollo de software? (Pregunta abierta)

## 1. Preguntas de Python (6)
9.	¿Cuál de las siguientes opciones es un framework de Python para desarrollo web?
    a) Laravel
    b) Django
    c) Flask
    d) b y c
        10.	¿Cuál de las siguientes estructuras de datos de Python es inmutable?
    a) Lista
    b) Diccionario
    c) Tupla
    d) Conjunto
11.	¿Qué hace la función zip() en Python? (Pregunta abierta)
12.	¿Cuál es la diferencia entre is y == en Python? (Pregunta abierta)
13.	¿Qué módulo de Python usarías para manejar conexiones a bases de datos SQL? (Pregunta abierta)
14.	¿Cuál es la salida de este código?

``` python
def func(value, lst=[]):
    lst.append(value)
    return lst

print(func(1))  
print(func(2))  
print(func(3, []))  
```
a) [1] [2] [3]
b) [1] [1, 2] [3]
c) [1] [1] [3]
d) [1] [1, 2] [1, 2, 3]

3. Preguntas de SQL (6)
	15.	¿Cuál es la diferencia entre INNER JOIN, LEFT JOIN y RIGHT JOIN? (Pregunta abierta)
	16.	¿Cuál es la diferencia entre WHERE y HAVING en SQL? (Pregunta abierta)
	17.	¿Cuál es la clave primaria en una base de datos relacional? (Pregunta abierta)
	18.	¿Cuál es la consulta correcta para obtener los nombres de los empleados cuyo salario es mayor a 50,000 en una tabla empleados?
a) SELECT nombre FROM empleados WHERE salario > 50000;
b) SELECT nombre FROM empleados HAVING salario > 50000;
c) FILTER nombre FROM empleados WHERE salario > 50000;
d) WHERE salario > 50000 SELECT nombre FROM empleados;
	19.	¿Qué hace la cláusula GROUP BY en SQL? (Pregunta abierta)
	20.	¿Cuál es la diferencia entre UNION y UNION ALL en SQL? (Pregunta abierta)

## 4. Preguntas de MongoDB (6)
21.	¿Cuál es la principal diferencia entre MongoDB y una base de datos relacional? (Pregunta abierta)
22.	¿Cuál es el equivalente de una “tabla” en MongoDB?
        a) Documento
        b) Colección
        c) Registro
        d) Esquema
            23.	¿Cuál de los siguientes comandos se usa para insertar un documento en una colección de MongoDB?
        a) db.collection.insertOne({...})
        b) db.collection.add({...})
        c) db.collection.push({...})
        d) db.collection.store({...})
24.	¿Cómo se realiza una consulta para encontrar todos los documentos donde edad sea mayor que 30 en MongoDB? (Pregunta abierta)
25.	¿Cuál es la diferencia entre findOne() y find() en MongoDB? (Pregunta abierta)
26.	¿Cómo se define un índice en MongoDB y cuál es su propósito? (Pregunta abierta)

## 5. Preguntas de Node.js (7)
27.	¿Qué módulo de Node.js se usa para trabajar con archivos del sistema?
        a) http
        b) fs
        c) path
        d) express
28.	¿Cuál es la diferencia entre require() e import en Node.js? (Pregunta abierta)
29.	¿Cómo se maneja el asincronismo en Node.js? (Pregunta abierta)
30.	¿Qué significa el event loop en Node.js? (Pregunta abierta)
31.	¿Cuál de las siguientes opciones es una promesa correctamente definida en JavaScript?

        a) new Promise((resolve, reject) => { resolve("Success"); })
        b) new Promise(resolve, reject) => { resolve("Success"); }
        c) Promise(function(resolve, reject) { resolve("Success"); })
        d) new Promise(resolve, reject) { resolve("Success"); }

32.	¿Cuál es la diferencia entre process.nextTick() y setImmediate() en Node.js? (Pregunta abierta)
33.	¿Cómo se instala un paquete en Node.js usando npm? (Pregunta abierta)

## 6. Preguntas de TypeScript (7)
34.	¿Cuál es la principal diferencia entre TypeScript y JavaScript? (Pregunta abierta)
35.	¿Cómo defines una interfaz en TypeScript? (Pregunta abierta)
36.	¿Cuál es el tipo de dato de let x: unknown; en TypeScript?
        a) String
        b) Number
        c) Cualquier tipo
        d) Solo objetos
37.	¿Cuál es la diferencia entre type e interface en TypeScript? (Pregunta abierta)
38.	¿Qué significa el operador ? en una propiedad de una interfaz en TypeScript? (Pregunta abierta)
39.	¿Cómo se define una función genérica en TypeScript? (Pregunta abierta)
40.	¿Cuál es la forma correcta de definir una variable que acepte solo strings en TypeScript?
        a) let nombre: string;
        b) let nombre: String;
        c) let nombre = string;
        d) let nombre: "string";


## Ejercicios


### Ejercicio 1.- Calculadora 


Realiza un programa en el lenguaje de programación que prefieras (de preferencia Node.js o Python).

El programa debe recibir una cadena de operaciones matemáticas, por ejemplo:

"5+3+8-9*7/3"

Debe procesar la cadena dividiéndola en sus componentes y resolviendo las operaciones respetando la jerarquía de operadores (paréntesis, multiplicación, división, suma y resta).

Restricciones:
	•	No se permite el uso de funciones automáticas como eval(), exec() o bibliotecas que resuelvan expresiones directamente.
	•	El procesamiento debe hacerse manualmente, analizando y evaluando la expresión.

Puntos extra:
	•	Si el programa soporta paréntesis para definir la agrupación de operaciones, se otorgarán puntos adicionales.

### Ejercicio 2.- API 

Crea una API básica que permita resolver las operaciones matemáticas del Ejercicio 1 y almacenar el historial en una base de datos.

Requisitos:
	1.	Endpoint para calcular una operación: Recibe una expresión matemática y devuelve el resultado.
	2.	Almacenamiento del historial: Guarda cada operación resuelta en una base de datos.
	3.	CRUD completo:
	•	Consultar la lista de operaciones realizadas.
	•	Eliminar una operación específica.
	•	Opcional: Editar una operación almacenada.

Puedes usar cualquier framework para desarrollar la API (por ejemplo, Express.js en Node.js o FastAPI en Python).

Ahora las instrucciones son más claras y estructuradas. ¿Quieres que agregue más detalles o ejemplos? 😊