# Projeto de analise de dados
## Cancelamentos de planos

Este projeto consiste na analise de dados dos clientes de uma empresa que tem notado um grande numero de cancelamentos. A analise ajuda a entender os cancelamentos.

## Dados
A analise será feita sobre os dados de clientes em diferentes planos, contando com as variaveis exibidas a seguir.
### Dataset
O dataset traz variaveis com informações de cancelamento dos clientes, contendo as seguintes variaveis.
<img src="Dataset1.png" alt="Dataset" />

### Proporção
Para garantir a representação é preciso conhecer a porporção dos dados disponiveis.
<img src="proportion.png" alt="Proporção" />
Note que existe uma boa distribuição entre os planos e os casos de cancelamento ou não.

## Analise
Algumas analises se destacaram de cara, mostrando forte ligação com a variavel *cancelou*. Veremos isso com algumas ilustrações a seguir.

### Numero de Ligações pro Call Center
Um alto numero de ligações pro Call Center claramente representa um problema, uma vez que o cliente não deve ligar se estiver tudo certo.
<img src="Liga.png" alt="Ligações ao Call Center" />

### Atraso no Pagamento
O atraso no pagamento também merece atenção, configurando indício de tendência para inadimplência.
<img src="Atraso.png" alt="Atraso no pagamento" />

### Analise Proposital
Dessa analise, é possivel observar a criticidade do atraso no pagamento e do numero de ligações para o Call Center, se mostrando como indicadores de cancelamento. Sendo o grande objetivo fidelizar o cliente e minimizar o cancelamento, essas variaveis merecem atenção juntamente com o tipo de plano.

![Analise de risco](Analise.png)

A fidelização dos clientes pode ser melhorada:
 - Promoção de upgrade de planos mensais para anuais;
 - Soluções ágeis para problemas relatados ao Call Center;
 - Atenção em pagamentos atrasados com frequência.