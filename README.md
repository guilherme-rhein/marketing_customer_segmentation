<h1 align="center">
    🗃️ Segmentação de Clientes 🗃️</a>
</h1>

<p align="center"> O objetivo do projeto é segmentar clientes por meio do comportamento de compras dos clientes definidas por recência, frequência e valores gastos. </p>

---
<h3 align="center">
    🎯 Experimente Aqui: <a href="https://www.linkedin.com/in/guilherme-rhein/">Aplicativo para Segmentação de Clientes 🎯</a>
    <br><br>
    💾 Base de dados: <a href="https://github.com/guilherme-rhein/marketing_customer_segmentation/blob/main/dados_input%201.csv">📊 Download 📈</a>
</h3>

---

## RFV - Segmentação de Clientes para Estratégias de Marketing e CRM 📌

O projeto RFV, que significa Recência, Frequência, Valor, é uma ferramenta poderosa para a segmentação de clientes 
com base em seus comportamentos de compra. Ao agrupar clientes em clusters semelhantes, este sistema permite a 
implementação de estratégias de marketing e CRM mais eficazes. 

## Principais Funcionalidades 🛠️

- Recência (R): Calcula a quantidade de dias desde a última compra de cada cliente.
- Frequência (F): Determina o total de compras realizadas no período analisado.
- Valor (V): Avalia o montante total gasto pelos clientes em suas compras.

## Objetivo ✔️

O objetivo fundamental é classificar cada cliente de acordo com as três componentes RFV mencionadas acima, 
resultando em agrupamentos finais designados pelas classes A até D. Essas classes permitem a identificação 
de clientes fiéis (classe "A") e daqueles que podem requerer uma gestão mais aprimorada (classe "D"). 

Conseguimos definir os principais benefícios:

- **Personalização do Conteúdo:** Compreender o comportamento individual dos clientes permite personalizar campanhas de marketing e comunicações para melhor atender às suas necessidades e preferências.

- **Retenção de Clientes:** A capacidade de identificar clientes em risco (classe "D") permite a implementação de estratégias direcionadas para aumentar a lealdade e retenção.

- **Otimização de Recursos:** Ao direcionar esforços de marketing e CRM com base nas características RFV, as ações tornam-se mais eficientes e orientadas para resultados, tratando cada cliente com exclusividade.

## Como Utilizar 🎈

- **Entrada de Dados:** Faça o Download do arquivo de dados como exemplo, são informações relacionadas a cada transação do cliente, incluindo a data da compra e o valor gasto.
- **Execução do Aplicativo:** O algoritmo calculará automaticamente as métricas de Recência, Frequência e Valor para cada cliente.
- **Resultados e Classificação:** Os clientes serão classificados nas classes de A até D, indicando a estratégia recomendada para cada segmento.

Este projeto é uma valiosa ferramenta para empresas que buscam otimizar suas estratégias de marketing e CRM, promovendo uma abordagem mais personalizada e eficaz para cada cliente.

## Dependencias e Instalação 📌

1. **Instalação:**                   
   - Clone o repositório: `git clone https://github.com/guilherme-rhein/marketing_customer_segmentation.git`
   - Instale as dependências: `npm install` ou `pip install -r requirements.txt` 

2. **Execução do código:**
   - Execute o projeto: `app_RFV.py`
   - Utilize a base de dados `dados_input 1.csv` ou `dados_test_input 2.csv`

3. **Acesse o Sistema:**
   - Abra utilizando `streamlit run app_RFV.py`
   

## Bibliotecas Utilizadas 📚

```bash
import pandas as pd
import streamlit as st
from io import BytesIO
```



