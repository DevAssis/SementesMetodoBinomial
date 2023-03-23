# Sementes Método Binomial
# *Projeto: Cálculo da probabilidade de germinação de sementes infectadas*

## Objetivo

Este projeto tem como objetivo calcular a probabilidade de uma semente infectada germinar com base nas informações disponíveis em um experimento. O experimento envolve a disseminação de 320 sementes de aveia após serem contaminadas com um fungo. A pesquisa deseja saber qual a probabilidade &Theta; de uma semente infectada germinar. Infelizmente o número exato de sementes germinadas não pode ser avaliado, mas sabemos que menos de 25 sementes germinaram.

## Linguagem e bibliotecas

O projeto foi desenvolvido usando a linguagem Python e as seguintes bibliotecas:

- `scipy`: usada para cálculos estatísticos e científicos.

## Solução

A solução encontrada envolve o uso da distribuição binomial da biblioteca `scipy` para modelar o número de sementes germinadas. O código define uma função que calcula a probabilidade acumulada da distribuição binomial até um valor limite para o número de sementes germinadas. Essa função é usada para calcular a probabilidade de observar menos do que um número específico de sementes germinadas para cada valor possível de &Theta;.

Os resultados do programa podem ser visualizados em um gráfico que mostra a probabilidade de uma semente infectada germinar em função de &Theta;. Você pode usar essa visualização para avaliar quais valores de &Theta; são mais prováveis com base nas informações disponíveis no experimento.
