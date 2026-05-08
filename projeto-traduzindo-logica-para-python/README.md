# 🐍 Traduzindo Lógica para Python

## 📝 Descrição do Projeto
Este projeto consiste na transposição de algoritmos complexos de pseudocódigo para a linguagem Python. O objetivo principal é demonstrar o domínio sobre a sintaxe da linguagem, garantindo o uso correto de tipos de dados, estruturas de repetição e lógica condicional.

Desenvolvido como parte da disciplina de Lógica de Programação, o sistema resolve quatro problemas distintos do mundo real, desde automação de vendas até simulações financeiras, provando a portabilidade de algoritmos entre linguagens de alto nível e modelos abstratos.

## 🚀 Tecnologias Utilizadas
 Linguagem Python 3.11
 Conceitos Casting de Dados (`float`, `int`), Estruturas de Decisão (`ifelifelse`), Repetição (`range`) e Manipulação de Strings.
 Ferramentas VS Code, IDLE ou qualquer ambiente Python 3.x.

## 📊 Módulos e Funcionalidades
O sistema é composto por quatro funções principais, cada uma traduzida de um pseudocódigo técnico

 Processamento de Vendas Valida estoque, calcula totais e aplica descontos progressivos (5% e 10%).
 Análise de Clima Monitora temperaturas semanais e dispara alertas de condições extremas (45°C ou -5°C).
 Gestão de Notas Automatiza a classificação de alunos em Aprovado, Recuperação ou Reprovado.
 Simulador de Poupança Projeta o rendimento de investimentos com aportes mensais e juros compostos.

## 🧠 Reflexão Crítica e Aprendizados
A transposição da lógica abstrata para uma linguagem real revelou pontos críticos sobre o funcionamento do computador

 Tipagem Dinâmica Reforcei a necessidade do uso de `float()` e `int()` em entradas de dados, uma vez que o Python lê todo `input()` como texto (string), o que impediria cálculos matemáticos.
 Limites de Iteração Aprofundei o conhecimento na função `range()`. Diferente do pseudocódigo tradicional, o limite final do Python é exclusivo, exigindo o ajuste `range(1, n + 1)` para atingir o valor esperado.

## 🔧 Como Executar
1. Clone o repositório.
2. Certifique-se de ter o Python instalado em sua máquina.
3. Execute o arquivo principal
   ```bash
   python main.py
