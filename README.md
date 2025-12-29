# Primeiro_Challege_Alura

📊 Análise das Lojas do Senhor João
📌 Descrição do Projeto

Este projeto tem como objetivo realizar uma análise comparativa do desempenho de quatro lojas pertencentes ao Senhor João, a fim de identificar qual loja deve ser vendida com base em indicadores financeiros, operacionais e de satisfação dos clientes.

A análise foi desenvolvida utilizando Python no Google Colab, com foco em manipulação de dados, estatísticas descritivas e visualizações gráficas.

🎯 Objetivo

Avaliar o desempenho das lojas e recomendar a venda da unidade menos rentável, considerando os seguintes critérios:

Faturamento total

Média de avaliação dos clientes

Frete médio por loja

Vendas por categoria de produto

Produtos mais e menos vendidos

🗂️ Estrutura dos Dados

Cada loja foi representada por um DataFrame, contendo, entre outras, as seguintes colunas:

Preço

Produto

Categoria do Produto

Avaliação

Frete

As lojas foram agrupadas em uma lista para facilitar a análise comparativa:

lojas = [loja, loja2, loja3, loja4]

🔍 Etapas da Análise
1️⃣ Faturamento

Cálculo do faturamento total por loja utilizando o somatório da coluna Preço.

2️⃣ Avaliação dos Clientes

Cálculo da média das avaliações para identificar a loja com maior e menor satisfação dos clientes.

3️⃣ Frete Médio

Análise do custo médio de frete por loja para avaliar o impacto logístico.

4️⃣ Vendas por Categoria

Contagem de vendas por categoria de produto para identificar os segmentos mais relevantes em cada loja.

5️⃣ Produtos Mais e Menos Vendidos

Identificação dos produtos com maior e menor volume de vendas.

6️⃣ Visualizações Gráficas

Gráficos de linha e pizza para facilitar a interpretação dos resultados.

📈 Principais Resultados

Maior faturamento: Loja 1

Menor faturamento: Loja 4

Melhor avaliação dos clientes: Loja 3

Menor desempenho geral: Loja 4

Apesar de apresentar o menor frete médio, a Loja 4 não se destacou positivamente nos demais indicadores analisados.

✅ Conclusão

Com base nos resultados obtidos, conclui-se que a Loja 4 apresenta o pior desempenho geral, sendo recomendada sua venda. Essa decisão permite ao Senhor João concentrar recursos e esforços nas lojas mais rentáveis e com maior potencial de crescimento, especialmente a Loja 3, que combina boa performance financeira e alta satisfação dos clientes.

🛠️ Tecnologias Utilizadas

Python

Pandas

Matplotlib

Google Colab

👤 Autor

Projeto desenvolvido como atividade de análise de dados, com foco em tomada de decisão baseada em indicadores.
