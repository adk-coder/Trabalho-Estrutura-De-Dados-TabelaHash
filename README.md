# Relatório: Trabalho Final de Estrutura de Dados (Tabela Hash)

# INTRODUÇÃO 
O problema a ser colocado no trabalho final é criar um "BANCO" de nomes inseridos por um arquivo de texto, na qual o professor @manassesribeiro nos disponibilizou, fazendo listas encadeadas.

# OBEJTIVOS
* Imprementação da Tabela Hash(o código ASCII);
* Utilização de uma lista encadeada dupla;
* Manipulação de uma base de dados com mais de 100.000 elementos;
* Tratamento de colisão;
* Consulta;
* Quantidade de elemetos por chave(53);
* Remoção
* Entre outras.

# RESPOSTA
Foi utilizado a implementação da Tabela Hash, considerando a letra inical do nome  convertida para inteiro(código ASCII).A tabela deverá possuir 53 chaves, e o tratamento da colisão foi feito por listas encadeadas duplas.

# DESENVOLVIMENTO
Ao iniciar o processo de desenvolvimento comecei definindo as estrturas, sendo ("Elemento"; "ListaDupla"; "Tabela"), depois foram feitas as funções para que todos os objetivos sejam alcançados.Primeiro foi feito a função de "calcularIndice", que leva em consideração o código ASCII, que é um dos "Problemas" aprensentado pelo professor,
depois foi feito a função de "trocarNomes", onde ocorre a troca de nome de dois elementos na lista duplamente encadeada, e depois a função de "dividirLista", que implementa o algoritmo de particionamento do Quicksort, na qual é usado para rearranjar os elementos na lista de forma que todos os elementos menores que o "pivo" estejam à esquerda
e os maiores estejam à direira.E agora é implementado as funções "ordenarLista" e "ordenarTabela", onde basicamente é implementado o algoritmo Quicksort, para ordenar a lista duplamente encadeada.E depois foram feitos diversas funções, ("ordenarTabela"; "criarTabela"; "inserindoNaTabela"; "consultarNaTabela"; "contarElemetnosPorChave"; "removerDaTabela";
"exibirTabela"; "liberarTabela")que são basicamente funções que desempenham papéis específicos na manipulação e organização da TabelaHash implementada no código.

# CONCLUSÃO
Em resumo, o código implementa uma TabelaHash com tratamento de colisões usando listas duplamente encadeadas e oferece funcionalidade para manipular e consultar os dados na tabela.Desenvolver o projeto final foi uma experiência bastante complexa, embora tenha trazido mais desafios ao desenvolvimento, acabou ficando com um programa funcional que 
realizava todas as funções de imprimir os nomes, consultar-los, remove-lôs, e adiciona los manualmente ou atráves de um arquivo de texto e também ser ordenado utiliziando o algoritmo Quicksort, onde todas essas funções podem ser controlados pelo usuário, através de um menu.


![Screenshot_1](https://github.com/adk-coder/Trabalho-Estrutura-De-Dados-TabelaHash/assets/133603450/8dc8d61f-9d6a-414d-b03d-e8568b0c17ea)
