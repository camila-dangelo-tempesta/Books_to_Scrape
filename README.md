## **Books_to _Scrape**
 Web scraping, mining to extract data from the site, Book to Scrape, and converting them into structured information for further analysis.
***
# _**O método SAPE**_
***
1.	**Problema de Negócio**
   1. Problema de negócio: Qual catálogo possui o melhor preço de compra segundo as recomendações dos clientes?
***
2.	**Saída: ( Produto final )**
    2. A resposta para a pergunta: Mediana dos preços dos catálogos.
    2. Formato da entrega: Tabela e Gráfico
    2. Local da entrega: PowerBi
***
3.	**Processo ( Passo a Passo )**
3.1	Passo a passso para construir o cálculo da mediana ou média
[] Realizar o calculo da mediana sobre o produto, tipo e cor
- 
3.2	Definir o formato da entrega ( Visualização, Tabela, Texto)
[] Gráfico com a mediana dos preço dos produtos, por catálogo e avaliação 
[] Tabela com as seguintes colunas: product_name | product_price | product_stock | product_star | product_catalog
[] Definição do schema: Colunas e seu tipo
[] Definição a infraestrutura de armazenamento ( csv )Design do ETL ( Scripts de Extração, Transformação e Carga )
[] Fazer as visualizações
[] Entrega do produto final

3.3	Decidir o local de entrega ( PowerBi, Telegram, Email, Streamlit, Intranet )
[] PowerBI

4.	**Entrada (Fonte de dados)**

4.1	**Fonte de dados**
* https://books.toscrape.com/

4.2	**Ferramentas**
* Python 3.8.0
* Bibliotecas de Webscrapping ( BS4)
* VisualCode
* Jupyter Notebook ( Analise e prototipagens )
* PowerBI
