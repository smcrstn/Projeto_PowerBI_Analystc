Power BI Financial Analyst - Desafio de Projeto DIO

Este repositório contém o projeto final do desafio "Criando um Relatório Gerencial de Vendas" do curso de Power BI Analyst da DIO. O objetivo foi replicar um dashboard de vendas, aplicando melhorias na lógica financeira e na experiência do usuário (UX).

 Melhorias Realizadas (Diferenciais)

Em comparação ao modelo base proposto, este relatório apresenta evoluções críticas:

1.  **Lógica Financeira Corrigida:** Diferente do modelo inicial, foi estabelecida uma distinção clara entre **Vendas Brutas (Gross Sales)** e **Valor Líquido (Sales)**, garantindo que o cálculo de descontos e custos reflita a realidade de um balanço financeiro.
2.  **Sequência Lógica de KPIs (Fluxo de DRE):** Os cartões foram organizados da esquerda para a direita seguindo um fluxo intuitivo:
    *   **Vendas Brutas** -> **Unidades Vendidas** -> **Custo das Vendas (COGS)** -> **Total de Descontos** -> **Valor Líquido**.
3.  **Localização e Tradução:** Todos os termos técnicos foram traduzidos para o português e os nomes dos campos foram limpos (removendo prefixos como "Soma de"), tornando o dashboard profissional e pronto para o mercado brasileiro.
4.  **Desenvolvimento via Medidas DAX:** Foram criadas medidas específicas para os cálculos de KPI, evitando o uso de colunas implícitas e melhorando a performance e flexibilidade do relatório.

Tecnologias Utilizadas
*   **Power BI Desktop**
*   **DAX (Data Analysis Expressions)**
*   **Dataset:** Financials (fornecido pela Microsoft para fins de estudo)

Visualizações do Relatório
*   **Sales Report:** Visão geral de faturamento e custos.
*   **Gráficos de Barras:** Análise de vendas por segmento e produto.
*   **Análise Temporal:** Evolução de vendas por mês.
*   **Análise Geográfica:** Vendas por país.


Desenvolvido por Cristiano Gonçalves durante o bootcamp de Power BI Analyst da DIO.
