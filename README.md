# Análise de Desempenho e Impacto Salarial na NBA 🏀

Este projeto foi desenvolvido como parte da disciplina de **Introdução à Ciência de Dados (ICD)** na USP - São Carlos. O objetivo central é investigar se estatísticas de performance em quadra podem prever o salário de um jogador para a temporada subsequente, auxiliando na compreensão da gestão financeira e esportiva das franquias.

## 🎯 Problema de Negócio
Na NBA, a precificação correta de um atleta é um desafio de milhões de dólares. Este estudo busca responder: **é possível prever o salário de um jogador utilizando apenas suas estatísticas de performance?**

## 🛠️ Tecnologias e Ferramentas
- **Linguagem:** Python
- **Bibliotecas:** Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning:** Scikit-Learn (Modelos de Classificação e Regressão)
- **Ambiente:** Jupyter Notebook / Google Colab

## 📈 Metodologia e Resultados
O projeto seguiu o ciclo padrão de Ciência de Dados:
1. **Coleta e Limpeza:** Tratamento de dados históricos de performance e salários.
2. **Análise Exploratória (EDA):** Identificação de correlações entre métricas de jogo e faixas salariais.
3. **Modelagem:** Aplicação de algoritmos para prever o impacto financeiro.
   - Os modelos de classificação alcançaram uma acurácia de aproximadamente **57%**.
4. **Análise de Importância:** Identificamos as variáveis que mais impactam o modelo:
   - **MP** (Minutos Jogados)
   - **PTS** (Pontos)
   - **FGA** (Tentativas de Arremesso)
   - **AST** (Assistências)

## 📁 Estrutura do Repositório
- `notebooks/`: Contém o arquivo `.ipynb` com toda a análise e desenvolvimento dos modelos.
- `data/`: Bases de dados utilizadas no projeto.

## 👥 Autores
- **Caio Augusto Marangoni de Mello** (Estudante de Estatística e Ciência de Dados - USP)
- **Davi Ferrari Hannickel**
- **Gustavo Prevelato de Freitas**
- **Henrique Nardi Farbelow**

---
Desenvolvido durante a graduação no ICMC-USP.
