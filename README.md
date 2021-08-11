## Shopping-BI

Você pode checar os [arquivos no github](https://github.com/dibpedro/shopping-bi/) para essa visualização. ecommerce-analysis é um projeto de análise dos dados de compra on-line realizados em sites brasileiros entre 2016 e 2018. O projeto teve o objetivo de identificar padrões entre os usuários dos sites e utilizar esses padrões em possíveis tomadas de decisão posteriormente. A análise foi feita em Excel e Power BI

### 0. Tabela de Conteúdos
* [0. Tabela de Conteúdos](#0-tabela-de-conteúdos)
* [1. O conjunto de dados](#1-o-conjunto-de-dados)
* [2. Algumas perguntas](#2-algumas-perguntas)
* [3. Visuais e interpretações](#3-visuais-e-interpretações)
* [4. Oportunidades](#4-oportunidades)
* [5. Próximos passos](#5-próximos-passos)
* [Contato](#contato)

### 1. O conjunto de dados

O conjunto de dados usado é composto por informações acerca de mais de 100 mil pedidos de compra on-line realizados em diversas lojas brasileiras. Os dados foram fornecidos pela Olist (http://www.olist.com) e obtidos através do link https://www.kaggle.com/olistbr/brazilian-ecommerce?select=olist_orders_dataset.csv.
### 2. Algumas perguntas

1. O que o brasileiro tende a comprar mais pela internet?
2. Quais os estados que mais realizaram compras on-line nesse período?
3. Existe preferência por método de pagamento e costume de parcelamento das compras?
4. O que influencia a quantidade de parcelas?
5. Qual a participação do frete nessa receita?
6. Para o cliente, o valor pago pelo frete compensa o tempo de espera?
7. Pra quais estados o frete é mais caro?
### 3. Visuais e interpretações

<iframe width="800" height="636" src="https://app.powerbi.com/view?r=eyJrIjoiNWI4NzRlMDgtNjNkMi00ZDlkLWEzM2EtM2Y0Zjk2NmRjMGM4IiwidCI6ImIxY2E3YTgxLWFiZjgtNDJlNS05OGM2LWYyZjJhOTMwYmEzNiJ9" frameborder="0" allowFullScreen="true"></iframe>

A partir dessas visualizações, podemos fazer algumas conclusões:
- O público desses sites parece ter preferência por itens de decoração, já que esse tipo de produto ocupa boa parte do percentual de gasto total, mesmo não tendo as maiores médias de preço;
- O uso de cartão de crédito como método de pagamento é predominante. A média do número de parcelas, entretanto, depende. Ela parece ser diretamente propocional à média de preço do produto, tendo seu valor maior na categoria de produtos relacionados à informática. Possivelmente, são jovens universitários ou estagiários quem mais acessam as lojas digitais em busca desses produtos. Além disso, eletrodomésticos e itens para a cozinha também tiveram resultados expressivos quanto à média de parcelamento: mais um possível indicativo de classe socioeconômica do público alvo.
- O único estado em que o frete tem média menor que R$ 20,00 é SP. Isso pode ser um problema. Além disso, o tempo de entrega aumenta consideravelmente conforme os estados se distanciam da região Sudoeste do país, o que, assim como o alto custo, pode ser um fator de desistência na hora da compra ou de, no mínimo, insatisfação do cliente, podendo resultar numa avaliação negativa posteriormente.


### 4. Oportunidades

- Investimento em publicidade de outras categorias, como vestuário - que pouco aparece -  por exemplo, é uma forma de atrair novos clientes.
- Se for de interesse da empresa receber o dinheiro de forma integral, oferecer descontos para pagamentos à vista é uma alternativa para evitar o parcelamento.
- Parece existir certa relação entre o custo do frete/tempo de entrega e o número de compras realizadas por Estado. SP, que tem as menores taxas de frete e tempo de entrega, possui a maior parcela do total movimentado por cada estado. Já estados como PB e AL, cujos preços médios de frete e tempo de entrega são consideravelmente mais altos que de outros estados, possuem pouca participação na quantidade total arrecadada. Investimentos que visem diminuir esses custos para os clientes podem ser um incentivo para fazê-los optarem por lojas digitais em detrimento das lojas físicas.
### 5. Próximos passos

As próximas análises seriam em torno das categorias mais vendidas em cada mês e em cada época do ano, de modo que possamos fazer previsões para o estoque necessário e realizar também investimentos nas publicidades direcionadas para cada público, com foco em atrair mais clientes, além de manter os atuais. 

### Contato

Para dúvidas, mandar email para pedrodib100@gmail.com.
[Linkedin](https://www.linkedin.com/in/pedro-dib-597700139/)
