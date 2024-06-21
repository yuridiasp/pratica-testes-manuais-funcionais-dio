# Projeto de User Stories e Mind Maps

Este repositório contém a documentação de User Stories, incluindo mind maps, critérios de aceitação, testes adotados, dados utilizados e riscos envolvidos. O projeto faz parte de um exercício prático da Formação Automação de Testes com Cypress da [DIO](https://www.dio.me/), e é focado em dois casos de uso principais: consulta de produtos e sistema de avaliação de produtos.

## Sumário

- [User Stories](#user-stories)
- [Mind Maps](#mind-maps)
- [Critérios de Aceitação](#critérios-de-aceitação)
- [Testes Adotados](#testes-adotados)
- [Dados](#dados)
- [Riscos Envolvidos](#riscos-envolvidos)
- [Contribuição](#contribuição)
- [Licença](#licença)

## User Stories

### Consulta de Produtos

**Como** um cliente, **Quero** poder buscar produtos no shopping pelo nome, categoria ou preço, **Para** encontrar o que procuro de maneira rápida e fácil.

- **Critérios de Aceitação:**
  - Campo de busca disponível na página principal.
  - Filtros de busca por nome, categoria e faixa de preço.
  - Resultados exibidos com imagem, nome, preço e descrição do produto.

- **Valor:**
  - Proporcionar uma experiência de compra eficiente, facilitando a localização de produtos e aumentando a satisfação do cliente.

- **Requisitos:**
  - O sistema deve ter um campo de busca funcional.
  - O sistema deve permitir a aplicação de filtros (nome, categoria, preço).
  - O sistema deve exibir resultados relevantes e precisos de acordo com a busca.

- **Story Points:** 8

### Sistema de Avaliação de Produtos

**Como** um cliente, **Quero** poder avaliar e ver avaliações de produtos, **Para** tomar decisões de compra informadas.

- **Critérios de Aceitação:**
  - Opção de avaliar produto após compra.
  - Exibição das avaliações na página do produto.
  - Média das avaliações calculada e exibida.

- **Valor:**
  - Ajudar os clientes a tomar decisões de compra mais informadas e aumentar a confiança nos produtos oferecidos pelo shopping.

- **Requisitos:**
  - O sistema deve permitir que clientes registrem avaliações após a compra.
  - O sistema deve exibir avaliações de outros clientes na página do produto.
  - O sistema deve calcular e exibir a média das avaliações.

- **Story Points:** 5

## Mind Map

### Consulta de Produtos

![Mind-map: Consulta de Produtos](path/to/Mindmap_Consulta_de_Produtos.png)

## Critérios de Aceitação

Os critérios de aceitação para cada User Story estão descritos na seção [User Stories](#user-stories).

## Testes Adotados

### Consulta de Produtos
- Testes com banco de dados para verificar a busca correta de produtos
- Testes de API
- Testes funcionais com UI

### Sistema de Avaliação de Produtos
- Testes com banco de dados para verificar se a avaliação foi corretamente registrada
- Testes de API
- Testes funcionais com UI

## Dados

### Consulta de Produtos
- Nome do Produto
- Categoria do Produto
- Faixa de Preço

### Sistema de Avaliação de Produtos
- Avaliação do Cliente
- Comentários do Cliente
- Média das Avaliações

## Riscos Envolvidos

### Consulta de Produtos
- A busca não retorna resultados
- O sistema está fora do ar

### Sistema de Avaliação de Produtos
- Avaliação não registrada
- Avaliações não exibidas corretamente

## Contribuição

Se você deseja contribuir para este projeto, por favor siga as diretrizes de contribuição descritas no arquivo [CONTRIBUTING.md](CONTRIBUTING.md).

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
