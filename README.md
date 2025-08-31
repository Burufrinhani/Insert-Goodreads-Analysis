# 📚 Análise de Dados de reviews da Amazon - Books

Este repositório armazena o projeto de análise de dados sobre literatura, parte da disciplina de Modelagem de Banco de Dados II, do curso de Ciência da Computação 6º semestre.  
Estamos utilizando um conjunto de dados do **Goodreads**, extraído através do Kaggle. O objetivo principal da análise é explorar tendências e padrões no comportamento de leitores e no desempenho de livros ao longo do tempo.

---

## 📖 Índice

1. [Planejamento](#planejamento)  
2. [Fonte dos Dados](#fonte-dos-dados)  
3. [Estrutura do Repositório](#estrutura-do-repositorio)  
4. [Objetivo](#objetivo)  

---

## 🗓️ Planejamento

* **Planner do projeto:** [Trello](https://trello.com/b/glsrUTGu)

---

## 🔗 Fonte dos Dados

Este projeto utiliza o dataset **Amazon Product Reviews – Books**, que contém milhões de avaliações de livros feitas por usuários na plataforma Amazon.

* [Amazon Product Reviews - Books](https://cseweb.ucsd.edu/~jmcauley/datasets.html)  
  - **Conteúdo:** Cada registro possui informações sobre o livro e a avaliação do usuário.  
    🔹 Avaliações  
    🔹 Metadados dos Livros

---

<!-- Título com âncora segura usando HTML -->
<h2 id="estrutura-do-repositorio">📂 Estrutura do Repositório</h2>

* `data/`: Pasta contendo os arquivos CSV do dataset baixado do Kaggle.  
* `README.md`: Este arquivo, que fornece uma visão geral do projeto.

---

## 📍 Objetivo

O projeto busca responder as seguintes perguntas:  

* **Crescimento de Reviews:** Quais livros tiveram o maior crescimento no número de avaliações no último trimestre e ano?  
* **Efeito Hype/Fadiga:** A nota média de um livro tende a cair após picos de reviews? (Investigação sobre o "efeito hype").  
* **Desempenho por Editora:** Quais editoras têm o melhor desempenho por gênero em termos de nota média e volume de avaliações?
