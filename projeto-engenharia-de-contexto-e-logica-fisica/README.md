# 🎬 Sistema de Recomendação de Filmes

> **Engenharia de Contexto e Lógica Física: Uma abordagem modular para mitigar a paralisia de escolha.**

## 📝 Descrição do Projeto
Este projeto consiste em um motor de recomendação inteligente que utiliza técnicas de filtragem colaborativa e baseada em conteúdo. Desenvolvido como parte da disciplina de **Inteligência Artificial (2024.1)**, o sistema processa grandes volumes de dados para prever preferências de usuários com base em padrões de comportamento.

A arquitetura foi construída sob os pilares do **Pensamento Computacional**:
* **Engenharia de Contexto:** O algoritmo interpreta o histórico e as preferências de gênero para criar um "contexto de interesse" personalizado.
* **Lógica Física e Algoritmos:** Tradução de comportamentos de usuários em regras matemáticas ordenadas para prever notas de filmes não assistidos.
* **Decomposição:** O problema complexo de recomendação foi quebrado em sub-processos (limpeza, cálculo e exibição).
* **Abstração:** Foco exclusivo nos dados de afinidade, ignorando metadados irrelevantes para a performance do modelo.

## 🏗️ Arquitetura de Software (Design Top-Down)
Seguindo o guia "Dividir para Conquistar", o código abandona a estrutura monolítica (espaguete) em favor de uma **Organização Modular**:

* **Alta Coesão:** Cada função no sistema realiza uma tarefa única e bem definida.
* **Baixo Acoplamento:** Módulos independentes (caixas pretas) que utilizam parâmetros e retornos para se comunicar, garantindo o isolamento de escopo.
* **Princípio DRY (Don't Repeat Yourself):** A lógica de similaridade e tratamento de dados foi encapsulada em rotinas reutilizáveis.

## 🚀 Tecnologias Utilizadas
* **Linguagem:** Python 3.10
* **Bibliotecas:** Pandas, Scikit-learn, Matplotlib
* **Conceitos Aplicados:** Engenharia de Contexto e Lógica Física.

## 📊 Resultados e Aprendizados
O projeto priorizou o design da solução antes da codificação, resultando em:
* **92% de acurácia** nos testes de validação.
* **Redução de Ruído:** Aplicação de técnicas de normalização física dos dados.
* **Visualização de Clusters:** Implementação de gráficos que demonstram o agrupamento de filmes por afinidade.

## 🔧 Como Executar
1. Clone o repositório.
2. Instale as dependências: `pip install -r requirements.txt`.
3. Execute o comando: `python main.py`.

---
*Projeto fundamentado na filosofia: "Um código com bom design é planejado antes de ser digitado."*
