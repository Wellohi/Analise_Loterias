# 🎰 Quina Data Science: Análise Preditiva e Pipeline de Dados

Este projeto tem como objetivo realizar uma análise estatística e preditiva aprofundada dos resultados históricos da **Quina (Loterias CAIXA)**. Ele abrange desde a construção de um pipeline de extração automatizada de dados até a aplicação de modelos de Machine Learning para identificação de tendências e padrões.

---

## 🎯 Objetivos do Projeto

### 🛠️ Engenharia de Dados
- Criar um sistema de ingestão automatizado que consome a API oficial da Caixa Econômica Federal.

### 📊 Análise Exploratória (EDA)
- Identificar números frequentes ("quentes")
- Identificar números atrasados ("frios")
- Analisar correlações entre sorteios

### 🤖 Modelagem Preditiva
- Desenvolver algoritmos que sugiram jogos com base em:
  - Tendências históricas
  - Distribuições probabilísticas

### 💼 Portfólio Profissional
- Demonstrar competências em:
  - Python
  - Manipulação de grandes volumes de dados
  - Visualização de informações

---

## 🏗️ Arquitetura do Projeto

├── data/
│ ├── raw/ # Dados brutos coletados via API (CSV)
│ └── processed/ # Dados limpos e transformados
├── notebooks/ # Análises exploratórias e prototipagem
├── src/ # Scripts Python modulares


---

## ⚙️ Tecnologias Utilizadas

- **Linguagem:** Python  
- **Bibliotecas de Dados:** Pandas  
- **Ingestão de Dados:** Requests (API REST)  
- **Ambiente:** Virtualenv  

---

## 🚀 Diferenciais Técnicos

### 🔄 Pipeline de Carga Incremental

O projeto implementa um pipeline eficiente e resiliente:

- **Verificação Automática**
  - Identifica o último concurso salvo localmente

- **Consumo Inteligente da API**
  - Busca apenas dados novos, evitando redundância

- **Checkpointing**
  - Salvamento automático a cada 100 registros
  - Minimiza perda de dados em falhas

- **Resiliência**
  - Tratamento de erros de:
    - SSL
    - Timeouts de rede corporativa

---

## 📌 Considerações

Este projeto não tem como objetivo prever resultados exatos da loteria, mas sim explorar padrões estatísticos, probabilidades e técnicas de análise de dados aplicadas a um problema do mundo real.

---

O projeto segue boas práticas de organização em Ciência de Dados:
