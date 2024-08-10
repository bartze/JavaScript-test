Cada una de las declaraciones de métodos para el objeto calculadora tiene la sintaxis correcta, pero una de ellas NO tendrá el comportamiento deseado. ¿Cuál es y por qué?

const calculator = {
    result: 42,
    clearResult() {
        this.result = 0;
    },
    addTo: function (value) {
        this.result += value;
    },
    multBy: value => {
        this.result *= value;
    },
    displayResult() {
        console.log(this.result);
    },
};

Opciones de respuesta:

displayResult: no se puede registrar en la consola dentro de un método.
clearResult: no se pasó ningún argumento a la función.
multBy: en una función flecha, this NO se refiere al objeto que la contiene.
addTo: las funciones anónimas no se pueden almacenar como propiedades.
