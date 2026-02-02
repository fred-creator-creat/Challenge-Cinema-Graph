# Challenge: Banco de Dados em Grafo (Cinema & Séries)

Este projeto foi desenvolvido como parte do **Bootcamp da DIO (Digital Innovation One)** em parceria com o **Neo4j**.

**Autor:** [Fred Cavalheiro]

Este projeto consiste na modelagem e implementação de um banco de dados utilizando Neo4j para representar relações entre usuários, filmes, séries, atores e diretores.

## 🛠️ Tecnologias Utilizadas
- **Arrows.app**: Para a modelagem visual inicial.
- **Neo4j Aura DB**: Para hospedagem e consulta do banco de dados em nuvem.
- **Cypher**: Linguagem de consulta para grafos.

## 📊 Estrutura do Grafo
O banco de dados contém 10 nós e relacionamentos que conectam:
- **Usuário** que assistiu filmes e séries (com avaliações).
- **Filmes e Séries** pertencentes a gêneros específicos.
- **Atores** que atuaram nos filmes.
- **Diretores** que dirigiram as obras.

## 🚀 Como rodar o projeto
Basta copiar o código presente no arquivo `script.cypher` e executá-lo em um console Neo4j. Para visualizar os dados após a criação, utilize o comando:
`MATCH (n) RETURN n`

---
*Projeto realizado para fins educacionais no Bootcamp DIO + Neo4j.*
