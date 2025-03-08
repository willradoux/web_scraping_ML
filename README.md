# Mercado Livre Scraper

Este projeto é um web scraper para buscar produtos no Mercado Livre, salvar os dados em uma planilha do Excel e exibir um gráfico de boxplot para análise de preços.

## Funcionalidades
- Realiza busca de produtos no Mercado Livre
- Extrai nome, preço e link dos produtos
- Salva os dados em uma planilha do Excel organizada
- Aplica formatação condicional para preços acima e abaixo da média
- Gera um boxplot dos preços usando Seaborn

## Requisitos
- Python 3.x
- Bibliotecas Python:
  - `requests`
  - `beautifulsoup4`
  - `pandas`
  - `openpyxl`
  - `matplotlib`
  - `seaborn`

Para instalar as dependências, execute:
```sh
pip install -r requirements.txt
```

### `requirements.txt`
```
requests
beautifulsoup4
pandas
openpyxl
matplotlib
seaborn
```

## Como usar
1. Execute o script:
```sh
python mercadolivre_scraper.py
```
2. Digite o nome do produto que deseja pesquisar.
3. O script irá gerar uma planilha e exibir o boxplot dos preços.

## Exemplo
```sh
Digite o produto que deseja pesquisar: notebook
Itens encontrados: 50
```

## Melhorias futuras
- Adicionar paginação para buscar mais produtos
- Implementar filtros de preço e categoria
- Exportar os gráficos em formato de imagem

## Licença
Este projeto é livre para uso e modificação.

