# Sistemas-Inteligentes

Trabalhos desenvolvidos para a disciplina de Sistemas Inteligentes, na UTFPR campus Pato Branco, e ministrada pelo professor [Dalcimar Casanova](https://github.com/dalcimar).

## Enunciados

### Trabalho 1

Crie sua própria base de dados de classificação de frutas ou verduras. A mesma deve conter:

1. features/variáveis independentes (reais ou inteiros)

1. variável dependente (reais ou inteiros)

1. Possuir no mínimo 30 amostras, 15 de cada classe

### Trabalho 2

Utilizando o arguivo L03_scipython_notes.pdf, execute cada um dos comandos no ambiente colab. Para cada comando explique, com suas palavras, o que foi executado.

Compartilhe o colab final no email

### Trabalho 3

Crie um sistema especialista capaz de imitar a tomada de decisões de um especialista humano. A base de conhecimento a ser utilizada é a base do trabalho 1. Vc deve criar regras que separam as 2 classes de interesse e programa-las como um mecanismo de inferência. Para isso siga os seguintes passos:

1. Separe a base de dados em treinamento e teste. Essa separação deve resultar em 2 conjuntos de dados distintos: X_train e X_test, assim como 2 conjuntos de rótulos distintos: y_train e y_test. A base de treino deve ter 66% dos dados e a base de teste deve ter 33% dos dados.

1. Crie um scatterplot da base de treinamento

1. Visualize e interprete os dados, de forma a criar alguma regra de inferencia que separe as duas classes

1. Implemente a regra na forma de if/else, criando assim um mecanismo de inferência

1. Aplique as regras a cada amostra da base de dados de treino e verifique se classificou corretamente ou não. Calcule a média de acertos.

1. Com base na regra criada, determine a reta de decisão obtida e plote a mesma sobre o scatterplot

1. Crie um scatterplot 2, para a base de teste, plote a reta de decisão

1. Aplique as regras a cada amostra da base de dados de teste e verifique se classificou corretamente ou não. Calcule a média de acertos.

### Trabalho 4

Crie um classificador baseado na regra 1-rule (ver slides L04). Teu classificador deverá separar as classes com base em apenas uma regra, essa regra deve ser a melhor dentre todas as possíveis, portanto vc deverá testar todas as características e todos os intervalos

1. O objeto final deve conter os métodos fit(), predict() e score() 

1. A base de dados deve ser separada em base de treino e teste. A base de treino deve ter 66% dos dados e a base de teste deve ter 33% dos dados.

1. Deve ser plotado o scatterplot dos pontos e a reta de decisão obtida

1. A acurácia deve ser medida na base de treino e na base de teste
