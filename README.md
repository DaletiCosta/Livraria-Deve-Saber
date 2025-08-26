  # Projeto: Livraria DevSaber – Análise de Dados no BigQuery

Este projeto tem como objetivo construir e analisar um banco de dados relacional de uma livraria fictícia utilizando Google BigQuery, com foco em boas práticas de modelagem, integração e análise de dados. O projeto foi desenvolvido como parte do curso de Engenharia de Dados, explorando conceitos de ETL, SQL avançado e análise exploratória de dados.

## Estrutura do Banco de Dados

O banco de dados é composto por três tabelas principais:

- Clientes: Contém informações sobre os clientes, como IDCliente, Nome, Email, Telefone, Cidade, Estado e DataCadastro.

- Produtos: Catálogo de produtos da livraria, incluindo IDProduto, NomeProduto, Categoria e Preço.

- Vendas: Registros de vendas realizados, relacionando clientes e produtos com IDVenda, IDCliente, IDProduto, Quantidade, DataVenda e TotalVenda.

## Funcionalidades do Projeto

- Criação de tabelas normalizadas para garantir integridade e evitar redundâncias.

- Inserção de dados fictícios para testes de análise e consultas.

- Consultas SQL para gerar insights sobre vendas, produtos mais vendidos, clientes ativos e tendências de compras.

- Demonstração de joins, filtros, agregações e funções analíticas do BigQuery.

- Preparação do dataset para análises futuras, incluindo integração com ferramentas de BI.

## Tecnologias Utilizadas

- Google BigQuery: Armazenamento e processamento de dados em nuvem.

- SQL: Manipulação e consulta de dados.

- Google Colab (opcional): Para testes e análises exploratórias.

## Possíveis Extensões

- Integração com Looker para dashboards interativos.

- Adição de novas tabelas, como fornecedores, categorias detalhadas e promoções.

- Aplicação de modelos preditivos para previsão de vendas.
