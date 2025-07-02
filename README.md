# Classificação: Validação de Modelos e Métricas de Avaliação
Este projeto aborda o problema da identificação de clientes inadimplentes para uma empresa de empréstimo de automóveis. O objetivo principal é desenvolver um modelo de classificação que otimize a detecção de inadimplência, substituindo o processo manual impreciso e demorado por uma solução automatizada e eficiente.

Contexto do Problema
A empresa enfrenta desafios significativos devido à alta demanda por uma frota de veículos limitada e um grande número de clientes inadimplentes, resultando em perdas financeiras substanciais. A análise manual atual para identificar inadimplentes é ineficaz e consome muitos recursos.

Objetivo do Projeto
Classificar os clientes em adimplentes (não-inadimplentes) e inadimplentes utilizando dados fornecidos pela empresa, visando melhorar a precisão na detecção de risco de crédito.

Metodologia
O projeto segue as seguintes etapas:

Preparação dos Dados: Os dados são carregados a partir do arquivo emp_automovel.csv. O conjunto de dados inclui informações como receita do cliente, anuidade do empréstimo, anos na casa própria, avaliação da cidade, e diversas pontuações (score_1, score_2, score_3, score_social). A variável alvo para classificação é inadimplente.

Divisão dos Dados: O conjunto de dados é dividido em conjuntos de treino, validação e teste para garantir uma avaliação robusta do modelo.

Modelagem: Um modelo de Classificação é empregado para prever a inadimplência dos clientes.

Avaliação do Modelo: O desempenho do modelo é avaliado usando as seguintes métricas:

Acurácia: Medida geral de correção do modelo.

Precisão: Proporção de verdadeiros positivos entre os resultados positivos previstos.

Recall (Revocação): Proporção de verdadeiros positivos que foram corretamente identificados.

F1-Score: Média harmônica de precisão e recall.

Average Precision (AP): Métrica que resume a curva precisão-recall.

Resultados e Métricas
Os resultados do modelo de classificação foram os seguintes:

Categoria

Precisão

Recall

F1-Score

Suporte

0

0.92

0.99

0.95

10479

1

0.25

0.04

0.07

1002

Accuracy





0.90

11481

Macro Avg

0.58

0.52

0.51

11481

Weighted Avg

0.86

0.90

0.87

11481

Acurácia no Conjunto de Treino: 1.00

Acurácia no Conjunto de Teste: 0.90

Acurácia no Conjunto de Validação: 0.91

Average Precision (AP): 0.09399
