# Filtrar Mulheres - EBAC - Stram

Este é um projeto simples em Java que lê uma lista de nomes e sexos separados por vírgula a partir do console, cria uma lista de objetos com essas informações e utiliza expressões lambda para filtrar e exibir apenas os registros de mulheres.

## Funcionamento

O programa realiza os seguintes passos:
1. Solicita ao usuário uma lista de nomes e sexos no formato `nome,sexo` separados por `;`.
2. Converte a entrada em uma lista de objetos `Pessoa`.
3. Filtra a lista para exibir apenas os registros com o sexo `F` (feminino).
4. Exibe a lista filtrada no console.

## Exemplo de Entrada

- Maria,F;João,M;Ana,F;Carlos,M;Mariana,F


## Exemplo de Saída

- Lista de mulheres: Maria (F) Ana (F) Mariana (F)
