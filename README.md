# Atividade-----Pweb.
Exercício 01 

console.log("Bom dia, turma!");

Exercício 02

console.log("Meu nome é");
console.log("Fernanda e Larissa");
console.log("Estou aprendendo JavaScript");

Exercício 03

const cidade ="cedro";
console.log (cidade);

Exercício 04

let idade = 16;
idade = 17;
console.log("idade");

Exercício 05

const escola = "ifce";
escola = "ifce cedro";
console.log("escola");
// O erro foi que não tinha as aspas no console.log

Exercício 06 

// PrimeiroAluno
// NomeCompleto
// PrecoTotal
// NotaFinal
// ifce

Exercício 07

const disciplina = "programacao web";
const quantidadeaulas = 20;
const estaaprovado = true;
const observacao = null;
let mediafinal;
console.log("disciplina");
console.log(" quantidadeaulas");
console.log("estaaprovado");
console.log("observacao");
console.log("mediafinal");

Exercício 08

const disciplina = "programacao web";
const quantidadeaulas = 20;
const estaaprovado = true;
const observacao = null;
let mediafinal;
console.log(typeof disciplina);
console.log(typeof quantidadeaulas);
console.log(typeof estaaprovado);
console.log(typeof observacao);
console.log(typeof mediafinal);

Exercício 09

const altura = 1.72;
const peso = 65;
console.log("altura");
console.log("peso");

Exercício 10

const a = "5";
const b = 5;
//A minha previsão é que vai aparecer 55 no terminal.
console.log("a + b");
// a variável a é um texto e a variável b é do tipo número ai quando colocamos o + ele junta os numeros formando 55.

Exercício 11

let nome = "Ana";
console.log("Bem-vindo," + nome + "!");

Exercício 12

let nome = "Ana";
console.log(`Bem-vindo,${nome}!`);

Exercício 13

let frase = "JavaScript é divertido";
console.log(frase.length);
console.log(frase.toUpperCase());
console.log(frase.toLowerCase());

Exercício 14

let nome = "Ana";
let sobrenome = "Silva";
let nomecompleto = nome + " " + sobrenome;
console.log(nomecompleto);

Exercício 15

let produto = "Caderno";
let preco = 12.5;
console.log(`o produto ${produto} custa R$ ${preco}`);

Exercício 16

let numeroa = 10;
let numerob = 3;
console.log(numeroa + numerob);
console.log(numeroa - numerob);
console.log(numeroa * numerob);
console.log(numeroa / numerob);
console.log(numeroa % numerob);
console.log(numeroa ** numerob);

Exercício 17

let contador = 0;
contador += 5;
console.log(contador);

contador *= 3;
console.log(contador);

contador -= 1;
console.log(contador);

Exercício 18

// true 
console.log(10 > 5);
// false
console.log(10 < 5);
// true
console.log(10 >= 10);
// false
console.log(10 <= 9);

Exercício 19

console.log(7=="7");
console.log(7==="7");
// o operador == compara apenas o valor 
// o operador === compara o valor e o tipo

Exercício 20

let temcarteira = true;
let temcombustivel = false;
console.log(temcarteira && temcombustivel);
console.log(temcarteira || temcombustivel);
console.log(!temcarteira);

Exercício 21

let idade = 20;
if (idade >= 18){
    console.log("Maior de idade");

} 

Exercício 22

let idade = 20;
if (idade >= 18){
    console.log("Maior de idade");

} else {
    console.log("Menor de idade");
}

Exercício 22.2

let idade = 15;
if (idade >= 18){
    console.log("Maior de idade");

} else {
    console.log("Menor de idade");
}

Exercício 23

let nota = 9;
if (nota >= 7){
    console.log("aprovado!");
} else if (nota >=5){
    console.log("recuperacao");
} else {
    console.log("reprovado!");
}

Exercício 23.2

let nota = 6;
if (nota >= 7){
    console.log("aprovado!");
} else if (nota >=5){
    console.log("recuperacao");
} else {
    console.log("reprovado!");
}


Exercício 23.3

let nota = 3;
if (nota >= 7){
    console.log("aprovado!");
} else if (nota >=5){
    console.log("recuperacao");
} else {
    console.log("reprovado!");
}

Exercício 24

let numero = 7;

if (numero % 2 === 0) {
    console.log("Par");
} else {
    console.log("Impar");
}

Exercício 24.2

let numero = 10;

if (numero % 2 === 0) {
    console.log("Par");
} else {
    console.log("Impar");
}


Exercício 25

let idade = 16;
let anoAtual = 2026;

let ano = anoAtual + (18 - idade);

console.log("Voce completa 18 anos em " + ano);

Exercício 26

let senhaCorreta = "ifce2026";
let senhaDigitada = "ifce2026";

if (senhaDigitada === senhaCorreta) {
    console.log("Acesso liberado");
} else {
    console.log("Senha incorreta");
}

Exercício 26.2

let senhaCorreta = "ifce2026";
let senhaDigitada = "ifce2025";

if (senhaDigitada === senhaCorreta) {
    console.log("Acesso liberado");
} else {
    console.log("Senha incorreta");
}

Exercício 27

let idade = 20;
let temIngresso = true;

if (idade >= 18 && temIngresso) {
    console.log("Pode entrar");
} else {
    console.log("Nao pode entrar");
}

Exercício 27.2

let idade = 20;
let temIngresso = false;

if (idade >= 18 && temIngresso) {
    console.log("Pode entrar");
} else {
    console.log("Nao pode entrar");
}



Exercício 28

let idade = 16;
console.log(idade);
// O erro era que "console" estava escrito errado como "console".

Exercício 28.2

const nota = 8;

if (nota == 7) {
    console.log("Aprovado");
}
// O erro era usar "=" no if. Para comparar valores deve-se usar "==" ou "===".

Exercício 28.3

const idade = 20;

if (idade >= 18) {
    console.log("Pode entrar");
}
// O erro era que faltava a chave "}" para fechar o bloco do if.

Exercício 28.4

const nome = "Ana";
console.log(nome);
// O código funcionava, mas faltavam os pontos e vírgulas no final das linhas.

Exercício 28.5

const preco = 10;
console.log(preco);
// O nome da variável estava com cedilha ("preço"). Nomes de variáveis não devem usar acentos nem caracteres especiais.

