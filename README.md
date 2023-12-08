# Guia Didático JavaScript 📚

[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=flat&logo=javascript)](https://link-para-mais-informacoes)

## Introdução 🔖

Bem-vindo ao Guia Didático JavaScript! Este documento oferece uma visão geral dos conceitos fundamentais do JavaScript, a linguagem de programação amplamente usada para criar interatividade nas páginas web. 🚀

## Variáveis e Tipos de Dados 

📌 JavaScript é uma linguagem dinamicamente tipada, o que significa que você não precisa declarar o tipo de uma variável.

```javascript
// Declarando uma variável
let nome = "John";

// Tipos de dados
let idade = 25; // número
let altura = 1.75; // número decimal
let estudante = true; // booleano
let frutas = ["maçã", "banana", "laranja"]; // array
let pessoa = { nome: "Alice", idade: 30 }; // objeto
```

## Estruturas de Controle de Fluxo

Use estruturas de controle de fluxo para tomar decisões e repetir tarefas.

```javascript
// Estrutura if-else
let hora = 14;
if (hora < 12) {
    console.log("Bom dia!");
} else {
    console.log("Boa tarde!");
}

// Estrutura de repetição (for)
for (let i = 0; i < 5; i++) {
    console.log(i);
}
```

## Funções

As funções são blocos de código reutilizáveis.

```javascript
// Declarando uma função
function saudacao(nome) {
    return "Olá, " + nome + "!";
}

// Chamando a função
let mensagem = saudacao("Ana");
console.log(mensagem);
```

## Manipulação do DOM

JavaScript é frequentemente usado para interagir com o Document Object Model (DOM).

```javascript
// Selecionando um elemento pelo ID
let meuElemento = document.getElementById("meu-id");

// Adicionando um evento de clique
meuElemento.addEventListener("click", function() {
    console.log("Clicou no elemento!");
});
```

## AJAX e Requisições Assíncronas

Realize requisições assíncronas para obter e enviar dados sem recarregar a página.

```javascript
// Requisição AJAX usando Fetch API
fetch("https://api.exemplo.com/dados")
    .then(response => response.json())
    .then(data => console.log(data))
    .catch(error => console.error("Erro: " + error));
```

## Conclusão

O JavaScript é uma linguagem poderosa que permite adicionar interatividade dinâmica às páginas web. Ao compreender variáveis, estruturas de controle, funções e interações com o DOM, você estará bem equipado para criar experiências web mais dinâmicas.

## Recursos Adicionais

- [MDN Web Docs - JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [JavaScript.info](https://javascript.info/)
```

Este é um guia básico para começar com JavaScript. Sinta-se à vontade para personalizar e expandir conforme necessário para atender às suas necessidades específicas.
