# Numerical Algorithms Platform
**A platform for implementing, testing and analyzing numerical algorithms, focusing on interpolation and regression methods. Includes computational complexity analysis and performance evaluation, aimed at students and researchers in numerical analysis.**

---

## Table of Contents

- [Description](#description)
- [Features](#features)
- [User Stories](#user-stories)
- [CRC Cards](#crc-cards)
- [License](#license)

---

## Description

This project provides a flexible platform for implementing and experimenting with numerical algorithms, particularly focusing on interpolation and regression methods. The platform is designed for use directly in the console, offering an interactive environment for testing and analyzing various numerical techniques. It includes tools for visualizing results, evaluating performance, and analyzing the computational complexity of different algorithms. The goal is to provide a simple, yet powerful, command-line interface for students and researchers in numerical analysis.

## Features
- **Interpolation Methods**: Polynomial interpolation methods.
- **Regression**: Linear and polynomial regression techniques.
- **Linear Systems Solvers**: Algorithms for solving systems of linear equations, such as Gaussian elimination.
- **Analysis**: Computational complexity analysis and performance evaluation of different algorithms.
- **Extensibility**: Easily extendable to add new numerical methods.
- **Visualization**: Tools for visualizing results in the terminal.

## User Stories

1. **Como estudante**, quero acessar exemplos práticos e bem explicados de métodos para resolver interpolação e regressões lineares.
   - **Critérios de aceitação**:
      - Código fonte com explicações claras em comentários
      - Documentação sobre funcionamento de cada método
      - Exemplos de entrada e saída de cada algoritmo
        
2. **Como pesquisador**, quero comparar diferentes métodos de interpolação em termos de precisão e custo computacional, a fim de determinar o método mais adequado para determinado problema.
   - **Critérios de aceitação**:
     - Análise da complexidade computacional
     - Explicação das vantagens e desvantagens de cada método

3. **Como professor** gostaria de ferramentas simples e diretas para métodos de interpolação, a fim de confeccionar exercícios e provas, estando a par da dificuldade desses pelos retornos das ferramentas.
   - **Critérios de aceitação**:
      - Apresentação dos métodos de interpolação por meio de uma lista hierárquica, construída com base na complexidade computacional
      - Escolha do formato de saída (ex.: decimal, fração imprópria, notação ENG, dentre outros) dos resultados das ferramentas.

4. **Como matemático** gostaria de um catálogo de ferramentas diversas para ajuste de curvas e interpolação numérica, com o intuito de obter com precisão aproximações para funções mais complexas de serem calculadas manualmente.
   - **Critérios de aceitação**:
      - Catálogo organizado das funções do programa
      - Retorno de funções como respostas, dada necessidade de aproximações polinomiais

5. **Desenvolvedor Educacional** gostaria de um ambiente colaborativo onde professores possam compartilhar recursos e exercícios, provas antigas e materiais didáticos sobre interpolação e regressão para construir uma comunidade ativa.
   - **Critérios de aceitação**:
      - Plataforma para upload e download de exercícios, provas e materiais didáticos.
      - Sistema de comentários e avaliações para cada conteúdo compartilhado.

6. **Coordenador Pedagógico** gostaria de desenvolver um plano de aula que utilize a plataforma para ensinar os métodos numéricos com atividades práticas e conseguir avaliar o desempenho e progresso dos alunos.
   - **Critérios de aceitação**:
      - Plataforma agendar sessões de estudo em grupo com ferramentas integradas.
      - Fórum para discussão de dúvidas e compartilhar recursos úteis.
      - Sistema de acompanhamento do progresso dos alunos, com o resultado da atividade realizada.


## CRC Cards

### Class: Interpolator
- Responsabilidades
- Colaborações

### Class: Regressor 
- Responsabilidades
- Colaborações

### Class: Matrix
- Responsabilidades
- Colaborações

### Class: LinearSystemSolver
- Responsabilidades
- Colaborações

### Class: ConsoleVisualizer
- Responsabilidades
- Colaborações

### Class: DataProcessor
- Responsabilidades
- Colaborações

## License 
This project is licensed under the MIT License.

   

