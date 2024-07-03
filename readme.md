
# Quiz de Prerrequisitos para TypeScript y Node.

1. **JavaScript Básico:**
   - Describe qué es una función en JavaScript y cómo se declara.
   R/Es un conjunto de código, el cual se puede reciclar(reutilizar) en diferentes partes del código, solo llamándolo desde el nombre de la función.
   function "name function" ("datos que podrían entrar","otro dato",...) {"código que se llamara"}:

2. **Manipulación del DOM:**
   - Explica cómo seleccionar un elemento del DOM y cambiar su contenido.
---------------->

3. **Programación Orientada a Objetos (OOP):**
   - ¿Qué es una clase en JavaScript y cómo se define una?
---------------->

4. **Eventos en JavaScript:**
   - ¿Cómo se agrega un evento de clic a un botón en JavaScript?
    Mediante addEventListener(), (pero no recuerdo muy bien a que se le designara el evento)

5. **Variables y Tipos de Datos:**
   - Explica las diferencias entre `var`, `let`, y `const` en JavaScript.
   R/var->Es global, se puede llamar antes de declararse, pero no estará definida
   let->Es un dato que es variable, puede cambiar despues que se declara
   const->Es un dato que es constante, cuando se determina, no se puede cambiar

6. **Control de Flujo:**
   - ¿Qué son las estructuras de control de flujo y cuáles son algunas de las más comunes en JavaScript?
   R/Malo para recordar nombres, pero seguramente si se que es.

7. **Funciones de Flecha:**
   - Describe qué es una función de flecha en JavaScript y proporciona un ejemplo de cómo se usa.
   R/ Ha diferencia de las funciones declaradas, estas no se pueden llamar en cualquier parte del codigo y en el momento que se expresan, son ejecutadas en el momento.
    -
8. **JSON:**
   - ¿Qué es JSON y cómo se utiliza en JavaScript?
    R/funciona como una base de datos local.

9. **Promesas:**
   - Explica qué es una promesa en JavaScript y proporciona un ejemplo de su uso.
   R/Es una forma de expresar que se solicita algo para continuar con un proceso, mientras que ocurren otros al mismo tiempo

10. **Depuración:**
    - ¿Cuáles son algunas de las herramientas o métodos que se pueden usar para depurar código JavaScript?
------------>

## Preguntas de Selección Múltiple (20)

11. ¿Cuál de las siguientes es la forma correcta de declarar una variable en JavaScript?
   - A) `var myVariable;`
   - B) `variable myVariable;`
   - C) `let myVariable;`
   - D) `A y C son correctas.`

   R/C

12. ¿Qué método se utiliza para agregar un elemento al final de un array en JavaScript?
   - A) `push()`
   - B) `pop()`
   - C) `shift()`
   - D) `unshift()`

   R/A

13. ¿Cuál de los siguientes operadores se utiliza para comparar tanto el valor como el tipo de dos variables en JavaScript?
   - A) `==`
   - B) `===`
   - C) `!=`
   - D) `!==`

   R/B

14. ¿Cuál es la salida del siguiente código?
   ```javascript
   console.log(typeof null);
   ```
   - A) `null`
   - B) `undefined`
   - C) `object`
   - D) `number`

   R/C

15. ¿Cuál de los siguientes métodos se usa para recorrer todos los elementos de un array?
   - A) `forEach()`
   - B) `map()`
   - C) `filter()`
   - D) `Todas las anteriores`

   R/

16. ¿Qué se entiende por “hoisting” en JavaScript?
   - A) Declaraciones de variables y funciones se mueven al principio de su ámbito.
   - B) Es un término para describir la eliminación de variables.
   - C) Es un método para agrupar varias funciones.
   - D) Ninguna de las anteriores.

    R/A

17. ¿Cuál es la diferencia entre `null` y `undefined` en JavaScript?
   - A) `null` significa que una variable ha sido declarada pero no definida, `undefined` significa que no se ha declarado.
   - B) `null` es un valor asignado intencionalmente, `undefined` significa que una variable no tiene valor.
   - C) `undefined` es un valor asignado intencionalmente, `null` significa que una variable no tiene valor.
   - D) No hay diferencia.

   R/B

18. ¿Cuál es el propósito del método `Array.prototype.map()`?
   - A) Modificar el array original.
   - B) Crear un nuevo array con los resultados de aplicar una función a cada elemento del array original.
   - C) Filtrar los elementos de un array.
   - D) Encontrar un elemento en un array.

19. ¿Qué es el `Event Loop` en JavaScript?
   - A) Un ciclo que controla las llamadas recursivas.
   - B) Un proceso que permite a JavaScript realizar operaciones asincrónicas.
   - C) Un método para iterar sobre arrays.
   - D) Ninguna de las anteriores.

   R/B

20. ¿Cuál es la salida del siguiente código?
    ```javascript
    console.log(0.1 + 0.2 === 0.3);
    ```
    - A) `true`
    - B) `false`
    - C) `undefined`
    - D) `NaN`

    /B

21. ¿Qué se entiende por `strict mode` en JavaScript?
    - A) Un modo que permite utilizar características experimentales.
    - B) Un modo que cambia la forma en que se ejecuta JavaScript, haciéndolo más seguro.
    - C) Un método para validar datos.
    - D) Ninguna de las anteriores.

22. ¿Cuál de las siguientes es una forma correcta de crear un objeto en JavaScript?
    - A) `let obj = {};`
    - B) `let obj = Object.create();`
    - C) `let obj = new Object();`
    - D) A y C son correctas.

23. ¿Qué es un `callback` en JavaScript?
    - A) Una función que se pasa como argumento a otra función.
    - B) Un tipo de variable especial.
    - C) Un método para declarar funciones.
    - D) Ninguna de las anteriores.

24. ¿Cuál es el propósito de `async` y `await` en JavaScript?
    - A) Ejecutar funciones síncronas.
    - B) Manejar operaciones asincrónicas de manera más simple y legible.
    - C) Declarar variables globales.
    - D) Ninguna de las anteriores.

25. ¿Cuál de las siguientes es una estructura de datos inmutable en JavaScript?
    - A) Arrays
    - B) Strings
    - C) Objetos
    - D) Ninguna de las anteriores.

26. ¿Cómo se puede convertir un objeto JSON en una cadena de texto en JavaScript?
    - A) `JSON.parse()`
    - B) `JSON.stringify()`
    - C) `toString()`
    - D) `parseInt()`

27. ¿Qué es un `Promise` en JavaScript?
    - A) Una función que se ejecuta inmediatamente.
    - B) Un objeto que representa la eventual finalización (o falla) de una operación asincrónica.
    - C) Un método para declarar variables.
    - D) Ninguna de las anteriores.

28. ¿Qué método se utiliza para agregar uno o más elementos al principio de un array y devolver la nueva longitud del array?
    - A) `push()`
    - B) `pop()`
    - C) `shift()`
    - D) `unshift()`

29. ¿Cuál es la diferencia entre `localStorage` y `sessionStorage` en JavaScript?
    - A) `localStorage` almacena datos solo durante la sesión del navegador, `sessionStorage` almacena datos de manera persistente.
    - B) `sessionStorage` almacena datos solo durante la sesión del navegador, `localStorage` almacena datos de manera persistente.
    - C) No hay diferencia entre ellos.
    - D) Ambos almacenan datos solo durante la sesión del navegador.

30. ¿Qué método se utiliza para detener la propagación de un evento en el DOM?
    - A) `event.stopPropagation()`
    - B) `event.preventDefault()`
    - C) `event.stop()`
    - D) `event.cancel()`