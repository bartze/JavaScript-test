Pregunta
¿Cuál de las siguientes opciones está accediendo a la propiedad _title del objeto usando el método getter?

Código
JavaScript

const book = {
  _title: 'Harry Potter',
  _author: 'J.K. Rowling',
  get title() {
    return this._title;
  },
  get author() {
    return this._author;  
  }
}
Opciones de Respuesta
book._title();
book.title();
book.title;
book._title;
