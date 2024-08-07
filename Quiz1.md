Pregunta
¿Cuál de las siguientes líneas de código es una forma más restringida de acceder a una propiedad de un objeto?

Código
JavaScript

const coat = {
  _pockets: 5,
  get pockets() {
    return this._pockets;
  },
  set pockets(newPockets){
    this._pockets = newPockets;
  }
};
Opciones de Respuesta
coat.pockets;
coat._pockets;
coat.pockets = 3;
console.log(coat._pockets);
