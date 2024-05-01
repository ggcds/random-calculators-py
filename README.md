# Calculadoras Aleatórias

Este projeto consiste em um conjunto de três calculadoras desenvolvidas em Python, demonstrando a aplicação prática de conceitos avançados de design de código e arquitetura de software. Cada calculadora foi projetada para lidar com diferentes tipos de cálculos, ilustrando como técnicas específicas de programação podem ser empregadas para resolver problemas matemáticos complexos com eficiência e precisão.

Os conceitos abordados incluem:
- **Separação de Responsabilidades**: Cada parte do código foi estruturada para ter uma única responsabilidade, facilitando a manutenção e a expansão futura do projeto.
- **Tratamento de Lógicas Complexas**: Foi demonstrado como decompor problemas complexos em subproblemas mais simples, utilizando abordagens claras e eficientes.
- **Uso de Bibliotecas Terceiras**: A utilização da biblioteca NumPy exemplifica como integrar ferramentas externas para otimizar cálculos e processamentos de dados.
- **Testes Unitários**: Foram implementados testes para garantir a confiabilidade das funcionalidades oferecidas por cada calculadora, assegurando que elas operem conforme esperado sob diversas condições.
- **Tratamento de Erros**: Foi abordado estratégias eficazes para o manejo de exceções, garantindo que o programa seja robusto e estável mesmo quando confrontado com entradas inválidas ou situações inesperadas.

Este projeto não apenas reforça fundamentos teóricos, mas também proporciona uma experiência valiosa em como aplicar essas técnicas em um contexto real de desenvolvimento de software.

## Funcionalidades

- **Calculadora 1**: 
  - Recebe um número como entrada e o divide em três partes iguais.
  - A **primeira parte** é dividida por 4, o resultado é somado a 7, elevado ao quadrado, e então multiplicado por 0.257.
  - A **segunda parte** é elevada à potência de 2.121, dividida por 5, e então somada a 1.
  - A **terceira parte** é mantida sem alterações.
  - Por fim, os três valores são somados para fornecer o resultado final.

- **Calculadora 2**: 
  - Recebe uma lista de números (N números).
  - Multiplica cada número por 11 e eleva o resultado à potência de 0.95.
  - Calcula o desvio padrão dos resultados obtidos e retorna o inverso desse desvio padrão.

- **Calculadora 3**: 
  - Recebe uma lista de números (N números).
  - Calcula a variância desses números.
  - Se a variância for menor que a multiplicação dos números, apresenta uma mensagem de sucesso.
  - Caso contrário, apresenta uma mensagem de falha.

## Tecnologias Utilizadas

- ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
- ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
