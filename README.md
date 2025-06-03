# Projeto Introdutório de Elasticsearch

Este projeto tem como objetivo apresentar, de forma prática, os conceitos fundamentais do [**Elasticsearch**](https://www.elastic.co/pt/), utilizando notebooks interativos (`.ipynb`) em Python para demonstrar cada funcionalidade.

## 📁 Estrutura do Projeto

Cada pasta deste repositório contém um notebook (`.ipynb`) com exemplos práticos:

1. **CRUD - Básico**  
   Operações de Create, Read, Update e Delete usando Elasticsearch.

2. **Pesquisa - Básico**  
   Realização de pesquisas simples usando queries básicas.

3. **Mapeamento**  
   Definição e uso de mapeamentos personalizados para tipos de dados.

4. **Pesquisa - Básico 2**  
   Continuação e aprofundamento das pesquisas com novos exemplos.

5. **Vetorização**  
   Introdução à vetorização de dados e buscas semânticas.

6. **Analise de Texto**  
   Análise textual com Elasticsearch, incluindo tokenização e filtros.

---

## 🚀 Preparando o ambiente

O projeto depende de dois componentes

1. Elasticsearch
2. Python
3. Bibliotecas terceiras

### 🚀 Como instalar o Elastisearch


Você pode instalar o Elasticsearch de duas formas:

1. Docker (recomendado)

Caso a sua máquina tenha docker, basta modificar o arquivo [.env](.env) para alterar a senha do banco.
Em seguida, execute o comando
```
docker-compose up
```

O Elastisearch estará dispónivel na porta 9200, com o usuário 'elastic' e a senha que foi colocada
no arquivo [.env](.env)

2. Manual

Para instalar manualmente, siga o [link](https://www.elastic.co/downloads/elasticsearch)

### 🚀 Como instalar o python

Para instalar o python, acesse o [link oficial da linguagem](https://www.python.org/downloads/). Na página inicial, terá o botão para entrar na sessão do download. 


### 🚀 Como instalar as bibliotecas terceiras

O projeto utiliza 3 bibliotecas python

1. notebook
2. elastisearch
3. elastisearch_dsl

Para instalar todas, basta rodar o comando
```
pip install -r requirements.txt
```

É recomendável criar um ambiente isolado para instalar as bibliotecas. No link a seguir mostra como criar um novo ambiente usando venv [link](https://docs.python.org/pt-br/3.13/library/venv.html)

## Como rodar o projeto

Rodando o comando a seguir, uma página no navegador abrirá, mostrando todas as pastas. Entre na pasta que deseja e seleciona o notebook que deseja estudar. 

```
jupyter notebook
```

