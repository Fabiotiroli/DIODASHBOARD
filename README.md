# DIODASHBOARD
Dashboard Analise de Dados
# Dashboard de Análise de Assinaturas e Receitas

Este projeto apresenta um **dashboard interativo em Excel** criado para analisar métricas de assinaturas, receitas e planos de usuários. Utilizando **Tabelas Dinâmicas**, **segmentações (slicers)** e **modelagem simples de dados**, o objetivo é permitir uma visualização rápida e intuitiva das informações, facilitando decisões estratégicas e análises exploratórias.

---

## 📊 Objetivo do Projeto

O dashboard foi desenvolvido para:

- Analisar a distribuição dos usuários por tipo de assinatura.
- Calcular e visualizar valores pagos por cada plano.
- Explorar indicadores específicos, como:
  - **Total Value**
  - **EA Play Season Pass**
  - **Minecraft Season Pass**
- Permitir filtragem dinâmica por:
  - Tipo de assinatura (Subscription Type)
  - Plano (Plan)
  - Outras dimensões contidas na base

---

## 📁 Estrutura do Arquivo

O arquivo principal do projeto é:

- **DashBoard_Finalizado_vfinal.xlsx**

Ele contém:

- Aba **Dashboard** → visualização e segmentações  
- Aba **Assets** → dados complementares  
- Aba **Bases** → base de dados bruta  
- Aba **Cálculos** → tabelas dinâmicas utilizadas no dashboard

---

## 🧠 Dados Utilizados

A base contém colunas como:

- `Subscriber ID`
- `Name`
- `Plan`
- `Start Date`
- `Auto Renewal`
- `Subscription Price`
- `Subscription Type`
- `EA Play Season Pass`
- `EA Play Season Pass Price`
- `Minecraft Season Pass`
- `Minecraft Season Pass Price`
- `Coupon Value`
- `Total Value`

Esses dados permitem somatórios, análises cruzadas e segmentações customizadas.

---

## 🔧 Tecnologias e Recursos Usados

- **Microsoft Excel**
- **Tabelas Dinâmicas (PivotTables)**
- **Slicers / Segmentações**
- **Painel de Campos da Tabela Dinâmica**
- **Formatação condicional**
- **Modelo de visualização customizado**

Nenhuma linguagem de programação adicional foi utilizada — apenas os recursos nativos do Excel.

---

## ▶️ Como Reproduzir o Dashboard

1. Abra o arquivo **DashBoard_Finalizado_vfinal.xlsx**.
2. Acesse a aba **Dashboard**.
3. Utilize as segmentações (Subscription Type, Plan etc.) para filtrar os resultados.
4. Caso precise ajustar as tabelas:
   - Acesse a aba **Cálculos**
   - Clique sobre as Tabelas Dinâmicas
   - Use o painel de campos à direita para reorganizar valores, filtros e rótulos
5. Para atualizar dados:
   - Substitua ou edite a aba **Bases**
   - Clique em **Dados → Atualizar Tudo**

---


