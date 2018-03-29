# Busca Binaria em C

## Como Utilizar:

1- Baixe o BuscaBinaria e o cep_ordenando_reduzido
2- Entre no diretorio onde se encontram ambos os arquivos
3- Execute a busca usando o comando ./BuscaBinaria "cep desejado"
  Ex: de utilização ./BuscaBinaria 20550170

## Casos de Erro:

1- O algoritmo não executará caso o numero de parâmetros passados seja diferente 2, sendo o primeiro o proprio algoritmo e o segundo o CEP que será buscado
2- O algoritmo não executará caso o CEP passado tenha um numero de algarismos diferente de 8

## Sobre o Funcionamento:

A busca binaria funciona da seguinte forma, a cada busca o CEP procurado será comparado com o CEP do meio do arquivo, caso seja o CEP desejado, o programa encerra trazendo as informações do endereço.
Caso contrario, a lista com os CEPs será dividida ao meio e a busca se sucederá em apenas uma metade, no caso do CEP passado como parâmetro ser menor que o CEP encontrado no meio, a metade trabalhada será a primeira, caso seja maior, a metade trabalhada será a segunda.

O algoritmo ficará nesse loop até encontrar o CEP desejado
