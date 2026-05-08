# 🏢 Auditoria de Orçamentos Corporativos (Python)
 
[![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![Status](https://img.shields.io/badge/status-concluído-brightgreen.svg)]()
 
## 📖 Sobre o Projeto
Este projeto foi desenvolvido como parte da disciplina de Sistema de Auditoria de Recursos Corporativos do curso de Ciência da computação. O objetivo do script é processar e calcular o orçamento de uma estrutura organizacional complexa (dicionários aninhados) de uma multinacional, aplicando regras de negócio dinâmicas e auditoria de execução.
 
A solução foi arquitetada utilizando conceitos avançados de Python para garantir flexibilidade, performance e rastreabilidade.
 
## 🚀 Funcionalidades
- **Cálculo Hierárquico:** Varredura completa da estrutura corporativa, independentemente do nível de profundidade.
- **Filtros Dinâmicos:** Capacidade de ignorar setores específicos e todos os seus subsetores na hora do cálculo financeiro.
- **Conversão de Câmbio:** Suporte a parâmetros opcionais para conversão de moedas em tempo de execução.
- **Sistema de Auditoria:** Monitoramento automatizado de tempo de execução e registro (logging) dos parâmetros utilizados na transação financeira.
 
## 🛠️ Tecnologias e Conceitos Aplicados
Este projeto foi construído utilizando Python puro (Standard Library), com foco nos seguintes paradigmas e recursos:
* **Funções Recursivas (Recursion):** Utilizadas para a navegação na árvore de dados (dicionários aninhados).
* **Decorators:** Implementação do `@auditor` para injetar comportamentos de log e cronometragem sem modificar a lógica de negócios.
* **Empacotamento de Argumentos (`*args` e `**kwargs`):** Utilizados tanto no decorator quanto na função principal para permitir a passagem dinâmica de departamentos a serem ignorados e taxas de câmbio.
 
## ⚙️ Como Executar
 
### Pré-requisitos
* Python 3.8 ou superior instalado.
 
### Passo a Passo
1. Clone este repositório:
   ```bash
   git clone https://github.com/keynavas/projeto-sistema-de-auditoria-de-recursos-corporativos.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd projeto-sistema-de-auditoria-de-recursos-corporativos
   ```
3. Execute o script principal:
   ```bash
   python sistema_de_auditoria_de_recursos_corporativos.py
   ```
 
## 🧠 Lógica e Estrutura do Código
Breve explicação de como o código foi organizado:
* O código foi dividido em partes para facilitar a organização e o entendimento da lógica utilizada no projeto.

Primeiro foi criada uma estrutura de dados utilizando dicionários aninhados para representar os departamentos e subsetores da empresa. Cada setor possui seus próprios orçamentos e, em alguns casos, outros departamentos internos.

A função calcular_orcamento() foi desenvolvida utilizando recursão. Quando a função encontra um novo dicionário dentro da estrutura, ela chama novamente a si mesma até percorrer todos os níveis da empresa e somar os valores encontrados.

Também foi implementado um decorator chamado @auditor, responsável por monitorar a execução da função principal. Ele registra informações como tempo de execução, argumentos recebidos e início/fim do processo de auditoria sem alterar diretamente a lógica do cálculo principal.

Os parâmetros *args foram utilizados para permitir que departamentos específicos sejam ignorados dinamicamente durante a soma dos valores. Já os **kwargs foram utilizados para receber configurações opcionais, como taxa de câmbio e moeda de destino.

* **Dados:** Os dados simulados da empresa foram estruturados em Python utilizando dicionários aninhados para representar a hierarquia organizacional da multinacional.

O primeiro nível representa a matriz principal da empresa. Dentro dela existem departamentos como TI, RH, Financeiro e Marketing. Alguns desses setores possuem subsetores internos, que também foram organizados em novos dicionários.

Os últimos níveis da estrutura armazenam valores numéricos inteiros, representando os orçamentos de cada área da empresa.
 
## 👤 Autor
 
* **Yuri Navas Moreira** * LinkedIn: https://www.linkedin.com/in/key-yuri-navas/
* E-mail: yurin.2000@gmail.com
 
---
*Projeto acadêmico com foco na aplicação prática de conceitos avançados da linguagem Python.*
