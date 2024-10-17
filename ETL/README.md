
# Cenário
    Fonte de dados:
        Tabela raw_sales: Contém os dados de transações brutas de vendas.
        Tabela raw_products: Contém informações de produtos em estado bruto (inconsistentes).
        Tabela raw_customers: Contém os dados brutos dos clientes.
    Destino:
        Tabela dim_products: Dimensão de produtos limpa e normalizada.
        Tabela dim_customers: Dimensão de clientes limpa.
        Tabela fact_sales: Fato de vendas com os dados processados e transformados.

Passos do ETL:

    Extract (Extração): Extraímos os dados das tabelas brutas.
    Transform (Transformação): Aplicamos validações, limpeza, normalização e outras transformações.
    Load (Carga): Carregamos os dados transformados nas tabelas de fato e dimensões.

## Componentes Críticos
Extração: A query acessa os dados brutos diretamente das tabelas de origem (raw_sales, raw_products, raw_customers).
Transformação: Aplicação de regras de negócios como normalização de campos, validação de dados e cálculos. Esses dados são enriquecidos ao serem unidos a outras dimensões (dim_products, dim_customers).
Carga: Os dados processados são inseridos nas tabelas de fato e dimensão, prontos para serem consultados no Data Warehouse.