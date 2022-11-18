# estrutura-de-repeti-o
const notas = [10, 9, 7, 8, 5, 10]

//Calcular média aritimética das notas

let soma = 0
for(let item of notas) {
  soma = soma + item
}
console.log(soma/notas.length)
