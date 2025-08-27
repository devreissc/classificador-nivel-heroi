# Classificador de Nível de Herói

Este projeto classifica heróis em diferentes níveis com base em sua experiência (XP).

## Como funciona

O arquivo [`main.js`](main.js) contém uma lista de heróis, cada um com um nome e uma quantidade de XP. O script percorre essa lista e imprime no console o nível correspondente de cada herói, de acordo com a tabela abaixo:

| XP                | Nível        |
|-------------------|--------------|
| 0 - 1000          | Ferro        |
| 1001 - 2000       | Bronze       |
| 2001 - 5000       | Prata        |
| 5001 - 7000       | Ouro         |
| 7001 - 8000       | Platina      |
| 8001 - 9000       | Ascendente   |
| 9001 - 10000      | Imortal      |
| 10001 ou mais     | Radiante     |

## Como executar

1. Certifique-se de ter o [Node.js](https://nodejs.org/) instalado.
2. Execute o script no terminal: node main.js

## Exemplo de saída

|O Herói de nome Kratos está no nível de Radiante   |
|O Herói de nome Gohan está no nível de Ascendente  |
|O Herói de nome Ares está no nível de Prata        |
|O Herói de nome Naruto está no nível de Ouro       |
|O Herói de nome Saitama está no nível de Imortal   |

### Arquivo principal
[`main.js`](main.js): Script principal para classificação dos heróis.