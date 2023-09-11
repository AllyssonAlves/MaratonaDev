# MaratonaDev
1º Maratona Dev de Programação

Repositorio onde serão alocados as questões:
https://kroton-my.sharepoint.com/:f:/g/personal/allysson_carvalho_kroton_com_br/Eqgae5_V_y5MjYha06u_J1kBETzjNjV1GjMjBLcX7HSk0Q?e=yhrIdx


Lista de Desafios:

Desafios feitos em qualquer linguagem de programação.
_______________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
1) # Salario
Escreva um programa que leia o número de um funcionário, seu número de horas trabalhadas, o valor que recebe por hora e calcula o salário desse funcionário. A seguir, mostre o número e o salário do funcionário, com duas casas decimais.
Entrada
O arquivo de entrada contém 2 números inteiros e 1 número com duas casas decimais, representando o número, quantidade de horas trabalhadas e o valor que o funcionário recebe por hora trabalhada, respectivamente.
Saída
Imprima o número e o salário do funcionário, conforme exemplo fornecido, com um espaço em branco antes e depois da igualdade. No caso do salário, também deve haver um espaço em branco após o $.
Exemplos de Entrada	          Exemplos de Saída
25                              NUMBER = 25
100                            SALARY = U$ 550.00
5.50

1                              NUMBER = 1
200                            SALARY = U$ 4100.00
20.50

6                               NUMBER = 6
145                            SALARY = U$ 2254.75
15.55


________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
2) # Calculo Jogo
Leia a hora inicial e a hora final de um jogo. A seguir calcule a duração do jogo, sabendo que o mesmo pode começar em um dia e terminar em outro, tendo uma duração mínima de 1 hora e máxima de 24 horas.
Entrada
A entrada contém dois valores inteiros representando a hora de início e a hora de fim do jogo.
Saída
Apresente a duração do jogo conforme exemplo abaixo.
Exemplo de Entrada	              Exemplo de Saída
16 2                            O JOGO DUROU 10 HORA(S)
0 0                             O JOGO DUROU 24 HORA(S)
2 16                            O JOGO DUROU 14 HORA(S)


________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
3) # Valide o CPF
Quando se está trabalhando em um sistema corporativo, é comum a necessidade de validar CPF. Muita gente não sabe que um CPF para ser válido não basta apenas atender à máscara "###.###.###-##" (o caractere '#' representa um número), existe uma regra matemática que também deve ser verificada para um CPF ser considerado válido. 
[REGRA PARA VALIDAR CPF]

O CPF é formado por 11 dígitos numéricos que seguem a máscara "###.###.###-##", a verificação do CPF acontece utilizando os 9 primeiros dígitos e, com um cálculo simples, verificando se o resultado corresponde aos dois últimos dígitos (depois do sinal "-").
Vamos usar como exemplo, um CPF fictício "529.982.247-25".

[Validação do primeiro dígito]
Primeiramente multiplica-se os 9 primeiros dígitos pela sequência decrescente de números de 10 à 2 e soma os resultados. Assim:

5 * 10 + 2 * 9 + 9 * 8 + 9 * 7 + 8 * 6 + 2 * 5 + 2 * 4 + 4 * 3 + 7 * 2

O resultado do nosso exemplo é: 295
O próximo passo da verificação também é simples, basta multiplicarmos esse resultado por 10 e dividirmos por 11.

295 * 10 / 11

O resultado que nos interessa na verdade é o RESTO da divisão. Se ele for igual ao primeiro dígito verificador (primeiro dígito depois do '-'), a primeira parte da validação está correta.
Observação Importante: Se o resto da divisão for igual a 10, nós o consideramos como 0.

Vamos conferir o primeiro dígito verificador do nosso exemplo:

O resultado da divisão acima é '268' e o RESTO é 2
Isso significa que o nosso CPF exemplo passou na validação do primeiro dígito.

[[Validação do segundo dígito]]
A validação do segundo dígito é semelhante à primeira, porém vamos considerar os 9 primeiros dígitos, mais o primeiro dígito verificador, e vamos multiplicar esses 10 números pela sequencia decrescente de 11 a 2. Vejamos:

5 * 11 + 2 * 10 + 9 * 9 + 9 * 8 + 8 * 7 + 2 * 6 + 2 * 5 + 4 * 4 + 7 * 3 + 2 * 2

O resultado é: 347

Seguindo o mesmo processo da primeira verificação, multiplicamos por 10 e dividimos por 11.

347 * 10 / 11

Verificando o RESTO, como fizemos anteriormente, temos:

O resultado da divisão é '315' e o RESTO é 5

Verificamos, se o resto corresponde ao segundo dígito verificador.

Com essa verificação, constatamos que o CPF 529.982.247-25 é válido.

_____________________________________________________________________________________________________________________________________________________________________
4) # Fibonacci Fácil
A seguinte sequência de números 0 1 1 2 3 5 8 13 21... é conhecida como série de Fibonacci. Nessa sequência, cada número, depois dos 2 primeiros, é igual à soma dos 2 anteriores. Escreva um algoritmo que leia um inteiro N (N < 46) e mostre os N primeiros números dessa série.

Entrada
O arquivo de entrada contém um valor inteiro N (0 < N < 46).

Saída
Os valores devem ser mostrados na mesma linha, separados por um espaço em branco. Não deve haver espaço após o último valor.


_______________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

5) # Ordenação
Dada a sequência de números: 3 4 9 2 5 8 2 1 7 4 6 2 9 8 5 1, ordene-a em ordem crescente;
