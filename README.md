# ETL com dados reais: gasolina, petróleo e câmbio

## Autor: Guilherme Reikdal Medeiros

Este projeto foi desenvolvido como parte do meu processo de aprendizado em análise de dados, com foco na prática de ETL a partir de bases reais.

O objetivo foi trabalhar com dados de diferentes fontes: preços de gasolina, petróleo Brent e taxa de câmbio, que apresentavam padrões distintos, tanto em formato quanto em estrutura. As bases incluíam inconsistências comuns, como variações na formatação numérica, datas em padrões diferentes e frequências temporais não alinhadas (dados diários e mensais).

A principal etapa do projeto consistiu na transformação desses dados em uma base única e consistente. Para isso, foram realizados processos de limpeza, padronização de colunas, tratamento de datas, conversão de formatos e alinhamento das séries temporais por meio de técnicas como resampling e merge utilizando pandas.

Após a consolidação da base, foi realizada uma regressão linear simples com o objetivo de verificar o comportamento conjunto das variáveis já tratadas, sem que essa etapa fosse o foco central do projeto.

O principal aprendizado foi a importância da etapa de preparação de dados, especialmente ao lidar com múltiplas fontes. A padronização e integração das bases se mostraram etapas fundamentais para viabilizar qualquer tipo de análise posterior.


## Dados Utilizados

- Preço da gasolina (Brasil) – ANP
- Preço do petróleo (Brent) – mercado internacional
- Taxa de câmbio (USD/BRL) – Banco Central do Brasil



