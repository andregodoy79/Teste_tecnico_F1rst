# Teste_tecnico_F1rst

Esse projeto foi realizado como parte do processo seletivo para vaga de cientista de dados senior da F1rst - Parte 1 .

Essa parte consiste na elaboração de um Jupyter Notebook (ou outra ferramenta que lhe for mais conveniente para apresentação) com pelo menos 2 técnicas à sua escolha para resolver uma ou mais competições de Fraude contidas no Kaggle. O candidato tem a liberdade para escolha da competição que lhe for mais conveniente, bem como
de unir todas as bases de dados caso queira. 

A base de dados utilizadas nesse projeto foram do https://www.kaggle.com/c/ieee-fraud-detection 

# Descrição do projeto

O notebook principal é o test_part1.ipynb dentro desse notebook tem um link para outro notebook dedicado a análise e exploração dos dados EDA. O notebook do EDA sumariza as informações levantadas sobre o conjunto de dados, realiza os tratamentos das variáveis, como normalização e preenchimento dos dados faltantes, também há um procedimento para a seleção das variáveis considerando alguns critérios estatísticos.

Após a exploração, tratamento dos dados e seleção das variáveis, os conjuntos de dados são tratados e salvos para a etapa de modelagem que ocorre no notebook, principal.

No notebook principal temos a modelagem por alguns algoritmos de machine learning rasos do scikit learn e xgboost e por uma rede MLP simples usando o pacote do tensorflow.

Finalmente realizamos a otimização dos modelos rasos utilizando o pacote optuna, que trabalhar utilizando algoritmos especiais para a otimização de modelos.

# Modelagem
