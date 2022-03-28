# ANÁLISE EXPLORATÓRIA COM PANDAS E SQLSERVER

A ideia deste projeto é mostrar como é fácil conectar ao banco de dados com python e, dessa forma, utilizar para análises.

## 1° Etapa.
A 1° etapa foi a de popular o banco de dados. Neste projeto foi utilizado o SQL SERVER, onde foi aplicado ETL.
- Os dados foram extraídos do kaggle, sendo a famosa base de dados OLIST. Com isto, foi os dados foram importados para o banco de dados. 
- Foram realizados algumas transformações nos dados após a carga. Desta forma, manteve-se os dados originais e os dados transformados (em tabelas diferentes).

## 2° Etapa.
A 2° etapa foi conectar ao SQL SERVER utilizando python. Para isto, foi necessário utilizar a lib pyodbc. Com ela, pode-se criar a conexão com o BD de forma simples e rápida. No caso desse projeto, a autenticação foi configurada para autenticação do windows.

## 3° Etapa.
A 3° etapa consiste em fazer consultas ao BD. Com o pandas, é possível realizar as consultas diretamente na função pd.read_sql_query(). Esta função retorna a consulta em um objeto DataFrame.

## 4° Etapa.
Agora é possível analisar os dados.


## TECNOLOGIAS UTILIZADAS
- SQL SERVER Management Studio
- Python



