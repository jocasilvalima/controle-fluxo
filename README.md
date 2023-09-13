# Exercício de Controle de Fluxo em Java

Este é um exercício de Controle de Fluxo em Java que envolve a criação de um programa que conta números em um intervalo especificado pelo usuário. O programa também inclui tratamento de exceções personalizadas para lidar com cenários em que o segundo parâmetro é menor que o primeiro.

## Como executar o programa

Para executar o programa, siga as etapas abaixo:

1. Clone este repositório em sua máquina local:

git clone


2. Navegue até o diretório do projeto:


3. Compile o código-fonte Java:


4. Execute o programa:


5. O programa solicitará que você insira dois números inteiros como parâmetros. Certifique-se de que o segundo número seja maior ou igual ao primeiro número para evitar exceções.

6. O programa contará e imprimirá os números no intervalo especificado.

## Funcionamento do programa

- O programa permite que você insira dois números inteiros como parâmetros.
- Se o segundo número for maior ou igual ao primeiro número, o programa contará e imprimirá os números no intervalo, incluindo ambos.
- Se o primeiro número for maior que o segundo número, o programa lançará uma exceção personalizada chamada `ParametrosInvalidosException` com a mensagem "O segundo parâmetro deve ser maior que o primeiro".
- O tratamento de exceção garante que o programa não falhe quando os parâmetros são inválidos.

## Arquivos do projeto

- `Contador.java`: Contém o código-fonte principal do programa.
- `ParametrosInvalidosException.java`: Contém a classe de exceção personalizada para lidar com parâmetros inválidos.

## Exemplo de uso

Aqui está um exemplo de uso do programa:

Digite o primeiro parâmetro:
3
Digite o segundo parâmetro:
8
Imprimindo o número 3
Imprimindo o número 4
Imprimindo o número 5
Imprimindo o número 6
Imprimindo o número 7
Imprimindo o número 8


Neste exemplo, o programa conta de 3 a 8 e imprime os números no intervalo.

Espero que este README ajude a entender e executar o exercício de Controle de Fluxo em Java. Sinta-se à vontade para personalizar este README conforme necessário para o seu projeto.




