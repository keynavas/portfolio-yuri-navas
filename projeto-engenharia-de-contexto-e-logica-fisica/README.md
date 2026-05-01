# 🌍 Engenharia de Contexto e Lógica Física

## 📝 Descrição do Projeto
Este projeto integra o desenvolvimento de software com o mapeamento do mundo real. Ele está dividido em duas frentes lógicas:
1. **Análise de Microclima:** Processamento de dados meteorológicos e de qualidade do ar coletados manualmente em diferentes pontos urbanos.
2. **Simulador de Evacuação:** Um algoritmo de navegação espacial baseado no mapeamento físico de um ambiente real, lidando com obstáculos e gestão de recursos (chaves, energia).

## 🚀 Tecnologias e Conceitos Aplicados
* **Linguagem:** Python 3.10+
* **Estruturas de Decisão:** `match-case` (Python 3.10) e `if/else` aninhados.
* **Estruturas de Repetição:** Loops `for` aninhados e `while` para simulação de estados.
* **Matemática Computacional:** Criação de fórmulas de índice de conforto baseadas em múltiplas variáveis.

## 📊 Parte 1: Algoritmo de Microclima
O sistema utiliza uma função para calcular a **Nota de Conforto Urbano**. 
* **Variáveis:** Temperatura, Umidade e IQA (Índice de Qualidade do Ar).
* **Lógica:** Penalização de temperaturas extremas e classificação de saúde via IQA oficial brasileiro.

## 🏃 Parte 2: Simulador de Evacuação
Mapeamento de uma rota de fuga onde o "Agente" deve decidir como avançar.
* **Nós:** Cômodos e corredores mapeados fisicamente.
* **Obstáculos:** Portas trancadas, caminhos obstruídos e itens de inventário.

## 🔧 Como Executar
1. Execute o script de Microclima para analisar os pontos coletados.
2. Execute o Simulador de Evacuação para testar a lógica de saída do ambiente mapeado.
