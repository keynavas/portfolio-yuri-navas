# ⚖️ Sistema de Auditoria de Vendas Semanais

## 📝 Descrição do Projeto
Este projeto consiste em um sistema de análise de consistência de dados financeiros, desenvolvido para detectar anomalias e garantir a integridade de registros de vendas. O objetivo principal é aplicar a **Engenharia de Contexto** para identificar "outliers" (discrepâncias) que possam distorcer a realidade financeira de uma operação.

O sistema utiliza os pilares do **Pensamento Computacional** para tratar fenômenos da **Lógica Física** do mercado:
* **Engenharia de Contexto:** O software interpreta se uma venda é legítima ou suspeita comparando-a com o comportamento médio do grupo e limites de segurança globais.
* **Decomposição:** O processo de auditoria é dividido em: Entrada (Casting), Processamento (Média), Investigação (Anomalias) e Apresentação (Tipagem).
* **Abstração:** Foco nos valores monetários e margens de tolerância, ignorando detalhes burocráticos para otimizar a velocidade da análise.

## 🚀 Tecnologias Utilizadas
* **Linguagem:** Python 3.10 (f-strings, global scope, casting de tipos)
* **Conceitos de Engenharia:** Lógica Condicional, Escopo Global vs. Local e Detecção de Outliers.

## 🏗️ Arquitetura e Modularização
Seguindo o princípio **DRY (Don't Repeat Yourself)** e buscando **Alta Coesão**, o código foi estruturado para que a lógica de investigação seja independente da entrada de dados:
* **Escopo Seguro:** Uso controlado da palavra-chave `global` para permitir que gestores ajustem parâmetros de segurança em tempo de execução.
* **Isolamento de Funções:** A função `analisar_vendas()` atua como uma "caixa preta" que recebe os valores físicos e devolve um diagnóstico de quarentena ou revisão manual.

## 📊 Resultados e Aprendizados
O projeto demonstrou como a programação estruturada pode proteger sistemas contra erros humanos e fraudes:
* **Detecção de Anomalias:** Implementação de lógica que identifica vendas 5x maiores que a média (outliers).
* **Normalização de Dados:** Compreensão de como valores extremos podem "mentir" sobre a média e a importância de auditorias manuais.
* **Teste de Estresse:** O sistema foi validado com cenários de alta discrepância, garantindo que o alerta de "REVISÃO MANUAL" seja disparado corretamente.

## 🔧 Como Executar
1. Clone o repositório.
2. Certifique-se de ter o Python 3.10 instalado.
3. Execute o comando: `python auditoria_vendas.py`.

---
[Voltar ao início](https://github.com/seu-usuario/seu-usuario)
