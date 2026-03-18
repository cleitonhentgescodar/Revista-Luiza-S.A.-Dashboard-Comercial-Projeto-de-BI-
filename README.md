# 🛒 Revista Luiza S.A. — Dashboard Comercial (Projeto de BI)

## 📌 Sobre o Projeto

Este projeto consiste na construção de um **dashboard comercial completo** a partir de um **dataset sintético realista**, simulando a operação de uma grande varejista brasileira fictícia chamada **Revista Luiza S.A.**.

A proposta foi desenvolver um ambiente analítico de ponta a ponta, incluindo:

* Geração de dados com IA (LLM)
* Modelagem relacional
* Construção de métricas de negócio
* Desenvolvimento de dashboard interativo

---

## 🎯 Objetivo

Responder, através de dados e visualizações, às principais perguntas de negócio:

* Como estão as vendas?
* Onde estamos vendendo mais?
* Quem são nossos melhores clientes?
* Quais produtos performam melhor?
* Como está a logística?

---

## 🧠 Contexto

Os dados utilizados neste projeto **não são reais**, mas foram gerados com o auxílio de um modelo de linguagem (LLM), a partir de um prompt estruturado para simular um ambiente de varejo brasileiro.

O dataset foi projetado para reproduzir:

* Estrutura relacional consistente
* Regras de negócio realistas
* Distribuição geográfica nacional
* Sazonalidade de vendas (Black Friday, Natal, etc.)

---

## 🤖 Geração do Dataset

O dataset foi criado com base em um prompt detalhado, garantindo:

* Integridade referencial
* Coerência entre tabelas
* Regras matemáticas de consistência
* Simulação de comportamento real de clientes e vendas

---

## 📦 Estrutura do Dataset

### 🧱 Tabelas

* `clientes`
* `categorias`
* `produtos`
* `lojas`
* `pedidos`
* `itens_pedido`
* `entregas`

---

## 🔗 Relacionamentos

* clientes (1) → (N) pedidos
* pedidos (1) → (N) itens_pedido
* produtos (1) → (N) itens_pedido
* categorias (1) → (N) produtos
* lojas (1) → (N) pedidos
* pedidos (1) → (1) entregas

---

## 📊 Volume de Dados

* 10.000 pedidos
* ~20.000 itens de pedido
* 4.000–6.000 clientes
* 500–1.000 produtos
* 10–20 categorias
* 30–80 lojas / CDs

---

## ⚖️ Regras de Negócio

* `valor_total_item = quantidade × preco_unitario - desconto_item`
* `valor_total = valor_bruto - valor_desconto + valor_frete`
* Datas logísticas consistentes
* Presença de atrasos reais
* Pedidos cancelados não entregues
* Sazonalidade de vendas

---

## 📁 Estrutura dos Arquivos

```
dataset/
├── clientes.csv
├── categorias.csv
├── produtos.csv
├── lojas.csv
├── pedidos.csv
├── itens_pedido.csv
└── entregas.csv
```

---

## 📊 Dashboard

O dashboard foi desenvolvido com foco em análise comercial e dividido em:

### 📈 Visão Geral

* Faturamento
* Margem
* Ticket médio
* Evolução temporal

### 🛍️ Vendas & Produtos

* Receita por categoria
* Top produtos
* Análise preço vs volume

### 👥 Clientes

* Novos vs recorrentes
* Frequência de compra
* Perfil de renda

### 🚚 Logística

* SLA de entrega
* Tempo médio
* Atrasos por região
* Performance de transportadoras

---

## 🛠️ Ferramentas Utilizadas

* Power BI
* Modelagem de Dados
* SQL (conceitual)
* LLM para geração de dados sintéticos

---

## 🚀 Principais Insights

* Concentração de vendas no Sudeste
* Base sólida de clientes recorrentes
* Forte dependência de produtos eletrônicos
* Oportunidades de melhoria logística
* Potencial de expansão geográfica

---

## 💡 Diferenciais do Projeto

* Dataset sintético altamente realista
* Estrutura semelhante a ambientes corporativos
* Projeto end-to-end (dados → modelagem → análise)
* Uso estratégico de IA aplicada a dados
* Foco em tomada de decisão

---

## 🧠 Autor

**Cleiton**
Cientista de Dados

---

## 📌 Observação

Este projeto é fictício e não possui relação com empresas reais.
Todos os dados foram gerados artificialmente para fins educacionais e de portfólio.
