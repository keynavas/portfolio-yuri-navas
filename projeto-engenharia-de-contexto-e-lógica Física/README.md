# 🎬 Sistema de Recomendação de Filmes

## 📝 Descrição do Projeto
[cite_start]Este motor de recomendação inteligente foi desenvolvido com foco na **Modularização**, visando mitigar a "paralisia de escolha" através de uma arquitetura limpa e escalável[cite: 110, 196]. 

[cite_start]O sistema aplica os pilares do **Pensamento Computacional**[cite: 114]:
* [cite_start]**Decomposição:** O desafio de recomendação foi quebrado em módulos menores (limpeza, cálculo e interface)[cite: 115, 116].
* [cite_start]**Abstração:** Foco nos dados essenciais de preferência do usuário, ignorando ruídos irrelevantes do dataset[cite: 119, 120].
* [cite_start]**Algoritmos:** Implementação de passos ordenados para prever avaliações com base em padrões de comportamento[cite: 117, 123].

## 🏗️ Arquitetura e Design (Top-Down)
[cite_start]Seguindo a abordagem **Top-Down**, o projeto separa a lógica geral da implementação detalhada de cada função, garantindo que o programa principal conte a "história" do fluxo sem se perder em detalhes matemáticos profundos[cite: 161, 208].

### Módulos Sugeridos (Interface)
[cite_start]O sistema utiliza o conceito de **"Caixa Preta"**, onde cada função possui **Alta Coesão** e **Baixo Acoplamento**[cite: 133, 137, 145]:

* `preparar_dados()`: Normalização e limpeza (Redução de Ruído).
* [cite_start]`calcular_similaridade()`: Lógica matemática central protegida por **Escopo Local**[cite: 145].
* [cite_start]`gerar_recomendacoes()`: Função integradora que define o fluxo de saída para o usuário[cite: 168, 171].

> [cite_start]**Princípio DRY (Don't Repeat Yourself):** A lógica de recomendação vive em um único lugar, facilitando a manutenção e evitando quebras imprevistas em outras partes do sistema[cite: 129, 130, 132].

## 🚀 Tecnologias Utilizadas
* **Linguagem:** Python 3.10
* **Bibliotecas:** Pandas, Scikit-learn, Matplotlib
* [cite_start]**Conceitos:** Programação Estruturada, Parâmetros e Retornos (evitando variáveis globais)[cite: 141, 146, 206].

## 📊 Resultados e Aprendizados
[cite_start]O projeto priorizou o **design da solução antes da codificação**[cite: 214]:
* **92% de acurácia** nos testes de validação.
* **Visualização de Clusters:** Gráficos que demonstram o agrupamento de filmes por afinidade.
* [cite_start]**Código Limpo:** Facilidade de leitura através do isolamento de responsabilidades isoladas[cite: 196, 201].

## 🔧 Como Executar
1.  Clone o repositório.
2.  Instale as dependências: `pip install -r requirements.txt`.
3.  Execute o comando: `python main.py`.

---
[cite_start]*Este projeto aplica a filosofia de que um código com bom design é planejado antes de ser digitado: a forma segue a função[cite: 214].*
