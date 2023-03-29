// Obtener los elementos del DOM
const num1 = document.getElementById("num1");
const num2 = document.getElementById("num2");
const btnSuma = document.getElementById("btnSuma");
const btnResta = document.getElementById("btnResta");
const btnMultiplicacion = document.getElementById("btnMultiplicacion");
const btnDivision = document.getElementById("btnDivision");
const resultado = document.getElementById("resultado");

// Funciones flecha para realizar las operaciones
const sumar = () => {
  resultado.innerHTML = +num1.value + +num2.value;
};

const restar = () => {
  resultado.innerHTML = +num1.value - +num2.value;
};

const multiplicar = () => {
  resultado.innerHTML = +num1.value * +num2.value;
};

const dividir = () => {
  if (+num2.value !== 0) {
    resultado.innerHTML = +num1.value / +num2.value;
  } else {
    resultado.innerHTML = "Error: división por cero";
  }
};

// Event listeners para los botones de operaciones
btnSuma.addEventListener("click", sumar);
btnResta.addEventListener("click", restar);
btnMultiplicacion.addEventListener("click", multiplicar);
btnDivision.addEventListener("click", dividir);
