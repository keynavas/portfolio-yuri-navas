
🛡️ Algoritmo de Auditoria de Dados de Vendas

📝 Descrição do ProjetoEste projeto consiste em uma ferramenta de auditoria e conformidade financeira desenvolvida para identificar anomalias em registros de vendas. O objetivo principal é automatizar a detecção de valores atípicos (outliers) e garantir que a média das transações permaneça dentro de limites de segurança operacionais.

O script analisa trios de vendas, calcula médias e dispara alertas automáticos de "Quarentena" ou "Revisão Manual" caso detecte desvios significativos ou valores que excedam o teto de segurança estabelecido, mitigando riscos de fraudes ou erros de digitação.Figura 1: Fluxo lógico do sistema de auditoria e travas de segurança.

🚀 Funcionalidades e Regras de NegócioCálculo de Média Automático: Processa o valor de três vendas simultâneas.Trava de Segurança (Quarentena): Bloqueia o sistema caso a média das vendas ultrapasse o LIMITE_SEGURANCA (configurado em R$ 1.000,00).Detecção de Outliers (Revisão Manual): Identifica se alguma venda individual é 5 vezes maior que a média do grupo, sinalizando a necessidade de conferência humana.Validação de Tipagem: Garante a integridade dos dados conferindo o tipo primitivo das entradas (float).

🛠️ Tecnologias UtilizadasLinguagem: Python 3.xParadigma: Programação EstruturadaFerramentas: Google Colab / Ambiente Local Python📊 Lógica de AuditoriaO projeto foca em integridade e consistência.

Abaixo, a representação da sensibilidade do algoritmo:CondiçãoAção do SistemaMotivoMédia > R$ 1.000,00SISTEMA EM QUARENTENAVolume financeiro acima do limite operacional.Venda > (Média * 5)REVISÃO MANUALValor individual desproporcional à média (Outlier).
