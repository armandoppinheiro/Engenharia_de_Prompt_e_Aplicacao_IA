#ATIVIDADE DE APRIMORAMENTO DE PROMPT

*PROMPT SIMPLES: CRIE UMA PIRAMIDE

*PROMPT ESTRUTURADO: CRIE UM CÓDIGO DETALHADO EM PYTHON DE UMA PIRAMIDE FORMADA POR *, EXPLICANDO-O POIS SOU ESTUDANTE INICIANTE DE PROGRAMAÇÃO.

🧱 Código da pirâmide com *

# Solicita ao usuário a altura da pirâmide
altura = int(input("Digite a altura da pirâmide: "))

# Loop para cada linha da pirâmide
for i in range(1, altura + 1):
    # Calcula o número de espaços à esquerda para centralizar os asteriscos
    espacos = altura - i
    # Calcula o número de asteriscos na linha atual
    asteriscos = 2 * i - 1
    # Imprime a linha com espaços e asteriscos
    print(" " * espacos + "*" * asteriscos)

🧠 Explicação passo a passo

altura = int(input(...)): pede ao usuário que digite a altura da pirâmide (quantas linhas ela terá). O int() transforma o texto digitado em número.

for i in range(1, altura + 1):: esse laço vai do 1 até a altura da pirâmide, criando uma linha por vez.

espacos = altura - i: calcula quantos espaços colocar antes dos asteriscos para que a pirâmide fique centralizada.

asteriscos = 2 * i - 1: determina quantos * devem aparecer na linha. A fórmula garante que o número de asteriscos aumente de forma simétrica.

print(" " * espacos + "*" * asteriscos): imprime a linha com os espaços à esquerda e os asteriscos formando a pirâmide.

🧪 Exemplo de saída para altura = 4

   *
  ***
 *****
*******
