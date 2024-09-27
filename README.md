# Comparando modelos em dataset de churn
Durante o estudo da ciência de dados nos vemos com inúmeros tipos de modelos e diferentes ténicas. Este projeto visa comparar algumas ténicas de "Machine Learning clássicas" analisando seus resultados e observando custo computacional entre outros aspectos para um dataset de churn (O objetivo do estudo de churn é identificar quais clientes têm maior probabilidade de deixar a empresa, utilizando dados históricos e variáveis comportamentais)

## Modelos Utilizados
Naive Bayes: Um modelo simples, porém rápido, que pode ser eficiente para conjuntos de dados pequenos e bem formatados.
Regressão Logística: Modelo clássico para problemas de classificação binária.
K-Nearest Neighbors (K-NN): Um algoritmo baseado em instâncias, que classifica novos exemplos com base nas distâncias de seus vizinhos mais próximos.
Random Forest: Um modelo robusto baseado em árvores de decisão, útil para capturar padrões complexos nos dados.
LightGBM: Um algoritmo otimizado para grandes datasets, que constrói árvores de decisão de forma eficiente.

## Avaliação dos Modelos
Os modelos foram avaliados com as seguintes métricas:

Acurácia: Percentual de predições corretas.
Precisão: Percentual de predições positivas corretas.
Recall: Percentual de verdadeiros positivos identificados.
F1 Score: Média harmônica entre precisão e recall.
Foi observado também custo computacional ao longo dos treinamentos.

## Resultados
LightGBM e Random Forest obtiveram os melhores resultados em termos de acurácia e F1 Score, sendo capazes de capturar as interações mais complexas entre as variáveis que influenciam o churn.
As variáveis mais importantes incluíram Tenure (tempo de contrato), Support Calls (chamadas de suporte) e Payment Delay (atraso de pagamento).

##Contribuindo
Sinta-se à vontade para contribuir com melhorias ao projeto. Para isso, siga os passos abaixo:
Faça um fork do projeto.
Crie uma nova branch com suas modificações: git checkout -b minha-branch.
Faça commit das suas alterações: git commit -m 'Minha contribuição'.
Envie para o repositório: git push origin minha-branch.
Abra um pull request.
