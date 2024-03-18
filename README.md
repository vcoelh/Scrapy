## Coletor de Dados do Site Books to Scrape
Este repositório contém um script em Python para coletar dados do site Books to Scrape (https://books.toscrape.com/). O script coleta informações como URL, preço, descrição, etc., e salva os dados tanto em um arquivo JSON quanto em uma tabela MySQL chamada "book" dentro do banco de dados "Books".

## Funcionalidades
O script utiliza a biblioteca Scrapy para fazer a raspagem de dados do site.
Os dados coletados são estruturados e armazenados em um arquivo JSON para fácil análise.
Além disso, os dados também são inseridos em uma tabela MySQL para persistência.
## Pré-requisitos
### Certifique-se de ter as seguintes dependências instaladas:

- Python 3.x
- Scrapy
- MySQL
- MySQL Connector Python
Além disso, você também precisa ter uma instância do MySQL em execução, com um banco de dados chamado "Books" criado, e as credenciais de acesso configuradas no script.

## Como usar
1° Clone este repositório:
```bash
git clone https://github.com/vcoelh/Scrapy.git
```
2° Crie um Virtual Envirement:
```bash
python -m venv venv
````
3° Vá para o ambiente virtual (Em Windows): 
```bash
venv/Scripts/activate
```
4° Instale as dependências:
```bash
pip install -r requirements.txt
```
5° Vá para o shell do Scrapy:

```bash
scrapy shell
```

Execute o script scrapy crawl bookspider para iniciar a coleta de dados:
```bash
scrapy crawl bookspider
```

Isso iniciará a raspagem de dados do site e salvará os dados coletados tanto em um arquivo JSON quanto na tabela MySQL.


Licença
Este projeto é licenciado sob a Licença MIT - veja o arquivo LICENSE para detalhes.
