## Consumo de APIs Diversas

### Descrição Geral
Este projeto tem como objetivo exercitar o consumo de APIs utilizando a linguagem Python. O padrão **Strategy** é seguido, permitindo que os objetos sejam intercambiáveis em tempo de execução.

### Estrutura do Projeto
- **/main.py**: Arquivo principal, responsável por orquestrar as chamadas para cada uma das APIs.
- **/api.py**: Arquivo que contém as classes especializadas para chamar cada API, seguindo o padrão Strategy.

### Passo a Passo

1. Certifique-se de ter o Python 3 instalado. Para verificar, execute:

    ```bash
    python --version
    ```

2. Instale um ambiente virtual:

    ```bash
    python -m venv venv
    ```

3. Instale a biblioteca **requests**:

    ```bash
    pip install requests
    ```

4. Execute o **main.py**:

    ```bash
    python main.py
    ```

A execução deve retornar uma lista de dados buscados de cada API.

### Exemplo de saída

```bash
Consumo da API Pokémon
****************************************
(1, 'bulbasaur')
(2, 'ivysaur')

Consumo da API Rick and Morty
****************************************
(1, 'Rick Sanchez', 'Human')
(2, 'Morty Smith', 'Human')

Consumo da API Star Wars
****************************************
('Luke Skywalker', ['https://swapi.dev/api/films/1/', 'https://swapi.dev/api/films/2/', 'https://swapi.dev/api/films/3/', 'https://swapi.dev/api/films/6/'])
('C-3PO', ['https://swapi.dev/api/films/1/', 'https://swapi.dev/api/films/2/', 'https://swapi.dev/api/films/3/', 'https://swapi.dev/api/films/4/', 'https://swapi.dev/api/films/5/', 'https://swapi.dev/api/films/6/'])

Consumo da API Crônicas do Gelo e do Fogo
****************************************
('Jon Snow', ['Season 1', 'Season 2', 'Season 3', 'Season 4', 'Season 5', 'Season 6'])
('Walder Frey', ['Season 1', 'Season 2', 'Season 3', 'Season 4', 'Season 6'])

```
