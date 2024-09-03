<<<<<<< HEAD
# Algoritmo de Afinidade e Recomendação

Este algoritmo calcula a afinidade entre diferentes itens com base nos usuários que compraram ambos os produtos. O objetivo é fornecer sugestões de produtos em um site de e-commerce, melhorando a experiência do usuário ao recomendar itens que possam ser de interesse.


## O que foi feito:

- A partir de um conjunto de dados que inclui o ID do cliente e o ID do produto associado a cada compra, foi realizado o cálculo da pontuação de afinidade entre os produtos com base nos usuários que os adquiriram;

- Após carregar e inspecionar os dados, foram construídas duas listas contendo os IDs dos usuários e dos produtos, de forma única, ou seja, sem repetição;

- Em seguida, foi criado um DataFrame com três colunas para armazenar o ID dos produtos e seu respectivo valor de afinidade;

- Posteriormente, foi implementado um laço de repetição para percorrer a lista de IDs de produtos e armazenar em listas os IDs dos usuários que compraram cada produto;

- As listas foram analisadas para cada conjunto de produtos, e foi realizada a contagem dos usuários que compraram ambos os produtos;

- A pontuação de afinidade (score) foi calculada pela divisão entre o número de pessoas que compraram ambos os produtos e o número total de clientes;

- Os dados foram então armazenados no DataFrame criado anteriormente;

- Por fim, o resultado, mostrando os produtos com maior afinidade, foi apresentado com base na introdução de um ID de produto inicial.
=======
Desenvolvendo algoritmo de afinidade e recomendação
>>>>>>> f5a15110320320ba36d1863d5a006089fce29dfa
