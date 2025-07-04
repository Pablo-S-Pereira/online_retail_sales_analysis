# 📊 Online Retail Sales Analysis

Este projeto realiza uma análise exploratória de dados de vendas de uma empresa de e-commerce com sede no Reino Unido, utilizando a base pública [Online Retail Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset), com transações de 2009 a 2011.

---

## 🎯 Objetivos

- Investigar padrões de **sazonalidade** nas vendas.
- Comparar o desempenho entre os anos de 2010 e 2011.
- Analisar os produtos mais vendidos **em quantidade** vs **em receita**.
- Explorar **potenciais oportunidades de negócio** com base no comportamento de compra dos clientes por região.

---

## 🧰 Tecnologias Utilizadas

- Python 3
- Pandas
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 📁 Sobre a Base de Dados

A base contém transações reais de vendas de uma empresa de varejo online. Cada linha representa uma compra e possui colunas como:

- `InvoiceNo`: Número da fatura
- `StockCode`: Código do produto
- `Description`: Nome do produto
- `Quantity`: Quantidade vendida
- `InvoiceDate`: Data da venda
- `UnitPrice`: Preço unitário
- `Country`: País do cliente

> Fonte: [Online Retail Dataset - Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset)

---

## 📈 Principais Resultados

- A partir de setembro há um **crescimento expressivo em vendas e receita**, indicando forte sazonalidade.
- O ano de 2011 apresenta desempenho inferior a 2010, possivelmente por **interrupções operacionais**.
- Produtos com grande volume vendido nem sempre são os que mais geram receita, sugerindo **ticket médio baixo** em muitos casos.
- Itens **decorativos e sazonais** se destacam no final do ano.
- O **Reino Unido lidera** em vendas, mas **Oceania e Ásia** aparecem como mercados com potencial.

---

## 📌 Conclusão

A análise oferece insights relevantes que podem apoiar decisões estratégicas em marketing, logística e gestão de portfólio de produtos. A empresa poderia investir mais em campanhas sazonais e buscar maneiras de impulsionar as vendas no primeiro semestre do ano.

---

## 🔗 Acesse o notebook

Clique aqui para visualizar o notebook completo:

👉 [`online_retail_sales_analysis.ipynb`](./online_retail_sales_analysis.ipynb)
