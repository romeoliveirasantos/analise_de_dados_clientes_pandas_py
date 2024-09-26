# Análise de Dados com Pandas e PostgreSQL

Este projeto tem como objetivo analisar dados de clientes de um serviço de beleza utilizando a biblioteca Pandas em Python e um banco de dados PostgreSQL. A análise envolve a identificação de serviços mais escolhidos, os serviços mais rentáveis e clientes que necessitam de atenção por baixo número de serviços recorrentes.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação utilizada para a análise de dados.
- **Pandas**: Biblioteca utilizada para manipulação e análise de dados.
- **Matplotlib** e **Seaborn**: Bibliotecas utilizadas para visualização de dados.
- **SQLAlchemy**: Ferramenta utilizada para conectar e interagir com o banco de dados PostgreSQL.
- **PostgreSQL**: Sistema de gerenciamento de banco de dados utilizado para armazenar dados dos clientes.

## Configuração do Ambiente

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/romeoliveirasantos/analise_de_dados_clientes_pandas_py.git
   cd analise_de_dados_pandas_py

2. **Crie e ative um ambiente virtual**:
    ```bash
    python -m venv venv
    #utilizando o bash
    source venv/Scripts/activate  
    #No Windows use: venv\Scripts\activate

3. Instale as dependências:

    ```bash
    pip install pandas matplotlib seaborn sqlalchemy psycopg2


## Passos para Análise
1. Conexão com o Banco de Dados:

- Configure a conexão com o banco de dados PostgreSQL usando SQLAlchemy.

2. **Carregamento de Dados**:

- Utilize a função pd.read_sql para carregar os dados da tabela clientes.

3. **Análise de Dados**:

- Conte o número de serviços por cliente e calcule a soma da quantidade de serviços.

- Gere gráficos para visualizar a distribuição do número de serviços por cliente.

4. **Visualização**:

- Utilize Matplotlib e Seaborn para criar gráficos que mostram a distribuição dos serviços e outros insights relevantes.


## Gráficos Gerados
- Distribuição do Número de Serviços por Cliente: Gráfico de barras que mostra quantos clientes têm uma determinada quantidade de serviços.
- Serviços mais rentáveis: Gráfico de barras que mostra os serviços que geram mais retorno monetário.
- Tipo de serviço mais escolhidos pelos clientes: Gráfico de barras que mostra os serviços preferidos entre os clientes.