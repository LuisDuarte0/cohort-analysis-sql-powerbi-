# Projeto de Análise de Cohort no Varejo (Retail Cohort Analysis)

## Objetivo do Projeto

Este projeto tem como objetivo realizar uma **análise de cohort** utilizando **MySQL** para segmentar os dados em coortes com base em características compartilhadas, com foco principal em **métricas de clientes e receita ao longo do tempo**. Ao analisar aspectos como **quantidade de invoices (faturas)**, **número de clientes** e **receita por cohort**, o projeto fornece insights relevantes sobre **retenção de clientes, comportamento de compra e tendências de receita**. As visualizações em **Power BI** são usadas para apresentar essas análises de forma mais clara, apoiando interpretação e tomada de decisão estratégica.

> **Observação:** o projeto foi desenvolvido originalmente em **inglês**.

Clique na **imagem** abaixo:  
[![Imagem do Dashboard](https://github.com/nafiul-araf/Cohort-Analysis-using-SQL-and-Power-BI/blob/main/Dashboard%20Image.JPG)](https://app.powerbi.com/view?r=eyJrIjoiMGU5ZjU1YzQtYTIxYi00MTUyLThlMjMtOTlhMzJhNzI1NGNkIiwidCI6IjhjMTI4NjJkLWZjYWYtNGEwNi05M2FjLTk0Yjk3YjVjZWQ1NSIsImMiOjEwfQ%3D%3D)

## Etapas da Análise

### 1. Carregamento dos Dados no MySQL
O primeiro passo envolve importar os dados brutos para o **MySQL** para permitir a análise. Isso garante que os dados estejam estruturados e acessíveis para consultas. Após conectar ao MySQL, os dados são carregados em uma tabela que servirá como base para a análise de cohort.

### 2. Contagem de Invoices por Cohort
Nesta etapa, calcula-se a **quantidade de invoices (faturas)** por cohort. Cada cohort representa clientes agrupados pela **data da primeira compra** (por exemplo, por mês). Ao agregar as invoices por cohort, é possível entender a frequência de compra ao longo do tempo e como ela varia entre os grupos.

### 3. Taxa de Contagem de Invoices por Cohort
Depois de obter a contagem bruta de invoices, esta etapa calcula a **taxa de invoices por cohort**. Essa taxa mostra a **variação percentual** da contagem ao longo do tempo, destacando tendências de crescimento ou queda na atividade de compra de cada cohort.

### 4. Contagem de Clientes por Cohort
Aqui, calcula-se o número de **clientes únicos** dentro de cada cohort. Assim como a contagem de invoices, a contagem de clientes permite observar o engajamento ao longo do tempo. Acompanhar essa métrica ajuda a identificar mudanças em aquisição e retenção de clientes entre cohorts.

### 5. Taxa de Contagem de Clientes por Cohort
Após a contagem de clientes, calcula-se a **taxa de variação** da contagem de clientes por cohort ao longo de diferentes períodos. Essa visão percentual fornece insights sobre tendências de retenção, mostrando se as cohorts estão crescendo ou diminuindo ao longo do tempo.

### 6. Receita por Cohort
A receita por cohort soma a **receita total** gerada por cada cohort ao longo do tempo. Esse cálculo mostra a contribuição financeira de cada grupo e ajuda a entender **valor do cliente ao longo do ciclo de vida (LTV)** e a eficácia de períodos de aquisição.

### 7. Taxa de Receita por Cohort
A etapa final calcula a **taxa de variação da receita por cohort**. Essa métrica mostra a variação percentual da receita de cada cohort ao longo do tempo, indicando crescimento ou contração do valor gerado ao longo da vida de cada grupo.

---

**Feito por Luis Duarte**



