# Exercício Posto de Gasolina

Um posto de gasolina recebe periodicamente caminhões que abastecem seus tanques com os respectivos combustíveis:

*Gasolina Comum
*Gasolina Aditivada
*Etanol
*Diesel 


Cada um possui um determinado valor de custo. Cada tanque possui uma capacidade máxima de 20.000 litros para cada combustível e não é necessário o esvaziamento da capacidade total para um novo abastecimento.

Com os tanques abastecidos, posto atende seus clientes que optam pelo combustível desejado mediante o pagamento por litro baseado no valor de venda. A cada litro abastecido, o respectivo tanque tem sua capacidade reduzida de acordo com o nível de abastecimento. Cada combustível, portanto, possui um valor de venda e o cliente ao chegar no estabelecimento deve informar o valor em reais (R$) que deseja abastecer e a conversão em litros é feita para a subtração do tanque. A tabela de valores segue de acordo com a lista abaixo:

| Código | Combustível        | Custo/Compra | Venda/Litro |
|--------|--------------------|--------------|-------------|
|    1   |       Etanol       |     1,19     |     2,39    |
|    2   |   Gasolina Comum   |     2,19     |     3,49    |
|    3   | Gasolina Aditivada |     2,29     |     3,69    |
|    4   |       Diesel       |     1,39     |     2,89    |

Além do processo de abastecimento de veículos, o posto conta com serviços adicionais que podem ou não ser oferecidos aos clientes independente do abastecimento. Seguem os serviços na tabela a seguir:

| Código | Serviço         | Valor |
|--------|-----------------|-------|
| 1      | Ducha Ecológica | 8,00  |
| 2      | Troca de Óleo   | 50,00 |
| 3      | Balanceamento   | 35,00 |
| 4      | Café            | 2,00  |

Desenvolva uma aplicação em Java que gerencie o fornecimento de combustíveis junto ao controle de capacidade dos tanques; a venda dos combustíveis e prestação dos serviços adicionais e por fim, apresente relatórios referentes aos gastos do posto, às vendas de produtos e dos serviços e ao lucro obtido pelo estabelecimento.

## Funcionamento

No menu principal, aparecem 3 opções: 1 - Gerenciamento do posto; 2 - Vendas e 3 - Sair

## Gerenciamento do posto

Ao selecionar a opção 1 no menu principal, aparece a tela com as seguintes opções de gerência do posto:

1 - Abastecimento dos Tanques; <br>
2 - Relatório dos Tanques; <br>
3 - Relatório de Vendas; <br>
4 - Relatório de Despesas; <br>
5 - Relatório de Lucros; <br>
6 - Voltar <br>

### Abastecimento dos tanques

Ao selecionar a opção de abastecimento dos tanques, é exibida a tela para selecionar qual tanque será abastecido e em seguida o inserir valor em litros. Caso o valor inserido exceda a capacidade do tanque, o sistema exibe a mensagem "O valor excede a capacidade do tanque";

### Relatório dos Tanques

Exibe a quantidade atual de combustível nos tanques;

### Relatório de vendas

Exibe a quantidade em litros e o valor arrecadado para cada combustível;
Exibe também a quantidade realizada e o valor para cada serviço;

### Relatório de despesas

Exibe a quantidade em litros e o valor pago pela compra ao fornecedor para cada combustível, e também a soma total de litros comprados e o valor total;

### Relatório de lucros

Exibe o total de lucros brutos e lucros líquidos obtidos com a venda de combustíveis;
Abaixo,exibe o total de lucros brutos obtidos com a venda dos serviços;
Por último, exibe o total de lucros brutos e lucros líquidos da soma todas as vendas;

## Vendas

Ao selecionar a opção 2 no menu principal, aparecem as opções: 1 - Abastecimento, 2 - Serviços e 3 - Sair

### Abastecimento

Exibe a tela com os combustíveis na bomba e o valor por litro de cada um. Ao selecionar o combustível, exibe uma tela para inserir o valor em R$ a ser abastecido. Caso o tanque do combustível selecionado esteja vazio, exibe a mensagem "Tanque Vazio!!!". Caso o valor convertido de real em litros exceda a quantidade disponível no tanque, exibe a mensagem "Não há combustível o suficiente!!!";

### Serviços 

Exibe a tela com sos serviços e seus respectivos valores. Ao selecionar, exibe uma tela de confirmação do serviço realizado, e o sistema inclui o valor nos lucros;

### Sair

Encerra o sistema.


