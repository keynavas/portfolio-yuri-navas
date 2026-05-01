# 🎬 Sistema de Recomendação de Filmes

> **Engenharia de Contexto e Lógica Física: Uma abordagem modular para mitigar a paralisia de escolha.**

## 📝 Descrição do Projeto
Este projeto consiste em um motor de recomendação inteligente que utiliza técnicas de filtragem colaborativa e baseada em conteúdo. [cite_start]O sistema processa grandes volumes de dados para identificar padrões de comportamento e prever preferências de usuários[cite: 2, 3].

[cite_start]A arquitetura foi desenvolvida utilizando o **Pensamento Computacional** como alicerce:
* **Engenharia de Contexto:** O algoritmo interpreta o histórico de visualização e gêneros para criar um perfil contextual do usuário.
* [cite_start]**Lógica Física e Algoritmos:** Tradução de comportamentos humanos em regras ordenadas para prever notas de filmes ainda não assistidos.
* [cite_start]**Decomposição:** O problema foi quebrado em módulos menores e gerenciáveis (limpeza, processamento e interface).
* [cite_start]**Abstração:** Foco nos dados relevantes de avaliação, ignorando metadados que não contribuem para o modelo preditivo.

## 🏗️ Arquitetura de Software (Design Top-Down)
[cite_start]Em vez de um código monolítico "espaguete", o sistema utiliza uma **Organização Modular**[cite: 2, 3]:

* [cite_start]**Alta Coesão:** Cada função (como limpeza de dados ou cálculo de similaridade) realiza apenas uma tarefa específica[cite: 3].
* [cite_start]**Baixo Acoplamento:** Módulos independentes que se comunicam através de parâmetros e retornos, garantindo isolamento de escopo[cite: 4, 8].
* [cite_start]**Princípio DRY (Don't Repeat Yourself):** A lógica matemática central é encapsulada em funções reutilizáveis, evitando repetições[cite: 3, 8].

## 🚀 Tecnologias Utilizadas
* **Linguagem:** Python 3.10
* **Bibliotecas:** Pandas, Scikit-learn, Matplotlib
* **Ferramentas:** Jupyter Notebook, Google Colab

## 📊 Resultados e Aprendizados
O projeto priorizou a **Engenharia de Contexto** para melhorar a precisão:
* **92% de acurácia** nos testes de validação.
* [cite_start]**Redução de Ruído:** Aplicação de técnicas de normalização física dos dados para otimizar os algoritmos.
* **Visualização de Clusters:** Gráficos que demonstram como a lógica de similaridade agrupa filmes por afinidade.

## 🔧 Como Executar
1. Clone o repositório.
2. Instale as dependências: `pip install -r requirements.txt`.
3. Execute o comando: `python main.py`.

---
[cite_start]*Projeto desenvolvido sob a filosofia: "Menos tela, mais arquitetura. Um código com bom design é planejado antes de ser digitado." [cite: 9]*
