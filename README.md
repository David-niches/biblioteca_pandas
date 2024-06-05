# biblioteca_pandas

#O dataset que trabalhamos neste projeto é composto por informações de vendas de uma loja virtual que atua em todo o território nacional, vendendo produtos de diferentes departamentos. Além disso, a loja atua em diferentes canais de venda, como marketplace, loja própria, entre outros.

premissas de negócio:
Ao analisar os dados é importante salientar algumas considerações. A primeira delas é que, devido a um erro no sistema, algumas compras não possuem informações de UF (unidade federativa). Para solucionar este problema, foi decidido que essas compras serão consideradas como pertencentes ao estado de mato grosso do sul (MS). A segunda premissa é que o preço final não pode ser maior do que o preço com frete. Alguns dados de preço também aparecem como "em branco" (null), portanto foram substituídos pela média de preços.

Métricas com base nesse contexto e nas premissas de negócio estabelecidas, podemos avaliar as seguintes métricas:

1. Departamentos mais vendido: analisando os dados de vendas, podemos identificar quais são os departamentos mais populares entre os clientes. Essa informação pode ser útil para se entender quais são os produtos mais procurados pelos clientes e ajustar a estratégia de venda da loja em conformidade.
2. Média de preço com frete por nome de departamento: Para entender o comportamento de preço por departamento, podemos calcular a média de preço com frete por nome por departamento. essamétrica pode ajudar a identificar quais são os departamentos mais rentáveis e ajustar a precificação de produtos de acordo com a margem desejada.
3. Quantidade de vendas por mês: analisando a qquantidade de vendas realizadas em cada mês, podemos identificar sazonalidades no comportamento de compra dos clientes e planejar campanhas de marketing específicas para cada período.
4. Média de renda para cada tipo de canal de venda: identificar a média de renda dos clientes em diferentes canais de venda pode ajudar a loja a ajustar campanhas de marketing para cada público alvo em específico, buscando uma eficciencia maior.
5. Média de idade de clientes por bandeira: Saber a faixa etária dos clientes por bandeira pode ajudar a identificar perfis de consumidores para melhor atendimento do seu público.
