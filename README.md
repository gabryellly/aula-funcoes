﻿# aula-funcoes
function imprimirOlaMundo() {
   console.log("Ola mundo!")
}
imprimirOlaMundo()

function imprimeNome(nome){
  alert('Ola${nomeUser}')
}
let nomeUser = " "
nomeUser = prompt("digite seu nome")
imprimeNome(nomeUser)

function minhaFuncao(variavel) {
	return variavel * 5
}

console.log(minhaFuncao(10))
console.log(minhaFuncao(2))

let textoDoUsuario = prompt("Insira um texto");

const outraFuncao = function(texto) {
	return texto.toLowerCase().includes("cenoura")
}

const resposta = outraFuncao(textoDoUsuario)
console.log(resposta)

let String = "gaby"
let number = 15
let String ("gaby") + number ("15") String + ("estudante")
console.
