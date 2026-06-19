# Perceptron 

O ancestral de tudo. O Perceptron é a unidade mais básica de uma rede neural — um único neurônio que recebe entradas, multiplica por pesos, soma e passa por uma função de ativação pra produzir uma saída. Antes do MLP, antes do deep learning, veio isso aqui.

Exercício focado em entender o mecanismo mais fundamental do aprendizado de máquina baseado em redes neurais.

# No notebook

- Implementação e treinamento do Perceptron com Perceptron
- Visualização da fronteira de decisão linear gerada pelo modelo
- Testes com datasets linearmente separáveis e observação do comportamento


O Perceptron só consegue separar classes que são linearmente separáveis, ou seja, que dá pra dividir com uma linha reta. Quando Minsky e Papert provaram em 1969 que ele não resolve o XOR, o entusiasmo com redes neurais esfriou por décadas. Foi só com o MLP e o backpropagation que as coisas voltaram a andar. Entender o Perceptron é entender por que o MLP existe.
