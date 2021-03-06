<p align="center">
     <img src="/Images/csharp_logo.png" alt="C#" width="250px" />
</p>

# .NET - Introdução ao C# 8.0

## O que é C#?

C# é uma linguagem de programação, multiparadigma, de [tipagem forte](https://github.com/Pampa-Devs/articles/blob/master/typing.md)
desenvolvida pela **Microsoft** como parte da **plataforma .NET**. A sua sintaxe orientada a objetos foi baseada no C++ mas inclui muitas influências de outras linguagens
de programação, como Object Pascal e, principalmente, Java.

## Por que C# como primeira linguagem?

Não existe resposta certa para essa pergunta e cada pessoa provavelmente vai te dar uma resposta diferente se baseando em seu gosto e experiência. 
Então pretendo te apresentar algumas coisas legais que o C# oferece que me fazem acreditar que ele é uma ótima linguagem para se iniciar.

### C# é Versátil

Com ele você pode desenvolver:
* Aplicações para Windows
* Aplicações WEB
* Serviços WEB e WEB API
* Apps nativos iOS e android
* Inteligência Artificial e Machine Learning
* Aplicações e Serviços com a Azure Cloud
* Aparelhos com Internet das Coisas (IoT) 
* Video Games
* E muito mais

### Mercado

C# é uma das linguagens **mais utilizadas no mundo**, com uma breve busca no LinkedIn você encontra diversos empregos para quem trabalha com ela.
Cada região tem um salário, mas profissionais experientes são **muito bem remunerados**.

### .NET Core

O framework **.NET Core** da Microsoft permite desenvolvimento multiplataforma e é extremamente performático e modular

### Comunidade Gigantesca

Você pode aprender C# em diversos lugares diferentes e de graça. Além desse tutorial, vou deixar mais alguns links para ajudar no seu estudo:
* http://www.macoratti.net/08/08/c_bas1.htm
* https://docs.microsoft.com/pt-br/dotnet/csharp/tutorials/intro-to-csharp/
* https://www.udemy.com/pt/topic/c-sharp/free/

## Ferramentas Necessárias

Existem diversos editores de código, neste tutorial iremos utilizar o **Microsoft Visual Studio** que é especialmente dedicado ao C# (.NET Framework).

1. 💿 [**Instalando e configurando o Visual Studio**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/install-vs.md)
2. 💻 [**Criando o primeiro projeto**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/create-sln.md)

## Tutorial

Aqui iremos apresentar os conceitos básicos e elementares de programação e desenvolvimento de algoritimos, bem como características e paradigmas da linguagem de programação C#.

### Básico

Conceitos básicos que devemos saber prosseguir com o tutorial:

1. 🎲 [**Váriaveis**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/variables.md)
2. ▶️ [**Main - Ponto de partida da aplicação C#**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/main.md)

### Tipos
No C# existem dois tipos: **tipos de valor** e **tipos de referência**. As váriaveis de **tipos de valor** contêm diretamente seus dados
enquanto variáveis de **tipos de referência** armazenam a referência a seus dados, o último sendo conhecido como objetos.

3. 🔵 [**Tipos de Valor**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/value-types.md)
4. 🟢 [**Tipos de Referência**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/reference-types.md)
5. 🔷 [**"Tipo" var**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/var-type.md)

### Modificadores de acesso

Modificadores de acesso controlam se o seu **tipo** pode ser usado em outro bloco de código ou até em outro projeto.

6. 🚦 [**Modificadores de acesso**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/access-modifiers.md)

### Classes e Structs

Classes e structs são essencialmente uma **estrutura de dados** que encapsula um conjunto de *dados* e *comportamentos*. Esses *dados* e *comportamentos*
são os **membros** da classe ou struct, e eles incluem métodos, propriedades, eventos e mais alguns listados mais para frente.

7. 🧬 [**Propriedades**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/properties.md)
8. 🚶 [**Métodos**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/methods.md)
9. 🛠️ [**Construtores**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/constructors.md)
10. 🗑️ [**Finalizadores**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/destructors.md)
11. 🤝 [**Classes Parciais**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/partial-class-methods.md)
12. 👩‍👦 [**Herança**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/heritage.md)
13. 🎭 [**Polimorfismo**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/polymorphism.md)

### Coleções

Em diversas situações, você irá necessitar gerenciar um grupo de objetos. Abaixo algumas formas de como fazer isso no C#:

14. 🔢 [**Arrays**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/arrays.md)
15. 🔢 [**Listas**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/lists.md)
16. 🔠 [**Dicionários**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/dictionaries.md)

### Operadores

Operadores são os símbolos utilizados para realizar operações em váriaveis. 

No exemplo abaixo o `+` é o operador, `2` e `5` são os operandos.
```C#
int a = 2 + 5;
```

17. ➕ [**Operadores Aritméticos**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/arithmetic-operators.md)
18. ⁉️ [**Operadores Lógicos**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/logical-operators.md)
29. ✔️ [**Operadores de Igualdade**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/equality-operators.md)
20. ⚖️ [**Operadores de Comparação**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/comparison-operators.md)
21. ⚙️ [**Operadores Bitwise e Shift**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/bitwise-shift-operators.md)

### Estruturas

As estruturas são instruçõoes do nosso programa que realizam funções específicas.

22. 🔀 [**Estruturas Condicionais**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/conditional-statements.md)
23. 🔄 [**Estruturas de Repetição**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/iteration-statements.md)
24. 🛑 [**Exceções e Manipulação de Exceções**](https://github.com/Pampa-Devs/4starters/blob/master/Fundamentals/csharp/src/exceptions.md)

# Autores
* [Felipe Almeida](https://github.com/felipe-allmeida) - Fundador da PampaDevs e Engenheiro de Software
