
# 📊 Análise de Churn - Telecom

## 📌 Sobre o Projeto

Este projeto tem como objetivo analisar a evasão de clientes (Churn) em uma empresa de telecomunicações, identificando padrões e fatores que influenciam o cancelamento dos serviços.

A análise foi realizada utilizando Python e técnicas de Análise Exploratória de Dados (EDA), com foco em gerar insights estratégicos para redução da taxa de churn.

---

## 🎯 Objetivo

Identificar variáveis mais associadas à evasão de clientes e propor recomendações baseadas em dados para auxiliar na retenção.

---

## 🗂 Estrutura do Projeto

O projeto foi organizado seguindo a lógica de um processo ETL:

### 📌 Extração
- Importação da base de dados
- Verificação inicial das colunas e estrutura

### 🔧 Transformação
- Tratamento de valores nulos
- Conversão de variáveis categóricas e numéricas
- Padronização de colunas
- Criação da variável `Contas_Diarias`

### 📊 Carga e Análise
- Cálculo da taxa geral de churn
- Análise por variáveis categóricas
- Análise por variáveis numéricas
- Visualizações gráficas
- Análise de correlação (extra)

### 📄 Relatório Final
- Consolidação dos principais insights
- Recomendações estratégicas

---

## 📈 Principais Resultados

- Taxa de churn aproximada de **26,5%**
- Contratos mensais apresentam maior risco de cancelamento
- Clientes com menor tempo de contrato têm maior probabilidade de churn
- Mensalidades mais altas estão associadas à evasão
- Tempo de permanência (tenure) é o principal fator relacionado ao churn

---

## 💡 Recomendações

- Incentivar contratos anuais
- Criar programas de retenção nos primeiros meses
- Monitorar clientes com mensalidades elevadas
- Desenvolver estratégias preventivas para perfis de maior risco

---

## 🛠 Tecnologias Utilizadas

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## ▶️ Como Executar o Projeto

1. Clone este repositório:


2. Instale as dependências:

pip install pandas matplotlib


3. Abra o notebook:

jupyter notebook


4. Execute as células em ordem.

---

## 📚 Base de Dados

Dataset: Telco Customer Churn  
Contém informações demográficas, contratuais e financeiras dos clientes.

---

## 👩‍💻 Autora

Tânia Maria de Santana  
Projeto desenvolvido para prática de Análise de Dados e construção de portfólio.

---

## 📌 Observação

Este projeto tem finalidade educacional e demonstra aplicação prática de técnicas de análise exploratór
