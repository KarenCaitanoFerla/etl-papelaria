# README - Projeto ETL para Dados de Papelaria

Bem-vindo ao projeto ETL (Extract, Transform, Load) de papelaria. Este projeto tem como objetivo realizar a extração, transformação e carga de dados de um arquivo CSV relacionado a produtos de papelaria. Utilizando Python para a manipulação dos dados e SQL para a integração com um banco de dados, o projeto simplifica o processo de tratamento e análise de informações.

## Descrição do Projeto

O projeto ETL de papelaria é uma solução básica que automatiza as seguintes etapas:

1. **Extração de Dados:**
   - Carrega dados de um arquivo CSV contendo informações sobre produtos de papelaria.

2. **Transformação de Dados:**
   - Cria uma tabela para armazenar as informações.
   - Realiza o tratamento dos dados, especialmente na manipulação dos valores.
   - Calcula a margem de lucro para cada produto.

3. **Carga de Dados no Banco de Dados:**
   - Insere uma nova coluna na tabela para armazenar a margem de lucro calculada.
   - Finaliza inserindo os dados tratados no banco de dados.

## Funcionalidades

O projeto oferece as seguintes funcionalidades principais:

1. **Carregamento de Dados do CSV:**
   - Carrega dados de um arquivo CSV contendo informações sobre produtos de papelaria.

2. **Criação de Tabela:**
   - Cria uma tabela no banco de dados para armazenar as informações dos produtos.

3. **Tratamento de Dados de Valores:**
   - Realiza o tratamento necessário nos valores dos produtos.

4. **Cálculo da Margem de Lucro:**
   - Calcula a margem de lucro para cada produto, utilizando a fórmula específica definida no código.

5. **Inserção de Nova Coluna:**
   - Adiciona uma nova coluna na tabela do banco de dados para armazenar a margem de lucro calculada.

6. **Carga de Dados no Banco de Dados:**
   - Finaliza inserindo os dados tratados no banco de dados, garantindo que a tabela esteja atualizada com as informações mais recentes.

## Como Utilizar

Para utilizar este projeto, siga as instruções abaixo:

1. **Configuração do Ambiente:**
   - Certifique-se de ter o Python e um banco de dados (por exemplo, MySQL, PostgreSQL) instalados em seu ambiente.
   - Instale as dependências necessárias utilizando o seguinte comando:
     ```
     pip install -r requirements.txt
     ```

2. **Configuração do Banco de Dados:**
   - Crie um banco de dados e configure as informações de conexão no arquivo `config.py`.

3. **Execução do Código:**
   - Navegue até o diretório do projeto e execute o script principal:
     ```
     python etl_papelaria.py
     ```

4. **Resultados:**
   - Os resultados do processo ETL serão exibidos no console ou refletidos no banco de dados, dependendo da configuração do código.

Lembre-se de ajustar as configurações do banco de dados conforme necessário para o ambiente em que o projeto será executado.

## Contribuições

Aproveite o processo de ETL para análise de dados de papelaria! 📊🖇️
