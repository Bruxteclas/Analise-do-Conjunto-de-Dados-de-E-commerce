# Brazilian E-commerce Data Analysis

## Projeto: Análise de Dados de E-commerce Brasileiro

### Objetivo
O objetivo deste projeto é realizar uma análise detalhada dos dados de um e-commerce brasileiro para entender o comportamento de compra dos clientes, otimizar processos logísticos, recomendar produtos relevantes e segmentar os clientes de forma eficaz para campanhas de marketing. As principais perguntas de negócio abordadas incluem:
1. Qual o comportamento sazonal das vendas ao longo do ano?
2. Como otimizar os tempos de entrega para melhorar a experiência do cliente?
3. Como recomendar produtos relevantes com base nas compras anteriores?
4. Como segmentar os clientes de forma eficaz para campanhas direcionadas?

### Ações Realizadas
1. **Entendimento e Limpeza dos Dados**:
   - Carregamento dos datasets relacionados a clientes, pedidos, pagamentos, itens de pedido, revisões, localização, e produtos.
   - Remoção de duplicatas, tratamento de valores ausentes e padronização de dados para garantir uma base limpa e estruturada para as análises.
   
2. **Análises Exploratórias**:
   - **Comportamento Sazonal das Vendas**: Analisamos o volume de vendas ao longo do tempo, identificando picos em períodos como Black Friday e Natal.
   - **Métodos de Pagamento**: Observamos a distribuição dos métodos de pagamento ao longo do tempo e identificamos a predominância do cartão de crédito.
   - **Fretes**: Verificamos a variação do custo médio de frete e correlacionamos com o volume de vendas.

3. **Otimização de Entregas**:
   - Calculamos o tempo médio de entrega e identificamos as regiões com maiores dificuldades logísticas. Sugestões de otimização foram feitas com base na análise por estado e cidade.

4. **Sistema de Recomendação de Produtos**:
   - Implementamos um sistema de recomendação usando a técnica de Decomposição de Valores Singulares (SVD) para sugerir categorias de produtos aos clientes, com base em compras anteriores.

5. **Segmentação de Clientes**:
   - Segmentamos os clientes com base nos métodos de pagamento e no valor gasto, proporcionando insights para campanhas de marketing direcionadas.

### Resultados
1. **Comportamento Sazonal**: Identificamos um aumento acentuado nas vendas durante os meses de novembro (Black Friday) e dezembro (Natal), seguido por uma queda em janeiro.
2. **Métodos de Pagamento**: O cartão de crédito foi o método de pagamento mais utilizado, seguido pelo boleto. Métodos como débito e voucher têm baixa representatividade.
3. **Frete e Logística**: O tempo médio de entrega foi de aproximadamente 8,88 dias, com variações significativas entre regiões do Brasil. São Paulo apresentou o menor tempo de entrega (5,14 dias), enquanto estados como Roraima e Amazonas têm tempos superiores a 20 dias.
4. **Recomendações de Produtos**: O sistema de recomendação baseado em SVD sugeriu produtos relevantes para cada cliente, com uma performance razoável (RMSE: 1,19).
5. **Segmentação de Clientes**: A segmentação revelou que a maioria dos clientes prefere o parcelamento com cartão de crédito, enquanto uma parcela considerável ainda opta por pagamento via boleto.

### Tecnologias Utilizadas
- Python (Pandas, NumPy, Matplotlib, Scikit-learn, SciPy)
- Jupyter Notebook
- Kaggle API para download dos dados
- Técnicas de Machine Learning (SVD, KNN, K-Means)

### Dataset
Os dados utilizados neste projeto podem ser encontrados no Kaggle através do seguinte link:
[Kaggle Brazilian E-commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data)

### Conclusão
Este projeto oferece uma análise completa de um e-commerce brasileiro, fornecendo insights sobre sazonalidade de vendas, métodos de pagamento, otimização logística e um sistema de recomendação de produtos. As informações obtidas podem ser aplicadas para melhorar a experiência do cliente, reduzir custos operacionais e aumentar o volume de vendas por meio de recomendações personalizadas.

