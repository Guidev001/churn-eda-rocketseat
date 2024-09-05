# Análise de Churn

Este repositório contém o estudo de análise de churn de clientes, seguindo o conteúdo do curso de Inteligência Artificial da **Rocketseat**. Utilizamos ferramentas como `pandas` e `matplotlib` para manipulação e visualização de dados.

## Estrutura do Projeto

- **Pipfile**: Arquivo de configuração para gerenciar as dependências do projeto.
- **Jupyter Notebook**: Contém a análise exploratória de dados (EDA) dos clientes que cancelaram contratos.
- **Datasets**:
  - `churn_contracts.csv`: Informações contratuais dos clientes.
  - `churn_customers.csv`: Informações detalhadas dos clientes.
  - `churn_services.csv`: Informações sobre os serviços utilizados pelos clientes.

## Dependências

As dependências principais e de desenvolvimento estão gerenciadas pelo arquivo `Pipfile`. Elas incluem:

### Dependências principais
- `pandas`: Utilizado para a manipulação e análise de dados.
- `matplotlib`: Utilizado para a criação de gráficos e visualizações.

### Dependências de desenvolvimento
- `ipykernel`: Necessário para rodar notebooks no Jupyter.

## Instruções para Configuração

1. Clone este repositório:
  ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
  ```

2. Instale as dependências:
  ```bash
    pipenv install --dev
  ```

3. Ative o ambiente virtual:
  ```bash
   pipenv shell
  ```

4. Abra o Jupyter Notebook para executar as análises
  ```bash
   jupyter notebook
  ```

## Objetivo

O objetivo deste projeto é entender os padrões e comportamentos dos clientes que cancelaram seus serviços, utilizando técnicas de visualização e análise exploratória de dados, conforme os aprendizados do curso da Rocketseat sobre Inteligência Artificial.
