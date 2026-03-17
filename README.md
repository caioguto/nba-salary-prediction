# Análise de Desempenho e Impacto Salarial na NBA 🏀

Este projeto foi desenvolvido como parte da disciplina de **Introdução à Ciência de Dados (ICD)** no ICMC-USP São Carlos. O objetivo é investigar se as estatísticas de performance em quadra podem prever o salário de um jogador para a temporada subsequente (2025-2026), auxiliando na compreensão da gestão financeira das franquias.

## 🎯 Problema de Negócio
Na NBA, a precificação correta de um atleta é um desafio de centenas de milhões de dólares. Este estudo busca responder: **é possível prever o salário de um jogador utilizando apenas suas estatísticas de performance?**

## 🛠️ Tecnologias e Ferramentas
- **Linguagem:** Python
- **Manipulação e Análise:** Pandas, NumPy
- **Visualização:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-Learn (K-Means, LassoCV, Random Forest)
- **Ambiente:** Jupyter Notebook / Google Colab

## 📈 Metodologia e Pipeline
O projeto seguiu um fluxo completo de análise e modelagem:
1. **Engenharia de Dados (ETL):** Limpeza e tratamento de duplicatas, garantindo que as médias de jogadores que atuaram em múltiplos times fossem contabilizadas de forma única e justa.
2. **Análise Exploratória (EDA):** Identificação de correlações entre métricas de jogo e salários.
3. **Clustering (K-Means):** Aplicação de aprendizado não-supervisionado para agrupar jogadores com perfis similares, permitindo entender nuances entre funções táticas em quadra.
4. **Modelagem Preditiva:** Comparação entre modelos lineares regularizados (**LassoCV**) e modelos de conjunto baseados em árvores (**Random Forest Regressor**).
    - Para fins de análise, o modelo de classificação alcançou uma acurácia de aproximadamente **57%**.

### 📊 Principais Drivers Salariais
Identificamos as variáveis que mais impactam a predição do modelo:
1. **MP** (Minutos Jogados) - 0.20
2. **PTS** (Pontos) - 0.16
3. **FGA** (Tentativas de Arremesso) - 0.15
4. **AST** (Assistências) - 0.12

## 📁 Estrutura do Repositório
- `notebooks/`: Ciclo completo de desenvolvimento, desde o tratamento até a avaliação dos modelos.
- `data/`: Bases de dados históricas e salariais utilizadas.

## 👥 Autores
- **Caio Augusto Marangoni de Mello** (Estudante de Estatística e Ciência de Dados - USP)
- **Davi Ferrari Hannickel**
- **Gustavo Prevelato de Freitas**
- **Henrique Nardi Farbelow**

---
Projeto acadêmico realizado no ICMC-USP.
