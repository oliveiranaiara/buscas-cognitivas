# ☕ Azure AI Search - Projeto de Indexação e Consulta de Dados

Este projeto demonstra como utilizar o **Azure AI Search** para indexar e consultar dados de maneira inteligente e escalável. Através de uma base de dados com conteúdo textual, simulamos a análise e pesquisa de sentimentos em avaliações de produtos.

## 🔧 Tecnologias utilizadas

- Microsoft Azure
  - Azure Cognitive Search
  - Azure Storage
- JSON query editor (Search Explorer)
- Azure Portal

---

## 📁 Estrutura de Recursos Criados

No portal do Azure, criamos os seguintes recursos:

| Nome                  | Tipo                    |
|-----------------------|-------------------------|
| `pesquisanaiara`      | Serviço de pesquisa     |
| `armazenamentopesquisa` | Conta de armazenamento |
| `coffee-index`        | Índice de pesquisa      |

---

## 📦 Dataset Utilizado

Foi usado um documento contendo uma **avaliação de café**, exemplo:

```text
Review: I love the coffee drinks here, but my favorite part is the ambiance.

