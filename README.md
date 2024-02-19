<a href="https://projectx-eight-gilt.vercel.app/">
  <h1 align="center">Price Miner: ETL de Dados de Promoções </h1>
</a>

<p align="center">
  Processo de ETL de dados de ofertas nas Lojas Mercado Livre e Magazine Luiza.
</p>

<p align="center">
  <!-- <a href="https://twitter.com/placeholder">
    <img src="https://img.shields.io/twitter/follow/Projectx?style=flat&label=%40projectxy&logo=twitter&color=0bf&logoColor=fff" alt="Twitter" />
  </a> -->
  <a href="https://github.com/meglerhagen/projectx/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/meglerhagen/projectx?label=license&logo=github&color=f80&logoColor=fff" alt="License" />
  </a>
</p>

<p align="center">
  <a href="#"><strong>Python</strong></a> ·
  <a href="#"><strong>Apache Airflow</strong></a> ·
  <a href="#"><strong>Django</strong></a> ·
  <a href="#"><strong>API</strong></a> ·
  <a href="#"><strong>Database</strong></a>
</p>
<br/>

## Introdução

Bem-vindo ao Price Miner, um projeto de ETL end-to-end para coletar, processar e disponibilizar ofertas de diversas lojas em um único app.

## Descrição do Projeto

### Database

Inicialmente, estamos utilizando um banco de dados SQLite do próprio django, com apenas 1 tabela Products.

### API - price-miner-services

O processo de Extração de dados é feito por uma API Python construída em Django, com funções CRUD no banco de dados. 
A API também possui os serviços de extração e transformação de dados, podendo realizar a automação do processo utilizando os endpoint:

- Extract Dados (extract_{Abreviação da Loja}: Extrair e Transformar os dados (Realizado 1 Vez por dia)
- Delete Dados (delete_{Abreviação da Loja} Deletar Dados de Ofertas Antigas (Realizado 1 Vez por dia)
- Get Dados (get_{Abreviação da Loja} Obter os dados coletados (Realizado pelo Client)


### Airflow - price-miner-dags

O processo de automação da extração, transformação e carga de dados é feita com o airflow:

### Web Site - price-miner-web

O website comsome a API interna, com os dados atualizados e mostra as ofertas atualizadas.


## Tech Stack + Features

### Frameworks

- [Django](https://www.djangoproject.com/) – Django The web framework for perfectionists with deadlines.
- [Bootstrap](https://getbootstrap.com/) – A powerful, feature-packed frontend toolkit.
- 
### Platforms

- [Azure](https://azure.microsoft.com/en-gb/) – Plataforma de Hospedagem

### UI

- [Uiverse](https://uiverse.io/) – Open-Source UI elements for any project

## Repo Activity

![Price Miner repo activity – generated by Axiom](https://repobeats.axiom.co/api/embed/723580c47ac7209662914f2b7c552c3239105218.svg "Repobeats analytics image")


