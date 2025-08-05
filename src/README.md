# Projeto FP&A - Análise Financeira com Python/case para entrevista, para melhor entendimento da vaga

## Objetivo

Este projeto simula o processo de análise financeira em uma área de FP&A, focando no acompanhamento de resultados, orçamento e forecast de produtos financeiros como Cartões, Empréstimos, Seguros, entre outros, apenas como simulação para treino. 

O intuito é puramente de aprendizado, podendo ter erros conceituais, porém, tentei demonstrar a capacidade de estruturar e analisar dados financeiros, calcular KPIs essenciais, identificar riscos e oportunidades, e apresentar insights estratégicos para apoiar a tomada de decisão.

## Estrutura dos Dados

Os dados simulados abrangem um período de 36 meses e contêm as seguintes colunas principais:

- **Data**: período mensal dos dados.
- **Produto**: categoria do produto financeiro.
- **Receita_Orcada**: receita prevista no orçamento inicial.
- **Receita_Realizada**: receita efetivamente realizada.
- **Receita_Forecast**: previsão atualizada da receita.
- **Inadimplencia**: percentual médio de inadimplência por produto.
- **Margem**: lucro bruto aproximado em reais.
- **Margem_pct**: margem percentual calculada sobre a receita realizada.
- **Acuracia_Forecast_%**: medida de quão próximo o forecast ficou do realizado.

## Tecnologias  e bibliotecas Utilizadas

- Python (Pandas, Matplotlib, Seaborn)
- Ambiente VS Code

## Principais Análises Realizadas

- Comparação e visualização da evolução mensal da receita realizada, orçada e forecast.
- Cálculo de KPIs financeiros fundamentais, como margem, variação orçado vs realizado, acurácia do forecast e inadimplência.
- Análise de risco financeiro via monitoramento da inadimplência média por produto.
- Identificação dos períodos com maiores desvios para reforçar o controle financeiro.
- Síntese dos principais indicadores para suporte a decisões estratégicas.

## Como Executar

1. Instale as dependências necessárias:
   ```bash
   pip install pandas matplotlib seaborn

## Conclusão do Projeto
Este projeto foi realizado para fixação de alguns conceitos de FP&A, sendo eles, o acompanhamento detalhado do P&L, análise crítica de orçamento e forecast, e a geração de insights relevantes para apoiar a estratégia financeira da empresa.

Através da manipulação de dados financeiros simulados, foi possível criar KPIs que refletem a saúde e o desempenho dos produtos, identificar riscos como a inadimplência e monitorar a precisão das previsões, pontos cruciais para a tomada de decisão no contexto do varejo financeiro.

