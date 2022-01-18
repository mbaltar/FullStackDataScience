# FullStackDataScience

Projeto criado durante Bootcamp da [Stack](https://stacktecnologias.com.br/). O objetivo é apresentar um problema de negócio relacionado a Recursos Humanos - prever probabilidade dos funcionários deixarem a empresa - utilizando uma stack completa de Data Science, desde a captura dos dados, processamento, análises exploratórias, criação de modelos de previsão e deploy em ambiente de produção.

## Tecnologias utilizadas
- [Apache Airflow](https://airflow.apache.org/) - criação dos workflows para captura de dados (os dados estão em planilhas Excel, arquivos JSON e banco de dados mysql).
- [Minio](https://min.io/) - camada de datalake.
- [Python](https://www.python.org/) - Análises exploratórias e criação dos modelos. Destaque para pacotes utilizados:
    - [Anaconda](https://www.anaconda.com/) / [Scikit-learn](https://scikit-learn.org/stable/) para análises exploratórias e modelos de machine learning.
    - [PyCaret](https://pycaret.org/)
    - [Streamlit](https://streamlit.io/) para deploy do modelo em ambiente web.

Além destas, [Docker](https://www.docker.com/) foi utilizado para rodar Airflow, Minio e Mysql em containers.

O aplicativo em produção pode ser visulalizado em https://share.streamlit.io/mbaltar/fullstackdatascience/streamlit/app/app.py.
