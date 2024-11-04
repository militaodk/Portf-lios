# Análise de Telemarketing

Uma aplicação interativa para analisar e visualizar dados de campanhas de telemarketing, permitindo filtragem personalizada e download dos resultados processados.

## Descrição do projeto

Este projeto é uma aplicação de análise de dados desenvolvida com Streamlit para explorar uma base de dados de marketing bancário. Os usuários podem carregar um arquivo CSV com dados de uma campanha de telemarketing e, em seguida, aplicar filtros como idade, profissão, estado civil, entre outros. A aplicação permite visualizar dados brutos e filtrados, bem como baixar os resultados. Também é possível gerar gráficos personalizados para análise da taxa de aceitação..

## Utilização

### Dependencias

Dependências

    Python 3.x
    Bibliotecas:
        pandas
        streamlit
        seaborn
        matplotlib
        Pillow para carregamento de imagens

### Instalação

Clone este repositório para o seu ambiente local.
Instale as dependências necessárias:

pip install -r requirements.txt

Adicione os arquivos de dados de campanha no formato CSV ou XLSX. A aplicação está configurada para ler e interpretar esses tipos de arquivo.

### Executando o projeto

* Como rodar o projeto/programa
* Passo a passo em tópicos (bullet points)
```
bloco de código para os comandos necessários
```

## Ajuda

Para iniciar a aplicação, execute o seguinte comando na raiz do repositório:
```
streamlit run app_7.py

```
Acesse a aplicação através do link que aparecerá no terminal, normalmente http://localhost:8501.

Passo a Passo na Interface

    Upload de Arquivo: Na barra lateral, carregue seu arquivo de dados.
    Filtros: Configure filtros de acordo com as necessidades de análise (idade, profissão, estado civil, entre outros).
    Visualização: Os dados brutos e filtrados serão exibidos e podem ser baixados em formato Excel.
    Gráficos: Escolha o tipo de gráfico (barras ou pizza) para visualizar a proporção de aceitação da campanha.

Ajuda

    Certifique-se de que o arquivo de dados está no formato esperado (.csv ou .xlsx).
    Caso encontre algum erro ao aplicar filtros, verifique os valores válidos para cada coluna.

bash

streamlit run app_7.py --help
## Autores

Nomes dos desenvolvedores do projeto e informação para entrar em contato.

Gabriel Militao
LinkedIn:https://www.linkedin.com/in/gabriel-militao/

## Histórico de versões.

0.2

    Ajustes de visualização e melhorias nos filtros

0.1

    Versão inicial com funcionalidade básica de upload e visualização de dados

## Licença de uso

Este projeto é disponibilizado sob a licença MIT. Veja o arquivo LICENSE.md para mais detalhes.

## Fontes de inspiração

Inspiração, trechos de códigos utilizados, etc.
* [readme-template](https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc)
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
