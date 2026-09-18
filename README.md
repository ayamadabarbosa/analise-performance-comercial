# Análise de Performance Comercial

Dashboard de análise de performance comercial desenvolvido no Power BI a partir do dataset público de e-commerce brasileiro da Olist.

O projeto busca analisar a evolução das vendas, a geração de receita por categorias e produtos, o desempenho dos sellers e o comportamento dos clientes.

---

## 📊 Dashboard

### Visão Geral de Vendas

![Visão Geral de Vendas](imagens/1%20-%20Visão%20Geral%20de%20Vendas.png)

### Análise de Vendas

![Análise de Vendas](imagens/2%20-%20Análise%20de%20Vendas.png)

### Categorias e Produtos

![Categorias e Produtos](imagens/3%20-%20Categorias%20e%20Produtos.png)

### Sellers

![Sellers](imagens/4%20-%20Sellers.png)

### Clientes

![Clientes](imagens/5%20-%20Clientes.png)

---

## 🎯 Objetivo

Analisar a performance comercial do e-commerce ao longo do período de setembro de 2016 a agosto de 2018, identificando padrões relacionados à evolução da receita, volume de vendas, categorias, produtos, sellers e clientes.

---

## 💼 Perguntas de negócio

### Desempenho comercial

- Como a receita e o volume de pedidos evoluíram ao longo do período?
- Quais períodos apresentaram os maiores volumes de receita e pedidos?
- O crescimento das vendas está relacionado ao aumento do volume de pedidos ou ao ticket médio?

### Categorias e produtos

- Quais categorias concentram a maior parcela da receita?
- Quais produtos apresentam maior volume de vendas?
- Quais produtos apresentam maior geração de receita?
- Quais categorias apresentam maior ticket médio?

### Sellers

- Como a receita está distribuída entre os sellers?
- Quais sellers apresentam maior receita e volume de pedidos?
- Existem diferenças de ticket médio entre os sellers?

### Clientes

- Como a receita está distribuída entre os clientes?
- Qual é o nível de concentração da receita entre os clientes de maior valor?
- Quais clientes apresentam maior receita, volume de pedidos e ticket médio?

---

## 📈 Principais insights

- A receita apresentou crescimento de **138,75%** na comparação entre janeiro–agosto de 2017 e janeiro–agosto de 2018.
- No mesmo período, o ticket médio apresentou variação de aproximadamente **0,22%**, enquanto a receita cresceu significativamente. Isso indica que o crescimento da receita esteve principalmente associado ao aumento do volume de vendas.
- **Novembro de 2017** apresentou o maior volume mensal observado, com aproximadamente **R$ 99,66 milhões de receita**, **7.349 pedidos** e **8.549 itens vendidos**.
- As cinco principais categorias — beleza_saude, relogios_presentes, cama_mesa_banho, esporte_lazer e informatica_acessorios — representam aproximadamente **39,78% da receita total**.
- As dez principais categorias representam aproximadamente **62,33% da receita total**.
- Os 15 clientes com maior receita representam aproximadamente **0,66% da receita total**, indicando uma distribuição bastante pulverizada da receita entre a base de clientes.
- Os 10 sellers com maior receita representam aproximadamente **13,21% da receita total**.

---

## 🧩 Modelo de dados

O projeto utiliza um **modelo dimensional em estrela (Star Schema)**.

### Tabela fato

- **FactOrderItems** — concentra os itens dos pedidos e as principais informações relacionadas às vendas.

### Dimensões

- **DimProduct** — produtos e categorias.
- **DimCustomer** — clientes.
- **DimSeller** — sellers.
- **DimDate** — calendário para análises temporais.

A modelagem dimensional foi utilizada para organizar os dados, facilitar a criação das medidas em DAX e permitir análises por diferentes perspectivas de negócio.

---

## 📊 KPIs

Os principais indicadores utilizados foram:

- **Receita de Vendas Válidas**
- **Pedidos Válidos**
- **Itens Vendidos Válidos**
- **Ticket Médio**
- **Receita Média por Item**
- **Crescimento da Receita (%)**
- **Crescimento dos Pedidos (%)**
- **Crescimento dos Itens (%)**
- **Itens por Pedido**

---

## 🔎 Análises realizadas

O dashboard está organizado em cinco páginas:

1. **Visão Geral de Vendas**  
   Principais KPIs, evolução da receita, evolução dos pedidos e ranking de categorias.

2. **Análise de Vendas**  
   Evolução de receita e pedidos, crescimento mensal e comportamento do ticket médio.

3. **Categorias e Produtos**  
   Participação das categorias, rankings de produtos, ticket médio e relação entre volume e receita.

4. **Sellers**  
   Receita, pedidos, itens, ticket médio, participação e desempenho dos sellers.

5. **Clientes**  
   Receita, pedidos, itens, ticket médio e concentração da receita entre os clientes.

---

## 🛠️ Ferramentas utilizadas

- **Power BI** — desenvolvimento do dashboard, modelagem e análise.
- **Power Query** — preparação e transformação dos dados.
- **DAX** — criação das medidas e indicadores.
- **Notion** — documentação e organização do projeto.

---

## 📂 Dados

O projeto utiliza o dataset público de e-commerce brasileiro da **Olist**, contendo informações relacionadas a:

- Pedidos
- Itens dos pedidos
- Produtos
- Clientes
- Sellers
- Pagamentos
- Categorias de produtos

O período analisado no dashboard compreende **setembro de 2016 a agosto de 2018**.

---

## 📌 Sobre o projeto

Este projeto faz parte do meu portfólio de **Data Analytics / Business Intelligence** e foi desenvolvido com foco em análise de dados, modelagem dimensional, criação de indicadores e visualização de informações para apoio à tomada de decisão.
