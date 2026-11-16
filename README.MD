# 📦 Olist E-Commerce Analytics: Logística e Satisfação do Cliente

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-SQLite%20%7C%20PostgreSQL-lightgrey?logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)

## 🎯 Objetivo do Projeto
Este projeto realiza uma análise exploratória e diagnóstica sobre cerca de **100 mil pedidos reais** realizados no e-commerce brasileiro entre 2016 e 2018 (dataset público da Olist). 

O foco principal é investigar **gargalos logísticos** e entender como os prazos de entrega, o valor do frete e a localização geográfica impactam diretamente a **nota de avaliação (Review Score)** e a retenção dos clientes.

E é claro praticar as tecnologias necessárias
---

## ❓ Perguntas de Negócio Respondidas
1. **Impacto do Atraso:** Qual é a queda média na nota de avaliação quando um pedido é entregue após o prazo estimado?
2. **Gargalos Regionais:** Quais estados e rotas apresentam os maiores tempos de entrega e os maiores custos de frete proporcional ao valor do produto?
3. **Sazonalidade e Volume:** Como o volume de vendas e a taxa de atraso se comportam em períodos de pico (como a Black Friday)?
4. **Categorias Críticas:** Quais categorias de produtos concentram o maior índice de insatisfação e cancelamentos?

---

## 🛠️ Arquitetura e Ferramentas Utilizadas
* **Banco de Dados & Consultas (SQL):** Estruturação das 9 tabelas relacionais em banco local (`SQLite`), utilizando `JOINs`, `CTEs` (Common Table Expressions) e `Window Functions` para extração e agregação inicial.
* **Manipulação e Limpeza (Python):** `Pandas` e `NumPy` para tratamento de valores nulos, conversão de timestamps, detecção de outliers e engenharia de atributos (ex: cálculo de dias de atraso e tempo de aprovação).
* **Estatística & Visualização:** `SciPy`, `Matplotlib` e `Seaborn` para testes de correlação e geração de gráficos orientados a negócio.

---

## 🗂️ Estrutura do Repositório
