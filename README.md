# Price Miner Repository

Este repositório é dedicado ao projeto **Price Miner**, uma ferramenta projetada para selecionar e exibir promoções diárias de vários fornecedores da web. O objetivo principal é facilitar a busca por ofertas atrativas, ajudando os usuários a economizarem tempo e dinheiro em suas compras online.

## Descrição

O projeto **Price Miner** consiste em várias partes interconectadas, cada uma desempenhando um papel fundamental no processo de coleta, transformação e exibição das promoções.

### Estrutura do Projeto

1. **Price Miner Services**:
   - API para realizar a extração, transformação e carga de dados.
   - Oferece um endpoint para consumir as promoções coletadas.

2. **Price Miner ETL Airflow**:
   - DAG (Directed Acyclic Graph) no Apache Airflow para automatizar o processo de ETL (Extract, Transform, Load) diário.
   - Mantém a API atualizada com as últimas promoções.

3. **Price Miner Web**:
   - Front-End para exibir as promoções diárias (Em breve).

## Como Contribuir

Este projeto é aberto a contribuições! Se você tem interesse em melhorar o **Price Miner**, veja abaixo algumas formas de contribuir:

- **Reportando Problemas**: Encontrou um bug ou tem uma ideia para melhorar o projeto? Por favor, abra uma issue neste repositório.
- **Desenvolvendo Novos Recursos**: Se você é um desenvolvedor e deseja adicionar novos recursos ao projeto, fique à vontade para enviar um pull request.
- **Melhorando a Documentação**: Documentação clara e concisa é essencial. Se você identificar áreas que podem ser melhoradas na documentação, suas contribuições serão bem-vindas.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).




