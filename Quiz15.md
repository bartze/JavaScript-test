Selecciona la implementación correcta del método doHowl() para que devuelva el valor de la propiedad howl cuando se llame.

const wolf = {
  howl: 'ARH-WOOOOOOO',
  doHowl() {
    // devuelve la propiedad `howl` desde este método.
  }
};
console.log(wolf.doHowl());

Opciones de respuesta

JavaScript

doHowl() {
  return this.howl;
}

doHowl() {
  return this;
}

doHowl() {
  return howl;
}

doHowl() {
  return window.howl;
}
