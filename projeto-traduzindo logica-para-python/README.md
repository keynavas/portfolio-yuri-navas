# 🛠️ Laboratório de Lógica e Engenharia de Contexto

Este diretório contém uma coleção de algoritmos desenvolvidos para simular fluxos de decisão baseados em **Lógica Física** (clima, finanças) e **Engenharia de Contexto** (vendas e notas escolares).

## 🚀 Conceitos Aplicados (Dividir para Conquistar)
Seguindo as diretrizes de **Modularização**, cada script foi desenhado para atuar como uma "unidade funcional" independente:

* **Decomposição:** Problemas financeiros e climáticos foram quebrados em passos ordenados de entrada, processamento e saída.
* **Alta Coesão:** Cada função possui uma responsabilidade única (ex: `analisar_clima` foca estritamente em métricas térmicas).
* **Abstração:** Os simuladores focam apenas nos parâmetros essenciais, ignorando variáveis externas para garantir a precisão da lógica central.

## 📂 Descrição das Funções

1.  **Processador de Vendas:** Aplica engenharia de contexto para determinar faixas de desconto baseadas no volume financeiro.
2.  **Analisador de Clima:** Traduz a **Lógica Física** da temperatura em alertas operacionais e médias semanais.
3.  **Sistema de Notas:** Um integrador de desempenho acadêmico que contextualiza a média do aluno em estados de aprovação.
4.  **Simulador de Poupança:** Algoritmo de juros compostos que modela o crescimento físico de um capital ao longo do tempo.

---

## ❓ Perguntas de Reflexão Técnica

### Pergunta 1: Qual a importância da conversão de tipos no `input()`?
**Resposta:** Quando você utiliza o comando `input()` sem converter, o Python sempre retorna uma **string** (texto). Para realizar cálculos matemáticos ou comparar grandezas (Lógica Física), é obrigatório converter esse dado para `int` (inteiro) ou `float` (decimal), caso contrário, o sistema gerará um erro de tipo.

### Pergunta 2: Qual a diferença crucial entre o `PARA` do pseudocódigo e o `range()` do Python?
**Resposta:** No pseudocódigo tradicional, a instrução `PARA m DE 1 ATE meses` geralmente inclui o valor final. No Python, a função `range(inicio, fim)` possui o **limite final exclusivo**. Isso significa que o valor de parada nunca é incluído. Por isso, para simular de 1 até o mês desejado, utilizamos `range(1, meses + 1)`.

---
*Desenvolvido com foco em Código Limpo e Isolamento de Escopo.*
