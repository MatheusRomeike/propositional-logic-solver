# Propositional Logic Solver

[🇺🇸 English](#english) | [🇧🇷 Português](#português)

---

## English

A simple propositional logic solver built with **Python**.

The project generates truth tables for logical variables and evaluates propositional expressions using custom logical operators.

It was originally developed as an academic challenge for a Mathematical Logic / Problem Solving course, focused on practicing logical reasoning, truth tables and expression evaluation.

### Features

- Truth table generation
- Variable extraction from logical expressions
- Expression evaluation based on all possible truth combinations
- Support for propositional logic operators
- Parentheses support for expression grouping
- Command-line input flow

### Supported operators

| Operation | Symbol |
|---|---|
| AND | `&` |
| OR | `|` |
| Implication | `<=` |
| Biconditional | `==` |

### Expression example

```txt
a & (b <= c)
```

Another valid example:

```txt
a == (b | c)
```

### How it works

The application receives a logical expression as input, extracts the variables used in the expression, generates all possible truth combinations and evaluates the expression for each row of the truth table.

For example, an expression with three variables generates `2³ = 8` possible combinations.

### Project structure

```txt
.
├── main.py
└── README.md
```

### Technologies

- Python
- Propositional logic
- Truth tables
- Expression parsing
- Logical operators

### Purpose

The goal of this project is to demonstrate basic concepts of propositional logic through code.

It explores:

- Logical operators
- Truth table generation
- Expression evaluation
- Variable combination generation
- Computational representation of mathematical logic

### Notes

This is an academic project and not a production-ready parser.

The current implementation uses Python expression evaluation internally, so it should only be used with trusted input.

Possible future improvements:

- Replace dynamic evaluation with a custom parser
- Add lexical analysis
- Add syntax validation
- Add support for more operators
- Add formatted truth table output
- Add automated tests
- Add CLI arguments

---

## Português

Um resolvedor simples de lógica proposicional desenvolvido com **Python**.

O projeto gera tabelas verdade para variáveis lógicas e avalia expressões proposicionais usando operadores lógicos personalizados.

Ele foi desenvolvido originalmente como um desafio acadêmico para uma disciplina de Lógica Matemática / Resolução de Problemas, com foco em raciocínio lógico, tabelas verdade e avaliação de expressões.

### Funcionalidades

- Geração de tabela verdade
- Extração de variáveis a partir de expressões lógicas
- Avaliação da expressão com todas as combinações possíveis de verdadeiro/falso
- Suporte a operadores de lógica proposicional
- Suporte a parênteses para agrupamento de expressões
- Entrada via linha de comando

### Operadores suportados

| Operação | Símbolo |
|---|---|
| E | `&` |
| OU | `|` |
| Implicação | `<=` |
| Bicondicional | `==` |

### Exemplo de expressão

```txt
a & (b <= c)
```

Outro exemplo válido:

```txt
a == (b | c)
```

### Como funciona

A aplicação recebe uma expressão lógica como entrada, extrai as variáveis utilizadas, gera todas as combinações possíveis de verdadeiro/falso e avalia a expressão para cada linha da tabela verdade.

Por exemplo, uma expressão com três variáveis gera `2³ = 8` combinações possíveis.

### Estrutura do projeto

```txt
.
├── main.py
└── README.md
```

### Tecnologias

- Python
- Lógica proposicional
- Tabelas verdade
- Avaliação de expressões
- Operadores lógicos

### Objetivo

O objetivo deste projeto é demonstrar conceitos básicos de lógica proposicional usando código.

O projeto explora:

- Operadores lógicos
- Geração de tabelas verdade
- Avaliação de expressões
- Geração de combinações de variáveis
- Representação computacional de lógica matemática

### Observações

Este é um projeto acadêmico e não um parser pronto para produção.

A implementação atual utiliza avaliação dinâmica de expressões em Python internamente, então deve ser usada apenas com entradas confiáveis.

Possíveis melhorias futuras:

- Substituir avaliação dinâmica por um parser próprio
- Adicionar análise léxica
- Adicionar validação de sintaxe
- Adicionar suporte a mais operadores
- Adicionar saída formatada da tabela verdade
- Adicionar testes automatizados
- Adicionar argumentos de CLI
