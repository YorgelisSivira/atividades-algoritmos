# Experiência Prática I - Algoritmos e Pensamento Computacional

Este repositório contém o planejamento estrutural e o desenvolvimento do algoritmo em pseudocódigo para o monitoramento de preços da cesta básica, desenvolvido para a disciplina de Algoritmos e Pensamento Computacional na Universidade Cruzeiro do Sul.

## 📋 Cenário e Desafio
O objetivo do sistema é auxiliar um órgão municipal de defesa do consumidor na análise de variações de preços de produtos essenciais ao longo do tempo. O programa recebe os dados de **três produtos distinots** (nome, preço do mês anterior e preço do mês atual), calcula a variação percentual e classifica o status de cada item em:
- **Aumento de Preço**
- **Redução de Preço**
- **Manutenção de Preço (Estável)**

## 🔍 Planejamento Estrutural do Algoritmo
A sequência lógica programada para execução do sistema segue as seguintes etapas:
1. **Inicialização:** Configuração do bloco de memória com variáveis do tipo Texto (String) e Real (Float).
2. **Entrada de Dados:** Coleta sequencial do nome e preços (mês anterior e atual) para os 3 produtos.
3. **Processamento:** Cálculo matemático da variação percentual absoluta.
4. **Decisão:** Aplicação de estruturas condicionais aninhadas (`Se... Então... Senão`) para classificar a oscilação de valores.
5. **Saída:** Exibição de um relatório formatado com o diagnóstico final para o usuário.
