# RNA-2025.1-PP3

Integrantes:
Guilherme Montenegro, Diogo Gomes, Danilo Jorge, Leonardo Abinader, Rodolfo Simões, Caio Bertoldo

## Sobre o projeto
Neste projeto, a tarefa a ser realizada é a previsão da nota final no exame de alunos (variável exam_score), com base em um conjunto de variáveis que representam hábitos de estudo, estilo de vida, saúde mental, apoio familiar, etc. Assim, podemos dizer que se trata de um problema de regressão supervisionada, cujo objetivo é construir um modelo capaz de estimar a pontuação final do aluno com base em seus dados individuais. A validação do desempenho do modelo será conduzida por meio da técnica de validação cruzada do tipo K-Fold com k=5, a fim de garantir robustez estatística e evitar overfitting. Já para a seleção de hiperparâmetros do modelo, será utilizada a técnica de Grid Search, com uma grade inicial de busca composta por combinações de parâmetros como número de estimadores (n_estimators), profundidade máxima (max_depth) e critérios de divisão dos nós internos da árvore, totalizando entre 8 e 16 combinações. Essa configuração visa balancear desempenho preditivo com viabilidade computacional, subsidiando o início dos testes de treinamento e avaliação dos modelos regressivos.
