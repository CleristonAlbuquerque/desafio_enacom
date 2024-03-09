# **DESAFIO ENACOM**

Este notebook está relacionado ao desafio Enacom.

## **Objetivo**

O objetivo deste projeto é criar um modelo de previsão de geração de energia hidrelétrica anual.

## **Dados**

Os dados sobre geração de energia foram obtidos no site de dados aberto ONS, disponíveis em: [Link do dataset](https://dados.ons.org.br/dataset/geracao-usina-2).
Os dados sobre hidrológicos nos reservatórios foram obtidos no site de daos aberto ONS. disponíveis em: [Link do datasset](https://dados.ons.org.br/dataset/dados-hidrologicos-res)

## **Insights e Exploração de Dados**

Após a exploração dos dados, foram obtidos os seguintes insights:

- Distribuição das fontes de energia por região.
- Geração de energia por região.
- Correlação entre a geração de energia nas diferentes regiões.
- Correlação entre as fontes de energia nas diferentes regiões.
- Correlação entre as variáveis dos reservatórios e a geração de energia hidrelétrica.
- Média de geração de energia no país.
- Média de geração de energia por região.
- Gráficos de geração hidrelétrica por região.


## **Modelos de Aprendizagem de Máquinas**

As variáveis consideradas no uso de aprendizagem de máquina foram:

- Região (Norte, Nordeste, Sudeste e Sul)
- Dados advindos dos reservatórios das usinas hidrelétricas

Foram empregados três modelos:

1. Regressão Linear
2. Árvore de decisão
3. Floresta Aleatória
4. Rede Neural
5. XGBloost

Utilizamos o Mean Squared Error (MSE) como métrica de avaliação de desempenho do modelo. Além disso, aplicamos a validação cruzada (Cross - Validation). Não foi possível aplicar o Grid Search para otimizar os parâmetros do modelo.

## **Contato**

- **Nome:** Clériston Cláudio Carneiro Pereira de Albuquerque
- **E-mail:** cleriston.albuquerque@yahoo.com.br
- **Telefone:** +55 81 98618-0278
- **Linkedin:**[Link do linkedin](https://www.linkedin.com/in/cleristonalbuquerque)

## **Sobre o autor**

Clériston Cláudio Carneiro Pereira de Albuquerque é graduado em Engenharia de Produção pela Faculdade Boa Viagem, mestre em Engenharia de Produção pela UFPE,
possui MBA em Investimento em Ações e Mercado de Capitais pela UNICAP, MBA em Ciência de dados para o mercado financeiro pela XP Educação e atualmente está graduando em Ciência de Dados pela Wyden.
É professor de educação profissional pelo Governo de Pernambuco e já atuou em diversas áreas, como na área de planejamento, logística e qualidade.