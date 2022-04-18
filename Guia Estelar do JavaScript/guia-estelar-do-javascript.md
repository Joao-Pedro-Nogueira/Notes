# DATA TYPES

## String

- É uma cadeia de caracteres. Podem ser números, letras, símbolos, espaços, podem ter pontuação, acentuação.

// "" aspas duplas
// '' aspas simples
// `` template literals ou template strings (mais funcionalidades)

- Tomar cuidado com as strings que tiverem algum dos elementos acima, pois podem dar erro.

- As crases (template literals) permitem quebra de linhas e interpolação (cálculo utilizando "${cálculo aqui}")

## Number

- Basicamente números de vários tipos.

// 33 ou -33 inteiros
// 12.4 reais
// NaN not a number
// Infinity infinito

## Boolean

- Verdadeiro ou falso

// true -> verdadeiro
// false -> falso

## Undefined vs Null

- A palavra "undefined" e "null" são reservadas no JS
- Undefined = indefinido
- Null = vazio, não possui nada dentro, nenhum valor

## Object

- Objeto que possui diversas propriedades/atributos e funcionalidade/métodos
- Sintaxe: "{ propriedade: valor }

## Array (vetor)

- Basicamente é uma lista,um agrupamento de dados
- Sintaxe: "["João Pedro", 19, "Campo Grande - MS"]"

## Tipos de dados segundo ECMAScript

- O JS é focado em trabalhar com objetos
- Documentação: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects
- Segundo o ECMAScript existem 9 tipos de dados, divididos em 3 categorias:

### Primitive value (não é objeto e seu valor é imutável)

- String
- Number
- Boolean
- undefined
- Symbol
- BigInt

### Structural

- Object

  - Array
  - Map
  - Set
  - Date
  - outros...

- Function

### Structural primitive / Structural root primitive

- null
