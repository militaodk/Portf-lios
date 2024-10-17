
# Explicação
Essa query é projetada para realizar análises profundas, com agregações complexas e cálculos incrementais. Ela é típica de cenários em que engenheiros de dados lidam com grandes volumes de dados e precisam fornecer insights complexos para equipes de analytics ou BI..

## Tecnologias
CTE sales_summary: Agrega vendas por produto, loja e cliente, com rankings por loja e categoria usando funções de janela (ROW_NUMBER e RANK).
CTE running_totals: Usa SUM() OVER() para calcular totais acumulados de vendas e quantidade vendida por produto e loja, mês a mês.
CTE monthly_growth: Utiliza LAG() para calcular o crescimento percentual mês a mês, comparando a receita e quantidade de vendas com o mês anterior.
CTE category_share: Calcula a participação de cada produto nas vendas totais de sua categoria em um determinado mês, usando SUM() OVER().
Consulta Final: Combina todas as CTEs e exibe informações detalhadas sobre vendas, crescimento percentual, totais acumulados e participação nas categorias, além de rankings de vendas.
