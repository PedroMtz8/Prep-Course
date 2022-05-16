* Objetos
    Los objetos son como los arrays, los arrays pueden tener multiples elementos relacionados unos con otros, los objetos pueden contener mucha información de una sola cosa.
    La diferencia con los arrays es que a los objetos se les puede asignar una "clave" y un "valor", por ejemplo:

        var estudiante = {
        nombre: "Pedro",
        edad: 19,
        hobbi: "Deportes"
        }

    Como se puede ver, se declara una variable y despues se agregan los objetos con sus CLAVE-VALOR, los objetos son toda la información dentro, a estos se les asigna la clave y el valor, la clave seria: ['nombre', 'edad', 'hobbi'] y los valores de cada clave serian: ['Pedro', 19, 'Deportes'].




* Propiedades
     Las propiedades son las claves de los objetos, son a las que se les asigna un valor.



* Métodos
     En los objetos, a los valores se les puede establecer funciones, las funciones guardadas en un objeto se les llama metodos

* Bucle `for…in`
     Para iterar con objetos se utiliza "for...in", cuando queramos iterar sobre un par clave-valor en nuestro objeto, a diferencia con las matrices que se utiliza un estándar para el bucle y una variable de número de índice, los objetos no contienen índices numericos, por lo que el bucle estándar no funcionará para los objetos. Para sustituir el blucle estándar Javascript tiene otro tipo de bucle llamada "for... in loop". Este tiene una sintaxis un poco diferente, comienza igual pero entre paréntesis declararemos una variable, la palabra clave `in` y el nombre del objeto. Esto recorrerá cada clave del objeto y finalizará cuando se hayan iterado todas las claves. Podemos usar esta clave, y la notación de corchetes, en nuestro bucle for para acceder al valor asociado con esa clave.

     Ejemplo: 
        for (let clave in usuario){
        console.log(clave);
        console.log(usuario[clave]);

     
* Notación de puntos vs notación de corchetes

     Una vez que tengamos los pares clave-valor, podemos acceder a esos valores llamando al nombre del objeto y la clave. Hay dos formas diferentes de hacer esto, usando puntos o usando corchetes.

        Con la notación de puntos podemos llamar al nombre del objeto, un punto y el nombre de la clave. Así como llamamos a la propiedad `.length` en una matriz. La propiedad de longitud es un par de clave-valor.

        La notación de corchetes es como llamar a un elemento en una matriz, aunque con corchetes debemos usar una cadena o número, o una variable que apunte a una cadena o número. Se puede llamar a cada clave envolviéndola con comillas.