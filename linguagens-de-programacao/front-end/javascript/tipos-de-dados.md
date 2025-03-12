# 📌 Tipos de Dados Primitivos no JavaScript

No JavaScript, os **tipos de dados primitivos** são os tipos básicos de valores que não são objetos e não possuem métodos. Eles representam os valores fundamentais da linguagem.

## 📝 Tabela de Tipos Primitivos

| Tipo        | Descrição |
|------------|-----------|
| **String** | Representa uma sequência de caracteres, usada para armazenar texto. Exemplo: `"Olá, mundo!"` |
| **Number** | Representa números inteiros e de ponto flutuante. Exemplo: `42`, `3.14` |
| **Boolean** | Representa um valor lógico: `true` (verdadeiro) ou `false` (falso). |
| **Undefined** | Indica que uma variável foi declarada, mas ainda não recebeu um valor. |
| **Null** | Representa a ausência intencional de um valor ou objeto. |
| **BigInt** | Utilizado para representar números inteiros muito grandes, além do limite do tipo `Number`. Exemplo: `12345678901234567890n` |
| **Symbol** | Representa um identificador único e imutável, geralmente usado como chave em objetos. |

📌 **Dica:** Um número dentro de aspas será um texto com um valor ou seja quando houver entrada de dados por meio de um `prompt()` e não houver a conversão para `Number` ele será considerado como `String` pela linguagem.

## 🎯 Exemplo de Uso

```javascript
let nome = "Alice"; // String
let idade = 25; // Number
let ativo = true; // Boolean
let saldo; // Undefined
let vazio = null; // Null
let grandeNumero = 12345678901234567890n; // BigInt
let id = Symbol("id"); // Symbol
```

Cada um desses tipos de dados tem um propósito específico e é fundamental para a programação em JavaScript.

---
📌 **Dica:** Para verificar o tipo de uma variável, use `typeof` no console:

```javascript
console.log(typeof nome); // "string"
console.log(typeof idade); // "number"
```

